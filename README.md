# 优雅的 MAC

2016-02-27 序：作为毕业生加入 ThoughtWorks 已经有 7 个月了，浸泡在这样一个追求敏捷和高效的环境中，不知不觉也形成了很多（让我们相信是）好的习惯，也有要把它分享出来的欲望。这方面已经有很多人分享了自己的实践和想法，ThoughtWorks 公司也翻译了一本《卓有成效的程序员》，有很多的参考。那么本书一方面是自己提升效率路上的学习总结，另一方面希望对快捷背后的理念进行提炼，从观念上改变对自己手艺——犹如剑士对手中之剑——固有但低效的使用习惯，并把理念、想法和方案落实渗透到实践中去。理念，正是本书所希望有所创新的亮点。

2017-05-04 补序：一年未碰此仓库，现在要拾起。看原来序，未免有些客套，敏捷未必，高效也未必。最近想拾起这个系列的原因，以及这一年来的发现，倒是更有意义。此处小铺展开。

这个 5 月我的工作地点换到深圳，也许是一次小转折。深圳带来的压力，成都不能比。整理过去书签的时候，我发现我有个整理的习惯，但很多东西，整理了并不用，那么这样的整理除了浪费时间和满足个人表面的完美癖，其意义何在？答案是，不去总结提炼产出内化的话，价值是没有的，而且就是浪费了时间而已。整理越多，浪费越多，越是焦虑。因此，继续这本书的写作，是因为我看到，只有有目的地写作产出，整理才是有价值的。

另外，原来我对于「敏捷」「高效」这个命题深信不疑，觉得没有证明的必要。是吧，能快你为什么要慢呢。这与我对 TDD 的观点也是一致的，核心就是快，别扯什么测试什么维护什么团队合作的，能快你为什么要慢呢？不可忽略的是，任何工具都有学习成本，也正是这样的「成本」，直接阻挡了很多人探索的脚步。我觉得归根结底，包括我，人在学东西的时候功利诱惑是很难避免的。功利是人的问题，不是技术问题。我一直是这样认为的，以至于在技术及其他领域，我都对交流感觉悲观。所谓套路，其背后的假设仍是功利。

直到与大伟聊过一次。我才猛然发现到，我的问题在于没有全局优化，没有回答「为什么（要高效）」这个问题，或者说，我只从「极致的快」这个维度来回答。单一的维度是没有办法判断对错的。仝健讲四色建模，讲到它是个沟通工具，使所有的人能够用同一套语言进行交流，从而减少了沟通成本，增强了团队的响应力。所有的实践都是围绕这个目的来进行，比如 TDD 啊，敏捷啊。你不能说，TDD 做完我的进度下去了，响应力降低了，我不管，我就是要 TDD。实践一定是为目的服务的。那么，我也得问自己，「高效」的目的是什么？它的判断依据是什么？有没有可衡量的标准？

这是我写作此书会尝试解答的问题。

2017-10-06 补：「为什么要快」。其实也没有想多快，只是想在肉眼可见的范围内优化一下速度而已。爱快快，不爱看左上叉叉。不好意思右上。哪有那么多精力解释这个问题。

2018-06-02 补：大伟讲的是团队角度的 TDD，它是推广的问题。TDD 和 TDD 推广是两个基本不相干的问题（如果不是毫不相干）。对于个人 TDD 这个事情，现在觉得没有必要多费口舌，爱学咱没有保留，不爱学左（右）上角。应该定这个调，纠结个啥。

2018-06-24 补：目前我觉得，「意义」这个事情，暂时可以不用去回答的；这本书好的地方或许，有价值的地方，是它提出了「声明式」这个观点。它是目前整个快捷体系的总提纲，是评判效果的标准。什么样叫高效呢？更快地完成工作。更快地达到目标。实现更好的价值。这里介绍的是手法，但背后这些不可言说的东西同样重要。

## 阅读地址

[Linesh Gitbook: Elegant Mac Tools System Closure](https://www.gitbook.com/book/linesh/gitbook-elegant-mac-tools-system-closure/details)

## 待办事项(TODOLIST)

* 提交格式：`[(prefix: book chapters)]: brief of added/amended content`
* 录制操作的 gif
* 自动压缩图片
* 自动化本书提到所有工具的版本信息、下载链接信息的维护
* 维护通过不同渠道**安装**的软件信息，对这些信息进行版本管理同时能从维护的元信息中一键安装所有软件
* 对所有软件的配置信息(configuration/preferences)进行自动备份、版本管理，可能需要各个软件提供 API 来支持自动导出或备份、然后再与 git 和 dropbox 进行连接

## 别人已经做过的工作

请参考[参考文章-Reference 一节](publish/reference/reference.md)。
