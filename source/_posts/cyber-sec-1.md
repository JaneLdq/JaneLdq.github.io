---
title: Cyber Attacks Note 1 - Vulnerability, Threat & Attack
date: 2019-04-15 20:04:30
tags:
---

失踪人口回归啦～《Cyber Attacks Notes》系列正式开坑～

新坑由来是这样的：
在一个多月前，由于高估了自己的主观能动性，一个激动点击了Coursera上的**Cyber Attacks**这门课的trial，然后就晾那儿了。时隔一周，突然收到一条扣费短信（黑人问号脸.jpg，思考甚久，原来是trial到期直接续费了。
既然钱都交了，不把证书拿到岂不是很亏～因为视频看得有点赶，课程里涵盖的内容又比较泛，结课了觉得还是有必要复盘一波。

---

第一篇笔记，我们先回答几个比较宽泛的问题：
* 什么是Vulnerability？
* 什么是Threat？
* 什么是Attack？
* 它们各自又分为哪些类型呢？

<!--more-->
---
# Vulnerabilities
// TODO

---
# Threats

下面是从*From CIA to API, An Introduction to Cyber Security*这本书中摘录的：
> The term *threat* is used in cyber security to describe **the bad things that hackers can do to assets**. 

*PS：这本书也是这门课的老师自己写的一本书，内容比较浅显，多为点到即止的概念介绍，正如它的定位，一本适合大众阅读的科普书。不过我个人认为，对于梳理这类概念性的信息还是有帮助的。*：

## Threat Types
Threat又可分为三大类：
1. Confidentiality Threat (sensitive information leakage)  - 保密性，通常指敏感信息的泄露。现在经常爆出的用户信息泄露新闻就属于这类Threat。
2. Integrity Threat (corruption of some asset) - 完整性，对于数据而言主要是信息的完整和真实性受到威胁；对于其他assets，比如计算机，被恶意应用入侵甚至控制。（在英语中经常会见到"Compromised"这个词来形容被“感染”的asset，也就是指面对hacker的入侵“妥协”了的意思。）
3. Availability Threat (intentional blocking of access to a computer or network system) - 可得性，通常指不能正常访问某个系统或服务，请求被阻塞住了。最典型的一个availability threat应该属**DDoS - Distributed Denial of Service**
4. Fraud (steals a service withou paying, and resulting impact doesn't fit well into disclosure, integrity or denial of service categories) - 使用欺骗的手段获取一些非法利益，但是又不太符合以上三种类型。比如在Q币还很流行的时候，有很多坏蛋盗号花别人的Q币啊（想当年年幼无知，也是受害者之一了

## CIA Model
取前三类Threat类型的首字母就组成了所谓的*CIA Model of Cyber threats*。（其实就是起了个组合名嘛，还把人家小F排除在外，哼～

看个表格总结一下：

|Threat Type|Motivation|Defining Attributes|
|---|---|---|
|Confidentiality|Secrets|Personal and business information|
|Integrity|Degradation|Remote operational control/change|
|Availability|Disruption|Distributed botnet attacks|
|Fraud|Money/Goods|Ingenious and clever means for theft|

---
# Attacks
// TODO

---

* **参考资料**
* [confidentiality, integrity, and availability (CIA triad)][1]

  [1]: https://whatis.techtarget.com/definition/Confidentiality-integrity-and-availability-CIA

