#动力学的世界观

动力学最初的一鸣惊人，是空前绝后的牛顿三定律的提出，而牛顿第二定律又是三定律的核心，只要有高中数学基础的人就知道，它是力与加速度的关系，看起来不起眼，但是它包含了整个动力学的核心思维，是什么？ 是受力分析吗？ No。 第二定律的本质，是预测，而预测无穷尽的未来，你不需要太多信息，只需要知道此刻和与之最近的下一刻的关系（微分的思维，下一刻是一个极限的概念，恰好脱离此刻的时刻），所谓s(t+1)=f(s(t))。s代表state，即状态， f就是由此刻的状态得到下一刻的状态的迭代关系。有了f和初始时刻的s，未来即确定。

这个方法的威力说多大也不夸张，想象一下，如果你是上帝，这是一个多么省事的方法，你无须操心大千世界芸芸众生的未来，只需要设定一个f，叫它不停迭代，就可以管理整个宇宙了。牛顿发现了这个上帝偷懒的方法，于是人类把握了上帝的力量。

第二定律的成功就不用多说，但是在最初的两百年，这种成功也就是机械领域，脱离了机械运动，似乎人们不太有办法使用几何关系预测变化。 而从19世纪开始，动力学的理论开始由机械运动的领域逐步向其它领域扩散，最初是物理领域内的扩散，到20实际以后又开始向物理领域外延伸，一部现代科学发展史，可以看做动力学深入各个学科的历史。

一切的改变，基于两个如雷贯耳的名字，拉格朗日和哈密顿。

这两个人奠定了整个分析力学，但是分析力学最初的目标不是放大动力学的应用， 而是对更抽象的数学形式的追求（其实形式亦决定本质），由此得到牛顿定律2.0版。以前的牛顿力学研究真实空间里的运动，而这两个人把空间的概念拓展为抽象的广义空间。广义空间是和广义坐标结合在一起的（generalized cooridnates），这两个人想到，既然物体的状态由位置和速度共同决定，而且它们是独立的，那么何不把速度也看做一种抽象的位置，那么物体速度的变化就可以看做广义坐标的里位置的变化，那么，物体状态的全部信息，均可以作为坐标信息表述，而动力学的全部，都可以用几何关系表达。

广义坐标的应用，使得动力学的经纬-位置和速度取得了对等的地位，我们通常把位置和速度构成的空间叫做相空间（一个全新的6维空间，包含位置三维和速度三维）。如果用一句话描述相空间的好处，就是真实空间里你只能看到物体运动的那条轨迹，而在相空间里，你可以看到物体所有可能运动的轨迹。或者说，相空间把空间从三维拓展到六维，而这个空间里我们看到不仅是我们生活的那个宇宙，而是所有可能宇宙的总和。

为什么？ 因为，物体所有可能的状态均是相空间里的一个点（位置+速度），在牛顿的世界观里，只要初始状态确定，那物体运动的轨迹随之确定，如果说此刻物体的状态是一个点，那么它的运动过程就是这个空间里的一条曲线。而如果物体的初始状态具有不确定性，它就不是一个点，而是围绕某个点的一小块区域，而物体的运动轨迹也不再是一条曲线，而是流形（flow=曲线的集合），类似于流体力学里液体。

我们所说的历史大潮，就是相空间里物体运动轨迹的集合。 分析力学的伟大正在于把物体在三维空间里的运动化作了高维空间里的流。表面上看这样的方法使运动失去了直观性，但实质上，却更接近了运动的本质。在这个观点上，越抽象，就越真实，应用就越广泛。

高维空间的好处有什么呢？最重要的，他使我们由关注研究物体的某一条运动轨迹，变为了同时研究物体所有可能的轨迹，所有可能的历史，所有可能的未来。也就是说三维空间是我们的宇宙，而分析力学的高维空间却具有把握的却是平行宇宙，那些符合物理定律的所有宇宙。这个思维意想不到的开拓了整个现代物理，从统计到量子力学。

在相空间里我们可以得到一个叫哈密顿的函数（H）， 相互作用不需要在用力表达，画很多的箭头做受力分析，而是用H，H最简单的理解是能量，由动能和势能共同组成，由广义坐标唯一确定。在一个能量守恒的系统里，它包含了系统变化的全部信息。

哈密顿方程背后有一个更为惊人的基本原理：就是最小作用原理-或为哈密顿原理：它告诉我们，有一个叫作用量的函数，这个函数的特点是把物体在相空间的运动轨迹给对应为一个数。最小作用原理告诉我们，真实物体的轨迹，就是让这个数最小的那一个。

这个原理的伟大不亚于能量守恒定律，它告诉我们所谓物理的真实，就是遵循最小作用原理。几乎所有物理定律及四大力学（经典力学，电动力学，统计力学，量子力学）均可统一于这个原理，它是宏观物体的机械运动和微观系统的状态变化的桥梁。

研究电子，光子的运动，牛顿定律用不上，但是牛顿定律的灵魂却以哈密顿的形式在所有其他体系里复生。它告诉我们为什么光与台球，都要沿直线传播，都有类似于反射和折射的现象。而为什么在广义相对论里，光又可以不沿直线传播。

动力学的威力在这里已经淋漓尽致了，它不仅解释那些我们看见了的世界，还告诉我们没有看见的世界是什么，什么是有可能发生的，即使我们没有看到，只是因为我们看的时间还不够长。

它是一种超越性的思维，让我们绕过事物的表现，直抵本质，两种截然不同的领域，只要它们具有结构相同的微分方程，它们就是一回事。在动力学的世界，无论是太阳升起降落，还是交流电的震荡，甚至我们的心跳与王朝的更替，只要归于同类方程引导的周期运动，就是同质的。这就如同万有引力定律，苹果落地与地球绕日运动， 在动力学的角度里只是初始速度不同而已，本质都是引力。

---

由于动力学的思维的高屋建瓴，因果关系的表述之清晰，决定了动力学终将不止步于物理，而它也的确席卷了那些我们物理不能染指的领域，如生物学，社会学，经济学，甚至语言学，心理学，每当动力学进入一个领域，我们就可以说我们真正理解了那个领域，而之前，最多只是描述而已。

然而这个过程却只是进入20世纪才开启，为什么？ 原因在于，相比物理系统，那些领域都显得太复杂了，而复杂的原因有三，一是元素太多，二是非线性，三是能量不守恒。所谓元素多，好理解，无论是生物系统，还是社会，都是又无数的小单元组成的，如细胞，人。而非线性就较难表述。

首先，什么是线性？线性=可加和性。物理系统往往是线性的。如在牛顿力学里，力是可以加和的，物体受的合力是所有施加在物体的力的和，每一种力混合在一起时候都和它们单独存在时候一致。

线性显然在生活或社会这样的系统上不成立，你并不是把一堆细胞放在一起就有了生命体，也不是把一堆人放在一起就有了社会，细胞组成生命或人组成社会，都是在更大尺度上形成了新的组织。 而这些组织所呈现的性质，完全不能等价于组成它们的单元的性质的加和。

至于第三点能量不守恒，生物或社会系统都是典型的耗散系统，这些系统的本质特点即不停的与外界交换能量和信息，一旦这些系统能量守恒往往意味着已经死亡。能量不守恒使得哈密顿方法根本无法进入这些系统，那些复杂的积分公式在真实的复杂性面前望而却步了。

开放性的复杂系统，能量信息的输入和输出，以及涌现性（非线性叠加）构成了它的本质。

这些传统物理方法难以触及的领域，在很长时间里无人问津，直到20世纪几个革命性的理论提出后。这些方法包括非平衡态的统计物理和相变理论，复杂网络，非线性动力学， 混沌论，协同论，博弈论等。而这些方法综合在一起，衍生了一门叫做复杂系统的新学科，它使得动力学进入了这些物理不可染指的理论。

而动力学的方法，给人类使用计算机大规模解决复杂问题奠定了基础。计算机模拟的一般方法即先列出一个系统里的变量（相空间的维度），然后需找“运动法则” - 此刻与相邻时刻状态的迭代关系，并列出方程。这正是构建一个基本的动力学系统的方法。而计算机解决这些问题的过程，其实就是检验我们的动力学系统是否正确。如果我们我们抓住了动力学系统的全部要点，计算机的模拟甚至会比真实更真实。当然现实中，我们永远都要做近似。

非线性动力学，是物理学的思维进入传统方法所不能解决的问题的一座丰碑。也是非常有前途的工具学科，它为大数据时代提供潜在的分析引擎。 为什么说非线性，因为物理之外的系统大多数不能用线性系统表述

动力学的核心使命是预测系统的变化，非线性动力学在这点上也是一样的。

预测一个系统的未来，你需要知道它在微小时间尺度里的性质并列出动力学方程

维度是动力学系统的最基本属性 。它决定系统的复杂性，及其可能具有的基本性质。 还有，我们有多大把握预测系统的未来。

最简单的系统是一维系统，预测一个一维的非线性系统，往往只需抓住一个关键性信息-定点。

一维系统与定点（Fix Point） “简单系统偏好平衡”

18世纪末，在工业革命前夜的英国，一个叫做马尔克斯的伟大思想家提出了这样一个困扰了人类几个实际的问题： 人类的人口呈指数增长，而食物的总量至多成代数增长，所以当人口的增长超过食物，人类将不可避免的陷入饥荒，疾病和战争。而普遍性的贫穷，是人类文明的宿命。

马尔萨斯的理论，其实诠释的是一个叫Fix Point-定点的动力学概念。 它所说的是，在一个复杂系统里，事物的增长往往不是线性的，而是存在一定的稳恒状态，系统的变化会逐步减速并自发的把自己维持在这个状态上。

非线性动力学用定点fix point来描述这种现象。 为什么fix point 普遍存在？ 因为负反馈的普遍存在。当一个事物像一个方向走的太远，就往往有一种反方向的作用力把它拉回，有点像我们所说的物极必反或阴阳相抵。

回到马尔萨斯，人口理论其实符合一个叫做Logistic Model的经典一维动力学模型, 它也因它那美妙绝伦的S曲线而闻名。 这个模型说的是，在没有环境压力的时候（人人吃饱饭）人口的增长率是恒定的，所以如果第一年是2，那么第N+1年即使2的N次方（几何增长），但是一旦人口接近环境的阈值，就会有人开始饿死，而这个饿死的比例随着人口的增长而增大（负反馈）。这样，当饿死的人等于出生的人，两个此消彼长的要素就在某个点上平衡了。 所谓定点。

这个定点具有一个更深刻的性质，无论你的人口一开始是多少，只要K给定，系统都会趋于一个相同的值。这个值由环境本身的容量所确定。

马尔萨斯的确是一个有着深刻洞察力的思想家，它在没有任何这些数学概念的时候发现了这一原理。 当人口的增长达到一定限度，大规模的饥荒和战争将使人口增速变慢实现大自然的平衡。这的确是人类社会的基本矛盾，而且是古代社会变化的一个核心动力。

王朝末年往往经历了较长的太平期，人口增长，土地不变（可开垦的荒地往往被开垦光了），造成人多地少局面，马尔萨斯的预言就开始发挥效力，系统通过农民战争，饥荒，需找平衡（定点）。

土地与人口的比例，是中国历史的第一主要变量，但是它无法解释为何中国历史进入循环而非静态平衡?

马尔萨斯完全正确吗？ 事实上，马尔萨斯的诅咒可以用于所有古代文明，却唯有一个不再试用，那就是产生马尔萨斯的文明本身-西方文明。西方文明崛起的时代，就是人类人口快速增长，而人均生活水平却在不断提高的时代。 为什么？ 很简单，答案依然在定点理论。

农业技术的发展使得环境的负载值K也在增长，甚至比人口N还快，就使得系统的定点随时间增长，因而人口可以不停增长。这里面其实还有一个潜在的动力学效应。就是人口数量增加如果配合良好的教育，甚至会成为科技发展的动力，因为有更多的人从事研究，而这种效应，无疑提供一个人口增长强大的正反馈，事实上观察美国等现代国家的发展也正是这样的例子。

动力学系统定点的分析，告诉中国人，要感激的是袁隆平而不是邓小平。还有，人类不想返贫的办法只有不停的投入研发。

动力学里最重要的概念-定点（fix point），但是定点本身却只具有系统很少的信息，更关键的性质来自于对定点周围区域的分析。 或者说定点的稳定性。

在一些情况里，定点好想是系统变化的宿命。起点还是什么都不重要，你不需要担心输在起跑线上，只要你起跑了，就会到一个地方-定点。 而在另一些情况里，定点虽然存在，但是你只有在极特殊的条件下才能达到，类似于屌丝逆袭，屌丝的逆袭是有的，但是要有极好的运气+相当高的智慧才行。即使你达到了这样的定点，稍有风吹草动也会失去它。 我们用一个叫做稳定性的概念来描述这一特性。稳定性是描述当系统处在定点周边的状态，它是比较容易进到定点还是离开它。

一个典型的例子是单摆, 单摆的微分方程有两个取零的点，但是你通常看到摆处在最低点却极少有机会看到一个处在顶点的单摆。原因很简单，单摆的低谷是稳定定点而高点是不稳定的。 除非你一开始就静止在最高点而且排除任何外力，否则最轻微的偏离就可以导致单摆回到稳定的最低点。

在物理的角度很容易理解一个定点是稳定的还是不稳定的，只需要稍微的离开定点，看一下系统的运动情况，看看系统在定点的相邻区域里的运动趋势怎么随位置变化。而这翻译成动力学语言就是在定点周围进行泰勒展开，并取一阶线性近似（在一维得到一个线性的斜率，高维就是雅可比矩阵的特征值）。如果在定点周围的运动趋势指向定点（线性的斜率为负，雅可比矩阵特征值为负），则定点在局域内稳定，反之则局域不稳定。

定点的稳定性，取决于泰勒展开的不为零的第一项的正负。左图为稳定平衡，右图为不稳定平衡，虽然均为定点，但周边性质迥异。

稳定性，换一个词叫吸引力。一个稳定性定点，就像一个区域的主人，它能把进入其辖区内的所有人都吸收到它的点上。它所管辖的区域，称为-Basin of Attraction。它是强韧性的代表，无论你怎么干扰它，迫害它，结局都将归于它。找到Basin of attraction 是利用定点预测系统的必备条件，给定一个系统，如果它的初始位置处在basin of attraction，那么它必归于定点。

最强的定点具有全局稳定性，即无论任何初始条件，系统都将趋于这样的定点，这样的系统就是高度可预测系统。

很多系统往往具备一个稳定点和一个不稳定点成对出现。比如刚才的人口模型，人口为0就是一个不稳定平衡点。当人口为0的时候，它可以永远为0，但只要系统的人口增长了1，它就会趋于定点K，掌控系统除0之外所有区域的稳定点。

判断简单系统，抓住定点就是抓住了命门。

二维系统与振动

为什么振动普遍存在？ 为什么自由竞争的结果往往是垄断？ 如何理解经济周期的运行？ 解决这些非常基本的问题，我们需要一个二维的动力学系统。 二维可以描述比一维丰富多的现象，正如通物理学从描述两个物体的相互作用开始描述了世界。

一维的系统往往归于单调的定点，而二维系统的主角却是振动，人类几千年来描述自然最有利的工具。 看看我们周围，从自然到人类，世界可以看作一部不同频率振动组成的交响曲。四季周而复始，太阳升起落下，我们的呼吸，脉搏，心跳，新陈代谢，生命的更替,经济系统的周期涨落，中国历史的王朝更替， 几乎有运动的地方，就有振动。

为什么振动的形式这么广泛的存在？ 其实依然是因为定点的广泛存在， 所谓振动，无非围绕一个却确定的状态的上下波动。

对于为什么振动如此普遍， 非线性动力学之父庞加莱有一个神一样的定理： Poincare-Bendixson Theorem：

条件： 1.2D - 你有一个二维的动力学系统 2.Continous - 系统连续可微 3. Confined - 动力学流在一个区域内封闭 4. No Fix point- 在此区域内定点不可达到 结论： 该区域内的动力学流将收敛于一条闭合轨道（等价于圆）。

相平面的闭合轨道=周期性运动=振动。 这个定理告诉我们，有限二维系统里的运动形式只有有两种： 1. 平衡态（归于定点） 2. 周期运动。 不存在其它情况。 有限只得是系统不会无限取值或发散。由于自然中负反馈的普遍存在这一条一般是满足的。 这条定律解释了振动普遍存在的根本原因，因为它是二维运动的范式。

作为一条以拓扑学为根据的定理，它标志了人类思维的新形式-拓扑思维，这种把各种不同形式的系统归于空间里的拓扑研究的思想，是一种超越性的思想。它标志了数学在解释世界的能力上的新高度。 从此，我们对世界的认识，取决于我们对几何空间的拓扑性的归类。 那些能够归于同一拓扑结构的系统，则具有相同的动力学本质，即使他们的物质组成有多不同。因此，拓扑的思维具有高屋建瓴，以一敌百的特性。

当一个系统有能量流入流出，我们称之为开放系统（为与能量守恒的保守系统区分），对于一个二维的开放系统， 庞加莱定理依然成立，系统若不归于平衡，则步入永恒的循环。

中国历史的循环，是以一个标志性的事件开始的： “秦王扫六合，虎视何雄哉！挥剑决浮云，诸侯尽西来！” 秦始皇以为自己开创了万世不灭的基业，没想到它只是开启了一个历史的闭合轨道。

我们要看到为什么这样的循环从秦开始，因为秦是中国历史的第一次大规模中央集权尝试，像齐度量衡，收天下之兵，立郡县制。 这样的行动，在那个交通通讯尚不发达的年代，势必疯狂增加国家的管理陈本。 所谓20年导致天怒人怨，无非是秦解除原生的地方组织（六国），而管理一个超级帝国需要一个无比烧人烧钱的中央管理体系的必然结局。当中央集权的成本分摊到每个百姓头上，使得其生存能力更加脆弱，超过承受阈值，那就是“ 王侯将相宁有种乎”的时刻。

为什么后面的王朝也无法逃出这个宿命呢？ 看看它们也确实吸收了历史教训，每当朝代开始就打土豪分田地施行仁政什么。 还是那个问题，马尔萨斯陷阱。王朝交替的时候，系统通过战争消减人口，这个时候分田地自然可以过几年好日子，但是太平久了，人口上升，人均土地又不够。但是维持中央集权的成本却随着总人口的上升而上升（超级帝国管理成本已经巨大）。这也容易理解，要管更多的人，就需要更多的官。这样一来，就要加税，而加税，就等于在本来手里土地已经变少变穷的农民头上雪上加霜，此时系统已经处于临界点，只要遇上一点随机因素，像小病小灾，就将导致翻盘，无论是黄巢起义还是李自成起义。

我们称一个系统自身动力学模式发生变化的过程为Bifurcation-非线性动力学理论的又一丰碑。

---

## 相变与混沌

动力学的世界里，无所谓色彩味道，只在乎系统所包含的自由度-或者说维度，一定的维度对应一定的现象。

维度是动力学系统的最基本属性 。它决定系统的复杂性，及其可能具有的基本性质。 还有，我们有多大把握预测系统的未来。高维空间的属性绝非只有爱因斯坦在乎，而是与你我息息相关。

一维的世界里我们看到的是反馈和定点-或者说静态平衡的法则。 二维的世界我们看到振动这一自然永恒主题的出现，这是大自然的动态平衡。 此篇将继续上一篇对二维系统的讨论，并之后引入三维系统和那里才会出现的混沌，最后直指高维系统和复杂网络。

二维系统可以稳定存在的运动状态有两个，一个是定点，一个是振动。这两种状态却不是一乘不变而是经常可以转变，有的是从一个定点到另一个定点的转化，也有的是定点和振动之间的转化。 这就涉及一个非线性动力学永恒的主题-Bifurcation（分叉）。

我们用Bifurcation研究一个动力学系统的演变。动力学系统由状态变量（系统可以自由变化的量）和控制变量（参数）组成。在初步讨论一个动力学系统性质的时候，我们先假设参数不变，因此可以得到系统动力学在相平面的拓扑图，然后求定点和轨道。 在二维的情况下，参数给定，动力学流型得出，则一切皆可精确预测。

真实的世界里从来没有一程不变的参数，真正不变的只有变化，而有的时候参数和变量甚至难以区分彼此。 因此，非线性动力学给出的对世界的最精密的描述，不是确定参数下的流行，而是在参数空间里对应的不同相平面流型。 简单的讲，动力学不仅感兴趣我们现在所在的那个世界，而是所有可能的世界（每个参数就是一个世界）。 参数的空间好比小径分叉的花园（无限可能性的博物馆），每一点上你都有一扇窗户， 打开可以看到那个世界的可能性。 在这个花园里走路，你将看到一种可能性是如何演化成另一种可能性的。

Bifurcation的本质是系统反馈性质的变化。当小球在谷底，一个负反馈保证它不离开（稳），而当谷底逐步变平突起的过程，负反馈演化成离开谷底的正反馈。

Bifurcation Point上的小球具有“自由意志”，或者说非常敏感，一个随机的扰动都可以被放大（正反馈的作用），使它向左或向右。这就是历史的转折点。而当Bifurcation的过程结束，小球就落入了新的平衡点。此时的它，已经被一个负反馈束缚住，非有强大的能量，是不会离去了。

Bifurcation， 正是物理里相变的化身。 在动力学的世界观里，那些定量的改变等于没变，而只有Bifurcation-分道扬镳，才是真正的变化。物理，化学，生物一切最有趣的现象，都在Bifurcation点上，因为它的敏感，它的无限可能。

Hopf-Bifurcation : 沟通平衡与振动的世界。

我们高中课本有个东西叫化学平衡， 说的是化学过程最终都导致平衡，该反应的反应过了，我们就得到一堆万年不变的反应产物。 但是1950年代的一个苏联科学家belousov却在它的反应里发现了一个十分惊人的现象， 他发现他手里的混合物反应后还会在一段时候回到原来的状态，然后又重新反应，如此周期反复。这一现象一出，他就被封杀了。因为他的结果不符合热力学第二定律（根据热力学第二定律，自发状态下系统必须趋于平衡），又加上适逢冷战，他到死也没看到他的成果被承认，成为科学史上几个重大悲剧之一。 但是它的发现却开拓了一个全新的领域-化学振荡，而他的发现也成为复杂性可以从简单系统中诞生的典型例子，与图灵对生物斑图的研究一起，开拓了复杂科学的先河。

Belousov的化学振荡可以自发产生美丽复杂的斑图（上图），被认为是复杂性从简单系统产生的典范。 对生命起源等问题都很有启发。 如果我们给这个化学反应写出热力学方程，我们就可以发现，循规蹈矩的化学平衡和“异常”的化学振荡可以完全统一在一个系统里，只是根据反应物浓度不同而不同。 它的本质即Hopf Bifurcation。

Hopf Bifurcation 作为阐述振动和静态平衡互相演化的基本手段， 在生物，经济等领域反复出现。 甚至我们的生命过程本身也可以理解为一个大的Hopf Bifurcation。 心脏的跳动和新陈代谢的循环伴随我们一生，这是系统的振动解。 我们死的那一刻，振动停止我们步入了静态平衡。这就是Bifurcation Point，from live to death。

中国历史的演变可以看做一个大Hopf Bifurcation。 从中国历史的初始阶段-东周列国（不考虑部落传说时代的夏商）到大秦帝国的诞生，可谓经历了Bifurcation。因为动力学系统的性质前后发生了根本变化， 从之前小邦国的平衡状态发展到帝国循环的动力学模型。 春秋战国可谓中国历史的关键期（critical period）。 但即使在秦帝国初建的时候，前一个动力学模型依然没有完全结束，两个模型依然在竞争（Bifurcation point）。 所以秦帝国才只持续那么短，因为邦国并立的组织虽已破坏，但其“鬼影”还在，新帝国的形式并不稳定。

当系统的维数达到三维， 主宰动力学模型的就不在是那些稳定可测的点或圆环，而是初值敏感，极难预测的混沌。

混沌其实没有你想的混沌，系统依然具有确定性的方程，只是其复杂性使得它看上去像是随机，毫无秩序而已，所以，混沌实则乱中有序（人类社会缩影？）。

我用一种最简洁的方法说明混沌如何可以产生。 刚才我在一维系统反复强调定点，因为定点是一维系统唯一可以具备的稳定状态。而在二维非线性系统我反复强调闭合轨道，因为二维系统定点和闭合轨道是二维系统唯一可能的稳定状态（庞加莱大法）。顺下去推理三维非线性系统，可能的稳定状态是什么？遵守点线面的顺序， 你一定猜到了是曲面。对，三维系统的稳态可以是三维空间里复杂的曲面。 只是说一个曲面稳定已经不再有意思了，我们管它叫吸引子，是三维空间里吸引系统进入的一个物体。

那么好了，为什么三维非线性系统可以产生混沌？ 因为物体被一个整个曲面吸引，不知道往哪里去了。 即使它被紧闭在这个曲面上，它也可以具备无数的轨道（面上的曲线）。 轨道变得复杂不可预测，因而混沌。

图为洛伦兹吸引子，由洛伦兹方程确定的三维系统具有两个吸引中心（定点），系统围绕两个定点旋转，形成极为复杂不可捉摸的轨道，形如扇扇翅膀的蝴蝶。

对这一系统最简单的理解是，洛伦兹系统依然描述闭合轨道，这和之前描述的二维系统的振动是相同的。但是在三维系统里，我们有两个定点及随之确定的吸引子曲面。系统时而绕着其中一个定点旋转，时而绕着另一个定点旋转， 但是它哪个时候改变绕转的对象却是不可测的。 混沌准确的定义是相邻轨道的稳定性-或者说初值敏感性，你是否可以从一步之遥，发展到天壤之别。不过和之前我分析定点的稳定性不同的是，这次需要的是分析轨道的稳定性。

混沌实则是复杂秩序的产生者，它所产生的秩序，叫做分型结构-Fractal。 分型结构的本质是自相似性-或者说标度不变形。就是说把它放大或缩小N倍和原先张的一样，或者说宇宙里包含着小宇宙的无限迭代形式。分型是自然界中的图案的主宰，从树叶到海岸线，到我们的肺都具有此类结构。分型如此常见，是自然界中的混沌动力学体系写下的诗篇。每一个分型结构的背后，大概都藏着如蝴蝶翩翩起舞般美丽的动力学方程。

凯恩斯是政府干预理论的创始人。他的理论基于一个二维的模型，以市场供求永不能自发平衡为原因，主张以政府干预调节市场周期。 而哈耶克作为凯恩斯的大反派坚决反对市场干预，他的模型是高维的，混沌的，认为对市场这样的高维体系，没有人能够真正预测其走势，政府干预多害少利。两者模型的维度大小决定了理论的高度。 * 混沌的不可预测其实是描绘初值敏感，两个起初靠在一起的轨道注定要发散。 但是它终究是确定性系统，与量子力学的不确定不同。

当系统的维度发展到大于三，或者任意N维，我们就得到了一个复杂网络。因为系统的维数即变量个数，一个N维的系统意味着N个互相作用的变量，这就已经是一个复杂网络了。复杂网络是复杂科学的物质载体，而得到我们这个时代或未来任何实用的理论模型，都离不开它。
