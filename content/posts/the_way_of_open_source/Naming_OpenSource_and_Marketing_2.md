---
categories:
- 开源
- 感悟
date: 2017-01-26T21:02:38+08:00
description: "深受”秘方“文化洗礼的国人，再加上共产主义的破灭，对于开源软件始终处于莫名其妙的误解之中。有鸵鸟式的‘拿来主义’、有泼皮式的‘流氓形态’、有厚颜无耻的独立IP型、有挂羊头卖狗肉式的伪装型等等不一而足，可谓是千奇百怪，丑态百出。本文试图从创新的角度来看开源软件能够成功的背后因素。如果能够正本清源，让世人认识到开源的本质的话，也算是一件颇欣慰的事。"
keywords:
- Open Source
- Culture
- Reading
- News
tags:
- 开源文化
- 开源之道
title: 开源软件是开放式创新的最佳注解
url: ""
---
> 想象一下几个世纪之前，科学是如何被信仰所感知的。科学在一开始被认为是信仰之外的东西，受到宗教的残酷打击和压制，这样的情形就像是现在的软件公司对待开源软件的工作一样。其实正如科学不会破坏宗教制度一样，开源也不会粉碎现有的软件系统，开源旨在开发出更优秀的软件而已。                  ———— Linus Torvalds ，Linux 创始人

某种程度上 Linus 的此番话语，在今天看来已经实现了。

## 写在开始之前

其实我最初构思这篇文章的时候是想为文章[《为开源和商业正名》](http://www.ocselected.org/posts/Naming_OpenSource_and_Marketing/)做一篇续作，因为那篇文章虽然说是一气呵成，但是我本人觉得并不满意，后来也没有人和我辩论，然而我却一直在思考，上篇文章说的更多的是市场术语，商业上的成功案例等，而阅读我文章的人，大多是技术出身，不屑于这些，所以我尝试换一个角度去论述：“为什么开源会逐渐成为主流（显学）？”也就是创新的角度。

另外要提及的一点就是，其实引发我作出辩解的是对于开源商业上的误解，对于误解本身，得上升到社会、制度、历史、习俗等来解释，此处仅提及一点，那就是可口可乐式秘方文化在其中作祟。限于篇幅，我又不能偏离技术去批判文化与世俗，所以针对此我只想引用一句王小波的话来说明：

> “身为一个中国人，由于有独特的历史背景，很难理解科学是什么。我在匹兹堡大学的老师许倬云教授曾说，中国人先把科学当作洪水猛兽，后把它当作呼风唤雨的巫术，直到现在，多数学习科学的人还把它看成宗教来顶礼膜拜，而他自己终于体会到，科学是个不断学习的过程。”  ————王小波《生命科学与骗术》

## 何为开放式创新？

开放式创新，由加州大学伯克利分校的教授 Henry Chesbrough 在《开放式创新：新的科技创造盈利方向》（2003）一书中提到。

“开放式创新是指公司利用外部思想进行创新，拓展科技。”或者指"与合作伙伴一起创新，分享风险，分享盈利。"公司和周围环境之间的界限变得模糊，创新可以在公司以内和公司以外进行。开放创新的核心思想是世界上充满了知识，公司不需要完全依赖公司内部进行科研，可以把创新进行授权(如通过专利)给其他公司。另外，公司内部不能进行的创新可以在外部进行(例如通过授权、合资公司、资产分拆)等。

随着时间的推移，开放式创新逐渐被人们所认知，开始有很多人研究了起来。近年，开放式创新的学术研究，逐渐增多，其中对于开源软件的研究也有人开拓先河。如[Joel West](http://www.joelwest.org/Research/OpenSource) 博士的研究成绩。而其中开源软件是开放式创新的绝佳注脚。

## 开源软件的创新实例

创新的理论，和很多艺术的批判总结一样，都是事后的总结。开放式创新似乎也难逃其咎，开源软件在今天已经用事实证明开放的力量是足够的强大。我们就以下面几个事例来旁证一下。

### 1999年 IBM 投入 Linux

IBM 当年在PC失利之后，以谁说大象不能跳舞的姿态转型服务的时，其中就有一项相当有魄力的决定：所有的硬件平台和中间件、数据库产品均开始支持Linux，并提供完全的服务。并投入大量的人力和资金，不仅对Linux本身的开发，还有修改所有软件均支持Linux 的移植。这一决定现在看起来仍然是及其明智的。不仅给IBM带来了直接的经济利益，也为日后的产业标准、开源战略奠定了基础，如后来的WebSphere市场占有率和Eclipse的成功。即使在互联网迅猛发展的21世纪头10年，IBM仍然是IT全面解决方案的龙头，其中尤以产品线全面支持Linux为特色。

### Mac OS X 的发展史

我们知道Apple公司的操作系统（MacOSx、iOS、tvOS、watchOS等）核心均来自一个项目，那就是大名鼎鼎的 Darwin，而Darwin的历史要追述到1989年，史蒂夫.乔布斯被赶出苹果创建NeXT公司开始说起，最初的名称并不叫做 Darwin，虽然一开始就借力 BSD，但是直到1999年才明确下来，整个MacOSX ，内核等主要技术使用BSD衍生技术，只有图形界面采用闭源的方式开发。

![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Unix_timeline.en.svg/2000px-Unix_timeline.en.svg.png)

### 浏览器 Safari 的演变

在1997年之前，Apple的 Macintosh 上可以运行的web浏览器是网景和Cyberdog，之后就是微软的IE统一这Mac的天下，直到2003年， Steve Jobs 声称Apple将自己开发web浏览器，不再受制于人。但是Apple并没有重新制造轮子，而是使用了著名开源KDE的称作为 KHTML的渲染引擎（webkit）开发的，一直沿用至今。Apple也一直以后都是webkit的主要贡献者之一，而现在的Safari 10 已经走过了13个年头，并稳居浏览器市场的前三。WebKit也是Apple 移动端操作系统iOS主要使用的技术引擎。

当然，WebKit 也因为有了Apple的加入和反馈而彰显更强的生命力！

### Google TensorFlow 的开源之路

Google 的云计算平台在商业营收上始终差了AWS一大截，但是Google的自信来自于对自己技术的高度认可，认为争夺下一次的优势在于人工智能，于是在2015年11月9日，毅然决然的将旗下深度学习项目——TensorFlow 开源，并采用科学的社区管理模式，挖掘开源界人士，一年之后，硕果累累：

* 在GitHub上超过3000多个相关项目，其中Google发起的只有5个。
* 澳大利亚海洋生物学家利用TensorFlow进行搜索海牛海量识别
* 日本农民来识别优质黄瓜培育
* 放射科医生将TensorFlow应用于医学扫描，来识别帕金森病的症状。
* ......

在人工智能深度学习领域，Google拔得头筹，可以看一张类似项目的对比情况：

![](https://tctechcrunch2011.files.wordpress.com/2017/01/screen-shot-2017-01-30-at-11-54-19-am.png)

后来，微软、亚马逊、FaceBook纷纷效仿，争相开源。已是步后尘罢了。

### 不胜枚举

开源正在逐渐成为主要的创新方式，比如去年最大的新闻：微软青睐Linux，开放.NET平台源码，刚刚过去的春节发生了几件开源的大事：Google 贡献 Beam 大数据处理项目、亚马逊贡献MXNet给Apahce......各IT大鳄都在争相开源，背后的动机：增强自己的竞争力！绞尽脑汁的创新。

~~### 预测一下未来的开源软件项目~~

~~* 量子计算公司D-wave开源了项目Qbsolv，其发言人如此说道：“D-Wave是驱动量子计算硬件的，但是我们仍然想要大量的应用以及软件工具。” 这就是开放式创新的一个重要的支点。~~
~~* Blockchain 项目超级账本~~

## 成功的原因

### 不愿重新制造轮子

尽管开源界素有“乱造轮子”的不好声誉，但是对于商人来说，能够让产品快速的上市，迅速占领市场，或者占领先机才是王道。这就是Apple开发MacOSX 选择 BSD 核心、Safari浏览器使用webkit引擎背后的秘密。

其实现在的很大一部分商业产品中都使用了开源的项目，只要认真的读一下协议，基本都能看到类似OpenSSL、python等开源的许可。比如VMware，乃至公有云厂商如亚马逊AWS，使用的Xen虚拟化技术，就是典型的利用开源，和开源形成共识，然后形成自己的服务。

### 技术的进化

在《技术的本质》一书中，经济学家、技术思想家布莱恩.阿瑟精确的道出了技术什么，以及它是如何进化的。**所有技术产生于已有技术，也就是说，已有技术的组合使新技术成为可能** 。并在最后论道：“秩序、封闭、均衡作为组织解释的方式现在让位于开放性、不确定性、以及永恒的新颖性。”

技术的组合，产生新的问题，进而再解决，再组合，如此反复。跨学科的技术越来越普遍的存在，比如炙手可热的无人驾驶汽车。

“经济是技术的表达”！当今商业世界，技术创新日新月异。如果不利用外部知识和技术，几乎任何企业都无法保持独占鳌头的技术优势。

### Joy 法则

Sun 公司联合创世人Bill Joy，开源界赫赫有名的程序员、Hacker，对于人才的管理有一句耳熟能详的名言，称之为[Joy法则](https://en.wikipedia.org/wiki/Joy's_law_(management))。

> **"no matter who you are, most of the smartest people work for someone else,”**

可以解读为三层意思：

1. 聪明的员工不干活
2. 大部分聪明绝顶的员工不为自己公司干活
3. 因此创新都是来自公司外部

没错，要善于利用外部的力量！尤其是创新这种事情。

## 结语

我们不妨大胆的预测，未来会有更多的开放——开放的设计、开放的教育、开放的政府......而开源软件将一如既往的成为开放式创新的领头羊，人工智能，Google 开源项目 TensorFlow 即是站在风口浪尖、引领潮流的证明！著名家具销售商宜家，将其沙发等设计、供应链等开源，以创新的脚步追随顾客的需求！

随着世界的快速变化，加速发展，研究领域的彼此融合、沟通方式的便捷、协作方式的改进，开放式的创新将会是创新的主要方式————超越一家大型企业，甚至超越一个国家的机构能力。

开放——让世界更加的美好！