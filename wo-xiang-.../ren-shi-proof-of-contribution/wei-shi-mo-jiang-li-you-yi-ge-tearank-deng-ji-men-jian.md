# 为什么奖励有一个 teaRank 等级门槛？

> 此版本为社区翻译的非官方版本，仅供参考之用。请以官方文档为准。\
> 原文：[https://docs.tea.xyz/tea/i-want-to.../learn-about-proof-of-contribution/why-is-there-a-tearank-threshold-for-rewards](https://docs.tea.xyz/tea/i-want-to.../learn-about-proof-of-contribution/why-is-there-a-tearank-threshold-for-rewards)

_**tea**_ 协议在每个 epoch 中分配预设的 teaRank 奖励给注册项目。一个项目接收的 TEA 数量与其 teaRank 成正比。然而，只有达到一定 teaRank 阈值的项目才有资格领取奖励。

设置奖励阈值有两个主要目的：

1. 确保 teaRank 奖励公平地分配给有重大影响的 OSS 项目；
2. 通过阻止大量低 teaRank 项目吸引大量的 teaRank 奖励从而远离更有影响力的项目，来遏制垃圾邮件发送者。例如，100,000 个低 teaRank 项目每个接收 1 TEA 将导致从有影响的项目中拿走 100,000 TEA 代币。

目前接收 teaRank 奖励的阈值设置为 27（满分为 100）。即项目要接收 teaRank 奖励，其 teaRank 分数必须等于或大于 27。尽管这个阈值是在分析目前支持的包管理器中所有 OSS 项目的 teaRank 之后设定的；但它是一个可以通过 teaDAO 治理过程调整的协议参数。
