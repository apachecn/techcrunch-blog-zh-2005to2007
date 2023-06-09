# 帮助关键:抓住 802.11n 暴跌

> 原文：<https://web.archive.org/web/http://techcrunch.com/2007/05/21/help-key-taking-the-80211n-plunge/>

# 帮助关键:采取 802.11n 暴跌

![indexrange_20070109.png](img/c973a2fa54ae7a2e252d8c95694d998b.png)
实际结果可能会有所不同

802.11g 似乎就发生在昨天。今天，802.11g 是事实上的标准和 n，它理想地提供 242 Mbps，但实际上提供大约 50 Mbps。802.11n 还拥有更大的范围和更高的服务质量，这是家庭视频和音频流媒体所喜欢的。但是黄金时间准备好了吗？

为了测试当前的 802.11n 设备，我安装了一个苹果 Airport Extreme、 [Buffalo Wireless-N Nfiniti 基站](https://web.archive.org/web/20210307083934/http://www.buffalotech.com/products/wireless/wireless-n-nfiniti-dual-band/)和一个 Buffalo Nfiniti PC 卡。我试用了一些设备，包括诺基亚 770 网络平板电脑、支持 wi-fi 的手机、无线 TiVo 适配器、Apple TV 和一个旧的 Linksys 无线网桥，我已经用了大约两年时间来连接我的地下室机器和楼上的电缆调制解调器。因为我在 CG 总部没有合适的测试设施，甚至没有合适的测量范围测试系统，所以我不会在这篇文章中添加正式的统计数据。你可以在网上的多个网站上找到这些，但是相信我——作为一家[笔记本电脑杂志](https://web.archive.org/web/20210307083934/http://laptopmag.com/Review/Buffalo-N-Nfiniti-Dual-Band-Router-AP-WZR-AG300NH.htm)的前技术编辑，大多数路由器和其他设备的统计分析都充满了错误和/或干扰。没有人在他们的测试实验室里有法拉第笼，也许除了 PC 杂志。但是他们用这个来保存所有被解雇的记者和分析师的记录。但是我跑题了。

我最喜欢的网络内测试工具是 [iPerf](https://web.archive.org/web/20210307083934/http://dast.nlanr.net/Projects/Iperf/#whatis) ，这是一个完全跨平台的基于客户机/服务器的性能工具。如果你想测试计算机之间的速度——本质上是测试你的网络速度，它是最好的工具之一。

我可以说，在我的纯 802.11g 网络上，我看到的吞吐量约为 20-30 Mbps。这取决于我有多少设备连接到网络和我们的婴儿监视器的状态。例如，我今天的内部网络速度约为 10 Mbps，而由于电缆调制解调器的问题，我与外部世界的速度约为 5 kpbs，这给了我一个“哇，我的网络今天糟透了”的有效速度

当我安装 N gear 时，我知道我会遇到类似的问题。我用 Airport Extreme 基站替换了我的主 G 路由器，并使用 Nfiniti 路由器桥接了我的 Mac Pro。我拔掉了所有的无线 G 和 B 设备，并将 PC 卡连接到 Windows XP 笔记本电脑上。内部网络读大约 80 Mbps，一个相当不错的速度，从各方面考虑，比 G 网络有很大的改进。

然而，混合 G 网络是一个完全不同的故事。由于安全性、接收和驱动程序的不可预测性，混合网络在 N 个设备之间下降到大约 50 Mbps，在 G 个设备之间达到大约 20 Mbps。要点是:如果你需要在一个封闭的环境中使用相似的硬件获得最高的无线速度，802.11n 就是你要的。如果你运行的是混合网络，通过增加而不是立即升级来获得 802.11n。你可以在这里得到一块 PC 卡，在那里得到一个路由器，直到你的整个网络都是基于 N 的。否则，速度的提升可以忽略不计。

**快速提示**

*   不要期待奇迹，这是一个不完美的世界。用一句话来说，在电磁真空中，你会看到真正的 200 Mbps 速度。在现实世界中，速度增益会在超慢和相当快的速度之间波动。*   内部网=快，互联网=慢–添加您想要的所有 802.11n 设备。你的网页浏览将会得到微不足道的改善。正如我今天的经历所证明的，如果你的提供商给你发送的是涓涓细流，即使是最快的路由器也帮不了你。*   不要现在就购买——如果你必须升级你的网络，选择便宜的，而不是无线网络。802.11g 是一项成熟的技术，目前几乎不需要任何成本。802.11n 设备相当昂贵，并且仍处于草案阶段。这并不意味着 802.11n 设备“不工作”这意味着这里或那里可能会有固件更新，这可能会导致一些设备不兼容。这是极不可能的，但谁知道呢。*   新设备更好——总体而言，新的无线设备比旧的无线设备更好。使用旧设备创建混合网络可能会带来更多麻烦，超出您的需求。明智地选择您的硬件。例如，Airport Extreme 的一些安全设置会混淆旧硬件。结果是一个无用设备的混合网络，而不是你想要处理的东西。