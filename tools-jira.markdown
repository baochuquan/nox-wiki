---
layout: default
title: jira
parent: 工具索引
nav_order: 4
has_children: false
---

*  目录
{:toc}

---

## bug
`nox jira bug`

```shell

Usage:
    bug --set-resolved bug
    bug --set-reopen bug

Description:
    用于修改 BUG 状态

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --set-resolved|-r:                                  -- 更新 bug 状态为 resolved
    --set-reopen|-o:                                    -- 更新 bug 状态为 reopen
```

---

## query
`nox jira query`

```shell
Usage:
    query [--story-todo|...] [--project projectname] [--assignee assigneeldap] [--reporter reporterldap]

Description:
    查询 story，ui-bug，bug，提测申请，可指定项目、assignee、reporter 进行筛选。

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --story-todo|-t:                                    -- 指定 TODO 状态的 story
    --story-done|-d:                                    -- 指定 DONE 状态的 story
    --story-all|-s:                                     -- 指定所有状态的 story
    --bug-resolved|-r:                                  -- 指定 已修复 状态的 bug
    --bug-unfix|-F:                                     -- 指定 未修复 状态的 bug
    --bug-closed|-C:                                    -- 指定 关闭状态 的 bug
    --bug-all|-B:                                       -- 指定所有状态的 bug
    --uibug-unfix|-u:                                   -- 指定 未修复 状态的 uibug
    --uibug-fixed|-f:                                   -- 指定 关闭 状态的 uibug
    --uibug-all|-U:                                     -- 指定所有状态的 uibug
    --test-begin|-b:                                    -- 指定 提测 状态的 提测申请
    --test-inprogress|-i:                               -- 指定 测试中 状态的 提测申请
    --test-passed|-p:                                   -- 指定 测试通过 状态的 提测申请
    --test-all|-T:                                      -- 指定所有状态的 提测申请
    --project|-P:                                       -- 指定项目名称，如：SOLAR
    --assignee|-A:                                      -- 指定委派用户
    --reporter|-R:                                      -- 指定报告用户
```

如下所示，为查看 baocq 的所有未修复的 bug。

![](https://chuquan-public-r-001.oss-cn-shanghai.aliyuncs.com/nox/nox-jira-query-01.gif)

如下所示，为查看 jiaolf 的所有正在进行中的测试申请。

![](https://chuquan-public-r-001.oss-cn-shanghai.aliyuncs.com/nox/nox-jira-query-02.gif)



---

## test
`nox jira test`

```shell
Usage:
    test --request key

Description:
    申请提测并通知测试同学

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --request|-r:                                       -- 提测申请，如：SOLAR-12345

```

如下所示：

![](https://chuquan-public-r-001.oss-cn-shanghai.aliyuncs.com/nox/nox-jira-test.gif)