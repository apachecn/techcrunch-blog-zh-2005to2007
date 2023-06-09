# OpenDNS 想帮你看网络

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2006/07/18/opendns-wants-to-watch-the-web-for-you/>

# OpenDNS 想帮你看网页

 [](https://web.archive.org/web/20220818083047/http://www.opendns.com/) [OpenDNS](https://web.archive.org/web/20220818083047/http://www.opendns.com/) 是一家新成立的公司，它希望用户通过其 DNS 域名服务器重定向网络流量，其中一个异常大的缓存和一个被认为犯有网络钓鱼罪的网站的汇总列表将使我们的网上冲浪更快更安全。这是免费的，就像把你的 DNS 地址从你的 ISP 换成 OpenDNS 一样简单，但是已经有人对这项服务表示了严重的担忧。

这家旧金山公司由首席执行官 David Ulevitch 和前 CNet 产品开发和业务运营负责人 John Roberts 领导。它由 CNET 创始人哈尔西·米诺的基金 Minor Ventures 资助。收入模式是当用户输入拼写错误或无法识别的网址时，在搜索页面上做广告。该公司表示，除了增强的 DNS 服务之外，它还将提供额外的服务——可疑用户可能想在使用 OpenDNS 之前知道这些服务是什么。

该公司有两个主要卖点。第一个是它的网络钓鱼过滤器，这是一个由许多不同来源聚合的恶意网站列表，当试图通过 OpenDNS 访问时会被阻止。第二个是更快的页面加载速度，因为该公司的服务器布局合理，域名缓存容量大，可以比其他服务器更快地解析 DNS 查询，该公司表示，这些服务器必须经常向多个位置发送请求才能解析查询。

OpenDNS 还说它“更聪明”，因为它将理解拼写错误的 URL，我知道我很少经历这种情况，并且完全有能力照顾好自己。事实上，相对于他们必须进行的基础设施投资，当拼写错误发生时提供广告是该公司的商业模式，这在我看来是疯狂的。

这项服务已经受到了博客作者的严厉批评，他们声称这项服务从最终用户那里拿走了太多的控制权，容易被恶意方玩游戏，并且声称其卓越的速度是不现实的。一些人还警告说，集中 DNS 服务会给一方太多的权力。该公司的回应是允许用户关闭钓鱼阻止和拼写纠正功能——尽管如果有人打算关闭大部分功能但保留该服务，速度的提高必须能够很好地扩展并保持实质性。

在我看来，如果一个网络用户能够改变他们的 DNS 设置，那么他们应该有足够的能力来避免网络钓鱼的企图。

可以与之相比的一个网站是被迈克菲收购的 [SiteAdvisor](https://web.archive.org/web/20220818083047/http://www.siteadvisor.com/) 。这种服务主动出去并在网站上注册，下载网站提供的任何内容，并对所有内容进行恶意软件测试。太酷了。SiteAdvisor 似乎只是在恶意网站的搜索结果旁边添加了一个标记，而不是像 OpenDNS 那样从任何入口点阻止它们，但幕后实际发生的事情对我来说更有趣。也许 OpenDNS 网站列表的来源也在做类似的事情，但让 DNS 成为对抗恶意网站的切入点似乎是一个有问题的策略。

我不确定让用户通过一个集中的过滤器来重定向他们的 DNS 查询是否能够足够快地发生，以适应与反社会的在线奸商的快节奏军备竞赛。或许该公司希望 ISP 将他们的 DNS 服务外包给 OpenDNS，为客户提供更安全、更快捷的在线体验，摆脱糟糕拼写的困扰。

OpenDNS 肯定已经对其基础设施进行了大量投资，因此可能会有一些战略愿景出现。就目前的情况来看，我无法想象这会奏效。

对于不同的观点，请看[克里斯·皮里洛](https://web.archive.org/web/20220818083047/http://chris.pirillo.com/2006/07/18/boost-your-internet-speed-free/)、[马特·莫楞威格](https://web.archive.org/web/20220818083047/http://photomatt.net/2006/07/18/opendns/)和[斯科特·比厄](https://web.archive.org/web/20220818083047/http://laughingsquid.com/2006/07/18/opendns/)的正面评论。