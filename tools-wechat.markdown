---
layout: default
title: wechat
parent: 工具索引
nav_order: 8
has_children: false
---

---

## serve-notify
`nox wechat serve-notify`

```shell
Usage:
    serve-notify --message message --users user1,user2 ...
    serve-notify -m message -u user1,user2,...

Description:
    通过服务通知向指定 ldap 的用户发送企业微信

Option:
    --help|-h:                                          -- 使用帮助
    --debug|-x:                                         -- 调试模式
    --message|-m:                                       -- 指定消息内容
    --users|-u:                                         -- 指定 ldap 用户
```