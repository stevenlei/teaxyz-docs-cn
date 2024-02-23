# 投票机制

> 此版本为社区翻译的非官方版本，仅供参考之用。请以官方文档为准。\
> 原文：[https://docs.tea.xyz/tea/i-want-to.../learn-about-teas-governance/voting-mechanics](https://docs.tea.xyz/tea/i-want-to.../learn-about-teas-governance/voting-mechanics)

投票将通过 Snapshot 进行链下投票。

链下投票解决了使用 stTEA 确定参与者投票权力的独特挑战——每个参与者投票权力的分配。

当参与者将 TEA 质押到 OSS 项目并收到不可转让的 stTEA 时，他们的投票权力表示为在所有质押的 OSS 项目中质押的所有 TEA 的总和；然而，他们的 stTEA 余额分布在他们个人质押的所有项目中。此外，如果在质押的 OSS 项目中发现漏洞，每个参与者的投票权力可能会减少，因为质押的 TEA（及相关的 stTEA）可能会被削减。

链下投票允许对每个参与者的投票权力进行可审计的链下计算，并提供一种节省 gas 的方法来收集投票权力。

每次投票的法定人数定义为基于相对于流通 TEA 供应量的总票数的最小百分比。投票权力与持有的 stTEA 量成比例，相对于总流通 TEA 供应量。

{% hint style="danger" %}
分配给 teaRank 或质押奖励池且尚未分发给项目的 TEA 代币被排除在总流通 TEA 供应量计算之外。这两个池的发行曲线是保守的，跨越 50 年。
{% endhint %}

{% hint style="info" %}
链下投票还提供了增强的速度和灵活性，允许在不受区块链交易时间限制的情况下迅速做出决策。它还允许更大的投票者隐私，减轻了网络的负担，并利用了链下平台的既定安全措施，为协议的早期阶段提供了更安全、更高效的治理机制。
{% endhint %}

