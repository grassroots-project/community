# 第七课、Derivative Securities & Other Skills for Macro Trading

### 一、DERIVATIVE SECURITIES

在前面数篇中，我们反复强调 Trader 最重要的工作应该是观察资金流。这样就有一个很自然的推论：任何可能显著推动资金流的因素，都是需要 Trader 密切关注的。所以，由于认为负债对资产的驱动是影响力最大的资金流，我们将 Monetary Economics 放在最重要的 Skill Sets 之列。此外，还专门开《Trading Skills》篇讨论观察资金流和布局 Front Run 的技巧。如果还有其他因素可能对资金流形成类似的影响，Trader 也都必须一丝不苟的观察和推演。在 Macro Finance 领域，Derivatives 同样也可能引发重大的资金流转换。因为 Macro Finance 最常见的工具，如利率、汇率和股指，都是 Derivatives 呼风唤雨的领域，许多震撼市场的资金流是 Derivatives 产生的。而且，由于 Derivatives 引起的资金流规律性更强一些，如果能把握好这类型的资金流，就有能力做出非常漂亮的 Trade. 所以，称职的 Macro Trader 必须有能力做出扎实的 Derivatives 分析。

Derivatives 同样也是很折磨人、门槛极高的一个行当，好在 Macro Trader 们学习 Derivatives 并不是要成为 Financial Engineer，只是希望推演出市场上的 Derivatives 头寸在市场波动时其 Hedging 方式可能产生的资金流。所以 Macro Trader 并不需要精通 Stochastic Calculus，但必须对如下问题有透彻的了解。第一，市场结构问题，包括谁在买 Derivatives? 为什么买 Derivatives? 投行怎么卖 Derivatives？这其实也是分析如下问题：作为一个金融产品，Derivatives 的负债是如何驱动其资产的。第二，Derivative Flow 如何产生，尤其是 Gamma 和 Vega 的变化是否可能产生大量的 Delta Hedge 需求或者 Volatility Hedge 需求。这些问题的答案只能从金融市场客户特性中寻找，而且每个市场的客户习惯都不一样。比如爱投机的华人客户喜欢 FICC 领域的杠杆 Exotic Option 类产品，而韩国客户喜欢大手大脚做欧美股指类衍生品。所以，Macro Trader 最好是请教一位 Derivative Sales 或者 Structurer，不一定需要请教 Quant.

《熊猫笔记：20150824》记述了一个奇特的案例。我们都记得 811 汇改之后，CNH 缓步贬值了大约两个星期，然后突然在 8 月 24 日出现巨量的 USD/CNH 买盘。与此同时，CNH 的 Vol 大幅飙升，又影响到其他 CNH 资产。如果从 CNY 汇率机制上找这个现象的解释，肯定一无所获，因为这个奇特现象的发源地，不是 CNY 市场，而是 CNH Derivatives 市场。

我们提到华人特别喜欢汇率方面的杠杆投机 Exotic Option. 从 2013 年开始，由于 PBoC 长期压了汇率波动性，维持高 Carry，许多香港和台湾资金涌入 CNH 市场，玩形形色色的杠杆 CNH 投机产品，以 TARF 最为流行。下图描述了一个典型的 TARF 结构。这个 TARF 期限是 12 个月，期间每月如果 USD/CNH 汇率低于 6.35，客户就按 6.35 购入 10mio USD/CNH，如果在 6.35 到 6.6 之间，就按当时市场价格购入 10mio USD/CNH，如果 USD/CNH 高于 6.6，则客户必须按 6.35 的价格购入 20mio USD/CNH. 可以看出这是一个 Exotic Option，其复杂的结构完全是为了适应华人投机资金又贪又抠门，既酷爱投机交易，又舍不得支付初始费用的习惯。

![img](https://quip.com/blob/PDKAAAXI1m9/AHLnwrGIqrUHCafNFFXR2w?a=xrpmg1cZmlSPmBzNySiDeaaPYWCTAaCOnZ5Bhzdui4Ma)

我们提到 Macro Trader 研究 Derivatives 的视角是 Flow 观察者而不是 Quant，所以不需要掌握 Exotic Option 中那些折磨人的数学工具，只需要了解其结构后，知道如何使用 Quant 们做好的 Derivatives 软件做分析就可以。对接受过 Derivatives 基本训练的 Trader，使用这些软件计算这些 TARF 的 Delta、Gamma 和 Vega 并不难，计算结果见下图。再结合 Sales 和 Structurer 提供的估算，可知 2015 年 8 月前后市场上大约有 400 亿美元的 CNH TARF. 出售这些 TARF 的投行需要时刻对冲额外的 Vega 和 Gamma. 从 Vega 图可见，由于 TARF 结构复杂，对冲需求并不是线性的，在 6.4 以上，也就是 TARF 的 Strike 附近，Vega 会突然增加，产生大量的 USD/CNH Vol 买盘和 USD/CNH Spot 买盘。

![img](https://quip.com/blob/PDKAAAXI1m9/OEGxr0aGrdJmMBK4ccWJHw?a=zEbnsvN80cucQL8M1P9aAauo6Bxtl0zuARGzKoN52LEa)

![img](https://quip.com/blob/PDKAAAXI1m9/8nWbqlExHgcLtniiE8F-ng?a=1uXsB2CWO3gGXACykainrCy6j4BNkIOwM32lHtUjHL0a)

811 以后将近两周时间，CNH 慢慢贬值，市场波动看似缓和，其实已经暗流涌动接近 Vega 爆发点了。8 月 22 日是个周五，当天纽约时间，USD/CNH 汇率悄悄突破了爆发点。收市之后，许多投行的拿收市价格一算，就发现自己的 TARF Book 各项风险指标普遍大幅超标，必须加量对冲了。于是周一 8 月 24 日，CNH 市场突然被汹涌的 USD/CNH Vol 买盘和 USD/CNH Spot 买盘淹没。再按照《Case Study: HIBOR and CNH FX Puzzle》中推演的机制，大量的 USD/CNH 买盘将剧烈消耗 CNH 流动性，同时催动所有 CNH 资产的全面下跌，又进一步产生大量的 USD/CNH 平仓需求，形成螺旋式的自我强化。幸好金管局及时向市场提供了 CNH 流动性，否则香港金融机构可能会面临意外的金融稳定风险。

所以，了解 CNH Derivatives 市场之后，才能解释为什么 CNH 市场的最大冲击会拖了两个星期而姗姗来迟，但一露面就凶悍残忍，几乎重手废掉了整个 CNH 市场，甚至威胁金融稳定。

### 二、POLITICS

政治分析是 Macro Trader 最容易迷失的方向。一方面，政治因素往往对整个市场都形成震撼。对政治环境和金融环境欠发达的 EM，政治变乱往往能让 EM 金融市场不死也只剩半条命，给空头们巨大的机会。但另一方面，政治分析不是 Trader 们所擅长，但是狂妄自大的 Trader 们（这个行当极易偏执，很难谦卑），往往读几篇街头报告就信心十足，轻率的犯下错误。典型的例子比如公投之类的，特点是参与人群无序、信息杂乱、方向混沌，这往往成为神人最集中的地方，隔壁老王跟基友撸个串回来都能讲一大堆故事做一个高明的判断，但其实都是盲人摸象。

那么 Trader 们是否需要恶补自己的 Politics 知识？有条件的话补一点当然最好，但我也不赞成把这当成 Trader 的主攻方向。Trader 们最擅长的，应该还是对资金流 Flow Chart 的把握。所以，我建议 Trader 们研读政治分析时不以判断结果为目的，而是以设计尽可能全面的 Scenario，仔细推演。对 Trader 们，最合理的位置是不主动在政治事件上下注，但是对 Political Scenario 有扎扎实实的推演。所以当 Flow Chart 面临冲击时，Trader 们总能有足够的时间和空间，识别 Flow Chart 出现的传导失误或者低效转换，从而轻松的 Front Run 其他资金。

### 三、PORTFOLIO MANAGEMENT SKILLS

以上我们花了大量的篇幅谈论 Macro Trader/PM 需要的技能，对 Trader/PM 需要的一般性技能较少涉及。这主要是因为一般性技能的资料已经足够丰富了，例如本人最喜欢的

*Efficiently Inefficient: How Smart Money Invests and Market Prices Are Determined*

，对 Smart Money 应该具备的技巧就有很丰富的阐述。

强调一下，Portfolio Managment 方面的一般性技巧，例如 Portfolio Analysis，是 PM/Trader 的基本功。如果基本功不合格，即使 Monetary Economics/Macroeconomics 等方面非常出色，做一个 PM/Trader 也是有隐患的。这也是很多才华出众的人能做很好的研究，但是在 PM/Trader 职位上败退的原因。作为研究员，你只需要练好一部分 Skill Sets，但如果是 PM/Trader，那就需要掌握尽可能全的 Skill Sets，以避免犯错。如果掌握的 Skill Sets 有缺陷，建议 PM/Trader 应该有自知之明，宁可放弃一些很诱人的策略，以避免暴露短板。

越全面、越深刻的 Macro Trader，对市场的认识往往会越来越市侩，尤其不应该把做史诗级 Trade 当成自己的职业理想。只要人还在市场中，该抓住的资金流基本抓到，愚蠢的错误尽量少犯，多年以后，一个不败传奇就自然而然的形成了。