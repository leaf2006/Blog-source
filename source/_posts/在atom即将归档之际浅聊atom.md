---
title : 在atom即将归档之际浅聊atom
date : 2022-6-24
categories: 
- 碎碎念
---

# 在atom即将归档之际浅聊atom

- ##　总起

最近好久没写博客了，其实我也是有在打一些草稿的，但是后来都放弃了。最近中考已经考完，无聊中打开atom的门户网站，发现atom即将归档

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/100.png)


>When we formally introduced Atom in 2014, we set out to give developers a text editor that was deeply customizable but also easy to use—one that made it possible for more people to build software. While that goal of growing the software creator community remains, we’ve decided to retire Atom in order to further our commitment to bringing fast and reliable software development to the cloud via Microsoft Visual Studio Code and GitHub Codespaces.<br />Today, we’re announcing that we are sunsetting Atom and will archive all projects under the organization on December 15, 2022.


翻译：


>当我们在 2014 年正式推出 Atom 时，我们着手为开发人员提供一个可深度定制但也易于使用的文本编辑器，让更多人能够构建软件。 尽管发展软件创建者社区的目标仍然存在，但我们决定让 Atom 退役，以进一步履行我们通过 Microsoft Visual Studio Code 和 GitHub Codespaces 将快速可靠的软件开发带到云端的承诺。<br />今天，我们宣布我们将停用 Atom，并将于 2022 年 12 月 15 日归档该组织下的所有项目。

关于atom即将归档的通知也被放在了atom门户网站最显眼的地方

简称：atom要寄

当然，事实并不是这样，不过首先请允许我阐述我对于atom的看法

- ##　我对于atom的看法

  我差不多在2020年初就已经接触到了atom，现在看来其实atom的生命周期也已经走到尾声了。那个时候因为我下载了很多的编辑器打算找到一个适合我的，无意间就找到了atom

  ![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/101.jpg)

  <center>2020年十月份在家欢乐使用atom</center>

  atom当时给我的第一个印象就是——非常的美丽。atom的UI看着真的十分赏心悦目，界面也十分地友好，不会让人一上来就摸不着头脑。且它的插件众多，基本上atom的那些插件可以养活所有开发者了吧。优秀的内置git gui个人认为比vscode的那一套还要好。

  哦，有一件事情必须要提及，atom可以说是跨平台鼻祖——也就是Electron，为后来各种软件提供了跨平台方案，也为vscode出现铺平了道路。

  什么？vscode？完了，完了，乱杀了，乱杀了！

  - ## 是谁将atom打下神坛

    atom可以说是一个老牌软件，于2013年3月1日，在github发布了第一个版本

    ![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/102.png)

不过一开始的版本只能自行编译，并没有发布现成的安装包供用户使用，直到v0.39.0版本才开始出现直接供给使用的mac版的atom。在2014-2015这一期间，是atom更新的高峰期，可见在这一段时间内用户对于atom的呼声很大，可以说是atom的高峰时期了。

不过，2015年，又有一款跨平台、和atom类似的代码编辑器出现——**vscode**，可以说是atom的竞争者了。一开始的vscode我个人感觉并不是十分好用，但是微软满勤奋的，越来越多的开发者倒向vscode。

后来，又有一件事情，决定了vscode和atom的命运——atom必败。

2018年，微软收购github。而atom就是github下面的项目。这波vscode直接反手成了atom的爸爸……vscode这回可以光明正大地“借鉴”atom力（悲）。vscode越加成功，而atom在接下来的几年内便没有什么非常重要的更新，显得黯淡起来。今年，github又推出了github codespace，可以说就是免费的云服务器装了个vscode。github codespace推出后，我也在第一时间尝试了一下，不得不惊叹云开发越来越深入人心。在科学上网的情况下，直接在网页端使用codespace或是在本地vscode端远程连接codespace，体验都十分舒适，必须为github点赞。而在点赞的同时，谁又会想到github其实也有一款自己的代码编辑器——atom呢？

atom实际上并不只是败在vscode手下，也败在了它的性能上。并不是说Electron写的应用的性能就一定差的离谱，毕竟vscode我用着都不怎么卡。但是对于atom就是卡。我啥东西都没装，启动atom都要好久好久。当时我用atom写代码的时候，一些小问题我都不想用atom来修改，直接vim+文件名修改了事，因为atom性能实在是太差了。

atom有人为它开发中文插件，有人为它提供完整的插件市场，有人为它处理bug。也许……atom的性能再优化一下，atom也许还会继续被github所维护？也许vscode没有出现，atom能够一跃成为世间最美观、最强悍的代码编辑器？仅仅只是个人猜想

当然，这是不可能的。因为atom的性能就是那样，vscode也已经出现了。atom的缺点也全都暴露出来了，虽然说atom为后续的编辑器、甚至后续的跨平台应用奠定基础，可是是时候，也该结束了。

>在过去的几年里，Atom 没有重大的功能开发，尽管我们在此期间进行了维护和安全更新，以确保我们成为项目和产品的好管家。多年来，随着新的基于云的工具的出现和发展，Atom 社区的参与度显着下降。因此，我们决定停止使用 Atom，以便我们可以专注于使用 GitHub Codespaces 增强云中的开发人员体验。<br /><br />这是一个艰难的告别。值得一提的是，Atom 是 Electron 框架的基础，它为创建数千个应用程序铺平了道路，包括 Microsoft Visual Studio Code、Slack 和我们自己的 GitHub Desktop。但是，可靠性、安全性和性能是 GitHub 的核心，为了最好地服务于开发者社区，我们将 Atom 归档以优先考虑支持软件开发未来的技术。<br /><br />我们认识到社区仍在使用 Atom，并希望承认迁移到替代解决方案需要时间和精力。 我们致力于帮助用户和贡献者规划他们的迁移。<br />•今天，我们宣布六个月后的日落日期。<br />•在接下来的六个月中，我们将继续在产品和 atom.io 上通知 Atom 用户日落。<br />•2022 年 12 月 15 日，我们将归档 atom/atom 存储库以及 Atom 组织中剩余的所有其他存储库。<br /><br />GitHub 和我们的社区从提交问题、创建扩展、修复错误和在 Atom 上构建新功能的人中受益匪浅。 Atom 在许多开发人员的旅程中扮演着不可或缺的角色，我们期待着共同构建和塑造软件开发的下一个篇章。<br /><br />————《Sunsetting Atom》（已中文翻译）

Goodbye,atom...

- ## 也许并没有结束？

  github发表了要归档atom的这篇文章后，许多atom的忠实粉纷纷在atom的issue区用不同方式表达自己的不舍

  ![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/103.png)

截至当前issues数量刚好是886哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈，atom正好要归档了，莫名搞笑

有人表达自己对于atom的不舍

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/106.png)

有人在issue区撕逼

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/108.png)

内容我就不放出来了，大家如果好奇的话自己去issue区找。反正脏话都飙出来了就是了。

有人希望github官方能继续维护atom

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/104.png)

从这里可以看出，虽然github官方将会归档atom，但是由于atom是完全开源的，所以任何人都可以继续更新它。从许多用户的决定中可以看出，atom-community并没有就地解散，反而会在atom归档之后代替github官方继续维护。所以我个人的想法是，atom并没有完全结束，只不过因为vscode、微软和github自身原因官方停止维护，转变为atom-community贡献力量。

所以吧，为了写这个博客，我特意重新下载回了atom。归档后的atom将会怎样发展？目前来看情况还是乐观的，具体的情况就得看12月15日之后了吧。

- ## 结束语

**A hackable text editor for the 21st Century!**

- ## 参考资料

*[Sunsetting Atom:We are archiving Atom and all projects under the Atom organization for an official sunset on December 15, 2022.]https://github.blog/2022-06-08-sunsetting-atom/*





