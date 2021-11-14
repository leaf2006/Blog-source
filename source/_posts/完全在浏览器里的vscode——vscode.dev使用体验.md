---
title : 完全在浏览器里的vscode——vscod.dev使用体验
date : 2021-11-6
categories: 
- 评测
---

# 完全在浏览器里的vscode——vscode.dev使用体验

最近几天由于上学，加上上周忙着拍车，剪辑视频，两天硬是一天一更，就没啥时间管代码方面的事情了。今天更新了一下vscode，无意之中在更新日志里发现了这个玩意，于是点击链接进来看……这个东西是在今年的10月22日发布的，所以，当我在写这一篇博客的时候，已经很晚了。不过当我翻了一下百度以及其他好基友的博客之后，发现他们都没有写这个东西，心想也许我还能钻个空子😏

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/52.png)
<center>我笔记本很老了，屏幕分辨率只有1280x800😭</center>

<br />

这个一下子就震惊到我了，多年的梦想居然突然就被实现了，上方还有关于vscode.dev的介绍文档，啪的一下，很快昂，我就点进去看了😜

- ## 体验前的题外话

文档的第一段（中英对照，谷歌翻译）：

>Back in 2019, when the .dev top-level domain opened, we picked up vscode.dev and quickly parked it, pointing at our website code.visualstudio.com (or, if you are from the Boston area like me, we "pahked it"). Like a lot of people who buy a .dev domain, we had no idea what we were going to do with it. And we certainly didn't anticipate that it would end up being the fulfillment of a mission over a decade in the making.
<br />
早在 2019 年，当.dev顶级域名开放时，我们拿起vscode.dev并快速停放，指着我们的网站code.visualstudio.com（或者，如果您像我一样来自波士顿地区，我们“pahked”）。像许多购买.dev域名的人一样，我们不知道我们将用它做什么。而且我们当然没有预料到它最终会完成一项十多年的使命

啊？说实话这件事情我是一点都不晓得，立马就去Wayback Machine上看了一下，还真是…

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/53.png)

这是2021年8月31日的记录，也是在Wayback Machine上能找到的最早的记录，不过它指向的是microsoft的登录界面……

- ## 正式开始

以下就是我对于vscode.dev的所有评测

- ## 什么是vscode.dev？

这一点在官方的文档里也有相应的解释，“Visual Studio Code for the Web 提供完全在您的浏览器中运行的免费、零安装 Microsoft Visual Studio Code 体验，使您能够快速、安全地浏览源代码存储库并进行轻量级代码更改。”，也就是说你在使用它之前不需要做任何事，只需要一个稍微正常一点的设备和一个能正常访问的浏览器，然后访问[vscode.dev](vscode.dev)，就可以使用了。**没错，不需要任何其他的东西，就只是需要这么两样工具，你就可以使用了**。所以说他的本质很简单很简单，就是一个在浏览器上运行的web代码编辑器…就是一个…可以个性化，可以组件化的编辑器…嗯…也就是一个编辑器。

有些人也许就要开始问了：“啊？就只是一个编辑器啊？就那么普通啊？微软啊——你怎么这么堕落啊——”

的确，现在网上上类似这种东西的，不管是国内还是国外，都很多。国内的要说有较为完整的代码提示之类的东西的话就比如gitee的那个web ide或者w3school的了；国外的代码提示与补全比较齐全的就比如stackblitz了。

那么在这么广大的网页端代码编辑器之间，vscode.dev的优势保持在什么呢？

- ## vscode.dev：八十万对六十万，优势在我！

在这里不讲深层次的东西，只讲在平时用得到的浅显的东西

- ##### 易于入门

首先在vscode.dev上非常直观的一个优点就是——易于入门。

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/52.png)

从开头的这个图片很容易就能看出来，它和在本地运行的vscode基本没什么大区别，比起使用其他的网页端编辑器，vscode.dev能以更快的速度上手。因此，它的其他方面的功能也因为这一点变得无比好使

- ##### 可直接打开本地文件/文件夹（仅电脑端）

这个…也需要说一点吧，并不是大部分网页端编辑器都有这个功能，放到vscode.dev上也不知道为啥，就变得巨好无比…

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/54.png)

实测打开是完全没有问题的，不过打开只适用于电脑端。如果你是ipad，那只能上传。

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/55.png)

同时，你也可以打开github上的repo

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/56.png)

这个打开目前只能打开自己账号里的repo，这个应该都知道的。

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/57.png)

打开后也是没有问题，可以正常使用的

- ##### Source Control

非常令人惊喜，vscode.dev也可以使用Source Control。不过如果你是本地打开文件夹的，这个功能将不能使用，毕竟vscode.dev只是一个网页端的代码编辑器；不过如果你是打开github上的repo，那是可以使用的。（也仅限github）

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/58.png)

同步也和一般的vscode无两样

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/59.png)
<center>ohhhhh yes</center>

- ##### 插件！（ohhhh重头戏）

在vscode.dev中，可以使用部分原来vscode的插件（注意是部分！后面我会讲）

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/60.png)

这极大地赋予了vscode.dev的可玩性。同时也令人大为惊奇。vscode团队的这波操作啊，很好很强

- ##### 可以连接github codespaces

这点都也要归功于它的插件市场。不过这个是直接预装在vscode.dev里的。同时它的github插件也是一样，都被预装在了vscode.dev里。

当然codespaces我并不能体验一波。因为我codepsace的申请从去年到现在就一直没有通过……官方给出的说法是这个codespace的体验人数是分批的，叫我继续等待……

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/65.png)

此外，还有很多地方，同普通的vscode一样。在实际编码过程中（也只是编码），同普通的vscode是一模一样的。

当然，这也只是可玩性

- ## 不及之缺点

由于它是一个网页端的代码编辑器，也只是一个网页端的代码编辑器，**它不是一个云端IDE，它完完全全地在浏览器中运行**，在实际体验中会有很多很多的限制，无法与普通的vscode相比。如果论实用性的话，vscode.dev完爆。与它拥有同类UI（一个模子里刻出来的）云端IDE有[cloud studio](https://cloudstudio.net/)和[code-server](https://github.com/cdr/code-server)。cloud studio是腾讯云coding搞得，很不错，终端还是默认oh-my-zsh，他们宣传也做得很好，看上去非常诱人。就是免费使用空间只能用四个小时，老腾讯了😓code-server不用多说，没啥毛病，用就完了。

说到终端，就提到了vscode.dev的第一个缺点

- ##### 无终端之苦

这点很容易理解，由于vscode.dev完全在浏览器中运行，所以它是没有终端的。用vscode.dev文档里的话来说就是“这是有道理的”。

……

🤣

oh，没有终端的vscode就少了灵魂~

这点在vscode.dev的文档中也有写到

- ##### 支持的插件太少

很简单，也是由于它就是一个网页端代码编辑器的原因，它支持的插件非常少……

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/61.png)

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/62.png)

连C/C++的插件都没有支持，是不是血压立马就上去了？

- ##### 语言方面问题

vscode所有的语言支持都是依靠插件实现的，这在vscode.dev上也因此造成了一个比较尴尬的问题

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/63.png)

除了英语之外，你不能更换任何语言。同时这也不仅仅是啥插件的原因，在命令菜单里连Configure Display Language选项也没有…

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/64.png)

这可能对于部分时候会有略微的使用上的困难

- ##### 不可调试运行

这一缺陷直接导致了vscode.dev生产力的大幅度丧失。道理都懂……

不过非常神奇的是，vscode团队还是给它加上了Run and Debug选项？！（就蛮迷惑的）

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/66.png)

下面那个按钮指向的是本地的vscode……就无语……

- ## 所以说，vscode.dev到底有什么用？

我对于vscode.dev的评价就是：**可玩性极大，生产力很低。但是不能说它没有什么大用处。在一些情况下，vscode.dev能很轻量化地完成你的需求**。比如说你可以想象一个场景：你在外头游玩，或者在交通工具上，这时你的一个项目有了一点小问题，你可以用你的ipad直接打开vscode.dev，修改、提交，一气呵成。这样子使用还是蛮好的，可以避免把时间浪费在打开电脑、打开IDE上面。所以说这个东西对于小修小改还是蛮有帮助的，非常地轻量、非常地快。再比如说，你可以把它当作一个轻量的markdown编辑器用来记笔记。

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/67.png)

它的最大优点也同时表现在其他设备上。vscode.dev的文档特别地提到了在chromebook和ipad上使用vscode.dev。

>- 在 Chromebook 等低功率机器上编辑您的代码，您无法（轻松）安装 VS Code。
<br />
>- 在 iPad 上开发。您可以上传/下载文件（甚至使用 Files 应用程序将它们存储在云中），以及使用内置的 GitHub 存储库扩展远程打开存储库。

所以说，vscode.dev在这一点来上讲是非常优秀的。随着ipad os以及全新ipad的推出，ipad变得更加可用，变得更加可生产。一个ipad，配上一个键盘，再配上一个鼠标，简直就是一台小型电脑。vscode.dev的出现，使得在ipad上编写代码变得更加零门槛。

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/68.PNG)
<center>这里的“code”是我把vscode.dev添加到主界面（safari）</center>
<br />

![](https://cdn.jsdelivr.net/gh/leaf2006/image/img/69.PNG)

但是，即使它能在ipad上编写代码，它真的很实用吗？

- ## 对于vscode.dev的思考

vscode.dev无疑是vscode团队的一次脑洞大开的设计，也使得很多人心目中的所想变成现实。但是如果想要把它变成一个生产力的工具，那要付出的代价则是巨大的。它在目前看来，只适合轻量化的修改。有些人使用这个可能是因为，vscode.dev在ipad上适配非常好。但是如果我告诉你，cloud studio和code-server的体验会比vscode.dev好上几千倍，几万倍，有终端有git，你又会作何感想呢？

目前上来看，vscode.dev因为它的设计，阻止了它的地位。

我并不是对于vscode.dev做出完全贬义的态度，它作为一个轻量化的修改工具，亦或是作为一个markdown笔记编辑器，它是好样的；但是更多的人也许不需要这套东西来解决需求，加上它至始至终都欠缺的生产力，它的用途、地位也变得异常尴尬。

不过我对于vscode.dev的前途并不悲观，从vscode.dev的文档中，团队承诺，将在vscode.dev中支持更多的插件，证明在将来，vscode.dev将会接受更多的维护与更新。未来的vscode.dev，一定会发展的越来越好！

我在那个时代等它。

- ## 结束语

>“法拉第先生，这东西有什么作用呢？”
<br />
“夫人，一个刚刚出生的婴儿有什么作用呢？”