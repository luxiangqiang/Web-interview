# 🔥《大前端吊打面试官系列》

![](https://github.com/luxiangqiang/Web-interview/blob/master/images/logo.png)



## 📚更新日志

- **2020/1/7**  开始决定写近十几万字前端面试系列，规划整个系列目录提纲。
- **2020/1/8**   写完部分“面试官到底考察你什么”内容。
- **2020/1/9**   继续完善”面试官到底考察你什么“内容。
- **2020/1/11**  开始写准备简历部分。
- **2020/1/13**  完善面试前的准备内容。
- **2020/1/14**  对面试准备内容做一次整体的优化。
- **2020/1/15**  开始写 JavaScript 基础知识部分 。
- **2020/1/16**  写数据类型中的七大模块部分 。
- **2020/1/17**  写 this、闭包等重点部分。
- **2020/1/30**   写消息循环机制的原理
- **2020/02/02**  补充 new 的实现原理
- **2020/02/03**  补充继承等知识内容，以及一些参考文献
- **2020/02/04**  补充垃圾回收机制等知识内容
- **2020/02/05**  补充深浅拷贝等知识内容
- **会持续更新中...**

****

## 📖目录

- [本系列介绍](#本系列介绍)
  - [❓俺为什么要写本系列？](#❓俺为什么要写这一系列？)
  - [⛏️本系列有什么特点？](#⛏️本系列有什么特点？)
  - [🏆本系列的目标](#🏆本系列的目标)
  - [👨‍💻不适合人群](#👨‍💻不适合人群)
  - [⚠️阅读须知](#⚠️阅读须知)
- [💬面试到底考察你什么？](#💬面试到底考察你什么？)
    - [基础是否扎实过硬](#1、基础是否扎实过硬)
    - [思路是否清晰明确](#2、思路是否清晰明确)
    - [能否写高质量代码的能力](#3、能否写高质量代码的能力)
    - [是否有优化性能的能力](#4、是否有优化性能的能力)
    - [是否有快速学习能力](#5、是否有快速学习能力)
    - [是否有人际沟通能力](#6、是否有人际沟通能力)
    - [是否具备强大的综合能力](#7、是否具备强大的综合能力)
- [✏️面试前如何做准备？](#✏️面试前如何做准备？)
    - [简历准备](#一、简历准备)
        - [简历形式 ](#简历形式 )
            - [非统一简历](#非统一简历)
            - [简约大气](#简约大气)
            - [真实简历](#真实简历)
            - [PDF版本](#PDF版本)
        - [简历详情](#简历详情)
            - [简历页数](#简历页数)
            - [个人闪光点](#个人闪光点)
            - [谨慎熟悉、精通关键字](#谨慎熟悉、精通关键字)
            - [项目经历](#项目经历)
        - [小技巧](#小技巧)
        - [大忌](#大忌)
    - [了解公司](#了解公司)
    - [面试内容](#1、面试内容)
    - [主要业务产品](#2、主要业务产品)
    - [发展前景](#3、发展前景)

- [JavaScript 基础知识点](#JavaScript基础知识点)
    - [数据类型](#数据类型)
        - [1、数据类型的存储形式](#1、数据类型的存储形式) 
        - [2、Null](#2、Null) 
        - [3、数据类型的判断](#3、数据类型的判断) 
        - [4、类型转换](#4、类型转换) 
        - [5、四则运算](#5、四则运算) 
        - [6、逻辑运算符](#6、逻辑运算符) 
        - [7、比较运算符](#7、比较运算符) 
    - [this](#this)
    - [new](#new)
    - [闭包](#闭包)
    - [原型和原型链](#原型和原型链)
    - [继承](#继承)
      - [经典继承](#经典继承)  
      - [组合继承](#组合继承)  
      - [原型继承](#原型继承)  
      - [寄生式继承](#寄生式继承)  
    - [垃圾回收机制](#垃圾回收机制)
      - [两种垃圾回收策略](#两种垃圾回收策略) 
      - [标记清除法](#标记清除法) 
      - [引用计数法](#引用计数法) 
      - [如何管理内存](#如何管理内存) 
    - [深拷贝和浅拷贝](#深拷贝和浅拷贝)
    - [异步编程](#异步编程)
        - [执行上下文](#执行上下文) 
        - [执行栈](#执行栈) 
        - [宏任务](#宏任务) 
        - [微任务](#微任务) 
        - [运行机制](#运行机制) 
        
        

## 本系列介绍

嗨！各位好，额是小鹿，一位被耽误的前端打杂师。

本系列将会把大前端所有常考面试知识点以及如何准备面试进行全面复盘。按照常理，是做不到完全全面的复盘的。但是希望俺的这一系列能够帮助你在接下来的春招中能够收获自己满意的 offer。有一点说明一下，之所以下决心开始写本系列内容，因为俺觉得这也是一次给俺自己查缺补漏的过程，同时又能分享给学习前端的其他开发者，无论是你前端工作多年的开发者还是一个在校的初学者，欢迎为本系列提出合理的建议，俺会在后期不断完善本系列内容。



### ❓俺为什么要写这一系列？

俺个人是野鸡大学出身，无学历，无大厂背景，但是在自学中经历了各种苦逼的事情，正是因为这种苦逼的经历，让俺收获了很多，同时俺在大二的时候开始写作在公众号分享自学的经历和技术。在写作分享的过程中遇到了很多非科班以及自学者的交流，从和读者交流中得出，存在自学者知识的零散性和非科班面对毕业找工作的困惑等，所以让俺在 2020 年有了这一新的打算。

> PS：其实俺个人学前端没有多久，第一份工作是自学四个月之后，独自跑去一线城市面试，拿到了自我感觉满意的几个 offer（非大厂）。由于环境因素，所有 offer 全部放弃，也成功错过大三的春招和秋招，后来我陷入了对人生的思考......。

直到今年 2020 年，俺决定开始从零全面整理前端面试相关知识点。虽然系列的名字听起来挺牛 B 的，但是可能写的达不到很多人的期望，所以对本系列期望不要太过高。俺也会按照掘金小册的规模和要求去写。最后，俺给本系列设定了一下几个写作目标和特点。



### ⛏️ 本系列有什么特点？

- **文章中会加一些通俗易懂的动画。**
- **能够经历时间的考验。**
- **实时更新、常年更新。**
- **全面性（广度和深度）。**
- **和读者一块完成。**



一篇好的文章不是别人说他有多好就有多好，而是他能够经受住时间的考验，能够持续的给读者带来新的认识和帮助，同时为了考虑到很多初学者，俺这个业余的动画师会在文章中增加一些**动画演示**。

俺自己也买过很多的付费资料，也包括大佬们写的小册子，写的很不错、很受益。俺的这一系列虽不能和大佬们的小册相比，但是尽俺最大努力去写。可能有些知识点暂时不能做到很详细，但是在后期会对文章无论广度还是深度上不断的再进行打磨。

看到过很多文章下读者的评论，考虑到很多读者说到广度和深度上的问题，尽管是付费的内容，也有写的不尽人意的地方，这也是作者不可避免的。本系列也不可能一次将知识点写到位，俺想而是通过后期于不断与读者的交流中打磨。考虑到俺也是一个上班族，所以俺只能利用所有的下班时间和周末时间去完善本系列当的内容。

还有一点就是，这个系列并不是俺个人完成的，而是和所有阅读这一系列文章的读者一块完成的。因为一个人的能力有限，所有希望阅读本系列的读者可以补充文章的不足点，或者你在面试中遇到的一些问题，俺会通过筛选、搜集资料将内容进行实时补充，同时俺也在 Github 创建了一个仓库，专门来同步本系列的文章，如果本系列写得受欢迎，后期俺还会开展其他系列。（[Github 仓库可以戳这里咯~](https://github.com/luxiangqiang/Web-interview)）



### 🏆本系列的目标

- 希望帮助你找到一份满意的工作。
- 完善前端知识体系。
- 增强前端的“基本功”。



## 👨‍💻不适合人群

- 想通过本篇一步登天、走捷径的不建议阅读滴~。
- 仅仅想通过这一系列文章就进入 BAT 的，也不建议阅读滴~。
- 认为文章没价值的，没营养，给他人传播负能量，在评论区抱怨的也不建议阅读滴~。



## ⚠️阅读须知

- 本系列完全开源免费。（如想付费，现金可以吗？）
- 本系列会在知识点的广度和深度上实时更新，常年更新。**地球不爆炸，小鹿不放假**。
- 本系列会与公众号「**小鹿动画学编程**」以及 [Github](https://github.com/luxiangqiang/Web-interview) 同步更新，转载请说明出处，谢谢您的转载分享。



## 💬面试到底考察你什么？

无论是前端的面试还是其他职位的面试，一个重点的问题就是公司以什么标准来考察你？面试官到底考察你什么能力？之前很多朋友跟俺说，只要你技术好，能干活，基础扎实，有沟通能力等，面试基本基本没什么问题。那么问题来了，技术有多好叫做技术好？干活效率有多高叫做能干活？沟通能力有多强才算标准以及除了这些能力之外，面试还主要考察应聘者的哪些能力呢？有没有一个衡量的标准呢？



那么根据俺看的一些面试书籍、付费资料、论坛以及与面试的读者朋友交流中，再加上俺之前的一些不同公司的面试经历俺想谈谈个人的一些经验？（纯属个人经验，不喜勿喷哦！）



公司设定了一定的笔试也好，电话面视频面也好，还是面议也好，其实综合来看，公司选人标准就是从以下 7 个能力方面出发的。（PS：对于实习生和应届毕业生来说，相信这六个能力已经全部概括了所有的面试内容，特殊公司要求除外哦~）



- **基础是否扎实过硬;**
- **思路是否清晰明确;**
- **能否写高质量代码的能力;**
- **能否有优化性能的能力;**
- **能否有快速学习能力;**
- **能否有人际沟通能力;**
- **是否具备强大的综合能力**。



这些能力相信大家可以看出，不是在短时间内一蹴而就的，而是经过长时间的积累和练习，看过《**刻意练习**》这本书的小伙伴们知道，不仅注重日常学习中的练习，更要给自己设定一个高目标以及在练习中不断的进行反馈、反思、总结，才能有可能达到以上几个综合的能力。那下面，俺根据个人的自学经验分别对以上几个能力展开唠唠。



#### 1、基础是否扎实过硬

基础的重要性俺也不想过多的强调，大多数的的应聘者都基本知道面试最主要的考试应聘者的基础是否扎实能力。一面，二面以及一些笔试面都是考察你的基本功。相信很多初学者对掌握一个扎实的基础没有概念，所以俺在不得不这多唠叨几句。



不瞒大家，做程序员之前俺也是个习武之人，扎马步、端棍子是每天不可缺少的一项基础功练习，无论是刮风还是下雨天，师傅就让你每天都要做同样的事情，习武前俺并不知道为什么让俺总练这些没有实际用途的东西。后来，俺在看《**李小龙**》这部电视剧中找到了答案，俺也将这几句话贴在了俺的 Github 仓库上，时时刻刻提醒着自己“基本功”的重要性！

- **练习“站桩”每天要坚持，一天都不能少！**
- **练“武”不练“功”，到老一场空！**
- **内练心智，外练筋骨！**
- **再好的功夫，练不好基本功，也会走样！**
- **练”武“太急是大忌，”基本功“要稳！**



俺对自己总结的这几句话，在后来自学前端中对俺有很大的影响和感悟。俺这里不是强调俺功夫有多厉害（俺可以一个打一群的那种~），而是俺强调的是编程”基本功“的重要性，同时你我都应该重视起来~

前端的基本功俺认为最重要的有以下几个：

- **HTML / CSS**
- **JavaScript基础/进阶** 
- **前端性能优化**
- **网络原理** 
- **设计模式** 
- **数据结构与算法** 
- **操作系统**



很多人说，第一条“基本功”可以理解是重点，但是对于后边几个“基本功”，前端有必要深入学习吗？而且这三方面学习来比较枯燥、无趣，学了也不一定的在实际的业务中用到。可别这么想，上边的几个基本功都是可以提高你的“**个人核心竞争力**”，所谓的“个人核心竞争力”，所谓的核心竞争力就是别人大部分没有的能力，而你却有。除此之外，这些“基本功”可以更好你项目的业务逻辑（设计模式），提高项目功能的性能（数据结构与算法），优化提升网络的通信效率（网络原理）。最后，容俺多啰嗦一句，有些理论看似在实际开发项目中用不到，但是真的有必要知道，当你真正遇到该问题的时候，你能通过已知的理论能够够快速定位到该问题。



#### 2、思路是否清晰明确

相信很多小伙伴和俺一样，写代码有一个毛病，还没把整个程序的思路理清，就开始上手写代码。后来因为这种情况，俺吃了很多亏，所以现在几乎慢慢的改掉了这个坏习惯，可以说这是编程的大忌，尤其是在给企业做项目的时候，不仅造成企业项目中的损失也会造成个人时间上的损失。

确实有些简单的问题直接上手写代码也是没问题的，但是对于复杂的问题，就要求开发者的思路清晰明确，越是复杂，越是要求开发者具备这种能力。为了能够养成写代码前理清思路、写好文档的习惯，俺这里还是建议大家无论是简单问题还是复杂问题，在动手写代码之前一定要保证把思路清晰哦~

俺这里分享自己最实用的三种整理思路的方式，**手写、画图、测试**。



- **手写**

通常一般拿到客户需求文档，显示用文字的形式去理一下整个项目的逻辑。如果在校生的话，一般会刷一些算法题，刷题之前一般都会将想到的思路写在纸上，然后选择最优的一个思路来进行测试程序的性能。自然而然这种先理清思路后写代码的习惯，在面试中也不用刻意的去表现了。



- **画图**

除了将程序思路写下，另一种提倡的就是画图，画图更能够保持思路清晰的去解决问题。就拿俺经常用动画来讲解技术的经历，很多人看了动画以及制作的一些图，对整个程序的思路就立马有一个清晰的思路，一般在纸上大体画画就可以，如果追求画的美观，还是要下不少的功夫的~。



- **测试**

最后一个方法就是将程序中的所有测试用例列出来，用于对你写的程序思路是否完善。当然，所有的测试用例不可能我们单纯的用大脑想全面的，这个方式有一定的局限性，可以结合手写、画图理清项目的设计思路。



#### 3、能否写高质量代码的能力

什么是高质量代码？如何写出高质量代码？都是我们要弄明白的问题。对于什么高质量的代码，俺的个人见解一下几个方面。



第一，程序中的一些边界条件是否考虑清楚。通常我们前期写代码都是 bug 百出，而这些 bug 正式考虑的不全面导致的。比如：上传表单按钮，你是否考虑到避免用户连续单击重复提交的情况？再如有输入框地方是否存在 XSS 攻击？虽然这些都是小细节，正式以为小细节，有时导致牵一发而动全身的威力。



第二，在面试中，面试官让你做一些典型的题目，一般你认为越是简单的越是容易，而的确相反，简单的题目越是有坑，作为面试者越是不会轻易的考虑到细节点。因为这道题在你心里的定位是道简单的题，你已经放松了警惕，给自己一个定心丸“不必多思考”。比如你是否判断输入的值是否为空，是否判断空指针的情况等等情况。面试者除了要求你完成一定的功能，还要求你是否注意一些细节问题。



回到问题的本质，俺这系列要讲的是如何应对面试，提高自己能力，提高个人核心竞争力以及日常开发中减少一些 bug。如何锻炼自己写高质量代码的能力才是俺重点要分享的。如下三个步骤：

- **将程序或者项目中的边界条件或者特殊条件考虑全面（并不能全部考虑到，主要靠项目中多积累）。**
- **然后应对这些条件，列出要进行测试的例子。**
- **写完代码，将测试用例带入，判断程序是否正确运行。**



#### 4、是否有优化性能的能力

一个优秀的程序员，对程序的性能优化也是追求极致的。面试过程中，面试官会通过前端常见的页面性能优化以及算法题来考察你的性能优化的能力。前端的性能优化主要在于网络（资源的压缩、合并）、渲染层面（首屏渲染）的优化。这里推荐一个俺看过的一本小册，这本小册让俺受益匪浅，就是阿里巴巴修言的《前端性能优化与原理实践》（PS：没广告费，是俺觉得好，才真心推荐给你们滴~）。

其次面试的时候，面试官对于前端页面的优化只在口头聊聊，作为面试官考察你的性能优化能力只能在手写算法方面了。要想对算法进行各个方面的优化，首先你需知道各个数据结构的优缺点以及对算法时间和空间效率的分析。

能够具备优化性能的能力，是每一个前端工程师日常中不可忽略的能力。



#### 5、是否有快速学习能力

世界在发展，技术在变更。适者生存，不适者淘汰。能否有快速学习的能力直接决定着你个人生存与淘汰。前端技术迭代更新飞速，从 ES5 到 ES6、ES7、ES8、ES9、ES10，再到 webpack 1.0、2.0、3.0、4.0 ... 

如果作为一个前端人员，只有具备良好的学习能力才能跟得上技术的迭代更新。通常面试中，面试官考察你的快速学习能力会问你平常怎么进行学习的？看书还是视频，还是开源社区？之所以很多的面试官反感培训机构出来的程序员，这个短期的培训，自主的学习能力是培养不出来的，而且培训机构目标是速成。但是，不能完全否定的，即便培训机构出的自学能力并不差，但是公司为了降低筛选优秀程序员成本，自然而且会非培训中筛选。

你会的编程语言多不代表学习能力就强。作为一个前端工程，如果你认为日常开发主要与 JS 打交道，包括以后的个人的技术发展，那就是大错特错了。编程语言无界限，学习各个编程语言设计的优点，才是我们学习的精髓所在。

著有牛B轰轰《Thinking in C++》和《Thinking in Java》的世界级别编程界的大牛 `Bruce Eckel `说过。

**“除非你准备活到老学到老，不然的话，不要进入这个行业！编程看起来似乎是一个高收入而又稳定的工作。但要做到这一点，唯一的途径是：始终让自己更有价值。你学得越深入，你就越有价值，也就意味着你有更好的职业前景，可以配得上更高的薪水”**。

俺要说的是，怎么始终让自己有价值？那就是具备快速学习的能力才能使这个高薪的行业里始终有价值。



#### 6、是否有人际沟通能力

给公司做项目和自己在学校折腾项目不一样，公司应聘你就是为了能够给公司产生利益。技术扎实是能够进入一家企业的必要条件而不能作为充分条件，除此之外还要求你具备其他的能力，如人际沟通能力，要说这个能力有过重要？就拿俺自身的例子来说吧，之前给一家企业做一个外包项目，就是因为前期沟通的过程中，理解错了客户的需求，导致后续所做的开发、测试、上线都是白做。

在公司也一样，一个项目团队没有沟通好，就开始下手写代码，造成一个公司损失，如果你是公司的领导，还会招聘沟通能力差的人吗？

那怎么提升自己的人际沟通能力？每个人的沟通能力都不一样，其实俺没有一个通用的方法，俺都是通过犯错，踩坑，反思进行提高的，如果你有更好的方式，欢迎来撩~



#### 7、是否具备强大的综合能力

本来是主要强调前六条，最一条综合能力是俺后期补充上的，俺认为和前六条同样的重要。俺不认为程序员和一个机器一样只会写代码，而是每一个程序员除了会写代码，而且要具备一些管理能力、领导能力、谈判的能力等等。有句话说的好，叫**“技多不压身**”，也就是一个人的综合能力要强，综合能力同样能提升你的个人核心竞争力。

很多人在谈程序员 35 岁危机，俺的观点和这个恰恰相反，35 岁应该是一个程序员最“光辉”的阶段，凭着程序员前期的学习能力，完全可以轻松掌握多个领域的知识，到了 35 岁虽然代码写不动了，你可以转你所感兴趣的领域，而这种领域的学习是你前期不断学习建立起来的。

举个常见的例子哈，据俺了解，很多公司为了让一些写不动代码的老员工开始往管理岗位转，但是出现一个问题就是，老板都推着你往管理岗位转，但是此时很多老员工并不具备管理的能力，因为他更习惯于用技术思考问题，以及强打不动的固执，不愿学习技术以外的知识，导致了肉都到了嘴边也吃不到的感觉。



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>一开头俺就写了这么大的些，有些唠唠叨叨，但是俺认为这些唠唠叨叨的零碎内容也是构成这一系列的内容，就像炒菜，少一个配料，这菜就不香了。文章也是一样，少了这些就突然它不香了。之所以写成免费系列分享，就是为了不让俺自己在写作上受到一些条件限制，该写的一样不能少。我们开始进入下一个环节~</p>
</blockquote>



## ✏️面试前如何做准备？

### 一、简历准备

简历是应聘者第一印象的展现，可以说我们见到一个陌生，首先看的是颜值（知道当年马云爸爸为什么每次应聘都失败了吧）。虽然一份简历并不能代表你的全部，但是作为给面试官的第一印象，很有必要好好斟酌的设计一下（重点在于内容部分），下面分享一下俺的经验。



#### 简历形式 

一份让 HR 看了能够眼前一亮的简历的前提是**舒服、放松**，毕竟每天 HR 看上百上千份简历，如果你的简历能够让  HR 翻到你的简历的时候，让她瞬间感觉你的简历无论是排版还是内容，与其他简历形成强烈的对比，那么大大增加了你下一步与面试官的机会。按个人认为，简历遵循一下几点，在形式上可以打败 50% 的应聘者了。

- **非统一简历**
- **简约大气简历**
- **真实简历**
- **PDF 版本**



##### 非统一简历

很过的招聘网站都提供同一的简历模板（Boos 直聘、拉勾招聘、实习僧等），正式因为简历形式的统一性，体现不出你简历让 HR 眼前一“亮”的感觉，没有对比是没有伤害的。通过实际的投递，也感觉出来了。俺之前在几个平台投了几百份简历，每次投递的时候都让你选择在线版还是附件简历，每次俺都提交错（在线版），往往根本没有几个 HR 来搭理你。后来俺发现了这个问题（一直投递的是在线简历），然后换成了自制的附件简历，果然找你沟通的 HR 也多了。



##### 简约大气

很多小伙伴相信喜欢在简历网站下载一些模板，有些模板挺简约的，但是有的小伙伴确弄得简历样式花里胡哨，虽然在美学角度感觉起来设计的很不错。我们仔细想想，我们去展现的是自己的能力和技术，而不是在简历样式的设计上花里胡哨，有点说不过去了。简约、大气，给 HR 的印象让她关联到你也是属于这种类型的，属于简单、大气风格。



##### 真实简历

简历写的内容一定真实，这个就不用俺多的强调了吧，毕竟“撒谎的孩子不是好孩子”。



##### PDF 版本

如果不是特别需要，使用 word 写简历就 OK，然后转化为 PDF 版本。对于为什么是 PDF 版本而不是其他版本，主要是因为 PDF 兼容性好，谁也不知道 HR 将会用什么软件打开你的简历，无论什么版本，你能保证你的简历在 HR 看的时候排版完好无损就行了。下面是俺之前简易版简历模板：（**获取方式，公众号回复：「简历模板」**）

![](https://github.com/luxiangqiang/Web-interview/blob/master/images/简历模板.png)



#### 简历详情



##### 简历页数

简历的页数尽量控制在 1 ~ 2 页之间。



##### 个人闪光点

如果每个人的简历都是差不多相同的，怎么才能让 HR 和面试官眼前一亮呢？那就是个人的闪光点，也就是要突出你的核心竞争力在哪？说白了，同样是应聘者，你具备什么大多数人不具备的能力能够让面试官给你发 offer 呢？很多人说，平常在学校最多参加个比赛做个小项目之类的，没有什么可以拿的出手的东西。那好，俺举例两点，给你作为一个参考，因为这两点在俺之前学习中观察身边的人以及在企业实习得出来的。



**1) 快速定位问题、解决问题的能力**

一般毕业生大部分缺少项目经验，从而定位问题和解决问题的能力相对于较弱的。如果你在校或者平常自己做项目，多善于总结的话，相信你定位问题和解决问题的能力一定比大部分人强。那么在招聘中，你可以通过项目突出这一闪光点。

而且大多数的应届毕业生刚实习的时候，一般遇到项目问题很难在短时间内搞定（分不同难度的问题），除了和他人请教之外，只能自己硬着头皮解决。一旦你有定位问题和快速解决问题的能力，那么在项目中会节省很多的时间去干别的事情。



**2) 规范编写代码的习惯**

很多自学者以及在校生，写代码就如流水账（俺也是），几乎没有什么好的编码习惯，来了需求就直接往上怼代码，导致项目后期扩展功能带来了不必要的麻烦和更多的 bug。现在的企业面临的难题就是软件的维护成本远远大于软件的开发成本，而且需求是客户一点点往上增加的，使得测试变的越来越困难。一个好的编码习惯，会在项目中大大减少不必要的开发和维护时间，从而使企业减少成本。对于如何规范写代码的习惯问题，还是要从小事做起~



##### 谨慎熟悉、精通关键字

谨慎熟悉、精通、了解认识这几个简历中常用的关键词。很多人在面试中由于这几个关键字，吃了大亏，对，也包括俺自个。俺主要针对这几个关键字进行解释一下，分别对应自己知识技能如何填写。

- **精通：精通一词，不能轻易去写，写了就是给自己挖坑。**

  那为什么还会有人去踩这个坑呢？不是说高人没有，是高人太少，之所有另外很多人写精通一词，是站在自己的认知角度去看待该领域，认为自己已经掌握了大部分的内容，但是，在面试官看来只不过是冰山一角。

- **熟悉：简历中的大部分内容可以写熟悉某某技术项。**

  我们在学校参加过比赛的项目或者自己做的一些项目，遇到的问题都是自己独立解决的，可以在简历中写“熟悉”某某技术。

- **了解和认识：如果你只是知道和了解一些技术，看多一些文章或者书籍，并没有亲自实践过项目。**

  简历中“了解和认识”这方面的内容少写，因为这代表你知道一些理论和表面上的知识。比如：了解 Node、TypeScript等。



##### 项目经历

项目经历可谓是面试中的一大重点，一个有着丰富的项目经历和一个项目经历没有的应聘者就是天差地别（天才除外）。但是往往有些毕业生没有项目经历，那这地方要空白吗？没有项目经历那就赶快去经历经历，去哪经历？俺推荐几种方式。



##### 如何找项目？

- **Github 开源项目**

  如果你想不但要有项目经历，而且希望项目高逼格，那么 Github 是首选。比如你要做一个 Vue 的项目，可以直接搜索 Vue，下方会搜索出来一些 Vue 相关的开源项目了，每个项目都会有详细说明。

  ![](https://github.com/luxiangqiang/Web-interview/blob/master/images/搜索vue.png)

  ![](https://github.com/luxiangqiang/Web-interview/blob/master/images/搜索项目.png)

- **免费资料**

  如果你想看视频，世面上很多免费的视频资源（声明：拒绝盗版），比如很多公众号、开源社区等都可以获取到。实在找不到可以去俺公众号获取。搜索公众号「**小鹿动画学编程**」后台回复 “**资源**” 即可。



- **付费视频**

  如果一些免费的资源满足不了你，而且你不差钱，那么为了减少筛选的成本，可以去一些网站买一些付费类的课程看，俺前期的自学中也会买一些，毕竟时间很珍贵~



##### 项目描述

项目描述也是挺头疼的一件事，不知道从和说去，一有可能紧张导致思维逻辑有点乱了。看了网上都推荐 STAR 模型，那俺就拿来聊一聊。MBA智库百科介绍如下：

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>所谓STAR原则，即Situation（情景）、Task（任务）、Action（行动）和 Result（结果）四个英文单词的首字母组合。STAR原则是结构化面试当中非常重要的一个理论。</p>
</blockquote>



面试官让你描述一个项目，可以在一下几个方面描述：

- **Situation(情景) —— 项目的背景**

  开头可以给面试官简单的简述一下项目的开发背景，比如开发规模、开发需求、开发环境等。

- **Task(任务)：—— 分配给你的任务**

  这种重点，向面试官详细说明你在该项目中的任务，负责了哪一块。如果没有负责的地方就不要说了，因为面试官进一步对你做的地方详细的询问。

- **Action(行动)：—— 你做了哪些事情**

  这一部分是讲述如何完成分配给自己的任务的。比如你做了一个功能的页面，这个页面你是如何进行设计的？再比如，你做了数据库部分，你是如何设计数据库表的？

- **Result(结果)：—— 你在项目中的贡献**

  对于结果，可以详细说明一下，这里有个小技巧，什么时候用百分数什么时候用数字都是有讲究的。你说通过对页面的性能优化，首屏渲染提高了 20% 的速度。再比如，你在项目中解决了 8 个主要功能的 bug 等。

​	

##### 项目闪光点

对于以上的项目不能是流水账，应该突出你的个人核心竞争力，你在项目中解决了别人不能解决的问题，你做了哪些核心功能点，遇到难题又是如何进行解决的，都可以作为个人的闪光点。俺整理了一下几个方面，也欢迎文章下方留言补充哦~

- **项目遇到的问题是如何解决的？**
- **从项目中学到了什么？**
- **和团队成员有什么冲突？如何解决的？**



#### 小技巧

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>分享几个简历中的小技巧（欢迎留言补充哦~）。</p>
</blockquote>

- **学校名称排版位置**

如果你是某 985、211 的，学校的名字以及可以写在简历的开头，这样 HR 在筛选简历的时候，一眼看到你的学校名称（这个大家都知道，毕竟没有这么高的学历）。

如果你的学校和俺一样是野鸡大学，或者二本、三本之类的，可以将学校名称放在稍微靠后的位置，HR 第一眼会看到你的不是学校，而是你突出的能力。这样就会避免学校带来的缺陷（不能完全避免）。

- **最佳闪光点位置**

简历中最显眼的地方应该写你的个人核心竞争力的内容，因为这样会让 HR 眼前一亮（一般在简历的中上位置）。而那些无关紧要，作为补充性的内容可以不写或者写在偏靠下的位置。



#### 大忌

- **切记不懂装懂；**
- **切记胡编乱造；**
- **切记夸大自己来展示自己能力；**
- **切记列举一堆技能；**



### 二、了解公司

面试前的简历我们写好了，但是收到面试通知之后，很多小伙伴收到面试邀请之后难免有些紧张，尤其是对于第一次准备面试的小伙伴来说。造成这种现象的原因无非就是心里没底，总是想面试的时候出现 “如果...怎么办....” 的状况或者是前期面试没有准备好，难免会担心面试出现各种紧急状况。

对于面试前的焦虑和紧张，也不是完全没有办法。在面试前。我们以先去了解这个公司，俺总结了一下几个方面。

- **面试内容**
- **主要业务**
- **发展前景**



#### 1、面试内容

有小伙伴要问俺了，一个公司的面试流程和内容可以知道吗？如果你非要这么问俺的话，俺的回答只能说是【间接的】。什么是间接？一般有很多网站可以查询该公司的相关信息，（比如：看准网），部分下面有些之前面试者面试后的感受以及对公司的评价之类的，那么所谓的间接，就是通过一些信息筛选出对你有用的信息。比如：

“面试官很 nice，整个面试面试官会照顾到面试者的感受.... “，再比如，

“当面试官问到原型链的时候，回答的有点含糊”

...

提取关键信息，首先面试官的态度很好的，所以你去这家公司面试不用很紧张；第二，这个面试者在这家公司面试的时候，被问到有关原型链的知识，如果换做我，是否能够准确的回答上来呢？

那么又有小伙伴问了，如果在这种网站查询不到相关的面试信息嗯？俺给你介绍另一个法子，那就是去搜索个人博客，现在很多的人喜欢记录自己的面试经历，直接百度或者谷歌也是 Ok 的。

虽然这个法子不是百分之百的能够帮助你，但是在面试前的准备上让你能够放松了些，因为你也该公司的面试流程或者内容有了大体的了解。



#### 2、主要业务产品

> 主要业务。最起码知道你来这个公司做什么产品和主要干什么吧？

除了我们去了解该公司的面试流程和内容，还要去了解该公司的主要业务产品。公司招聘是双方互相选择的一个过程，而不是公司单方向选择你。那么问题来了，你这还没去面试呢。就需要提前了解该公司主要业务产品是干嘛的吗？当然，如果你不喜欢该公司的业务产，何必选择去面试呢？（单纯的体验一下面试的人除外~）

很多公司会在相关的网站列出自己公司的主要业务以及产品是干嘛的，难免也有与实际不否的地方，可以进一步提前准备好，在面试快结束的时候，来咨询一下面试官，公司的相关业务产品。



#### 3、发展前景

> 再一个就是了解该公司的发展前景，和你个人的爱好以及个人价值是否一致呢。

互联网公司覆盖的领域很广，医疗领域、教育领域、娱乐领域、游戏领域等等。俺把其公司作为两种分类，一类是产品公司，这一类主要是针对特定的用户进行开发产品的，比如某公司主要对于医院来开发医疗系统。另一类呢是互联网公司。主要是面向大众化的产品，比如抖音、今日头条、微信等。当然，不同类型的公司对应的开发也是不一样的，俺就不在这展开说了。



## JavaScript 基础知识点

### 数据类型

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：说说 JavaScript 中的基本类型有哪些？以及各个数据类型是如何存储的？</p>
</blockquote>

<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">javaScript</code> 的数据类型包括<span style="color:#ff502c;font-weight:bold;padding:0 2px">原始类型</span>和<span style="color:#ff502c;font-weight:bold;padding:0 2px">引用类型(对象类型)</span>。

原始类型包括以下 6 个：

- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">String</code>
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Number</code>
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Boolean</code>
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">null</code>
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">undefined</code>
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Symbol</code>



引用类型统称为 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Object</code> 类型，如果细分的话，分为以下 5 个：

- `Object`
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Array</code>
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Date</code>
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">RegExp</code>
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Function</code>



#### 1、数据类型的存储形式

> 栈（Stack）和堆（Heap），是两种基本的数据结构。Stack 在内存中自动分配内存空间的；Heap 在内存中动态分配内存空间的，不一定会自动释放。一般我们在项目中将对象类型手动置为 null 原因，减少无用内存消耗。

​	

![堆和栈内存](H:\编程笔记\前端面试整理\images\堆和栈内存.png)

原始类型是按值形式存放在**栈**中的数据段，内存空间可以自由分配，同时可以**按值直接访问**。

```javascript
var a = 10;
var b = a;
b = 30;
console.log(a); // 10值
console.log(b); // 30值

```

过程图示：

![栈变量复制](H:\编程笔记\前端面试整理\images\栈变量复制.png)

引用类型是存放在**堆**内存中，每个对象在堆内存中有一个引用地址，就像是每个房间都有一个房间号一样。引用类型在栈中保存的就是这个对象在堆内存的引用地址，我们所说的“房间号”。通过“房间号”可以快速查找到保存在堆内存的对象。

```javascript
var obj1 = new Object();
var obj2 = obj1;
obj2.name = "小鹿";
console.log(obj1.name); // 小鹿
```

过程图示：

![对象复制](H:\编程笔记\前端面试整理\images\对象复制.png)



#### 2、Null

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：为什么 typeof null 等于 Object?</p>
</blockquote>

不同的对象在底层原理的存储是用二进制表示的，在 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">javaScript</code>中，如果二进制的前三位都为 0 的话，系统会判定为是 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Object</code>类型。<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">null</code>的存储二进制是 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">000</code>，也是前三位，所以系统判定 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">null</code>为 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Object</code>类型。

**扩展：**

这个 bug 个第一版的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">javaScript</code>留下来的。俺也进行扩展一下其他的几个类型标志位：

- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">000</code>：对象类型。
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">1</code>：整型，数据是31位带符号整数。
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">010</code>：双精度类型，数据是双精度数字。
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">100</code>：字符串，数据是字符串。
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">110</code>：布尔类型，数据是布尔值。



#### 3、数据类型的判断

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：typeof 与 instanceof 有什么区别？</p>
</blockquote>

<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">typeof</code> 是一元运算符，同样返回一个字符串类型。一般用来判断一个变量是否为空或者是什么类型。

除了 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">null</code> 类型以及  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Object</code> 类型不能准确判断外，其他数据类型都可能返回正确的类型。

```javascript
typeof undefined // 'undefined'
typeof '10'      // 'String'
typeof 10        // 'Number'
typeof false     // 'Boolean'
typeof Symbol()  // 'Symbol'
typeof Function  // ‘function'
typeof null		 // ‘Object’
typeof []        // 'Object'
typeof {}        // 'Object'
```

既然 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">typeof</code> 对对象类型都返回 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Object</code> 类型情况的局限性，我们可以使用 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">instanceof</code> 来进行判断**某个对象是不是另一个对象的实例**。返回值的是一个布尔类型。

```javascript
var a = [];
console.log(a instanceof Array) // true
```

<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">instanceof</code>  运算符用来测试一个对象在其原型链中是否存在一个构造函数的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">prototype</code> 属性，如果对原型链不怎能了解，后边俺会具体的写到，这里大体记一下就 OK。

我们再测一下 ES6 中的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">class</code> 语法糖是什么类型。

```javascript
class A{}
console.log(A instanceof Function) // true
```

> 注意：原型链中的<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">prototype</code> 随时可以被改动的，改变后的值可能不存在于 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">object</code>的原型链上，<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">instanceof</code>返回的值可能就返回 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">false</code>。



#### 4、类型转换

类型转换通常在面试笔试中出现的比较多，对于类型转换的一些细节应聘者也是很容易忽略的，所以俺整理的尽量系统一些。<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">javaScript</code>是一种弱类型语言，变量不受类型限制，所以在特定情况下我们需要对类型进行转换。

「类型转换」分为<span style="color:#ff502c;font-weight:bold;padding:0 2px">显式类型转换</span>和<span style="color:#ff502c;font-weight:bold;padding:0 2px">隐式类型转换</span>。每种转换又分为<span style="color:#ff502c;font-weight:bold;padding:0 2px">原始类型转换</span>和<span style="color:#ff502c;font-weight:bold;padding:0 2px">对象类型转换</span>。



##### 显式类型转换

显式类型转换就是我们所说强制类型转换。

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>笔试题：其他数据类型转字符串类型！</p>
</blockquote>

对于原始类型来说，转字符串类型会默认调用 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">toString()</code> 方法。

| 数据类型  | String类型               |
| :-------- | :----------------------- |
| 数字      | 转化为数字对应的字符串   |
| true      | 转化为字符串 "true"      |
| null      | 转化为字符串 "null"      |
| undefined | 转化为字符串 “undefined” |
| Object    | 转化为 "[object Object]" |

```javascript
String(123);      // "123"
String(true);     // "true"
String(null);     // "null"
String(undefined);// "undefined"
String([1,2,3])   // "1,2,3"
String({});		  // "[object Object]"
```



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>笔试题：其他数据类型转布尔类型！</p>
</blockquote>

除了特殊的几个值 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">‘’</code>、 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">undefined</code>、 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">NAN</code>、 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">null</code>、 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">false</code>、 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">0</code>  转化为 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Boolean</code> 为 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">false</code> 之外，其他类型值都转化为 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">true</code>。

```javascript
Boolean('')         // false
Boolean(undefined)  // false
Boolean(null)       // false
Boolean(NaN)        // false
Boolean(false)      // false
Boolean(0)          // false
Boolean({})		    // true
Boolean([])		    // true
```



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
        <p>笔试题：转化为数字类型！</p>
</blockquote>

| 数据类型  | 数字类型                                                     |
| :-------- | :----------------------------------------------------------- |
| 字符串    | 1) 数字转化为对应的数字<br />2) 其他转化为 NaN               |
| 布尔类型  | 1) true 转化为 1<br />2) false 转化为 0                      |
| null      | 0                                                            |
| undefined | NaN                                                          |
| 数组      | 1) 数组为空转化为 0；<br />2) 数组只有一个元素转化为对应元素；<br />3) 其他转化为NaN |
| 空字符串  | 0                                                            |

```javascript
Number(10);        // 10 
Number('10');      // 10 
Number(null);      // 0  
Number('');        // 0  
Number(true);      // 1  
Number(false);     // 0  
Number([]);        // 0 
Number([1,2]);     // NaN
Number('10a');     // NaN
Number(undefined); // NaN
```



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>笔试题：对象类型转原始类型！</p>
</blockquote>

对象类型在转原始类型的时候，会调用内置的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">valueOf()</code>和 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">toString()</code> 方法，这两个方法是可以进行重写的。

转化原始类型分为两种情况：转化为<span style="color:#ff502c;font-weight:bold;padding:0 2px">字符串类型</span>或<span style="color:#ff502c;font-weight:bold;padding:0 2px">其他原始类型</span>。

- 如果已经是原始类型，不需要再进行转化。
- 如果转字符串类型，就调用内置函数中的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">toString()</code>方法。
- 如果是其他基本类型，则调用内置函数中的  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">valueOf()</code>方法。
- 如果返回的不是原始类型，则会继续调用 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">toString()</code> 方法。
- 如果还没有返回原始类型，则报错。



#### 5、四则运算

隐士类型转化是不需要认为的强制类型转化，<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">javaScript</code> 自动将类型转化为需要的类型，所以称之为隐式类型转换。



##### 加法运算

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>加法运算符是在运行时决定，到底是执行相加，还是执行连接。运算数的不同，导致了不同的语法行为，这种现象称为“重载”。</p>
</blockquote>

- 如果双方都不是字符串，则将转化为**数字**或**字符串**。
  - <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Boolean + Boolean</code>会转化为数字相加。
  - <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Boolean + Number</code> 布尔类型转化为数字相加。
  - <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Object + Number</code> 对象类型调用 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">valueOf</code>，如果不是 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">String、Boolean</code>或者 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Number</code>类型，则继续调用 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">toString()</code>转化为字符串。

```javascript
true + true  // 2
1 + true     // 2
[1] + 3      // '13'
```

- 字符串和字符串以及字符串和非字符串相加都会进行**连接**。

```javascript
1 + 'b'     // ‘1b’
false + 'b' // ‘falseb’
```



##### 其他运算

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>其他算术运算符（比如减法、除法和乘法）都不会发生重载。它们的规则是：所有运算子一律转为数值，再进行相应的数学运算。</p>
</blockquote>

```javascript
1 * '2'  // 2
1 * []   // 0
```



#### 6、逻辑运算符

逻辑运算符包括两种情况，分别为<span style="color:#ff502c;font-weight:bold;padding:0 2px">条件判断</span>和<span style="color:#ff502c;font-weight:bold;padding:0 2px">赋值操作</span>。

**条件判断**

- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">&&</code> ：所有条件为真，整体才为真。
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">||</code> ：只有一个条件为真，整体就为真。

```javascript
true && true   // true
true && false  // false
true || true   // true
true || false  // true
```



**赋值操作**

- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A && B</code>

首先看 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A</code> 的真假， <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A</code> 为假，返回  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A</code> 的值， <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A</code>  为真返回  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">B</code>  的值。（不管 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">B</code> 是啥）

```javascript
console.log(0 && 1) // 0
console.log(1 && 2) // 2
```

- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A || B</code>

首先看  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A</code>  的真假， <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A</code> 为真返回的是  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A</code>  的值， <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">A</code>  为假返回的是  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">B</code>  的值（不管 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">B</code>  是啥）

```javascript
console.log(0 || 1) // 1
console.log(1 || 2) // 1
```



#### 7、比较运算符

比较运算符在逻辑语句中使用，以判定变量或值是否相等。

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：== 和 === 的区别？</p>
</blockquote>

对于 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">===</code> 来说，是严格意义上的相等，会比较两个操作符的类型和值。

- 如果 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">X</code> 和  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Y</code> 的类型不同，返回  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">false</code> ；
- 如果 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">X</code> 和  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Y</code> 的类型相同，则根据下方表格进一步判断

| 条件                                                         | 例子                                                         | 返回值                               |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------ |
| undefined === undefined                                      | undefined === undefined                                      | true                                 |
| null === null                                                | null === null                                                | true                                 |
| String === String<br />(当字符串顺序和字符完全相等的时候返回 true，否则返回 false) | ‘a’ === 'a'<br />'a' === 'aa'                                | true<br />false                      |
| Boolean  === Boolean                                         | true === true<br />true === false                            | true<br />false                      |
| Symbol === Symbol                                            | 相同的 Symbol 返回 true，<br />不相同的 Symbol 返回 false    |                                      |
| Number  === Number<br />① 其中一个为 NaN，返回 false<br />② X 和 Y 值相等，返回 true<br />③ 0 和 -0，返回 true<br />④ 其他返回 false | NaN ==== NaN<br />NaN === 1<br />3 === 3<br />+0 === -0<br /> | false<br />false<br />true<br />true |



而对于 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">==</code>来说，是非严格意义上的相等，先判断两个操作符的类型是否相等，如果类型不同，则先进行类型转换，然后再判断值是否相等。

- 如果 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">X</code> 和  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Y</code> 的类型相同，返回  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">X == Y</code>  的比较结果；
- 如果  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">X</code> 和 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">Y</code> 的类型不同，根据下方表格进一步判断;

| 条件                                                         | 例子                     | 返回值         |
| ------------------------------------------------------------ | ------------------------ | -------------- |
| null == undefined                                            | null == undefined        | true           |
| String == Number，String  转 Number                          | '2' == 2                 | true           |
| Boolean == Number，Boolean 转 Number                         | true == 1                | true           |
| Object == String,Number,Symbol，将 Object 转化为原始类型再比较值大小 | [1] == 1<br />[1] == '1' | true<br />true |
| 其他返回 false                                               |                          | false          |



### this

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：什么是 this 指针?以及各种情况下的 this 指向问题。</p>
</blockquote>

<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>就是一个对象。不同情况下 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>指向的不同，有以下几种情况，（希望各位亲自测试一下，这样会更容易弄懂）：

- 对象调用，<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code> 指向该对象（前边谁调用 this 就指向谁）。

```javascript
var obj = {
    name:'小鹿',
    age: '21',
    print: function(){
        console.log(this)
        console.log(this.name + ':' + this.age)
    }
}

// 通过对象的方式调用函数
obj.print();        // this 指向 obj
```



- 直接调用的函数，<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>指向的是全局 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">window</code>对象。

```javascript
function print(){
	console.log(this);
}

// 全局调用函数
print();   // this 指向 window
```



- 通过 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">new</code>的方式，<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>永远指向新创建的对象。

```javascript
function Person(name, age){
    this.name = name;
    this.age = age;
    console.log(this);
}

var xiaolu = new Person('小鹿',22);  // this = > xaiolu
```



- 箭头函数中的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>。

由于箭头函数没有单独的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>值。箭头函数的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>与声明所在的上下文相同。也就是说调用箭头函数的时候，不会隐士的调用 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>参数，而是从定义时的函数继承上下文。

```javascript
const obj = {
    a:()=>{
        console.log(this);
    }
}
// 对象调用箭头函数
obj.a(); // window
```



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：如何改变 this 的指向？</p>
</blockquote>

我们可以通过调用函数的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">call、apply、bind</code> 来改变 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>的指向。

```javascript
var obj = {
    name:'小鹿',
    age:'22',
    adress:'小鹿动画学编程'
}

function print(){
    console.log(this);       // 打印 this 的指向
    console.log(arguments);  // 打印传递的参数
}

// 通过 call 改变 this 指向
print.call(obj,1,2,3);   

// 通过 apply 改变 this 指向
print.apply(obj,[1,2,3]);

// 通过 bind 改变 this 的指向
let fn = print.bind(obj,1,2,3);
fn();
```

对于基本的使用想必各位小伙伴都能掌握，俺就不多废话，再说一说这三者的共同点和不同点。



**共同点：**

- 三者都能改变 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>指向，且第一个传递的参数都是 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>指向的对象。
- 三者都采用的后续传参的形式。



**不同点：**

- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">call</code> 的传参是单个传递的（试了下数组，也是可以的），而 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">apply</code> 后续传递的参数是**数组形式（传单个值会报错）**，而 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">bind</code> 没有规定，传递值和数组都可以。
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">call</code> 和 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">apply</code> 函数的执行是直接执行的，而 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">bind</code> 函数会返回一个函数，然后我们想要调用的时候才会执行。



> 扩展：如果我们使用上边的方法改变箭头函数的 this 指针，会发生什么情况呢？能否进行改变呢？

由于箭头函数没有自己的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code> 指针，通过 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">call()</code> 或 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">apply()</code> 方法调用一个函数时，只能传递参数（不能绑定  <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">this</code>），他们的第一个参数会被忽略。



### new

对于 `new` 关键字，我们第一想到的就是在面向对象中 `new` 一个实例对象，但是在 JS 中的 `new` 和 `Java` 中的 `new ` 的机制不一样。

一般 `Java` 中，声明一个`构造函数`，通过 `new 类名()` 来创建一个实例，而这个`构造函数` 是一种特殊的函数。但是在 `JS` 中，只要 `new` 一个函数，就可以 new 一个对象，函数和构造函数没有任何的区别。

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：new 内部发生了什么过程？可不可以手写实现一个 new 操作符？</p>
</blockquote>

`new` 的过程包括以下四个阶段：

- 创建一个新对象。
- 这个新对象的 `__proto__` 属性指向原函数的 `prototype` 属性。(即继承原函数的原型)
- 将这个新对象绑定到 此函数的 `this` 上 。
- 返回新对象，如果这个函数没有返回其他对象。

```javascript
// new 生成对象的过程
// 1、生成新对象
// 2、链接到原型
// 3、绑定 this
// 4、返回新对象
// 参数：
// 1、Con: 接收一个构造函数
// 2、args：传入构造函数的参数
function create(Con, ...args){
    // 创建空对象
    let obj = {};
    // 设置空对象的原型(链接对象的原型)
    obj._proto_ = Con.prototype;
    // 绑定 this 并执行构造函数(为对象设置属性)
    let result = Con.apply(obj,args)
    // 如果 result 没有其他选择的对象，就返回 obj 对象
    return result instanceof Object ?  result : obj;
}
// 构造函数
function Test(name, age) {
    this.name = name
    this.age = age
}
Test.prototype.sayName = function () {
    console.log(this.name)
}

// 实现一个 new 操作符
const a = create(Test,'小鹿','23')
console.log(a.age)
```

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：有几种创建对象的方式，字面量相对于 new 创建对象有哪些优势？</p>
</blockquote>

最常用的创建对象的两种方式：

- **new 构造函数  **
- **字面量**

其他创建对象的方式：

- **Object.create()**



字面量创建对象的优势所在：

- 代码量更少，更易读
- 对象字面量运行速度更快，它们可以在解析的时候被优化。他不会像 `new` 一个对象一样，解析器需要顺着作用域链从当前作用域开始查找，如果在当前作用域找到了名为 `Object()` 的函数就执行，如果没找到，就继续顺着作用域链往上照，直到找到全局 `Object()` 构造函数为止。
- `Object()` 构造函数可以接收参数，通过这个参数可以把对象实例的创建过程委托给另一个内置构造函数，并返回另外一个对象实例，而这往往不是你想要的。



对于 `Object.create() `方式创建对象：

```javascript
Object.create(proto, [propertiesObject]);
```

- `proto：`新创建对象的原型对象。
- `propertiesObject：`（可选）可为创建的新对象设置属性和值。

一般用于继承：

```javascript
var People = function (name){
  this.name = name;
};

People.prototype.sayName = function (){
  console.log(this.name);
}

function Person(name, age){
  this.age = age;
  People.call(this, name);  // 使用call，实现了People属性的继承
};

// 使用Object.create()方法，实现People原型方法的继承，并且修改了constructor指向
Person.prototype = Object.create(People.prototype, {
  constructor: {
    configurable: true,
    enumerable: true,
    value: Person,
    writable: true
  }
});

Person.prototype.sayAge = function (){
  console.log(this.age);
}

var p1 = new Person('person1', 25);
 
p1.sayName();  //'person1'
p1.sayAge();   //25
```

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：new/字面量 与 Object.create(null) 创建对象的区别？</p>
</blockquote>

- `new ` 和 字面量创建的对象的原型指向 `Object.prototype`，会继承 `Object` 的属性和方法。
- 而通过 `Object.create(null)` 创建的对象，其原型指向 `null`，`null` 作为原型链的顶端，没有也不会继承任何属性和方法。



### 闭包

闭包面试中的重点，但是对于很多初学者来说都是懵懵的，所以俺就从最基础的作用域讲起，大佬请绕过。

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：什么是作用域？什么是作用域链？</p>
</blockquote>

规定<span style="color:#ff502c;font-weight:bold;padding:0 2px">变量和函数</span>的可使用范围叫做作用域。只看定义，挺抽象的，举个例子::chestnut:

```javascript
function fn1() {
    let a = 1;
}

function fn2() {
    let b = 2;
}
```

声明两个函数，分别创建量两个私有的作用域（可以理解为两个封闭容器），<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">fn2</code> 是不能直接访问私有作用域 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">fn1</code> 的变量 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">a</code> 的。同样的，在 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">fn1</code> 中不能访问到 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">fn2</code> 中的 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">b</code> 变量的。一个函数就是一个作用域。

![私有作用域](H:\编程笔记\前端面试整理\images\闭包\私有作用域.png)

每个函数都会有一个作用域，查找变量或函数时，由局部作用域到全局作用域依次查找，<span style="color:#ff502c;font-weight:bold;padding:0 2px">这些作用域的集合就称为作用域链。</span> 如果还不是很好理解，俺再举个例子​：:chestnut:

```javascript
let a = 1
function fn() {
    function fn1() {
        function fn2() {
            let c = 3;
            console.log(a);
        }
        // 执行 fn2
        fn2();
    }
    // 执行 fn1
    fn1();
}
// 执行函数
fn();
```

虽然上边看起来嵌套有点复杂，我们前边说过，一个函数就是一个私有作用域，根据定义，在 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">fn2</code> 作用域中打印 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">a</code>，首先在自己所在作用域搜索，如果没有就向上级作用域搜索，直到搜索到全局作用域，<code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">a = 1</code>，找到了打印出值。整个搜索的过程，就是基于作用域链搜索的。

![作用域链](H:\编程笔记\前端面试整理\images\闭包\作用域链.png)



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：什么是闭包？闭包的作用？闭包的应用？</p>
</blockquote>

很多应聘者喜欢这样回答，“函数里套一个函数”，但是面试官更喜欢下面的回答，因为可以继续为你挖坑。

函数执行，形成一个私有的作用域，保护里边的私有变量不受外界的干扰，除了<span style="color:#ff502c;font-weight:bold;padding:0 2px">保护</span>私有变量外，还可以<span style="color:#ff502c;font-weight:bold;padding:0 2px">保存</span>一些内容，这样的模式叫做<span style="color:#ff502c;font-weight:bold;padding:0 2px">闭包</span>。

闭包的作用有两个，<span style="color:#ff502c;font-weight:bold;padding:0 2px">保护和保存。</span>



**保护的应用**

- 团队开发时，每个开发者把自己的代码放在一个私有的作用域中，防止相互之间的变量命名冲突；把需要提供给别人的方法，通过 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">return</code> 或 <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">window.xxx </code>的方式暴露在全局下。
- <code style="background-color: #fff5f5;color: #ff502c;font-size: .87em;padding: .065em .4em;">jQuery</code> 的源码中也是利用了这种保护机制。
- 封装私有变量。



**保存的应用**

- 选项卡闭包的解决方案。



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：循环绑定事件引发的索引什么问题？怎么解决这种问题？</p>
</blockquote>

```javascript
// 事件绑定引发的索引问题
var btnBox = document.getElementById('btnBox'),
    inputs = btnBox.getElementsByTagName('input')
var len = inputs.length;
for(var i = 0; i < 1en; i++){
    inputs[i].onclick = function () {
        alert(i)
    }
}
```

闭包剩余的部分，俺在之前的文章已经总结过，俺就不复制过来了，直接传送过去~ [动画：什么是闭包？](https://juejin.im/post/5dc6449ae51d452bd321252c#comment)



### 原型和原型链

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：什么是原型？什么是原型链？如何理解？</p>
</blockquote>

**原型：**每个 `JS` 对象都有 `__proto__` 属性，这个属性指向了原型。跟俺去看看，

![原型1](H:\编程笔记\前端面试整理\images\原型\原型1.png)

再来一个，

![原型2](H:\编程笔记\前端面试整理\images\原型\原型2.png)

我们可以看到，只要是对象类型，都会有这个`__proto__` 属性，这个属性指向的也是一个原型对象，原型对象也是对象呀，肯定也会存在一个 `__proto__` 属性。那么就形成了原型链，定义如下：

**原型链**：原型链就是多个对象通过 `__proto__` 的方式连接了起来形成一条链。



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>原型和原型链是怎么来的呢？如果理清原型链中的关系呢？</p>
</blockquote>

对于原型和原型链的前世今生，由于篇幅过大，俺的传送门~ [图解：告诉面试官什么是 JS 原型和原型链?](https://juejin.im/post/5db0fec4518825648c3a8770)

> PS：下面的看不懂，一定去看文章哦！

再往深处看，他们之间存在复杂的关系，但是这些所谓的负责关系俺已经总结好了，小二上菜

![原型图](H:\编程笔记\前端面试整理\images\原型\原型图.png)

这张图看起来真复杂，但是通过下边总结的，再来分析这张图，试试看。

- 所有的实例的 `_proto_`都指向该构造函数的原型对象（`prototype`）。
- 所有的函数（包括构造函数）是 `Function()` 的实例，所以所有函数的 `_proto_`的都指向 `Function() ` 的原型对象。
- 所有的原型对象（包括 `Function` 的原型对象）都是 `Object` 的实例，所以 `_proto_`都指向 Object （构造函数）的原型对象。而 `Object` 构造函数的 `_proto_`  指向 `null`。
- `Function` 构造函数本身就是 `Function` 的实例，所以 `_proto_` 指向 `Function` 的原型对象。



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：instanceOf 的原理是什么？</p>
</blockquote>

之前留了一个小问题，总结了上述的原型和原型链之后，`instanceof `的原理很容易理解。

`instanceof` 的原理是通过判断该对象的原型链中是否可以找到该构造类型的 `prototype` 类型。

```javascript
function Foo(){}
var f1 = new Foo();

console.log(f1 instanceof Foo);// true
```

![instanceof](H:\编程笔记\前端面试整理\images\原型\instanceof.jpg)

### 继承

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：说一说 JS 中的继承方式有哪些？以及各个继承方式的优缺点。</p>
</blockquote>



#### 经典继承（构造函数）

```javascript
/ 详细解析
//1、当用调用 call 方法时，this 带边 son 。
//2、此时 Father 构造函数中的 this 指向 son。
//3、也就是说 son 有了 colors 的属性。
//4、每 new 一个 son ，都会产生不同的对象，每个对象的属性都是相互独立的。
function Father(){
	this.colors = ["red","blue","green"];
}

function Son(){
    // this 是通过 new 操作内部的新对象 {} ，
    // 此时 Father 中的 this 就是为 Son 中的新对象{}
    // 新对象就有了新的属性，并返回得到 new 的新对象实例
    // 继承了Father,且向父类型传递参数
	Father.call(this);
}

let s = new Son();
console.log(s.color)
```

**① 基本思想：**在子类的构造函数的内部调用父类的构造函数。

**② 优点：**

- 保证了原型链中引用类型的独立，不被所有实例共享。
- 子类创建的时候可以向父类进行传参。

**③ 缺点:**

- 继承的方法都在构造函数中定义，构造函数不能够复用了（因为构造函数中存在子类的特殊属性，所以构造函数中复用的属性不能复用了）。
- 父类中定义的方法对于子类型而言是不可见的（子类所有的属性都定义在父类的构造函数当中）。



#### 组合继承

```javascript
function Father(name){
	this.name = name;
	this.colors = ["red","blue","green"];
}

// 方法定义在原型对象上（共享）
Father.prototype.sayName = function(){
	alert(this.name);
};

function Son(name,age){
    // 子类继承父类的属性  
	Father.call(this,name);     //继承实例属性，第一次调用 Father()
    // 每个实例都有自己的属性
	this.age = age;
}

// 子类和父类共享的方法（实现了父类属性和方法的复用）                              
Son.prototype = new Father();   //继承父类方法,第二次调用 Father()

// 子类实例对象共享的方法
Son.prototype.sayAge = function(){
	alert(this.age);
}

var instance1 = new Son("louis",5);
instance1.colors.push("black");
console.log(instance1.colors);//"red,blue,green,black"
instance1.sayName();//louis
instance1.sayAge();//5

var instance1 = new Son("zhai",10);
console.log(instance1.colors);//"red,blue,green"
instance1.sayName();//zhai
instance1.sayAge();//10
```

**① 基本思想：**

- 使用**原型链**实现对**「原型对象属性和方法」**的继承。
- 通过借用**构造函数**来实现对**「实例属性」**的继承。

**② 优点：**

- 在原型对象上定义的方法实现了函数的复用。
- 每个实例都有属于自己的属性。

**③ 缺点：**

- 组合继承调用了两次父类的构造函数，造成了不必要的消耗。



#### 原型继承

```javascript
function object(o){
	function F(){}
	F.prototype = o;
    // 每次返回的 new 是不同的
	return new F();
}

var person = {
	friends : ["Van","Louis","Nick"]
};

// 实例 1
var anotherPerson = object(person);
anotherPerson.friends.push("Rob");

// 实例 2
var yetAnotherPerson = object(person);
yetAnotherPerson.friends.push("Style");

// 都添加至原型对象的属性(所共享)
alert(person.friends); // "Van,Louis,Nick,Rob,Style"
```

**① 基本思想：**创建临时性的构造函数（无任何属性），将传入的对象作为该构造函数的原型对象，然后返回这个新构造函数的实例。

**② 浅拷贝：**

> `object` 所产生的对象是不相同的，但是原型对象都是 `person` 对象，所改变存在原型对象的属性所有生成的实例所共享，不仅被 `Person` 所拥有，而且被子类生成的实例所共享。

③ **object.create()：**在 ECMAScript5 中,通过新增 **object.create()** 方法规范化了上面的原型式继承.。

- 参数一：新对象的原型的对象。
- 参数二：先对象定义额外的属性（可选）。



#### 寄生式继承

```javascript
function createAnother(original){
	var clone = object(original); // 通过调用object函数创建一个新对象
	clone.sayHi = function(){ // 以某种方式来增强这个对象
		alert("hi");
	};
	return clone; //返回这个对象
}
```

- **基本思想**：不必为了指定子类型的原型而调用超类型的构造函数（避免第二次调用的构造函数）。
- **优点**：寄生组合式继承就是为了解决组合继承中两次调用构造函数的开销。



### 垃圾回收机制

说到 `Javascript`的垃圾回收机制，我们要从内存泄漏一步步说起。

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：什么是内存泄漏？为什么会导致内存泄漏？</p>
</blockquote>

<span style="color:#ff502c;font-weight:bold;padding:0 2px">不再用到的内存，没有及时释放，就叫做内存泄漏。</span>

**内存泄漏是指我们已经无法再通过js代码来引用到某个对象，但垃圾回收器却认为这个对象还在被引用，因此在回收的时候不会释放它**。导致了分配的这块内存永远也无法被释放出来。如果这样的情况越来越多，会导致内存不够用而系统崩溃。



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：怎么解决内存泄漏？说一说 JS 垃圾回收机制的运行机制的原理？。</p>
</blockquote>

很多编程语言需要手动释放内存，但是很多开发者喜欢系统提供自动内存管理，减轻程序员的负担，这被称为<span style="color:#ff502c;font-weight:bold;padding:0 2px">"垃圾回收机制"</span>。

之所以会有垃圾回收机制，是因为 `js` 中的字符串、对象、数组等只有确定固定大小时，才会动态分配内存，只要像这样动态地分配了内存，最终都要释放这些内存以便他们能够被再用，否则，`JavaScript` 的解释器将会消耗完系统中所有可用的内存，造成系统崩溃

`JavaScript `与其他语言不同，它具有自动垃圾收集机制，执行环境会负责管理代码执行过程中使用的内存。



#### 两种垃圾回收策略

找出那些不再继续使用的变量，然后释放其内存。垃圾回收器会按照固定的时间间隔，周期性的执行该垃圾回收操作。

共有两种策略：

- **标记清除法**
- **引用计数法**



#### 标记清除法

垃圾回收器会在运行的时候，会给存储在内存中的所有变量都加上标记，然后它会去掉环境中变量以及被环境中的变量引用的变量的标记。剩下的就视为即将要删除的变量，原因是在环境中无法访问到这些变量了。最后垃圾回收器完成内存清除操作。

<span style="color:#ff502c;font-weight:bold;padding:0 2px">它的实现原理就是通过判断一个变量是否在执行环境中被引用，来进行标记删除。</span>



#### 引用计数法

引用计数的垃圾收集策略不常用，引用计数的最基本含义就是跟踪记录每个值被引用的次数。

当声明变量并将一个引用类型的值赋值给该变量时，则这个值的引用次数加 1，同一值被赋予另一个变量，该值的引用计数加 1 。当引用该值的变量被另一个值所取代，则引用计数减 1，当计数为 0 的时候，说明无法在访问这个值了，所有系统将会收回该值所占用的内存空间。

<span style="color:#ff502c;font-weight:bold;padding:0 2px">存在的缺陷：</span>

两个对象的相互循环引用，在函数执行完成的时候，两个对象相互的引用计数并未归 0 ，而是依然占据内存，无法回收，当该函数执行多次时，内存占用就会变多，导致大量的内存得不到回收。

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>最常见的就是在 IE BOM 和 DOM 中，使用的对象并不是 js 对象，所以垃圾回收是基于计数策略的。但是在 IE9 已经将 BOM 和 DOM 真正的转化为了 js 对象，所以循环引用的问题得到解决。</p>
</blockquote>



#### 如何管理内存

虽然说是 `js` 的内存都是自动管理的，但是对于 `js`  还是存在一些问题的，最主要的一个问题就是**分配给 Web 浏览器的可用内存数量通常比分配给桌面应用程序的少**。

> 为了能够让页面获得最好的性能，必须确保 js 变量占用最少的内存，最好的方式就是将不用的变量引用释放掉，也叫做**解除引用**。

- 对于局部变量来说，函数执行完成离开环境变量，变量将自动解除。
- 对于全局变量我们需要进行手动解除。（注意：解除引用并不意味被收回，而是将变量真正的脱离执行环境，下一次垃圾回收将其收回）

```javascript
var a = 20;  // 在堆内存中给数值变量分配空间
alert(a + 100);  // 使用内存
var a = null; // 使用完毕之后，释放内存空间
```

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>补充：因为通过上边的垃圾回收机制的标记清除法的原理得知，只有与环境变量失去引用的变量才会被标记回收，所用上述例子通过将对象的引用设置为 null ，此变量也就失去了引用，等待被垃圾回收器回收。</p>
</blockquote>



### 深拷贝和浅拷贝

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：什么是深拷贝？什么是浅拷贝？</p>
</blockquote>

上边在 `JavaScript` 基本类型中我们说到，数据类型分为**基本类型和引用类型**。对基本类型的拷贝就是对值复制进行一次拷贝，而对于引用类型来说，拷贝的不是值，而是**值的地址**，最终两个变量的地址指向的是同一个值。还是以前的例子：

```javascript
var a = 10;
var b = a;
b = 30;
console.log(a); // 10值
console.log(b); // 30值

var obj1 = new Object();
var obj2 = obj1;
obj2.name = "小鹿";
console.log(obj1.name); // 小鹿
```



要想将 `obj1` 和 `obj2` 的关系断开，也就是不让他指向同一个地址。根据不同层次的拷贝，分为深拷贝和浅拷贝。

- **浅拷贝：**只进行一层关系的拷贝。
- **深拷贝：**进行无限层次的拷贝。



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：浅拷贝和深拷贝分别如何实现的？有哪几种实现方式？</p>
</blockquote>

- 自己实现一个浅拷贝：

```javascript
// 实现浅克隆
function shallowClone(o){
    const obj = {};
    for(let i in o){
        obj[i] = o[i]
    }
    return obj;
}
```

- 扩展运算符实现：

```javascript
let a = {c: 1}
let b = {...a}
a.c = 2
console.log(b.c) // 1
```

- `Object.assign() `实现

```javascript
let a = {c: 1}
let b = Object.assign({}, a)
a.c = 2
console.log(b.c) // 1
```



对于深拷贝来说，在浅拷贝的基础上加上递归，我们改动上边自己实现的浅拷贝代码：

```javascript
var a1 = {b: {c: {d: 1}};
function clone(source) {
    var target = {};
    for(var i in source) {
        if (source.hasOwnProperty(i)) {
            if (typeof source[i] === 'object') {
                target[i] = clone(source[i]); // 递归
            } else {
                target[i] = source[i];
            }
        }
    }
    return target;
}
```

如果功底稍微扎实的小伙伴可以看出上边深拷贝存在的问题：

- 参数没有做检验;
- 判断对象不够严谨;
- 没有考虑到数组，以及 `ES6` 的 `set, map, weakset, weakmap `兼容性。
- 最严重的问题就是递归容易爆栈（递归层次很深的时候）。
- 循环引用问题提。

```javascript
var a = {};
a.a = a;
clone(a); // 会造成一个死循环
```

两种解决循环引用问题的办法：

- **暴力破解**
- **循环检测**



还有一个最简单的实现深拷贝的方式，那就是利用 `JSON.parse(JSON.stringify(object))`,但是也存在一定的局限性。

```javascript
function cloneJSON(source) {
    return JSON.parse(JSON.stringify(source));
}
```

对于这种方法来说，内部的原理实现也是使用的递归，递归到一定深度，也会出现爆栈问题。但是对于循环引用的问题不会出现，内部的解决方案正是用到了循环检测。对于详细的实现一个深拷贝，具体参考文章：[[深拷贝的终极探索](https://segmentfault.com/a/1190000016672263)](https://segmentfault.com/a/1190000016672263)



### 异步编程

由于 ` JavaScript` 是单线程的，单线程就意味着阻塞问题，当一个任务执行完成之后才能执行下一个任务。这样就会导致出现页面卡死的状态，页面无响应，影响用户的体验，所以不得不出现了同步和异步的解决方案。

<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：JS 为什么是单线程？又带来了哪些问题呢？</p>
</blockquote>

JS 单线程的特点就是同一时刻只能执行一个任。这是由一些与用户的互动以及操作 `DOM` 等相关的操作决定了 JS 要使用单线程，否则使用多线程会带来复杂的同步问题。如果执行同步问题的话，多线程需要加锁，执行任务造成非常的繁琐。

虽然 HTML5 标准规定，允许 `JavaScript` 脚本创建多个线程，但是子线程完全受主线程控制，且不得操作 `DOM`。

上述开头我们也说到了，单线程带来的问题就是会导致阻塞问题，为了解决这个问题，就不得不涉及 JS 的两种任务，分别为同步任务和异步任务。



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：JS 如何实现异步编程？</p>
</blockquote>

最早的解决方案是使用回调函数，回调函数不是直接调用，而是在特定的事件或条件发生时另一方调用的，用于对该事件或条件进行响应。比如 Ajax 回调： 

```javascript
// jQuery 中的 ajax
$.ajax({ 
    type : "post", 
    url : 'test.json', 
    dataType : 'json', 
    success : function(res) { 
       // 响应成功回调
    },
    fail: function(err){
       // 响应失败回调
    }
}); 
```

但是如果某个请求存在依赖性，如下：

```javascript
$.ajax({
    type:"post",
    success: function(res){//成功回调
        //再次异步请求
        $.ajax({
            type:"post",
            url:"...?id=res.id,
            success:function(res){
                 $.ajax({
                    type:"post",
                    url:"...?id=res.id,
                    success:function(){
						// 往复循环
                    }
                })
            }
        })
    }
})
```

就会形成不断的循环嵌套，我们称之为回调地狱。我们可以看出回调地狱有以下缺点：

- 嵌套函数存在耦合性，一旦有所改动，牵一发而动全身。
- 嵌套函数一多，就很难处理错误。
- 回调函数不能使用 `try catch ` 捕获异常(异常的捕获只能在函数执行的时候才能捕获到)。
- 回调函数不能直接 `return `。



以上有两个地方俺需要再进一步详细说明一下：

- **为什么不能捕获异常？**

其实这跟 `js` 的运行机制相关，异步任务执行完成会加入任务队列，当执行栈中没有可执行任务了，主线程取出任务队列中的异步任务并入栈执行，当异步任务执行的时候，捕获异常的函数已经在执行栈内退出了，所以异常无法被捕获。

- **为什么不能return？**

`return` 只能终止回调的函数的执行，而不能终止外部代码的执行。



<blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：如何解决回调地狱问题呢？</p>
</blockquote>

既然回调函数存在回调地狱问题，那我们如何解决呢？ES6 给我们提供了三种解决方案，分别是 Generator、Promise、async/await（ES7）。

由于这部分涉及到 ES6 部分的知识，这一期是有关 JS 的，所以会在下一期进行延伸，这里不多涉及。

【留下一个传送门~】



 <blockquote style="position: relative;border-left-color: #f75151;margin-left: 8px;padding:15px 23px;background:#f8f8f8;color:#666;">
    <p>面试官：说说异步代码的执行顺序？Event Loop 的运行机制是如何的运行的？</p>
</blockquote>

上边我们说到 ` JS`  是单线程且使用同步和异步任务解决 `JS` 的阻塞问题，那么异步代码的执行顺序以及 `EventLoop` 是如何运作的呢？

在深入事件循环机制之前，需要弄懂一下几个概念：

- <span style="color:#ff502c;font-weight:bold;padding:0 2px">执行上下文</span>(`Execution context`)
- <span style="color:#ff502c;font-weight:bold;padding:0 2px">执行栈</span>（`Execution stack`）
- <span style="color:#ff502c;font-weight:bold;padding:0 2px">微任务</span>（`micro-task`）
- <span style="color:#ff502c;font-weight:bold;padding:0 2px">宏任务</span>（`macro-task`）



#### 执行上下文

执行上下文是一个抽象的概念，可以理解为是代码执行的一个环境。JS 的执行上下文分为三种，<span style="color:#ff502c;font-weight:bold;padding:0 2px">全局执行上下文、函数(局部)执行上下文、Eval 执行上下文</span>。

- **全局执行上下文：**全局执行上下文指的是全局 `this` 指向的 `window`，可以是外部加载的 JS 文件或者本地`<scripe></script>`标签中的代码。
- **函数执行上下文：**函数上下文也称为局部上下文，每个函数被调用的时候，都会创建一个新的局部上下文。
- **Eval 执行上下文：** 这个不经常用，所以不多讨论。



#### 执行栈

执行栈，就是我们数据结构中的“栈”，它具有“先进后出”的特点，正是因为这种特点，在我们代码进行执行的时候，遇到一个执行上下文就将其依次压入执行栈中。

当代码执行的时候，先执行位于栈顶的执行上下文中的代码，当栈顶的执行上下文代码执行完毕就会出栈，继续执行下一个位于栈顶的执行上下文。

```javascript
function foo() {
  console.log('a');
  bar();
  console.log('b');
}

function bar() {
  console.log('c');
}

foo();
```

- 初始化状态，执行栈任务为空。
- `foo` 函数执行，`foo` 进入执行栈，输出 `a`，碰到函数` bar`。
- 然后 bar 再进入执行栈，开始执行 `bar` 函数，输出 `c`。
- `bar` 函数执行完出栈，继续执行执行栈顶端的函数 `foo`，最后输出 `c`。
- `foo` 出栈，所有执行栈内任务执行完毕。

![执行栈](H:\编程笔记\前端面试整理\images\原型\执行栈.gif)



#### 宏任务

对于宏任务一般包括：

- 整体的 `script` 标签内的代码，
- `setTimeout`
- `setInterval`
- `setImmediate`
- `I/O`



#### 微任务

对于微任务一般包括：

- `Promise`
- `process.nextTick`(Node)
- `MutationObserver`



> 注意：nextTick 队列会比 Promie 队列先执行。



以上概念弄明白之后，再来看循环机制是如何运行的呢？以下涉及到的任务执行顺序都是靠函数调用栈来实现的。

1）首先，事件循环机制的是从 `<script>` 标签内的代码开始的，上边我们提到过，整个 script 标签作为一个宏任务处理的。

2）在代码执行的过程中，如果遇到宏任务，如：`setTimeout`，就会将当前任务分发到对应的执行队列中去。

3）当执行过程中，如果遇到微任务，如：`Pomise`，在创建 `Promise `实例对象时,代码顺序执行，如果到了执行· `then` 操作，该任务就会被分发到微任务队列中去。

4）`script` 标签内的代码执行完毕，同时执行过程中所涉及到的宏任务也和微任务也分配到相应的队列中去。

5）此时宏任务执行完毕，然后去微任务队列执行所有的存在的微任务。

6）微任务执行完毕，第一轮的消息循环执行完毕，页面进行一次渲染。

7）然后开始第二轮的消息循环，从宏任务队列中取出任务执行。

8）如果两个任务队列没有任务可执行了，此时所有任务执行完毕。



**实战一下：**

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>消息运行机制</title>
</head>
<body>

</body>
    <script>
        console.log('1');
        setTimeout(() => {
            console.log('2')
        }, 1000);
        new Promise((resolve, reject) => {
            console.log('3');
            resolve();
            console.log('4');
        }).then(() => {
            console.log('5');
        });
        console.log('6');// 1,3,4,6,5,2
    </script>
</html>
```

- 初始化状态，执行栈为空。
- 首先执行 `<script>` 标签内的同步代码，此时全局的代码进入执行栈中，同步顺序执行代码，输出 1。
- 执行过程中遇到异步代码 `setTimeout`（宏任务），将其分配到宏任务异步队列中。
- 同步代码继续执行，遇到一个 `promise` 异步代码（微任务）。但是构造函数中的代码为同步代码，依次输出3、4，则 then 之后的任务加入到微任务队列中去。
- 最后执行同步代码，输出 6。
- 因为 `script`内的代码作为宏任务处理，所以此次循环进行到处理微任务队列中的所有异步任务，直达微任务队列中的所有任务执行完成为止，微任务队列中只有一个微任务，所以输出 5。
- 此时页面要进行一次页面渲染，渲染完成之后，进行下一次循环。
- 在宏任务队列中取出一个宏任务，也就是之前的 `setTimeout`，最后输出 2。
- 此时任务队列为空，执行栈中为空，整个程序执行完毕。

![消息循环](H:\编程笔记\前端面试整理\images\消息循环\消息循环.gif)



以上难免有些啰嗦，所以简化整理如下步骤：

- 一开始执行宏任务（`script `中同步代码），执行完毕，调用栈为空。
- 然后检查微任务队列是否有可执行任务，执行完所有微任务。
- 进行页面渲染。
- 第二轮从宏任务队列取出一个宏任务执行，重复以上循环。



### 作者持续更新中....