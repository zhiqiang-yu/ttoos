---
categories:
- 开源
- 技能
date: 2022-02-22T21:11:12+08:00
description: "跨越地理空间的协作在互联网发明之前是低效的，甚至是不可能的，然而，计算机本身的编程特性，却首先被自身的协作所验证，那么，显然并不是在经历同一个时间来完成的，而是跨越空间的非同步的情况下进行的，不得不说是人类合作史上伟大的奇迹。"
keywords:
- Open Source
- Culture
- Reading
- 开源技能
tags:
- 开源布道
- 开源之道
title: "LF APAC 开源布道者分享系列之七：如何娴熟使用异步沟通之法"
url: ""
Author:
- 开源之道
---

## 时间是最稀缺的

> 当人们共同工作时，时间往往在摩擦中白白消耗：分到与自身能力不相称的任务，或是由于某种差异而冲突不断。每个人都参加过长达数小时但结果欠奉的会议。有时我们构建团队所花的时间甚至远远超出完成实质性工作所用的时间。与他人共同完成某项工作给人带来的挫败感实在是太大了，大多数人宁可多花一些功夫独立完成任务，也不愿意与他人组成团队，共同完成某项工作。
>
>  ———— Roger Fisher 和 Alan Sharp 《横向领导力》

我们经常会听到这样的说辞：

> 将我自己复制个几十个，我一定可以完成巨大的工程项目，比如写个操作系统或数据库啥的。

尤其是能力较强的人，还通常有这样的愿望，面对自己独立无法完成的想法，在花时间和他人沟通时，所遭遇的情况，莫过于此感慨的，不过，这是一种积极的思考方式，大量的还是负面的抱怨：技能、沟通、表述、不合作等等。

这里要谈及的时间并非现代化，由各种技术所带来的时间都加速。而是针对一个团体当中在协作的过程中，每个人的时间加起来之后，如何尽可能的接近数学上的和，而不是现实中的，最糟糕的时候，还不如一个人的独立成绩。然而，我们做任何事，都需要时间。

然而，现实是，人们只能拥有自己所支配的有限的时间。时间在政治学家那里几乎成了人类最后的公平！

## 为何要异步

>  “我”就是带着这样专横狂妄的姿态降临到这个世界上，仿佛一个造物主。每一个“我”都以为自己是世界的中心，每当一个新“我”诞生，世界便又重新诞生一次。地球上的六十亿个人便是这个宇宙的六十亿个中心，从个人中心望去，世界个个不同。
>
> ​       ———— 张宏杰 《我是谁》

人将自己安排起来，已经非常的不易，从睁眼起床到躺下睡觉这中间，除了生理上必须的处理之外，休息、运动与劳作是最为主要的事情，那么能够将这段时间按照自己的意愿排列起来，作为现代人实属不易。

而且，每个人每天的时间是固定的，按照现代大部分国家的法律，8小时是属于工作时间，这是有限的，也是珍贵的。作为知识工作者，很多时候的工作是需要专心而长时间的思考，也就是说零碎的、规律性的工作不是知识工作者的日常，那么这就导致一个问题就是，在和他人沟通，与自我深度思考的平衡。

另外，人的大脑设定，在做类似于编程、写作、思考等过程等时候，是需要相对身体没有大的动作、安全静谧的环境中，才能做到，注意力更加是极度稀缺的。

再回到合作上来，显然人不合作，能做的事情是有限的，尤其是大型的工程，如操作系统、数据库这样的巨型工程。或者说软件天生就是需要合作的，因为任何一个功能都超出了个人的有限时间能完成的。

基于上述属性，想要实现更大的目标，唯有异步的沟通，才能实现个体无法做到的事情。

![](https://stitch-ai.com/wp-content/uploads/2020/07/89c65f23fe3166a965b52d3de8e0b3754ec5d10a-1024x572.jpg)

## 异步的优势

自律是人类卓越品质之一，看似简单却令无数人望而兴叹，自律是一个很容易理解词汇，也看起来没有什么难度，最大的难度就是可以自己按照符合自己的节奏进行生活和工作，换句话说，就是可以掌控自己的24小时，按照自己的意愿合理安排所做的事情。

如果让两个不同的个体，去相互配合，一定会有所不同，需要协商。

作为个体，最大的优势莫过于自己可以安排一天的时间做什么，并且在习惯这个强大的助手的支持之下，能够做到在何时以什么样的方式工作最舒适，高效而合理。

沟通固然重要，但沟通不是事情的全部，人还是要做好属于自己的那部分工作的，而这部分工作，是需要调动自身的大脑、身体而达到的一种状态。在需要沟通的时候沟通，确保最大化的沟通效果，而异步是控制沟通的最佳方式。

异步也是开源能够协作成功的最为重要的特点之一，基于源代码的协作本身也是条件之一。更多的不是传统意义上的面对面、协调等，而是按照模块、功能等来实现异步（康威定律）。

## 想象并理解他人的节奏

但凡有过工程经验和创作经验的人，都会明白沉浸式的状态，也就是著名的心流状态，在计算机编程、写作、阅读等都会有类似的状态，而这样的状态大多数时候是无人打扰的情形下实现的，这也就是Bill Joy 、Ricahard Stallman等开源英雄们常常连续工作十多个小时而不停歇的重要缘由。

想要异步，需要做到将自己的工作状态带入到他人的设身处地之中，希望自己多一些心流的时候，那么同样其他人也同样希望如此。

有的时候，由于分工的不同，我们无法能做到感同身受。只能尽最大努力通过沟通、对话、阅读来完成对他人工作的想象和理解。在开源当中，最重要的是编写程序，这是一项需要脑力专注的劳动，基本上是无法通过零碎的时间完成的。

当你了解了他人的工作状态之时，或者是根据自身的工作状态思考之后，再去和他人沟通的时候，其实异步的需求是极为强烈的，而且也会慢慢享受这种舒适的感觉。

## 用文字和代码来架设沟通的桥梁

选择异步，意味着不再能使用口头交流来完成工作的协作，而是采用了更为抽象的文化，当然在软件的开发中，使用的是代码。

这也意味着要发展自己的技能：文字表达，或者是编码能力，这是和他人协作的重要通道，将自己能做的都做好，替他人考量，留好接口。

这两项技能需要大量的练习才能习得和掌握，也需要花费大量的时间去练习，在写作或编写的过程中，锻炼其它的能力。

## 有效利用工具

即时通信在现代已经能够实现的非常之高效了，尤其是移动时代的到来，人们可以说是实现随时随地的音视频沟通，多人通话的能力，而且是廉价而简便的。当然，越是这样，异步的效能可能被忽视。

但是异步沟通的工具，仍然是坚实而不可替代的，如电子邮件及其列表，Web的发展是的平台性技术如GitHub issue等都能够实现异步沟通，参与者只需要根据自己的时间安排来进行协作，这也是所有开源项目默认的方式，也是开源之道中所倡导的方式，在跨全球的技术合作之下，这是最为高效和人性的方式。

* 邮件列表 
* Google doc /Office 365 在线文档编辑、日程安排

* GitHub/GitLab 等代码托管平台
* issue 或bug 跟踪系统 
* Wiki 等多人协作文档系统

技术已经帮助我们高效的实现了异步的工具，我们需要做的就是善于利用它们，和他人一起卓越的完成工作。

## 结语

有的时候，看起来是一项技术的使用问题，如笔者经常会遇到在微信里被丢一个ppt或word文档过来，其实背后隐藏的是人的思维观念，也就是说在协作这件事情上，我们真的是否考虑过他人？

观念不变，再高深的技术放在那里都是毫无意义的，即使到云计算无处不在的今天，我仍然会时不时的听到有人抱怨由于停电或咖啡洒电脑的原因，而丢失了写了数个小时的文档。

异步沟通，表象是某个程序使用的问题，背后的本质是人的观念和素养。从本质下手，然后训练自己的技能，而不是相反。

你准备好和他人协作了吗？或者说，你希望能够进入心流状态而不被他人打扰吗？如果是的话，那么请和我们一起倡导：**异步沟通！**

## 题外话： 中国人不适合异步？

我们经常会遇到，在国内/本土推广邮件列表失败的言论，然后基本都笃定地说：中国人不适合邮件列表，异步通信，有微信就证明了一切。在开始的几年，笔者也是蛮沮丧和备受挫折的。在经历了几年的观察和思考之后，放下所有的情绪，直面事情的背后真实逻辑。

我的观点/结论是**需求没有达到需要异步的程度**，大家996/711等加班加点，电话及时响应同步会议不分昼夜，具体的原因有很多，宏观条件下中国40年改革开放的现代化进程，文化中响应他人的优先，微观的原因也有很多，急于在公司上司面前表现，管理层善于心理操控等等诸多因素。

换句话说，从世俗社会到法理社会的转变还没有完成，人们性格中软弱的因素更多一些，个人时间的强烈诉求没有那么多。这是异步沟通难以流行的真实缘由。但是不用着急，只要现代化的进程不停歇，文明程度不断提升，社会需要更多创新，异步沟通这个刚需就会被提上日程。

当然，我很希望那一天的早日到来。