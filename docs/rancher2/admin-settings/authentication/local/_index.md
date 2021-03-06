---
title: 本地验证
description: 在配置外部身份验证系统之前，您将默认使用本地身份验证。本地身份验证是 Rancher 通过验证存储在本地的用户名和密码，对用户进行验证，验证通过后可以登录到 Rancher。默认情况下，用于首次登录 Rancher 的 `admin` 用户就是一个本地用户。无论是否使用外部身份验证，都应创建一些本地身份验证用户，以便在外部身份验证服务遇到问题时继续使用 Rancher。
keywords:
  - rancher
  - rancher中文
  - rancher中文文档
  - rancher官网
  - rancher文档
  - Rancher
  - rancher 中文
  - rancher 中文文档
  - rancher cn
  - 系统管理员指南
  - 登录认证
  - 本地验证
---

在配置外部认证系统之前，您将默认使用本地身份认证。本地身份认证是 Rancher 通过验证存储在本地的用户名和密码，对用户进行验证，验证通过后可以登录到 Rancher。默认情况下，用于首次登录 Rancher 的 `admin` 用户就是一个本地用户。

## 添加本地用户

无论是否使用外部认证系统，都应创建一些本地身份认证的用户，以便在外部认证服务遇到问题时继续使用 Rancher。

1. 在**全局**视图中，在导航栏中选择**用户**。

2. 单击**添加用户**。完成**添加用户**表单信息填写。单击**创建**按钮，完成用户创建。
