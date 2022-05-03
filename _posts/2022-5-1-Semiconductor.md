---
title: 半导体
author: Jin Jiefan
date: 2022-5-1
category: Jekyll
layout: post
---
# <光刻机系列>
> ## 光刻机之战

作者：金捷幡
发表：2019年4月

航空发动机一直被誉为人类顶尖工业皇冠上的明珠。但最近十年，不断挑战物理学极限的半导体光刻机，大有挑战明珠之王的趋势。


航发是在极端高温高压下挑战材料和能量密度的极限，而光刻是在比头发丝还细千倍的地方挑战激光波长和量子隧穿的极限。


更难得的是，和追求卓越不畏失败的航天高科技不同，航发和光刻的可靠性也是人类骄傲之花：前者保证了每天十万架飞机在天空安全翱翔，后者在全球工厂每秒钟刻出上千亿个晶体管分毫不差。



震撼一下，看看芯片内部
注：1nm=0.000000001米， Credit: ASML


### 引子


2000年，成立15年当时排名世界第二的荷兰ASML(阿斯麦)公司已经成功占领韩国和台湾市场，但还在琢磨怎么卖光刻机给那时芯片的绝对霸主英特尔(Intel)。


缺乏新一代157nm激光需要配置的反折射镜头技术也是让ASML焦虑的地方。同时，在美国能源部和几大芯片巨头合建的EUV光刻联盟里，ASML还只是个小配角。


这时下一代光刻技术发展会怎样，整个半导体届没有人知道。


在转折关头，ASML决定另辟蹊径，报价16亿美元收购市值只有10亿的硅谷集团(SVG)。曾经辉煌的SVG当时在光刻机的市场份额只有不到8%，年营业额只有2.7亿美元，而且193nm产品水平还远不如ASML。所以华尔街认为ASML买贵了，ASML股价当天暴跌7.5%。


然而从后来的结果看，ASML等于花钱买了光刻机行业最值钱的门票：英特尔的vendor code，同时摇晃了尼康(Nikon)的支柱。此外，SVG拥有最成熟的157nm光学技术，等于ASML买了一个技术双保险，这点后面会再详述。


不过，别以为西方人都是一家子。这次收购仍遭到美国政府和商会的阻挠，美国国防部审查说ASML董事长在一个曾经违反禁令偷偷卖夜视镜给伊拉克的荷兰公司当过董事。


中国公司的老对手美国外国投资委员会最终在收购协议上加了一堆条件，其中包括不许收购SVG负责打磨镜片的子公司Tinsley，以及保证各种技术和人才留在美国。


这些条件反而让ASML顺理成章地成为了半个美国公司，享受到美国强劲的基础科学带来的巨大好处，为多年后在EUV一支独秀做了有力的铺垫。


### 早期，60-70年代


光刻机的原理其实像幻灯机一样简单，就是把光通过带电路图的掩膜(Mask，后来也叫光罩)投影到涂有光敏胶的晶圆上。早期60年代的光刻，掩膜版是1:1尺寸紧贴在晶圆片上，而那时晶圆也只有1英寸大小。


因此，光刻那时并不是高科技，半导体公司通常自己设计工装和工具，比如英特尔开始是买16毫米摄像机镜头拆了用。只有GCA, K&S和Kasper等很少几家公司有做过一点点相关设备。


60年代末，日本的尼康和佳能开始进入这个领域，毕竟当时的光刻不比照相机复杂。


70年代初，光刻机技术更多集中在如何保证十个甚至更多个掩膜版精准地套刻在一起。Kasper仪器公司首先推出了接触式对齐机台并领先了几年，Cobilt公司做出了自动生产线，但接触式机台后来被接近式机台所淘汰，因为掩膜和光刻胶多次碰到一起太容易污染了。


1973年，拿到美国军方投资的Perkin Elmer公司推出了投影式光刻系统，搭配正性光刻胶非常好用而且良率颇高，因此迅速占领了市场。


1978年，GCA推出真正现代意义的自动化步进式光刻机(Stepper)，分辨率比投影式高5倍达到1微米。这个怪怪的名字来自于照相术语Step and Repeat，这台机器通俗点说把透过掩膜的大约一平方厘米的一束光照在晶圆上，曝光完一块挪个位置再刻下一块。由于刚开始Stepper生产效率相对不高，Perkin Elmer在后面很长一段时间仍处于主导地位。


### 80年代，群雄争霸


光刻机是个小市场，一年卖几十台的就算大厂了。因为半导体厂商就那么多，一台机器又能用好多年。这导致你的机器落后一点，就没人愿意买了。技术领先是夺取市场的关键，赢家通吃。


80年代一开始，GCA的Stepper还稍微领先，但很快尼康发售了自己首台商用Stepper NSR-1010G，拥有更先进的光学系统极大提高了产能。两家一起挤压了其它厂商的份额，尤其是Perkin Elmer的投影式光刻。P&E的市场份额从80年超过3成快速跌到84年不到5%。


看过我写的《内存的故事》的朋友都知道，80年代是日本半导体最风光的时候，本土几乎每家大公司大财阀都进入了半导体业。这给尼康和佳能双雄带来巨大的后盾，并开始反攻美国市场。


由于GCA的镜片组来自蔡司，不像尼康自己拥有镜头技术，合作的问题使得GCA产品出现了瑕。1982年，尼康在硅谷设立尼康精机，开始从GCA手里夺下一个接一个大客户：IBM、Intel、TI、AMD等。


到了1984年，尼康已经和GCA平起平坐，各享三成市占率。Ultratech占约一成，Eaton、P&E、佳能、日立等剩下几家每家都不到5%。


为什么我们要特地看1984年呢？


首先我们致敬一下苹果，震撼世界的广告《1984》发布了第一代Mac。然后，请出我们故事的主角：ASML。


ASML被广为传播成是飞利浦分离的出来的，虽然不能说不对，但是和大家想象的那样子还是不同的。


飞利浦在实验室里研发出stepper的原型，但是不够成熟。因为光刻市场太小，飞利浦也不能确认它是否有商业价值，去美国和P&E、GCA、Cobilt、IBM等谈了一圈没人愿意合作。


有家荷兰小公司叫ASM International的老板Arthur Del Prado听说了有这么回事，主动要求合作。但这家代理出身的公司只有半导体前后道的经验，对光刻其实不太懂，等于算半个天使投资加半个分销商。


飞利浦犹豫了一年时间，最后勉强同意了设立50:50的合资公司。1984年4月1日ASML成立的时候，只有31名员工，在飞利浦大厦外面的木板简易房里工作。




ASML最早成立时的简易平房，后面的玻璃大厦是飞利浦。Credit: ASML
ASML在头一年只卖出一台stepper，第二年卖出四台。第一代产品不够成熟，但是背靠飞利浦大树的各种资源和容忍让它生存了下来。


ASML在1985年和蔡司(Zeiss)合作改进光学系统，终于在1986年推出非常棒的第二代产品PAS-2500，并第一次卖到美国给当时的创业公司Cypress，今天的Nor Flash巨头。


有意思的是，1986年半导体市场大滑坡（比如光三星半导体就亏了3亿美元），导致美国一帮光刻机厂商都碰到严重的财务问题。ASML还小，所以损失不大，还可以按既有计划开发新产品。同期，GCA和P&E的新产品开发都停滞了下来。


1988年GCA资金严重匮乏被General Signal收购，又过了几年GCA找不到买主被关闭。General Signal旗下另外一家Ultratech最终被MBO，但是规模也不大了。1990年，P&E光刻部也支撑不下去被卖给SVG。


1980年还占据大半壁江山的美国三雄，到80年代末地位完全被日本双雄取代。这时ASML还只有大约10%的市场占有率。


### 波长的竞争


忽略掉美国被边缘化的SVG、Ultratech等公司，90年代一直到现在的格局，一直是ASML和尼康的竞争，佳能在旁边看热闹。


所以我们要开始讲一点点技术了。


半导体领域的原生驱动力是摩尔定律。摩尔定律其实应该被叫做摩尔预言，这个预言中间还改过一次。戈登摩尔博士1965年最早的预言是集成电路密度每年翻倍，而1975年他自己改成每两年翻倍。


有人说，这是人类历史上最伟大的“自我实现的预言”，因为英特尔就是照着这个预言一路狂奔数十年，直到光刻技术被卡在193nm上十多年变成网友说的“牙膏厂”。


为了实现摩尔定律，光刻技术就需要每两年把曝光关键尺寸(CD)降低30%-50%。根据瑞利公式：CD=k1*(λ/NA)，我们能做的就是降低波长λ，提高镜头的数值孔径NA，降低综合因素k1。


搞更短的波长是最直接的手段。90年代前半期，光刻开始使用波长365nm i-line，后半期开始使用248nm的KrF激光。激光的可用波长就那么几个，00年代光刻开始使用193nm波长的DUV激光，这就是著名的ArF准分子激光，包括近视眼手术在内的多种应用都应用这种激光，相关激光发生器和光学镜片等都比较成熟。


但谁也没想到，光刻光源被卡在193nm无法进步长达20年。直到今天，我们用的所有手机电脑主芯片仍旧是193nm光源光刻出来的。


90年代末，科学家和产业界提出了各种超越193nm的方案，其中包括157nm F2激光，电子束投射(EPL)，离子投射(IPL)、EUV(13.5nm)和X光，并形成了以下几大阵营：


157nm F2：每家都研究，但SVG和尼康离产品化最近。

157nm光会被现有193nm机器用的镜片吸收，光刻胶也要重新研制，所以改造难度极大，而对193nm的波长进步只有不到25%，研发投入产出比太低。ASML收购SVG后获取了反射技术，2003年终于出品了157nm机器，但错过时间窗口完败于低成本的浸入式193nm。


13.5nm EUV LLC：英特尔，AMD，摩托罗拉和美国能源部。ASML、英飞凌和Micron后来加入。

关于EUV，我放到后面在说吧。


1nm 接近式X光：日本阵营(ASET, Mitsubishi, NEC, Toshiba, NTT)和 IBM

这算是个浪漫阵营吧，大家就没想过产业化的事


0.004nm EBDW或EPL: 朗讯Bell实验室，IBM，尼康。ASML和应用材料被邀请加入后又率先退出。

这是尼康和ASML对决的选择，尼康试图直接跨越到未来技术击败ASML，但可惜这个决战应该发生在2020年而不是2005年，尼康没有选错技术但是选错了时间。尼康最重要的技术盟友IBM在2001年也分心加入了EUV联盟。


0.00005nm IPL: 英飞凌、欧盟。ASML和莱卡等公司也有参与。

离子光刻从波长来看是最浪漫的，然而光刻分辨率不光由波长决定，还要看NA。人类现有科技可用离子光刻的光学系统NA是0.00001，比193nm的NA=0.5～1.5刚好差10万倍，优势被抵消了。


以上所有努力，几乎全部失败了。


它们败给了一个工程上最简单的解决办法，在晶圆光刻胶上方加1mm厚的水。193nm的光波在水中被折射成134nm。


浸入式光刻成功翻越了157nm大关，直接做到半周期65nm。加上后来不断改进的高NA镜头、多光罩、FinFET、Pitch-split、波段灵敏的光刻胶等技术，浸入式193nm光刻机一直做到今天的7nm(苹果A12和华为麒麟980)。


2002年台积电的林本坚博士在一次研讨会上提出了浸入式193nm的方案，随后ASML在一年的时间内就开发出样机，充分证明了该方案的工程友好性。


随后，台积电也是第一家实现浸入式量产的公司，随后终于追上之前制程技术遥遥领先的英特尔，林博士因此获得了崇高的荣誉和各种奖项。


MIT的林肯实验室似乎不服气，他们认为自己在2001年就提出了这个浸入式方案。ASML似乎也没有在任何书面说明自己开发是受林博士启发。


其实油浸镜头改变折射率的方式由来已久，产业界争论是谁的想法在先从来不重要，行胜于言。林博士的贡献是台积电和ASML通力合作把想法变成了现实。


### 日荷争霸


在ASML推出浸入式193nm产品的前后脚，尼康也宣布自己的157nm产品以及EPL产品样机完成。然而，浸入式属于小改进大效果，产品成熟度非常高，所以几乎没有人去订尼康的新品。尼康被迫随后也宣布去做浸入式光刻机。


之前我们提到光刻领域是赢家通吃，新产品总是需要至少1-3年时间由前后道多家厂商通力磨合。别人比你早量产就比你多了时间去改善问题和提高良率。


光刻机就像印钞机，材料成本可以忽略不计，而时间就像金子一样珍贵。


半导体厂商更愿意去买成熟的ASML产品，不想去给尼康当白鼠。


这导致后面尼康的大溃败。尼康在2000年还是老大，但到了2009年ASML已经市占率近7成遥遥领先。尼康新产品的不成熟，也间接关联了大量使用其设备的日本半导体厂商的集体衰败。


佳能在光刻领域一直没争过老大。当年它的数码相机称霸世界利润很好，对一年销量只有百来台的光刻机重视不够。


佳能的思路是一款产品要卖很久，他们一看193nm尼康和ASML打得太厉害就直接撤了。直到现在佳能还在卖350nm和248nm的产品，给液晶面板以及模拟器件厂商供货。


尼康在浸入式一战败下来就彻底没有还手之力了，因为接下来EUV的开发需要投入巨资而且前景未卜，英特尔倒向ASML使得尼康失去了挑战摩尔定律的勇气。


### EUV光刻机


接下来，我们再说说EUV(极紫外光-光刻机)。这个产品其实是ASML在没有竞争对手的情况下研发的，而且做了十多年到今天也没有量产。


那它背后的驱动力是什么呢？我看了一些文献，英特尔绝对是最坚定的支持者，因为它的使命之一就是让摩尔定律走下去。


早在1997年，英特尔看到挑战193nm的巨大难度，决心集合人类精英一起愚公移山，有点流浪地球的意思。他们说服了美国对高科技最开明的克林顿内阁，以公司形式发起了EUV LLC这样的一个合作组织。


这个组织由英特尔和美国能源部牵头，集合了当时还如日中天的摩托罗拉以及AMD，以及享有盛誉的美国三大国家实验室：劳伦斯利弗莫尔实验室，劳伦斯伯克利实验室和桑迪亚国家实验室，投资两亿美元集合几百位顶级科学家，从理论上验证EUV可能存在的技术问题。


英特尔还力邀ASML和尼康加入EUV LLC，因为当时美国光刻已经不太行了。但此举受到美国政府的阻挠，因为他们舍不得让外国公司分享美国最前沿技术。


最终结果是尼康被排除在外，ASML做了一堆对美国贡献的许诺后被允许加入。另外一家例外的非美国公司是英飞凌，它被允许和Micron一起加入EUV LLC。


我们回看当年各种跨越193nm的技术方案，很多公司是左右下注的，只有英特尔坚定地选了EUV，而且让它最终成为了现实。


看当年的一些回忆录，说英特尔自己并未派出多少工程师，但是列了几百项难题一直拿着小鞭子督促那些科学家不停地努力。


EUV算是软X光，穿透物体时散射吸收都非常厉害，这使得光刻机需要非常非常强的光源，这个难度是巨大的。


EUV光源是高能二氧化碳激光打在只有30微米一滴一滴的金属锡滴上产生的等离子体。ASML特地收购了美国Cymer公司获取相关光源技术，但是极低的能量采集效率使得EUV的产能问题一直是个瓶颈。


传统光刻用的很多透镜因为会吸收X光都要换成反射镜。据说193nm的最新光刻机里镜头加起来就有一吨重，而这些技术都用不上了。


连空气都能吸收EUV，所以机器内部整个光路都做成真空的。即使这样，到达光刻胶时光能量损失已经超过95%甚至更多。如果被迫延长曝光时间的话，等于“印钞机”的印钞量就会大减。


由于光刻精度是几纳米，EUV对光的集中度要求极高，相当于拿个手电照到月球光斑不超过一枚硬币。反射要求的镜子平到什么程度呢？要求长30cm起伏不到0.3nm，这相当于是北京到上海做根铁轨起伏不超过1毫米。


所以，EUV不仅是顶级科学的研究，也是顶级精密制造的学问。


这些无比精密的反射小镜子由德国蔡司生产，由几十层硅钼等复合材料组成，每层只有几纳米厚，目的是刚好根据EUV的波长叠加反射最多的光。ASML因此特地购买了Carl Zeiss SMT公司24.5%的股份。

1997年-2003年，6年间EUV LLC的科学家发表了几百篇论文，验证了EUV光刻机的可行性。然后EUV LLC联盟解散。


接下来留给ASML一个问题，是做还是不做呢？


好在ASML从来没有犹豫过。2006年它推出原型，2007年建造了10000平米的超级无尘室，等着接待2010年诞生的第一台研发用样机：NXE3100。

2012年，ASML请英特尔、三星和台积电入股自己，希望大家共同承担这个人类的伟大工程，因为研发投入需要每年10亿欧元。


2015年，可量产的样机发布。虽然售价高达1.2亿美元一台，但还是收到雪片一样的订单。排队等交货，都要等好几年。


一台EUV光刻机重达180吨，超过10万个零件，需要40个集装箱运输，安装调试都要超过一年时间。


明年，我们就能买到EUV加工出来的芯片做的手机了。






EUV光刻机 Credit: ASML


### 后记


相信在未来，人类一定可以突破光学光刻机的极限，无论用电子离子还是最终放弃硅基。但是，就在刚写完文章的现在，我只想衷心为这些伟大的公司喝彩。


需要强调的是，在半导体制造中，光刻只是其中的一个环节，另外还有无数先进科技用于前后道工艺。


正是因为他们不屈不挠的努力，才使得我们在这个一切由芯片驱动的伟大时代，享受着各种手机、电脑、家电、汽车飞机和互联网带给我们的精彩生活。

# <内存专辑>

> ## 内存的故事
> ## 内存的故事-2-Rambus之战
> ## 内存的故事-3-金士顿的传说
> ## 内存行业的技术发展

# <半导体设备商>

> ## 应用材料公司(AMAT)的故事
> ## KLA-芯片制程控制之王
> ## LAM和电子束光刻
> ## ASM(L)和电子束光刻

# <半导体的发展>

> ## 为什么还没有18寸(450mm)晶圆
> ## 摩尔定律究竟死没死
> ## 和时间旅行者讨论半导体
> ## 未来三十年的芯片路线图
> ## 某国、IMAX、DMD和元宇宙–中式内卷的反面样本
> ## 特斯拉的独特气质、星际殖民和碳化硅革命
