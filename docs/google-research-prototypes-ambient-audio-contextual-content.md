# 谷歌研究原型环境音频上下文内容 

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2006/06/08/google-research-prototypes-ambient-audio-contextual-content/>

# 谷歌研究原型环境音频上下文内容

 [](https://web.archive.org/web/20220818162927/http://googleresearch.blogspot.com/) 来自[谷歌研究](https://web.archive.org/web/20220818162927/http://googleresearch.blogspot.com/)的一个团队开发了一个原型系统，该系统使用家用电脑的内置麦克风来收听房间内的环境音频，确定正在观看的电视节目，并提供与正在观看的每个节目相关的基于网络的补充信息、服务和购物。这很奇怪，但听起来很有效，人们可能真的会喜欢它。目前还没有迹象表明这是否或何时可以作为一项服务提供。

上周，谷歌研究团队成员米歇尔·科韦尔、舒米特·巴卢贾以及耶路撒冷希伯来大学神经计算中心的迈克尔·芬克因其在欧洲互动电视会议上关于该系统的报告获得了最佳论文奖。([“基于实时环境音频识别的社交和互动电视应用”](https://web.archive.org/web/20220818162927/http://www.mangolassi.org/covell/pubs/euroITV-2006.pdf) 10 pg PDF，参见论文上的[谷歌研究博客文章](https://web.archive.org/web/20220818162927/http://googleresearch.blogspot.com/2006/06/interactive-tv-conference-and-best.html#links)。)

系统将捕获的音频压缩成*不可逆的*(强调他们的)摘要统计数据，然后与大众媒体统计数据的数据库进行比较，并用于确定浏览器应该显示什么。本白皮书中讨论的可能服务分为四类:

*   **个性化信息层**这里是汤姆·克鲁斯在你正在观看的节目中穿的衣服，这里是你可以在你的邮政编码购买同样衣服的地方。
*   如果你想聊聊这部剧，你的十个大学朋友现在也在看。
*   **实时人气评级**尼尔森需要硬件，结果无法实时获得。你可能想知道现在看 9 频道节目的观众人数是否会激增。广告商可能也想知道。
*   **基于电视的书签**点击将一个节目或剪辑保存到您的视频库中，以后将有更多节目可供观看。

研究人员报告说，该系统不需要专用的电视连接硬件，保护了用户的隐私，在技术上是可行的。将笔记本电脑放在离电视机 10 英尺远的人的腿上，并与旁边的人大声交谈的实验成功地提供了匹配的在线内容——如果考虑频道冲浪的话。

为了避免你担心所有的广播电视都是一个巨大的数据集，该报告称，ff 摘要数据库只保存了 5 秒钟的 32 位描述符，那么长达一年的广播信息可能会保存在不到 1 GB 的空间内。研究人员报告说，通过重新运行，这变得更加可行。

在原型中解决了隐私问题，在将摘要数据传输到数据库进行比较之前，在用户的计算机上压缩捕获的音频，并在程序中提供静音按钮。鉴于谷歌最近的道德问题，这些隐私措施可能不足以安抚一些人。

![](img/b63b14374adf62f77c731aa1fea2b776.png)