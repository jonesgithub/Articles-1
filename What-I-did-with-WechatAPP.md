# 微信小程序一二事

## 小程序很尴尬

微信小程序发布之前，便在圈内掀起了一阵开发浪潮。上万的开发者跃跃欲试，千百个大小老板翘首企盼，有的是对新技术趋之若鹜，更多的人则是渴望着能够在小程序发布之初捞得一笔金。

1 月 9 号那天凌晨，小程序如期发布，霎时间洛阳纸贵，圈里圈外谈论的话题都离不开小程序，甚至有朋友发信息过来问我小程序要如何使用。外行人看热闹，内行人看门道，我作为一个热闹中略有门道的吃瓜群众，对小程序的前景隐隐担心。

小程序既然称之为程序，就意味着其和公众号不同，又加上小程序不能推送消息，所以小程序更加注重操作性也就是业务服务。因此想要靠小程序做营销推广或者媒体类内容的人可能进错了坑，我认为逻辑思维的退出也正是因此。

小程序的特点在于”触手可及，用完即走“，这就决定了小程序的轻便和简洁。小程序的页面深度在 5 层，并且程序包不能超过 1 M，因此小程序在业务逻辑上不能太复杂，这也决定了企业的产品必然要砍去一些旁溢斜枝，只留下主要功能。因此那些靠免费业务留住用户，通过附属内容变现的公司将不会涉足。

小程序的目的在于替代原生的手机应用，为手机减负。很多用户在下载小程序的同时删除了原生的手机应用，这也就意味着小程序会影响原生应用的日活数据，那些依赖于日活在应用商店发展用户的企业又在此受挫。

小程序的发布需要经微信团队审核，微信旨在打造一个干净、高效的生态。这也就意味着所有小程序的发布都需要遵循微信的标准，否则就无法发布，与苹果商店类似。实际上，微信生态不够成熟不足和苹果相提并论，并且安卓市场相对开放的环境对开发者和创业者非常友好，因此微信生态即使有着强大的用户基础和免费的流量，也不一定能留住蜂拥而至的吃瓜群众。

即使小程序发布初期吸引了众多的目光，但仿佛很快就又销声匿迹。相信很多人和我一样，在小程序发布的那天兴致勃勃地下载了好几个小程序，之后几乎就没再用过，手机上的应用倒是卸载了不少。这似乎也达到了”用完即走“的目的，但随着小程序的热度骤降，我的开发热情也随之趋于稳定。

有人认为小程序是公众号的替代品，有人认为小程序可以作为公众号的辅助，而我认为这些观点未免都有些狭隘。小程序和公众号的定位不同、特点不同、体验不同、功能不同，小程序更注重操作，公众号更注重传播。服务号倒是可以考虑做成小程序，但两者由于种种差异，终究不能一个完全替代另一个。

小程序的市场和用户基础都非常庞大，但用户粘性细若游丝。因此，小程序的红利不会如山洪爆发突飞增长，只会如涓涓溪流源远流长。

## 小程序开发事

小程序开发[官方文档](https://mp.weixin.qq.com/debug/wxadoc/dev/)。

微信官方小程序示例 DEMO（在小程序中搜索”小程序示例“）：

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/wedemo1.jpg) 

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/wedemo2.jpg)

我从内测时就开始关注小程序，也在学习中创造过一些很简单的轮子，并参与了公司的小程序开发。

期间我参加过很多会，听过很多大咖的分享，开发过程中也踩到了许多坑，有些在研究过后被填平，有些就被绕过了。我总结过一篇[小程序开发文档没有告诉你的那些事](https://github.com/Romeo0906/WeChatAPP/blob/master/Something-that-wxadoc-don't-tell-you.md)，建议通读官方文档之后再来阅读理解会更加深入。

部分内容如下：

* 框架部分：

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/framework.jpg)

* 组件部分：

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/component.jpg)

* API 部分：

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/API.jpg)

* 工具部分：

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/tool.jpg)

安利我写的一个轮子，内容如下图：

* 登录页

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/signin.jpg)

* 主页

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/index.jpg)

* 个人中心

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/profile.png)

* 用户详情

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/user.jpg)

* 帖子详情

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/post.jpg)

* 我的帖子

![](https://github.com/Romeo0906/Articles/blob/master/pics/What-I-did-with-WechatAPP/mypost.jpg)

主要实现了发帖分享的社交功能，实现了发帖、看贴、排行、收藏、查看用户等功能，源代码在[GitHub](https://github.com/Romeo0906/WeChatAPP)。

本例中使用了微信官方提供的框架、组件、API 和一些基础的开发技巧，仅作为学习使用，欢迎 star 或者 fork！