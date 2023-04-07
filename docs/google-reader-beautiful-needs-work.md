# 谷歌阅读器——漂亮，需要改进——TechCrunch

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2005/10/08/google-reader-beautiful-needs-work/>

谷歌[昨天在 Web2.0 上发布了](https://web.archive.org/web/20211017182310/http://www.google.com/press/annc/reader_launch.html)一款基于网络的 [ajax RSS 阅读器](https://web.archive.org/web/20211017182310/http://www.google.com/reader)。

不像 Bloglines 使用框架来避免页面刷新，Google Reader 使用 Ajax。这款阅读器在视觉上令人惊叹，乍一看似乎是一个竞争者。然而，在进一步审查后，我们发现了一些我们认为是严重的结构缺陷。

阅读器加载速度很快，并使用您存储的 gmail 凭据让您登录。通过 opml upload(我们这样做了)或使用搜索栏添加提要相当容易。添加提要时，您可以选择添加标签(称为“标签”)。单个帖子列在左边，点击一个帖子会在右边的查看框中显示内容。

谷歌阅读器实际上是谷歌的第二个 RSS 阅读器。参见 Google IG ，它是 Google 在 7 月下旬发布的。与 Google IG 不同，它的目标用户是只阅读少量提要的轻度 RSS 用户，他们的新阅读器针对的是那些希望快速浏览大量提要的用户。

## 谷歌阅读器做得好的地方

有很多积极的方面。

读者可以非常有效地使用 ajax 来避免页面刷新，并创建一个很好的视觉体验。

订阅源可以被标记，单个帖子可以保持未读并标上星号。

搜索功能非常出色，添加提要不需要 RSS、opml 或 XML 知识。都是自动的。搜索只显示你没有订阅的订阅源。

## 谷歌阅读器做错了什么

正如我上面提到的，Google Reader 的目标是重度 RSS 读者。然而，这个产品对于有效地浏览大量的提要并没有用。

文章是按照“相关性”(实际上似乎没有以任何相关的方式排序)或日期排列的。我需要在个人博客下对帖子进行分组，因为我会先阅读一些提要——谷歌阅读器不允许我这样做，我很难找到我最喜欢阅读的作者。在已经订阅的提要中没有搜索功能，所以没有办法找到这些内容。

读者反应迟钝。向下翻页会导致长时间的不可接受的延迟。顺便说一下，导入我的 OPML 列表需要大约 10 分钟。因为这是一次性成本，没什么大不了的。

因为这只是一个基于网络的阅读器，所以没有同步。

Google 用 ajax 代替框架。虽然框架是一项古老的技术，但使用它的阅读器允许多个滚动条-这意味着你可以在滚动单个帖子时保持提要框架锁定。这需要解决。

订阅源没有退订按钮。

谷歌阅读器针对火狐浏览器进行了优化。它还不能在其他浏览器上正常工作。

## 摘要

许多功能限制可以得到解决，但如果谷歌阅读器要严重威胁现有的重型 RSS 阅读器，它还有很长的路要走。布拉德·希尔也发表了一篇关于谷歌阅读器的长篇评论。