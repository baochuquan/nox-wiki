---
layout: default
title: jenkins
parent: 工具索引
nav_order: 3
has_children: false
---

*  目录
{:toc}

---

## ape-ios
`nox jenkins ape-ios`

```shell
Usage:
    ape-ios [--branch branch-name] [--target target-type] [--trigger-users user1[,user2,user3...]]

Description:
    打包 ape-ios 项目

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --branch|-b:                                        -- 分支，如果没有指定该选项，则默认为 master 分支
    --target|-t:                                        -- 包类型，包括：alpha, beta, dev, appstore，如果没有指定该选项，则默认为 beta 类型
    --trigger-users|-u:                                 -- 通知指定 ldap 用户，如果没有指定该选项，则默认为 config.yaml 中 ldap 指定的用户

```

---

## leo-ios
`nox jenkins leo-ios`

```shell
Usage:
    leo-ios [--branch branch-name] [--target target-type] [--trigger-users user1[,user2,user3...]]

Description:
    打包 leo-ios 项目

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --branch|-b:                                        -- 分支，如果没有指定该选项，则默认为 develop 分支
    --target|-t:                                        -- 包类型，包括：alpha, beta, dev, release, appstore, after_release，如果没有指定该选项，则默认为 beta 类型
    --trigger-users|-u:                                 -- 通知指定 ldap 用户，如果没有指定该选项，则默认为 config.yaml 中 ldap 指定的用户

```

---

## solar-flutter
`nox jenkins solar-flutter`

```shell
Usage:
    leo-ios [--branch branch-name] [--target target-type] [--trigger-users user1[,user2,user3...]]

Description:
    打包 leo-ios 项目

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --branch|-b:                                        -- 分支，如果没有指定该选项，则默认为 develop 分支
    --target|-t:                                        -- 包类型，包括：alpha, beta, dev, release, appstore, after_release，如果没有指定该选项，则默认为 beta 类型
    --trigger-users|-u:                                 -- 通知指定 ldap 用户，如果没有指定该选项，则默认为 config.yaml 中 ldap 指定的用户

```

---

## solar-ios
`nox jenkins solar-flutter`

```shell
Usage:
    solar-ios [--branch branch-name] [--target target-type] [--trigger-users user1[,user2,user3...]]

Description:
    打包 solar-ios 项目

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --branch|-b:                                        -- 分支，如果没有指定该选项，则默认为 develop 分支
    --target|-t:                                        -- 包类型，包括：alpha, beta, dev, release, appstore, afterRelease,orientation,scan，如果没有指定该选项，则默认为 beta 类型
    --trigger-users|-u:                                 -- 通知指定 ldap 用户，如果没有指定该选项，则默认为 config.yaml 中 ldap 指定的用户

```


如下所示：

![](https://chuquan-public-r-001.oss-cn-shanghai.aliyuncs.com/nox/nox-jenkins-solar-ios.gif)

---

## venus-ios
`nox jenkins venus-ios`

```shell
Usage:
    venus-ios [--branch branch-name] [--target target-type] [--trigger-users user1[,user2,user3...]]

Description:
    venus-ios 相关功能

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --branch|-b:                                        -- 分支，如果没有指定该选项，则默认为 develop 分支
    --target|-t:                                        -- 包类型，包括：alpha, beta, dev, appstore，如果没有指定该选项，则默认为 master 类型
    --trigger-users|-u:                                 -- 通知指定 ldap 用户，如果没有指定该选项，则默认为 config.yaml 中 ldap 指定的用户

```