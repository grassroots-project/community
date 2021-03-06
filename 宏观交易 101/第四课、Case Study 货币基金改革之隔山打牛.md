# 第四课、Case Study: 货币基金改革之隔山打牛

证券基金系统的改革，证券基金市场表示情绪稳定，利率市场鸭梨山大...

Onshore 利率市场的变化，Onshore 玩家表示情绪稳定，Offshore 市场鸭梨山大...

日本银行业美元流动性的紧张，日本银行业表示积极解决，美国国债市场鸭梨山大...

《Monetary Economics》篇多次提到，如果 Flow Chart 的结构发生变化，遵循原有 Flow Chart 流动的资金将不得不改道。如果受影响的资金很多，这批资金将搅动着洪荒之力，透过 Flow Chart 里那些最脆弱的环节，裹胁大群无辜吃瓜群众，在整个市场呼啸。市场里各式玩家的来来去去看似波澜壮阔，其实也就是海面上的风浪。而 Flow Chart 的变化，相当于海啸，事先没有征兆但突然就排山倒海搅动天地。2016 第三季度由于美国货币基金 2a-7 改革而引发的一系列变动，是一个绝佳的例子，说明货币传导机制里一个不起眼的变化，由于发生在最脆弱的环节，其传导和连带效应是如何让整个市场都受到意外影响的。

### 一、货币基金：不是银行，胜似银行

货币基金的管理极其无趣，然而货币基金的独特机制和独享特权，让每一个债券基金经理都眼红。《Monetary Economics》篇提到，判断是否有信贷创造，是依据 Dealer 是否能仅以少量的基础资产就能维持大量的偿付请求。最典型的例子是银行，只需要一点流动性准备，就能向所有的存款客户承诺兑付。而证券投资基金，虽然客户也能够赎回并获得现金，但是基金管理人不能承诺兑付，只能规规矩矩按照净值支付给投资者，投资者需要自行承担投资组合波动的风险。所以证券投资基金不是信贷机制，只是一个通道机制。但是固定面值(CNAV, Constant NAV)的货币基金是承诺足额兑付的。虽然这些 CNAV 基金投资组合里并不全是现金或者国债等流动性和安全性最高的基础货币类资产，而是有大量 CP/CD 等在 Flow Chart 中扩张出的信贷派生资产，严格来说是不能足额提前兑付的，但是货币基金仍然拍着胸脯承诺足额面值兑付。而且，货币基金承诺的流动性是全额T+1 甚至 T+0（各国货币基金可能会有不同，但都是仅次于即时）。这比银行定存都厉害，跟银行的储蓄账户差不多了。所以，在美国的货币统计体系里，Retail Money Market Fund 是被列入 M2 统计的。

这么牛的产品，自然必须有很多特权。最眼红的特权是 CNAV 基金可以用摊余成本法记账，货币基金经理基本上不用在乎投资组合净值波动，只需要算算每天的利息收入，然后分配给投资者就行了。这一点比银行都牛。银行存款也是摊余成本记账，但为了能够使用成本法，银行除了忍受繁杂的贷款风险管理监管，还必须保有相当的一级和二级资本。因为如果贷款出损失，或者投资没有办法兑付收益，银行是需要从资本里掏钱支付给投资者的。这些资本是为了能够让成本法正常运行必须提供的 Buffer. 然而货币基金就不需要 Buffer，货币基金经理们表示投资者进进出出很常见，就算赎回导致投资组合已经资不抵债，过一阵子就回来了。所以，在货币基金里，为先赎回的投资者当 Buffer 的其实是后知后觉的投资者。如果货币基金挤兑，那么投资组合就会越跌越惨，一旦炮灰接济不上，Buffer 们就会发现货币基金有赖账的风险。

可想而知，这种特权在监管者眼中多么扎眼。更要命的是，货币基金一旦发生挤兑几乎必然是全行业的挤兑，同时还会阻断大批企业和金融机构的短期融资渠道，后果不堪设想。所以，自从 1971 年货币基金诞生开始，一代代监管者们都试图与货币基金作斗争。然而，监管者们撼不动成本法，只能在投资风险上多做文章。以美国为例，旨在监管货币基金投资风险的 2a-7 法则从 1983 年发布开始，历经多次艰难的修订，限制 Duration Credit Risk Liquidity 等等等等，但还是防不住历史最悠久的 Reserve Primary Fund 在 2008 年因为踩中 Lehman 的坑而不得不跌破净值，先冻结后清盘。一大批投资者眼睁睁看着号称安全性流动性堪比现金的货币基金投资不仅不能兑付，还一路下跌，最惨的时候跌去 5%. 为了阻止可能出现的全行业挤兑和和对整个金融市场的冲击，FED 迅速宣布 Money Market Investor Funding Facility，对货币基金行业提供高达 6000 亿美元的流动性支持。这个 Facility 虽然一分钱都没有实际动用，但是被认为是金融危机中最正确的决定之一。

缓过气来后，监管者们痛定思痛，进一步限制 CNAV 型货币基金的空间。欧洲由于 VNAV 型基金（Variable NAV，浮动净值型）占据半壁江山，CNAV 无法独占话语权，所以改革阻力稍小，进展快一些。而美国 SEC 则遭遇了 CNAV 型基金群体的激烈抵抗，最终铁娘子 Mary Jo White 击败了阻挠者，于 2014 年 7 月 23 日宣布，从 2016 年 10 月 14 日起实施新的 2a-7 监管规定。虽然铁娘子仍然无法取消 CNAV，但是她极大压缩了 CNAV 的空间。相关细则，读者可以自行寻找相关资料阅读，只需要了解一点，有大概 1 万亿美元的资金，不得不转型为 VNAV，也就是由信贷机制转换为通道机制。通道机制的效果是集结零散资金投资，虽然也可以投资，但是效率比起能轻松翻番的信贷机制要差一些。所以对这些 VNAV，虽然他们仍然可以投资 CP 和 CD 之类的产品，但是胃口将极大受限。

其他改革措施，比如市场上还有很多人在讨论的国债投资期限和流动性准备方面的限制，我并不准备特别考虑，因为《Monetary Economics》篇提到，国债也有基础货币的职能，所以，一个平均期限 30 天的国债、现金和回购投资组合，和平均期限 300 天的国债投资组合，对 Flow Chart 不会有实质性的差异。

考虑到读者范围，简单引用一个研究结论：大约有 3000-5000 亿美元的资金，以前一直依靠向货币基金发行 CP/CD 市场融资的，将不得不寻找新的融资路径。毫无疑问，市场融资利率将会升高。但是作为 Macro Trader，我们更感兴趣这些资金承载的资产是什么。利率上行和融资利率的升高将压制这些承载资产的吸引力，这时候还持有这些资产可要当心。更重要的是，如果投资者缺乏新融资路径或者难以忍受高昂的融资成本，他们不得不卖掉资产，偿还债务，缩表走人。这时候 Macro Trader 将有一个绝佳的 Front Run 这些头寸的机会。

### 二、ONSHORE 平平淡淡

我们已经意识到，虽然 2a-7 改革纯粹是一个证券投资基金改革，但这是在 Flow Chart 的一个重要节点上动刀，效果相当于收紧流动性。

2a-7 改革对证券投资基金业的影响，主要是事务性的，没有太多实质性影响。货币基金投资管理方面，美国基金经理们历经多年磨难已经相当成熟，风险偏好不大。应对 2a-7 改革的工作，更多是体现在拆分或者成立新基金、修订基金合同、聘请新受托人等等法律事务工作，投资组合调整反而不大。货币基金投资人方面，QE 和零利率以后，投资者已经习惯了货币基金收益长期徘徊在几个 BPs，而 CNAV 货币基金方便记账、没有银行交易对手风险等好处对企业 CFO 和 PM 们还是挺有吸引力，所以即使 2a-7 可能降低 CNAV 基金的收益率，投资者仍然高高兴兴的把钱放到新的 CNAV 基金里。所以美国货币基金的 AUM，其实没有发生太大的变化。结构转换方面，主要的货币基金早在 2016 年 1 季度就开始转换，在 7 月份开始进入转换高峰，10 月初基本已完成。整个转换过程应该说是平稳有序的，毕竟整个行业为这次转换已经准备了两年多的时间。

![img](https://quip.com/blob/PDKAAAXI1m9/bRNyTgs8_TMk_rYZrkpXoA?a=flTYbCHUZJeXo6ELzUDWaaahyFHElWS9rP6fuyasa7ga)

对利率市场的影响，则体现在数千亿美元需要寻求新的融资途径，这样势必会造成融资利率的上行。由于 3 个月是美国 CP 市场的主要融资期限，所以进入 7 月份以后（在 10 月份截止前发行 3 个月 CP 的最后期限），3 个月期限 LIBOR/OIS Spread 一路飙升，接近 5 年以来的最高点。但是这只是价的变化，并不是 Macro Trader 最关注的量的变化。量方面，美国银行业还堆积着超过 2 万亿美元的超额准备金，能够轻松抹平本土市场可能出现的流动性青黄不接。所以本土市场，除了融资利率上升十几个 BPs 让融资者颇为不爽以外，正常的融资能够继续进行。本土的波澜不惊还体现在美国本土机构的融资利率其实还算稳定，下图亮黄线显示金融机构 CP 融资利率上行幅度低于 LIBOR，绿线显示非金融企业的 CP（70% 为美国企业）更是几乎没什么变化。（9 月底的 OIS 和 CP 利率的走高是因为考虑了 12 月份加息预期）

![img](https://quip.com/blob/PDKAAAXI1m9/yrM88hQbwQO7_29E67ho7A?a=dkg1HAbcYGV0t7aoJaAI2CjKxMPzKMUynRpaZlC9Daoa)

### 三、OFFSHORE 好戏连台

《Monetary Economics》篇提到，美元是真正的全球货币，主要金融机构都有大量的美元需求。体现在地域上，就是离岸美元市场极其庞大。仅以 CP 市场为例，2016 年 6 月底外国金融机构在美国发行了 2700 亿美元的 CP 来融资，此外还有体量更庞大的欧洲美元 CP 市场，2016 年 6 月底规模超过 5500 亿美元，其中有一半是美元。美国金融机构也喜欢庞大的离岸市场，Prime Money Market Fund 的投资中，在美国本土的经常不到一半，大部分投资投在欧洲、亚洲和其他离岸美元市场。

虽然货币基金改革影响全部的离岸美元市场，但欧洲银行业压力比日本银行业小。这是因为欧洲的离岸美元市场发展已经相当成熟，资金来源多样化，玩家多样化，货币体系抗冲击能力强。而日本银行业明显玩的太 High 了。据估算，日本银行业在美国的分支机构通过 CP、CD 等市场融入的美元在 2016 年 1 季度末超过 6000 亿美元。毫无疑问，当 Prime Money Market Fund 不得不关闭 CP/CD 窗口的时候，日本银行业的重要美元融资渠道被严重压缩了。

外国金融机构用 CP/CD 市场搞那么多美元拿来做什么？必须搞明白这个问题才能理出 Flow Chart 中最值得攻击的环节。Credit Suisse 的 Zoltan Pozsar 列举了 4 项，分别是进行 IOER 套利、补充监管要求的高流动性资产、在美国本土放贷和调回本国使用。Zoltan Pozsar 是一个严肃的 Analyst，对几种情况做了深入的分析。但我们是 Macro Trader，我们只对最脆弱的环节感兴趣。我们发现，在 Flow Chart 扩表出来的资产比如股票、商品等，市场对其波动有极大的容忍度。另外一个有意思的发现是实盘投资者，例如外国投资者以及套牢了就不撒手的散户，市场对他们的 P&L 波动也表现的很淡漠。相比之下，金融机构随便一个负面新闻，都能让所有玩家的心跳陡然加速。这是因为这些资产或者参与者的 Liability 很轻，而金融机构 Liability 很重。特别强调一下，

Liability 驱动的交易往往是 Convergence 最强的交易。如果 Asset 一方出现波动但是 Liability 相对稳定，玩家往往还有套牢死磕的空间。但是一旦 Liability 出现问题，比如投资者赎回、银行削减 Credit Line、Margin Call 等等，玩家将陷入极端被动的境地。所以，熊猫在做 PM 的时候即使再目中无人，但见到客户，甚至见到自家 Sales，也是要客客气气的。

那么 Liability 驱动的交易可能出现在哪里？我们希望找到同时具备如下特点的环节。一是 Liability 出现大幅收缩的可能性很大，最好是《Monetary Economics》中描述的基础资产比如备付金等出现收缩，或者银行金融机构扩表意愿出现大幅收缩，这样 Liability 的收缩将以成倍的效果，扩张到 Flow Chart 各个环节。二是流动性自我纠偏的能力很弱，容易出现羊群效应，这时候我们不喜欢强力的央行，而离岸市场正好没有央行。所以，Zoltan Pozsar 列举的四项中，或者是在 Flow Chart 同一层级腾挪资产，难以形成 Liability 收缩，或者是有很强力的替代机制，自修复能力强，不容易攻击。唯独日本银行业的美元市场，用 Prime Money Market Fund 融入的美元起到备付金的作用。我们注意到这个市场的备付金正面临威胁，又是一个缺乏强力流动性提供者的离岸市场，再加上日本银行业的美元市场参与者行为高度同质化，很容易形成一致效应，所以这就是我们最喜欢的地方。最终，我们见到 LIBOR/OIS 逐渐走高的时候，JPY Basis 狂跌不止，接近 2011 年欧债危机时候的水平，可见日本市场 USD Funding 紧张到什么状态。BoJ 在 7、8 月份虽然喊话要提供美元流动性，但是嘴炮太多真金白银太少。可怜的日本银行业高兴了两天，回头发现美元还是紧的不行。

![img](https://quip.com/blob/PDKAAAXI1m9/mydY7sX5MfYnjf9aj3ictA?a=UKZ5es6vyysXZ8WKk3ezfZvS31HTbUd928ZuCARSbt4a)

至此，读者可以把这个故事理解为 “美国货币基金改革关闭日本融资渠道所以日本跪求美元”。这个解释其实已经可以拿来指导策略设计了。但是这个解释跳过了很多地方，真实的情况其实更加复杂，因为日本银行业的美元市场本身就是一个结构完整的离岸货币银行系统，包括实体经济、银行和证券系统，同样蕴含了许多有意思的结构，值得仔细推敲。首先是日本银行业的 Funding 结构，一些读者已经指出，日本银行业的美元 Funding 渠道并非 CP/CD 一条路，FX Swap 的融资量就同样可观，此外还有资本流入等等。BoJ 前不久曾发布过一片工作论文 Recent Trends in Cross-currency Basis 曾讨论到这个题目。我需要说明，CP/CD 的融资被压缩，并不是一口气把日本银行业的美元融资砍断了，而是起到一个急剧提高边际成本的作用。其次，美元 Liability 压缩不意味着 Funding 就必须紧，因为美元在这个货币体系里起到备付金的作用。《Monetary Economics》篇指出，只有在交易量增加又伴随着货币体系传导效率下降或者货币体系收缩时，才会出现显著的流动性收紧。这正是 7 月份以后日本银行业面临的情况，由于对货币政策和美元成本升高感到懵逼，日本金融机构不得不多囤积美元以应对不确定性。事实上 BoJ7 月份宣布要提供 USD 流动性的时候，市场情绪有一定恢复，JPY Basis 出现明显的回调，但很快玩家们就发现 BoJ 只是嘴炮，又开始争先恐后的抢美元。第三个因素是，日本市场的离岸美元货币银行体系确实出现了雪上加霜的传导效率下降。这是个独立事件，起源于金融危机之后美国和欧洲监管机构普遍进一步加强了对银行的监管，因此银行提供流动性的能力越来越差。以 CCY Basis 为例，美资金融机构每笔 CCY Basis 都需要计算 CVA，把本来就紧张的 JPY Basis 成本再加高十几个 BPs。第四个因素，恰巧也在 7 月份前后出现的 Brexit 和德银等风险事件，也影响了全球金融机构信贷偏好，Flight to Quality 必然会导致 JPY Basis 跌跌不休，USD 紧的不行。（关于 JPY Basis 和 Flight to Quality 的讨论可以见随后的《Case Study：日元避险货币之宝宝心里苦但是宝宝不说》）

### 四、老乡别跑

现在我们已经整理出了最脆弱的 Liability 环节。作为 Macro Trader，我们可以选择两个方法来 Front Run 日本人的钱。第一个方法是在 Liability 方向，研判出 LIBOR 走高的机制后事先多囤一些 USD，趁着日本人火烧屁股的时候高价借给日本人，赚高利贷。这当然不是什么高招，所以我们要在 Asset 方向做更狠的招数，就是研判这些 Liability 承载的 Asset，Liability 越高日本人越撑不住，很可能会斩一些 Asset 平仓出局。抢在日本人之前斩这些 Asset，把伤口撕得更大一点，然后利用日本人的斩仓 Flow 平空头，能获得更丰厚的收益。

Liability 驱动的 Asset 策略，往往是利润最丰厚的机会。因为玩家既然要用 Liability 承载 Asset，那么 Liability 一般期限短、流动性好、Risk Premium 低，Asset 一般期限长、流动性差、Risk Premium 高。这样才能赚到 Asset/Liability 之间的价差。典型的如银行存款期限短而贷款期限长，又比如金融危机之前大批对冲基金发行 ABCP 投资 Subprime 甚至 CDO。市场波澜不惊时，这些玩家可以赚到利差。但是一旦市场反转，Asset 跌起来比 Liability 猛多了。如果能成功 Front Run 这些遭遇 Squeeze 的 Asset 斩仓盘，Macro Trader 们就能赚到前所未有的丰厚利润。

在海外投资的日本金融机构主要是寿险公司和银行。他们都是投资活动受到严格监管的机构，因此主要投资在美国和欧洲的国债、MBS 和高等级公司债等市场。寿险公司通常对冲大部分外汇敞口，银行更是几乎 100% 对冲外汇敞口。因此，扣除对冲成本之后的 10 年期美国国债实际收益率具有基准意义。进入 7 月以后，美国国债收益率受 Brexit 和德银风险事件等影响不断下行，10 年期美国国债收益率在 7 月 8 日达到 1.38 的低点。几乎在同时，Prime Money Market Fund 改革的效应开始在 LIBOR/OIS 和 JPY Basis 市场显现。下图可见 2016 年 7 月 8 日，扣除日元对冲成本之后的 10 年期美国国债收益率第一次触及 0，这意味着美国国债对日本人已经毫无价值。接下来如果美元继续趋紧，日元对冲成本进一步上升，日本人卖美债只是个时间问题。可以推测，大批投机者默默观察着 JPY Basis（中间肯定有人落井下石加码 Squeeze 了一把 JPY Basis），同时建好了美债看跌头寸。JGB 在 8 月底 9 月初由于揣测 BoJ 态度而出现的收益率上行也成为空头友军。所以这一天并没有太久，9 月初日本投资者开始卖美债，很快就把美债收益率推高了 20 个 BPs，将近一块五毛多钱。

![img](https://quip.com/blob/PDKAAAXI1m9/chraVdYi5XNh-A7qAB3Oaw?a=h5cNROptKZ6a3nGL2xZhnp3PZaaDcSlDbor7aGtapQMa)

这个故事似乎今天（2016 年 10 月 14 日）正式结束，实际上还要结束的早一些。因为 Basel III 要求银行把 30 天以内应付债务计入 LCR，所以银行除非太任性，否则不会去发行 30 天的 CP/CD 来消耗 LCR。考虑到 10 月 14 日是最终生效日，银行寻求融资的最晚时间其实是 9 月 14 日。因此，这个 Trade 最佳窗口是 9 月初。所以，Macro Trader 们需要注意，银行的每一个微小细节，都需要放到你的策略中考虑。

参考资料

1. Investment Company Institute. “Money Market Fund Resource Center".

2. Office of Financial Research, "U.S. Money Market Fund Monitor"

3. Federal Reserve. "FRB: Commercial Paper Outstanding", Weekly Statistical Release

4. The Collaborative Market Data Network,

5. Credit Suisse Global Research, "Global Money Notes #7: Japanese Banks, LIBOR and the FX Swap Lines", Aug 3rd, 2016

6. 熊猫笔记，20150828

7. Fumihiko Arai, Yoshibumi Makabe, Yasunori Okawara and Teppei Nagano, ”Recent Trends in Cross-currency Basis“, Bank of Japan Review, 2016