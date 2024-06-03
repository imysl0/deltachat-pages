---
title: Chatmail for instant, interoperable and privacy-preserving messaging
lang: zh_CN
---

## 什么是 Chatmail 服务器，如何选择？

<img alt="Chatmail logo" src="../assets/logos/chatmail.svg" width="80" style="float:right;" />

Chatmail 服务器为 Delta Chat 优化，提供保护隐私且快速的用户体验，使Chatmail 和传统电子邮件服务器可以安全互通。
**点击 Chatmail 服务器链接** 查看主页，然后点击那里的 QR 邀请码：

- [nine.testrun.org](https://nine.testrun.org) 是 Delta Chat 应用的默认 Chatmail 服务器，自 [2023年12月 Chatmail 公告](https://delta.chat/en/2023-12-13-chatmail) 以来一直稳定运行。

- [mehl.cloud](https://mehl.cloud) 面向德语用户，自 2024年1月 以来一直稳定运行。

- [mailchat.pl](https://mailchat.pl) 面向波兰语用户，自 2024年1月 以来一直稳定运行。

- [bcc.chat](https://bcc.chat) 在美国运营，自 2024年2月 以来一直稳定运行。

- [chatmail.woodpeckersnest.space](https://chatmail.woodpeckersnest.space/) 面向意大利语用户，自 2024年5月 以来一直稳定运行。

所有 Chatmail 服务器由不同的团体和人员运营。
nine.testrun.org 默认服务器由 Delta Chat 核心团队成员运营。

## 我可以使用常规电子邮件服务器代替 Chatmail 吗？

是的，许多用户成功地使用常规电子邮件服务器，特别是如果他们希望使用 Delta Chat 处理他们的常规电子邮件通信。
查看 [供应商数据库](https://providers.delta.chat) 了解选项。
请注意，Delta Chat 支持多账户，因此可以配置一个账户使用您的常规电子邮件地址，另一个账户用于聊天。

## Chatmail 服务器与电子邮件服务器有何不同？

Chatmail 服务器是为速度、安全性和便利性设计的最小化电子邮件服务器：

- **便利性：** 自动登录仅需几秒钟，并接收推送通知

- **隐私：** 不提问任何问题，不需要姓名、数字或电子邮件

- **速度：** 消息传递在不到一秒钟内完成，端到端

- **可靠性：** 没有烦人的垃圾邮件检查或速率限制

- **安全性：** 出站消息必须端到端加密，
  入站消息严格检查真实性。

## Chatmail 服务器有多可信？

每个 Chatmail 服务器在其网页上提供额外的隐私信息。
通常，Chatmail 服务器只处理加密消息，
并实施自动、无条件的消息删除，最多保留 20 天。

Delta Chat 提供 [保证的端到端加密](https://delta.chat/en/2023-11-23-jumbo-42) 
这意味着在大多数使用情况下，即使服务器运营商尝试，也无法阅读您的信息，
这一保证得到了 ETH Zuerich 最近的 [安全分析](https://delta.chat/en/2024-03-25-crypto-analysis-securejoin) 的支持。

## 如何运行 Chatmail 服务器？我可以自己运行一个吗？{#selfhosted}

所有 Chatmail 服务器都使用 [公共 Chatmail 开发存储库](https://github.com/deltachat/chatmail) 自动部署和更新。
Chatmail 服务器由经过验证的标准电子邮件服务器组件组成，
[Postfix](https://postfix.org) 和 [Dovecot](https://dovecot.org)，
配置为无人值守运行，并且需要非常低的维护工作量。
Chatmail 服务器可以在低端硬件上愉快地运行，如 Raspberry Pi。

# Chatmail 服务器是如何获得资金支持的？

Chatmail 服务器在设计上就考虑了低成本运营，
它们通常由运营商自筹资金。
请查看每个 Chatmail 服务器的首页以获取更多信息。

为了支持 Chatmail 的开发和运行默认的登机服务器，
非常欢迎您贡献力量。

[捐助钱款](donate){: .cta-button}
