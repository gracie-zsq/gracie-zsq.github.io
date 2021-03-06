---
layout:     post
title:      针对匿名社交app用户答题机制的竞品分析
subtitle:   bilibili会员入会题、soul灵魂测试和summer“答卷”对拥抱app的启示
date:       2020-07-05 12:03:16
author:     Siqi Grace
catalog: true
tags:
    - 拥抱app
    - 竞品分析
---
**一、背景 （为什么做分析？）**

“陌生人社交”，又名“匿名社交”一直是互联网领域一个经久不衰的热门。从早期的secret和PostSecret，到之后涌现出的陌陌、探探，再到近两年的soul，summer等。而这次我们想要做的概念产品“拥抱”app也属于这一范畴，其灵感来源于豆瓣小组“985five计划”。five组是一个各种自认为失败，愧对于自己985/211/海外学历背景的人士吐槽自己经历和现状，互相鼓励的小家园。我们希望我们的app也可以提供给这些自嘲为“做题家”的人士一个互相匿名吐槽和交流，抱团取暖的天地。在产品设计的探讨中，我们对是否需要加入一个用户注册或初次使用前的性格测试功能和如果加入，具体应该如何定位这一功能产生了疑问。为了解答这个问题，我选取了bilibili、summer和soul这三个定位、主要功能不一但都加入了类用户答题功能的app，进行了仅针对用户答题这一功能的定向竞品分析。希望通过系统分析三个app的定位和功能以及用户答题机制在整个app中起到的作用和实际效果，为“拥抱”app1“.是否应加入用户注册时的性格测试功能”2.“如果加入，应该如何设计这一功能“这两个问题找到一个比较合理和可行的解决方案。


**二、竞品对象：选择bilibili、summer、soul这三个产品作为竞品的原因**

首先，bilibili（以下简称为b站），summer和soul三个产品都是流量很大的成功app，根据b站2020年第一季度财报官方数据，b站的日活跃用户数量已经突破了5000万大关。soul的活跃用户也在千万级。summer虽然后劲相较前两者比较疲软，但是刚刚推出的时候也短时间内达到了百万级用户量，吸引到了字节跳动的投资。对标这些取得了巨大成功的产品，可以让我们从别人的成功中借鉴到经验，尽量减少自己摸索道路会遇到的失败。
分别来说，b站的答题机制是用户从level 0到level 1的一个必经“筛选门槛”，也就是说，要想成为b站的正式会员，拥有发送弹幕等会员“特权”功能，必须在b站100道题答题中取得满分的成绩才行。拥抱app中的用户答题机制如果确定加入设计，也是为了起到用户注册后，必须通过答题取得一定分数，才能开始正式使用的一个筛选功能。同b站已有的答题机制功能相仿，分析b站的这一功能上线后的反响和背后的机理，可以方便我们更好的分析是否应在拥抱app中加入答题机制。<br>
Soul则是作为年轻人匿名社交app的领头羊之一，跟“拥抱”app的领域相似，目标人群年龄层相仿。Soul的灵魂测试的定位和拥抱app目前的想法和设计并不完全一样。我们可以借分析Soul,探讨用户答题功能设计和定位上的更多可能性。<br>
Summer作为主打高端大学生匿名交友的app，可以说是市面上比较成功，用户总量和日活都比较高的app中，跟我们最为对标的竞争对手（竞品）了。分析它的答题机制（用户答卷），可以让我们借鉴直接竞争对手的得失，尽量避免踩坑。


**三、竞品分析**<br>
*3.1 产品定位：用户画像分析*<br>
注：用户画像的相关信息来源于网络，包括艾瑞数据，公司对外公布的财报和相关采访报道
<img src="https://gracie-zsq.github.io/assets/userportrait.png" class="inline"/>
可见。在用户画像上，3个app有重叠的部分，也有不同之处。在用户年龄上，summer因为严格限定为大学生，所以年龄段最为集中。而soul的年龄构成最为偏大，bilibili的年龄跨度很大，从小学生到30岁出头的工作人士都有。而用户集中在一线城市，有旺盛的网络表达欲可以说是3个app用户画像上最大的共同点。<br>

*3.2 产品结构图* <br>
因为我们只想要分析各个产品的类答题机制，所以这里的结构图只包含跟答题机制相关的部分。<br>
3.2.1. bilibili
<img src="https://gracie-zsq.github.io/assets/bilibili.png" class="inline"/>
哔哩哔哩的答题机制为100道选择题，全对才可以获得会员称号。会员等级从lv0开始,随着升级用户的权限不断扩大。而只有成为了正式会员，才能享受弹幕，投稿等一些哔哩哔哩作为视频网站最基础的功能。可以说，不通过答题机制，除了单纯观看视频以外无法使用b站的任何功能。由此可见，哔哩哔哩的答题机制主要目的是通过题目，“筛选出”，或者说让用户认为进入bilibili社区的都是同一类人（热爱二次元/追星/追求新鲜事物的年轻人），增强用户的社区认同感，从而增强社区粘度。事实上，b站的用户粘性也确实在各类社交app里傲视群雄：正式会员第12个月留存率超过80%。
<br>3.2.2Soul
<img src="https://gracie-zsq.github.io/assets/soul.png" class="inline"/>
Soul的答题机制主要是应用于星球和用户匹配的功能。软件可以通过性格测试“灵魂测试”为用户匹配到不同的星球。soul上的测试五花八门，而且在不断更新完善。用户做的测试越多，Soul也可以更好的为用户匹配更合适的星球和用户。根据Soul的官方说法，这些测试的目的也是为了呼应app的基本理念“弱化看脸的现实社交本质，匹配注重内在的线上社交“。由此可见，soul的答题机制实际上是性格测试，主要起到用户匹配的作用；通过用户测试答题所创建的画像，进行用户划分。同时，很多趣味测试的题目也很有意思，也改善了用户的使用体验和加强了用户粘性。<br>
3.2.3 Summer<br>
<img src="https://gracie-zsq.github.io/assets/summer.png" class="inline"/>
summer整个app因为面向的是高校在校生，所以功能命名上充满着浓浓的“学生气”，例如，一般交友app都有的社区/论坛被命名为了“黑板墙”。这一点在summer的答题机制上也可以非常明显的体现出来。summer的答题机制为用户自己“出题”其他人可以来“回答”：用户设置问卷，其他用户进行浏览并回答。系统会自动根据用户在个人资料中填的性取向，来将试题推荐给对应性别的用户。问题的形式可以为为问答题、选择题、语音题或者视频题。值得注意的是：试卷不会设置正确答案，也不会由后台判断正确，而是由出题用户在收到回答时自行“批阅”。可以通过设置有意思的题目，来吸引其他用户回答，用户也可以根据实际答案，判断是否合眼缘。可以说，summer答题机制的设计，一方面通过独特的命名和功能设定更加吸引目标用户（在校大学生）的注意，并且把自己同其他定位类似的匿名社交app（例如前文的Soul)区分开来，增强了用户的互动感和粘性，值得我们的借鉴。

**四、结论** <br>
综上所述，我个人认为，拥抱“app”可以加入用户注册后的强制测试功能。这个测试的目的，可以是像我们之前探讨的那样，同哔哩哔哩的机制相似，覆盖到一些基础的用户规则，确保我们的用户都属于目标用户群“较高文化素质的大学在校和毕业生”群体。后期的话如果人力物力足够，也可以加上像soul一样的各类心理测试，不过这个可以等注册用户数和日活量达到一定数据之后再补充，并且可以像soul学习，直接出现在用户主页的栏目里。而测试题目的视觉ui设计和名称，题目种类，可以参考summer，多做一些贴近学校生活的尝试。


