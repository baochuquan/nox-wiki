---
layout: default
title: gerrit
parent: 工具索引
nav_order: 1
has_children: false
---

---

## init
`nox gerrit init` 

```shell
Usage:
    init

Description:
    用于在工程中自动生成 changeId、移除代码连续空行、移除多余的后缀空格

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
```

---

## submit
`nox gerrit submit`

```shell
Usage:
    submit                                              -- 静默提交，reviewer 是自己
    submit --notify                                     -- 企业微信通知 reviewer
    submit --reviewers user1[,user2,...] [--notify]     -- 提交并通知自己
    submit --solar-ios-reviewers [--notify]             -- 提交并通知小猿搜题 iOS 用户组

Description:
    在 git 仓库中向 Gerrit 提交 code review

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --notify|-n:                                        -- 是否向 reviewer 发送企业微信通知
    --reviewers|-r:                                     -- 指定 ldap 用户为 reviewer，user1(,user2,...)
    --solar-ios-reviewers|-s:                           -- 指定小猿搜题 iOS 用户组为 reviewer
```

如下所示：

![](https://chuquan-public-r-001.oss-cn-shanghai.aliyuncs.com/nox/nox-gerrit-submit.gif)