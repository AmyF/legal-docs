---
title: QuickNAS 支持
description: QuickNAS 支持与 Bug 报告指南
permalink: /quicknas/support-zh
last_updated: 2026-02-13
---

# QuickNAS 支持

最后更新：2026年2月13日

需要 QuickNAS 帮助？本页说明如何联系我们，以及哪些信息能帮助我们更快定位问题。

## 1. 联系方式

- 支持邮箱：`support@unko.fun`
- 服务条款：[QuickNAS 服务条款](/quicknas/terms-zh)
- 隐私政策：[QuickNAS 隐私政策](/quicknas/privacy-zh)

## 2. 联系支持前请准备

请准备以下信息：

- QuickNAS 应用版本和构建号
- macOS 版本
- 使用的登录方式（Direct URL 或 QuickConnect）
- 问题发生在直接上传模式还是上传并分享模式
- 复现步骤
- 期望结果与实际结果

## 3. 推荐：在应用内报告 Bug

在 QuickNAS 中：

1. 打开 **Settings**
2. 前往 **About**
3. 点击 **Report Bug (support@unko.fun)**

QuickNAS 会先生成邮件草稿，并附带近期诊断信息供你确认。

常见附件包括：

- `support-info.json`（应用/环境快照）
- `recent-client.log`（近期客户端日志）
- 包含上述文件的 ZIP 包（打包成功时）

发送前你可以查看并编辑全部内容。

## 4. 手动邮件模板

如果你更倾向手动发送邮件，请发到 `support@unko.fun`，并包含：

- 主题：`[QuickNAS Bug] <version> (<build>)`
- 设备/macOS 信息
- NAS 端点类型（Direct URL 或 QuickConnect）
- 错误信息文本（尽量完整）
- 复现步骤
- 截图或日志（如有）

## 5. 常见问题

### A. 无法连接到 NAS

请检查：

- NAS 地址/QuickConnect ID 是否正确
- 当前网络下是否可访问 NAS
- NAS 所需端口和协议配置是否正确

### B. 会话需要重新登录

可能原因：

- NAS 会话已过期
- 密码/OTP 已更改
- 账户端点设置被修改

请在账户详情页重新登录以恢复会话。

### C. 上传冲突处理与预期不符

请检查 **Settings > General > Duplicate File Handling**：

- **Overwrite**：覆盖目标路径中的同名文件
- **Skip**：仅跳过冲突文件，其他文件继续上传

### D. 上传并分享打包问题

对于多文件（或需要打包的文件夹上传），QuickNAS 会应用已配置的打包大小限制。

- 当前应用限制最高支持 4 GB 打包大小
- 超出限制时，请调整设置或拆分上传

## 6. 支持范围

我们可以协助：

- QuickNAS 应用行为问题
- QuickNAS 中的登录/会话流程
- 上传/分享流程与设置行为
- 应用日志解读

以下情况可能无法提供完整支持：

- 与应用行为无关的 NAS 固件/服务端内部问题
- 第三方网络基础设施问题
- QuickNAS 之外的自定义脚本/插件

## 7. 响应时间

我们会尽快回复。实际响应时间取决于问题复杂度和消息量。

提供完整复现步骤和日志可以显著加快排查。
