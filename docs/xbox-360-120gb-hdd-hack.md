# Xbox 360 120GB 硬盘黑客| TechCrunch

> 原文：<https://web.archive.org/web/http://techcrunch.com:80/2007/04/23/xbox-360-120gb-hdd-hack/>

自 360 发布以来，Xbox 360 的 120GB 硬盘的发布是我们(粉丝们)一直在等待的。但是 179 美元对于一个我们能以更低的价格购买的硬盘来说太贵了。唉，互联网让我看到了光明，有一个黑客可以为我心爱的 Xbox 360 添加一个便宜得多的 120GB 硬盘，西部数据天蝎座 BEVS-LAT SATA 2.5 英寸 PC/笔记本电脑。

此外，我想强调的是，有两个版本的 WD BEVS 硬盘:RST 和拉特版本。该工具目前仅支持“LAT”版本！你可以在硬盘的标签上找到它的版本。我希望在这个工具的未来版本中能够支持 RST 版本的驱动器。

> 来自官方自述:
> 
> 专家的 Hddhacker v0.90。
> 
> *免责声明:
> 这个工具只有我测试过。对我很有效。虽然已经非常小心，这个工具可能包含错误，因此可能会严重损害您的硬盘。使用风险自担！！！
> 
> *内容:该工具允许您使用未经微软“认证”的硬盘。该特定工具仅适用于 Western Digital BEVS 系列！
> 
> *使用方法:给自己买一个西部数据 SATA BEVS 硬盘。要使用此工具，您需要一个硬盘安全扇区文件(' hddss.bin ')。如果你没有，下面是如何从一个有效的 xbox 360 硬盘创建一个:
> –将 hddss.bin 文件
> 从可写介质(如软盘)转储到 dos。将*原装* xbox 360 硬盘连接到您的 SATA 控制器。确保它是唯一连接的 SATA 设备。现在运行' hddhackr -d '。这将创建一个文件“hddss.bin ”,并将其保存到启动 hddhackr 的路径。
> –修改您的 Western Digital
> 现在关闭您的电脑，连接 Western Digital 并再次启动 dos。
> 从保存 hddss.bin 文件的同一路径键入“hddhackr -f”。这将使你的简历闪光。它会询问你是否想要创建一个撤销文件。建议这样做。这将创建一个“undo.bin”文件，如果你想撤销黑客攻击，你需要这个文件。
> –检查它是否工作
> 关闭您的电脑，重新启动至 dos，并再次键入‘HDD hackr-f’。它现在应该会告诉您，该驱动器应该可以在 x360 上工作。如果是这样，将其连接到 x360，然后转到您的仪表板/系统/内存，在那里您应该能够格式化驱动器。
> –将您的 WD 恢复到原始状态
> 如果您不想再在 x360 中使用您的调制 WD，并且您想将其刷新回原始大小，那么您现在可以这样做。再次引导至 dos 并运行‘HDD hackr-u’。这将使用您之前创建的 undo.bin 文件将驱动器恢复到其原始状态。
> 
> 常见问题:
> 问:当我试图从 120 gb 硬盘转储 hddss.bin 时，我收到一个错误。
> 答:这个版本还不能从 elite drive 转储。您必须使用 winhex 之类的工具手动转储扇区 16-22，将它们保存为“hddss.bin ”,然后像平常一样继续使用 hddhackr。
> 
> 问:这个工具允许我将 500 gb 的硬盘连接到我的 x360 吗？
> 答:不可以。16 区的信息已经签名，不能更改。您只能在拥有有效签名的情况下使用 size。换句话说，如果有更大的硬盘问世，你可以使用那个签名。
> 
> 问:这适用于哪种硬盘？
> 答:它目前仅适用于 Western Digital Scorpio BEVS 系列的“LAT”版本。目前不支持该驱动程序的“RST”版本
> 
> 问:我是否需要与扇区 16 上的硬盘大小相同的硬盘？
> 答:不可以。你可以使用更大的硬盘，但不能超过 16 区规定的容量。你不能使用比扇区 16 更小的硬盘。例如，您可以将一个 40 GB 的硬盘与一个 20 GB 的硬盘的扇区 16 一起使用，但当然不能反过来使用。
> 
> 问:我可以再次使用电脑中的硬盘吗？
> 答:当然。该工具带有一个“撤消”选项，可以恢复原始大小。例如，您使用一个 40 gb 的 WD 硬盘，您使用了有效的 xbox 20 gb 硬盘中的 hddss.bin，因此该工具会将您的 40 GB 硬盘转换为 20 gb 硬盘。但是，您可以随时使用撤销选项将其恢复到 40 gb。
> 
> 问:我有一个 x360 核心版本，想用这个黑客购买一个便宜的硬盘。但是我怎么连接呢？
> 答:如果您没有额外费用，可以将硬盘内置。一个很棒的教程将告诉你如何在这里做到这一点。
> 
> 问:该工具无法检测我的硬盘！
> 答:首先，确保你是在 dos 下运行，而不是在 windows 下的 dos 下运行。如果硬盘不自动检测您的 SATA 控制器(例如，如果您有一个 nForce 芯片组)，那么您可以手动编辑硬盘以支持它。为此:
> 
> 1.找到您的 SATA 芯片组用于数据通信的两个端口(有关如何进行此操作的更多详细信息，请参见 MTKediting 线程)，基本上，您需要运行“msinfo32”，然后转到 storage/scsi 或 storage/ide，这取决于您的 SATA 芯片组，然后查找两个端口之间相差 7。例如:
> I/O 口 0x0000EFE0-0x0000EFE7
> I/O 口 0x0000EFAC-0x0000EFAF
> I/O 口 0x0000EFA0-0x0000EFA7
> I/O 口 0x0000EFA8-0x0000EFAB
> I/O 口 0x 0000 ef90-0x 000 ef9 f
> I/O 口 0x 0000 e800-0x 000 E8 ff
> 
> 在本例中，您正在寻找的两个端口(差异为 7)是 0xEFE0 和 0xEFA0
> 2。在 hexeditor 中打开 hddhackr.com，搜索字符串“port=MPRT”(在文件的末尾)。现在，这个“MPRT”字符串有 4 个字节长:0x4D 0x50 0x52 0x54。您必须用 2 个端口号替换这 4 个字节(每个端口号都是 2 个字节长，因此您总共替换了 4 个字节)，因此在上面的示例中，您用“0xEF 0xE0 0xEF 0xA0”替换这 4 个字节。
> 3。如果您随后启动 hddhackr，它将自动检测到您编辑了该字符串，因此它将跳过 SATA 自动检测器，而使用您提供的端口号。
> 
> 问:你能为我的希捷、迈拓、三星或其他驱动做这件事吗？是的，但是我不打算这么做。最便宜的 WD 驱动器(40 gb)售价约为 50 美元，因此是最便宜的驱动器之一。将这个工具转换成其他品牌的工具需要做很多工作，我认为不值得这么麻烦。
> 
> 问:如何确定我的 BEVS 硬盘是否是“LAT”硬盘？
> 答:它印在驱动器标签上的型号名称中。例如:WD1200BEVS-60LAT0
> 
> 问:未来会支持 RST 运动吗？
> 答:我希望很快收到一个 RST 驱动，然后希望能找出问题所在，并在该工具的未来版本中支持它。
> 
> 问:我可以在哪里捐赠？
> 答:无处可去。尽情享受吧
> 
> 感谢:MODFREAKz 团队最初的逻辑板实验，Loser 团队在第 16 区的发现，Antman1 和 Rutger1413 提供关于新的 120 gb 签名的信息，以及 XS/XBH 的所有人。
> TS 2007 年 4 月