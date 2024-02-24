# 捐助 OSS 项目

> 此版本为社区翻译的非官方版本，仅供参考之用。请以官方文档为准。\
> 原文：[https://docs.tea.xyz/tea/i-want-to.../begin-earning-tea-and-interact-with-the-protocol/donating-to-oss-projects](https://docs.tea.xyz/tea/i-want-to.../begin-earning-tea-and-interact-with-the-protocol/donating-to-oss-projects)

通过 _**tea**_ 协议向 OSS 项目捐款可以让您直接支持您所依赖和欣赏的开源软件的开发和维护。捐款还会影响到依赖项，为软件构建提供坚实的基础。

通过 _**tea**_ 协议捐款为您提供了一种跟踪和审计您或他人对任何 OSS 项目所做捐款的方式。由于所有捐款都存储在区块链上，捐赠者自动获得链上认可，因为他们的捐款对其他社区成员来说是可见的。这种透明度和问责制对用户和包维护者都非常重要，这是通过区块链提供的不可变账本的力量实现的。

### 捐款如何在项目的依赖项之间分配？

每个收到捐款的项目保留捐款金额的 80%，并根据其 teaRank 将剩余的 20% 分配给其依赖项。每个依赖项反过来保留它们收到的捐款的 80%，并将剩余的 20% 根据其 teaRank 分配给它们自己的依赖项。这种分配持续迭代，直到达到堆栈的底部。

例如，假设项目 `foo` 有 2 个依赖项 `fee` 和 `bar`。

* `fee` 的 teaRank 是 35，
* `bar` 的 teaRank 是 65。

假设 `foo` 收到了 10,000 USDC 的捐款。`foo` 将保留 8,000 USDC，剩余的 2,000 USDC 将按以下方式在 `fee` 和 `bar` 之间分配：

* `fee` 收到 (35 / (35+65)) = 35% 的 2,000 USDC，即 700 USDC
* `bar` 收到 (65 / (35+65)) = 65% 的 2,000 UDC，即 1,300 USDC

现在假设 `bar` 有 2 个依赖项：`fie` 和 `foe`。

* `fie` 的 teaRank 是 10，
* `foe` 的 teaRank 是 20。

`bar` 收到了 1,300 USDC，并保留 1,300 x 80% = 1,040 USDC，留下 260 USDC 在 `fie` 和 `foe` 之间分配。

* `fie` 收到 (10 / (10+20)) = 33.3% 的 260 USDC，即 86.7 USDC
* `foe` 收到 (20 / (10+20)) = 66.7% 的 260 USDC，即 173.3 USDC

### 如何在 _tea_ 协议上向 OSS 项目捐款

当 _**tea**_ 激励测试网启动时，按照以下步骤向您选择的项目捐赠 TEA：

1. 导航到您的 _**tea**_ 仪表板中的 OSS 质押界面。
2. 搜索并选择您想要捐赠的项目。
3. 向下滚动并从“通过捐款支持 `ProjectName`卡片中复制项目的地址。
4. 使用您的 _**tea**_ 本地数字钱包向复制的地址发送所需数量的 TEA 代币以进行捐赠。
5. 等待交易确认。
