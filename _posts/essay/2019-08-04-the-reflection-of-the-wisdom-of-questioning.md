---
title: 《提问的智慧》有感
excerpt: 提问之前、网络礼节、如何准确地定义问题
category: essay
---

互联网普及，部分问题能在网上得到准确答案，例如一般编程和生活常识的问题。进一步地，如何提高获取这些问题答案的速度和准确度？黑客社区流传已广的[《提问的智慧》](https://github.com/DebugUself/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md#%E5%A5%BD%E9%97%AE%E9%A2%98%E4%B8%8E%E8%A0%A2%E9%97%AE%E9%A2%98)能帮助你。以下是我感触颇深的几点：

## 提问之前

《提问的智慧》一开始并没有直接告诉你问题的答案在哪里，而是列出提问之前需要做些什么，

> 在你准备要通过电子邮件、新闻群组或者聊天室提出技术问题前，请先做到以下事情：
>
> 1. 尝试在你准备提问的论坛的旧文章中搜索答案。
> 2. 尝试上网搜索以找到答案。
> 3. 尝试阅读手册以找到答案。
> 4. 尝试阅读常见问题文件（FAQ）以找到答案。
> 5. 尝试自己检查或试验以找到答案
> 6. 向你身边的强者朋友打听以找到答案。
> 7. 如果你是程序开发者，请尝试阅读源代码以找到答案。

为何如此？在我看来，这考虑到，**互联网信息是可复用**。因为你的问题很大可能早已被其他人提问了且已有答案，重新提问只能被别人重复浏览相同的问题并忽略，而自己却等待别人的回复，浪费时间。而更有效的方法是，自己先动手看是否能寻找到已有答案，这是尊重别人也是尊重自己的时间。即便最后未能找到心仪的答案，建立起有效寻找答案的方法也是莫大裨益。

## 注意网络社交礼节

不同于亲身会面，互联网中的你我有着物理阻隔，我们只能通过文字、图片等进行交流，而缺少了语气、表情等交流要素，想要准确快速地理解对方变得困难一些。例如，你有一个重要且紧急的问题想要请教，为了表达对问题的紧迫程度，你在问题标题上加上了「紧急」二字。但如此而为，非但不能快速解决问题，而且会被别人习惯性地忽略，因为在别人看来，有着「紧急」二字的标题是无礼而自私的，这是企图引起关注的行为，别人更愿意去解决对彼此有得益，而不是那些有吸引眼球只对提问者重要的问题。当然，这只是众多错误的冰山一角，注意好网路社交礼节，才更有可能得到好的交流。

## 准确地定义问题

对如何提出一个好问题，《提问的智慧》只用例子粗略地说明，但我认为这非常重要。

想要通过提问来获取答案，首先得学会怎样准确地定义一个问题。没有一个被准确定义的问题，想要得到答案是不可能的。

用一次python课程同学提出的一个问题作说明，是最好不过了。他的问题是：「[如何找到高质量的包？](https://gitlab.com/101camp/1py/tasks/issues/74)」

他一开始的设想是，能否找到一个对包进行评测的地方，以此能了解此包质量的高低。他找到了 [Libraries.io](https://libraries.io/) 这样一个对包进行评分的网站，用户可根据 source-rank、most-used 等进行排名以便选择。下一步，假如他找到了排名第一的包，他得花费多少学习这个包的精力呢？设想一下可能的结果：学习这个包所花费的精力实在太多了，最后发现想要解决的问题却毫无进展。如此，这样的结果是不期的，为何在解决实际问题时候，所谓「评分高」的包，所谓「高质量」的包反而没有帮助呢？

- 所谓「高质量」是否真的代表高质量呢？
- 高质量是对什么而言？
- 如果没有划定范围，是否存在一种高质量的包对所有问题都适用？

答案是肯定的，不存在一种高质量的包对所有问题都适用，一个包只能对特定范围的问题有帮助，也可能存在另外一包对此范围的问题为最优解。高质量就意味着最优解，但这对什么而言？「如何找到高质量的包？」并没有说明问题的范围，所谓的「高质量」也就不存在了，解决问题也就无从谈起，所以， 提问之前，准确地定义问题，就是获取答案不可或缺的一步。

如果下次遇到问题，如何避免犯同样的错误——没有划定范围？

答案是西方用于分析问题方法的总结—— 5W2H [[1]](https://baike.baidu.com/item/5W2H%E5%88%86%E6%9E%90%E6%B3%95/8111597?fromtitle=5W2H&fromid=17202456)  [[2]](https://wiki.mbalib.com/wiki/5W2H%E5%88%86%E6%9E%90%E6%B3%95)，when（何时），where（何地），who（何人），why（何因），what（何事），how（怎样），how much（多少）。

- when（何时）：什么时候出现此问题
- where（何地）：什么地方出现这个问题
- who（何人）：谁是提问者，提问者的背景是什么，应该向谁提问，回答者的背景是什么
- why（何因）：为何要提出这个问题和涉及的事物
- what（何事）：问题涉及什么事情，涉及的事物含义是什么
- how（怎样）：如何解决，有何方法
- how much（多少）：怎么才算解决，什么程度

如此，问题被框定在何时和何地等要素内，当然，此范围可进一步细化，但问题总体清晰不少，结合众多要素，找到答案也指日可待了。

## logs

2019-8-4：init 

2019-10-25：5W2H instead of 5W1H 