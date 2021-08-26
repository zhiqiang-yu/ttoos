---
categories:
- 开源
- 感悟
date: 2021-08-17T16:35:12+08:00
description: "笔者一直以来都认为，如果对某些事情不能够做到充分的理解，就尽量不要去触犯他们的禁忌，这不是说是否受到惩罚的问题，而是一个文明达到一定高度的标志，如果你没有这么做，代表着落后、愚昧和无知，失去的就是信任、尊严和社会资本。"
keywords:
- Open Source
- Culture
- Reading
- News
tags:
- 每周精选
- 开源之道
title: "在开源世界里，应该持有什么样的法律思维"
url: ""
authors:
- 开源之道
---

> 没有一个社会是靠多打官司而变富变强的。法院即使处理纠纷再公正，从社会整体角度来看，总体效果也只是“左兜装右兜”——只是在既有的社会产值中进行分配和再分配，而没有增加总体产值，甚至为此还要把纳税人的收入拿出来填补司法程序的耗费，这甚至是一种内耗。
>
>  ———— 刘晗 《法律是种思维方式》

## 引言：从社会分工出发

关于人类分工协作生产[1]，经济学家们都讲过非常好的故事，甚至可以说是脍炙人口，如亚当·斯密在《国富论》提到过的别针的案例，以及 Leonard E. Read的《我，一支铅笔》[2]，这些小的故事，让我们理解到社会分工为我们现代的繁荣带来的极高价值。

作为近几十年来高速发展的计算机相关技术，也概莫能外，伴随着技术的不断涌现，由技术引发的相关的经济、法律、社会等也出现相当多的细分领域，其中尤为注目的公司的法务这样一个新的岗位，一名优秀的商业律师和公司法务，除了必须有律师证、会打官司之外，还要懂财务、懂商业、懂管理，甚至还要有极强的社交能力，才能够应对公司所面临的极为复杂的法律问题。

软件相关的法律问题，自从被纳入知识产权范畴，可以合法售卖之后，自由软件运动、开源软件运动，以及当下修改开源许可协议等等一系列事件，也说明了这个领域的细化。

社会分工，意味着人除了自己花了数年的刻苦训练之外所获的的知识和经验之外，对于其它行业的了解和认识是空白的，所谓的“隔行如隔山”，那么这也就意味着程序开发者、工程师、和法律许可、知识产权的分离，彼此之间存在着相当大的隔阂，任何一个专业都需要花上数十年的功夫才能掌握。而想要彼此配合，唯一能做的就是把自己熟悉的部分做好，不要去做突破规则的事情。

## 从法律的历史，看规则的重要性

>  *不以规矩，不能成方圆*。
>
> ———— *孟子《离娄章句上》*

从刑法的角度，去追溯法律的起源，是从复仇开始的，而之所以演变为现代法律，是因为社会控制系统的升级。而回到知识产权的官司升级，是因为经济的发展，为了保护最初的发明和创新者的努力成果，关于此点描述，美国著名历史学家丹尼尔·布尔斯廷（DANIEL J. BOORSTIN）在其著名《民主的历程》[3]中所描述的：

> 美国对勘探和开发大陆的新办法的需要，以及对财富的任意的追求，产生了无数的新技术、新机器和新装置。即使发明者可能是一个孤独的淡泊名利的天才，通常他的旁边总有别人看到了发财致富的机会。这些专为自己打算的旁观者往往就是律师。在内战后的那一个世纪里，差不多每次重大发明都引起一场法律斗争。虽然许多次斗争都是专利权问题进行的，但是专利问题还是不可避免地和契约法、公司法、税制以及习惯法规定的各种权利与义务的技术细节混在一起。同时，这种情况也同“洲际贸易”，管辖权的斗争以及联邦宪法的其它奥理玄义纠缠在一起。
> 美国专利权斗争这出戏的登场人物形形色色，但戏的情节确实非常一致的，有几个人可能差不多同时发明了一种新机器或新技术，大家都希望为他自己或他的许可证持有者保有全部生产利润。在这期间，出场的可能还有许多商人，他们从相互竞争的“原创”发明者那里买下了一部分合法权利。接着，每一个“改进者”当然也提出了权利要求，说只有经过他改进的机器或技术才能真正解决问题。官司一直打了几十年，但是不管是哪一个发明者或商人打赢了官司，胜利者总归是律师。他们不仅得到了大量的费用，而且对于公司的权利和弱点了然于胸，因而常常能把公司置于自己的掌握之下。他们开始时还不过是领航员，最后却成了船长。

毫不夸张地说，没有法律，现在的世界将会是另外一番天地。那么归根结底，法律就是一个关于规则的事情。

我们知道，法律的核心是“凡事讲规则”。事实上，只要是由人组成的社会，就会有各式各样的规则。即便是原始部落，内部也会有各种规范，否则便无法维持秩序[4]。回到版权方面，据记载，我国最早的版权，始于宋朝。

![](http://p3.itc.cn/q_70/images03/20201119/2f17763bce2e446ba18e0e8ad8ac5f44.jpeg)

如上图所警示：“不许覆板”。但在尚无法律保障之当时，实属威吓之举。[5]

开源的许可，也不例外，它也是一系列规则，作为软件代码的原作者，申明了自己的作品应该如何被传播和使用的细则。目前世界上，被开放源代码促进中心OSI [6]承认的开源许可协议超过了10多种，如此之多的规则，是不是需要专门的分工了呢？答案是“yes”，但是，其它和此紧密相关的职业，又需要对它了解多少了呢？

## 开发者对开源许可证的知识应该掌握多少？

其实，这是一句没有用的废话，最佳答案应该是：“能掌握多少就掌握多少，多多益善。”

但是，现实中其实并没有那么的乐观，除了我们在引言中提及的分工精细带来的认识和教育上的困难之外，还有更多的问题是开发者没有时间来学习，比如开源许可证之间的兼容性问题，这还真的必须是专业的人员才能解读。

理解开源许可证，我们还要追溯到什么是软件许可，如果要理解软件许可，我们还需要何为著作权[7]、专利、商标，以及世界各国的定位，当然，还有什么是公共领域。这是非常专门的知识。

不过笔者也认为，大可不必焦虑，我们至少作为社会人，应该都可以理解开源的定义：

```
1. 自由再发布
2. 源代码可用
3. 可派生作品
4. 作者源代码的完整性
5. 不能歧视任何个人和团体
6. 不能歧视任何领域
7. 许可证的发布
8. 许可证不能针对某个产品
9. 许可证不能约束其他软件
10. 许可证必须独立于技术
```

那么在复制他人代码，或者是自己的代码以开源协议发布的时候，掌握并遵守这几条原则是最起码的要求。

## 不用法律，本身就是法律思维

在笔者所生存的环境下，所遇到的大部分人，谈到开源许可的时候，直觉上就是如果我违反了，会受到什么惩罚？如果没有惩罚的话，那么我就可以肆无忌惮的做下去。这个想法本身无可厚非，毕竟中国几千年的历史都是这么过来的。但是既然意识到了，这样的思考方式是有问题的，那么就需要去做出改变的行动。也就是说，如果我们想拥抱开源，加入开源的大家庭，就需要遵守相应的规则，而不是利用一些手段来钻空。

不过近年来，很多人开始相信，随着知识产权保护的过度扩张，知识产权这个概念创立之初的宗旨已经改变：知识产权的目的已经从保护公众利益变为保护知识创造者的利益。这可能会给一些“盗版”者们以理由，更加乖张的进行违反开源许可的活动。但是作为开源从业人员，要分清楚这点，抵抗知识产权的过度扩张，不是去使用和贩卖盗版，而是应该拥抱自由/开源软件，积极的为自由/开源软件尽一份力，而不是被知识产权的捍卫者们抓住把柄。

另外，开源许可本身并不是为了官司而存在的，而是一种对违反规则的人或组织的自我保护。

> 我们生活的时代，愈发强调透明、快速、低价、创新和市场化等价值。然而，法律体系却不能太透明、太迅速、太普惠、太灵敏、太商业化。否则对法律人不好，对法律不好，对社会也不好。法律毕竟代表了社会不完美的一面，突出了人性不完善的一面。即使一个案件最终实现正义，也只是弥补了一个悲剧，而不是创造了一个喜剧。一如既往，法律提供的只是次优解决方案。 这就启示我们，在日常生活中，我们不但要学会用法律解决问题，还要学会不用法律解决问题。最高级的法律思维是备而不用。从更大的意义上来说，任何一个行业，都有解决问题的独门秘诀，同时也有行业本身的内在限制。“请神容易送神难”：我们在解决任何问题的时候，都要考虑解决方案本身会带来什么新的问题。[3]

在开源的世界里，有很多组织，其实就是抱着这样一个思路来做事的，如开放发明网络OIN[8]、如[软件自由法律中心（SFLC）](posts/foundation_introduce/introduction_of_software_freedom_law_center/), 所谓之：“防人之心不可无”， 我们最终的目的是让自由/开源软件能够尽可能多的服务于我们所赖以生存的社会，而不是将作品变为控诉他人的武器，不仅浪费自己的时间，同时也在浪费这社会宝贵的资源。

总结一句话，虽然开源的许可是一种具有法律效益的著作权申明，但是这更多的时候是一种自我保护。为了让更多人受益，为了不被钻空的人利用，必须这么做，而这个武器我们不会轻易使用（这也是大家很少听到关于开源软件官司的原因），不轻易使用，恰是开源的法律思维的精髓。

## 加速带来的风险，该如何处理？

但是，我们仍然不能停留在理论上，我们仍然要在实际中能够可执行。否则不过是一种理想的状态的空谈罢了。

我们所生存的环境，随着物理技术和社会技术的不断发展，尤其是全球化的供应链的形成，以及信息技术的超级发展，让我们的生活变得越来越快，甚至由于高铁的加速，一日跨几千公里的城市，都让人产生了一种对空间的错觉，笔者的一位朋友就在自己的朋友圈描述过：

> 中午在西安的公司食堂吃午饭，稍事歇息，赶回北京，在赶往北京南站的过程中匆匆吃了个饭，晚上10点中到达自己在天津的家里，在孩子们即将上床休息的前一刻。

大加速的背后，是信息的瞬间到达、交易和支付的便捷、交通工具的调度、食物加工和冷冻技术的进步，以及成就这个最为关键的因素：人类的主动分工与协作。

加速其实在信息产业里的计算机软件是最形象不过的了，那么在DevOps和持续交付的当下，源代码是否遵守开源许可，不仅是一件智力和知识的挑战，更多的是体力上的挑战，但是计算机的思维里，有一项美德：**能自动化的绝不应该由人来做**。

相应的工具，一应俱全：

* 开源项目在线扫描服务：中国信通院代码合规SaaS平台[9]、LFX[10]
* 代码扫描开源工具：SPDX、FOSSID
* 商业代码扫描工具：BlackDuck、Snyk、WhiteSource等
* 相关工作流程和标准：OpenChain

有了这些工具的帮助，开发者、法务以及开源共同体，大家都相安无事，和谐发展！共创开源世界的美好未来。

如果你对开源的法律思维有更进一步的思考，欢迎来OSCAR2021 可信开源大会的开源知识产权等论坛，和在场专家一同交流，如果没有也没有关系，至少过来可以学习如何做好开源互惠合法的工具，并进一步了解这些分析平台的最新进展。

## 参考材料

2. 《社会分工论》，[[法\] 埃米尔·涂尔干](https://book.douban.com/search/埃米尔·涂尔干)，生活·读书·新知三联书店，2017-1
2.  https://zhuanlan.zhihu.com/p/108725355 , 最后访问时间：2021.8.18 
3. 《美国人：从殖民到民主的历程（三部曲 ）》， [[美\]丹尼尔·J·布尔斯廷](https://book.douban.com/search/丹尼尔·J·布尔斯廷)，上海译文出版社，2014-12
4. 《想点大事：法律是种思维方式》，刘晗，上海交通大学出版社，2020.5
5. “翻刻必究”：中国古代著作权人的自我保护 ，https://www.sohu.com/a/432822836_523187，最后访问时间：2021.8.18
6. https://opensource.org/ ，最后访问时间：2021.8.18
7. https://zh.wikipedia.org/wiki/%E8%91%97%E4%BD%9C%E6%AC%8A ,最后访问时间：2021.8.18
8. https://openinventionnetwork.com/about-us/why-oin/ ,最后访问时间：2021.8.18
9. http://scan.opensourcecloud.cn/o/open-monitor_saas/ ，最后访问时间：2021.8.18
10. https://security.lfx.linuxfoundation.org/ ,最后访问时间：2021.8.18