<p align="center">
  <a href="https://heao.ai-hao123.com/liuliang/marketing-25729600.html"><img src="docs/media/banner-zh-CN.jpg" alt="Filee 拖一下，放一下，转好了。" width="100%"></a>
</p>

<p align="center">
  <b>用拖放操作的免费开源文件格式转换器。</b><br>
  按住一个键（<kbd>Ctrl</kbd>，macOS 为 <kbd>Option</kbd>）拖动文件，光标处会弹出格式圆环，放到想要的格式上即可。
</p>

<p align="center">
  <a href="https://bbhn.ai-hao123.com/jishu/story-83695768.html"><b>官网</b></a> ·
  <a href="https://knfc.wtpuscm.cn/jiaocheng/roi-224312.html"><b>下载</b></a> ·
  <a href="https://chzh.yx-sf.com/xinwen/lead-11868436.html"><b>LinkedIn</b></a> ·
  <a href="#安装">安装</a> ·
  <a href="#命令行">命令行</a> ·
  <a href="#开发">开发</a>
</p>

<p align="center">
  <a href="https://bbhn.ai-hao123.com/jishu/story-83695768.html"><img src="https://github.com/KnifeLemon/Filee/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://djcz.wtpuscm.cn/gongsi/study-981499.html"><img src="https://img.shields.io/github/v/release/KnifeLemon/Filee?color=7F77DD&label=release" alt="最新版本"></a>
  <a href="https://cand.wtpuscm.cn/xinwen/accessibility-146226.html"><img src="https://img.shields.io/github/downloads/KnifeLemon/Filee/total?color=1D9E75" alt="下载次数"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-3C3489" alt="Windows 10 | 11">
  <img src="https://img.shields.io/badge/Linux-x64%20%7C%20ARM64-3C3489" alt="Linux x64 | ARM64">
  <img src="https://img.shields.io/badge/macOS-preview-534AB7" alt="macOS 预览版">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-6A62C9" alt="MIT 许可证"></a>
</p>

<p align="center">
  <a href="https://ozcn.wtpuscm.cn/kaifa/progress-329616.html"><img src="https://trendshift.io/api/badge/trendshift/repositories/276987/weekly?language=C%23&v=2" alt="Filee: #1 C# repository of the week on Trendshift" width="250" height="55"></a>
  <a href="https://bgvd.ai-hao123.com/paiming/experience-27775705.html"><img src="https://trendshift.io/api/badge/trendshift/repositories/276987/daily?language=C%23&v=2" alt="Filee: #1 C# repository of the day on Trendshift" width="250" height="55"></a>
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.es.md">Español</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a> ·
  <b>简体中文</b> ·
  <a href="README.zh-TW.md">繁體中文</a> ·
  <a href="README.pl.md">Polski</a> ·
  <a href="README.hi.md">हिन्दी</a> ·
  <a href="README.ru.md">Русский</a> ·
  <a href="README.ar.md">العربية</a> ·
  <a href="README.pt-BR.md">Português (Brasil)</a> ·
  <a href="README.pt-PT.md">Português (Portugal)</a> ·
  <a href="README.fr.md">Français</a> ·
  <a href="README.th.md">ไทย</a>
</p>

<table>
  <tr>
    <td width="33%" valign="top">
      <b>就在光标旁</b><br>
      无需打开应用窗口。
      只显示适合当前拖动文件的格式，就在你所在的位置。
    </td>
    <td width="33%" valign="top">
      <b>266 种格式，无需其他软件</b><br>
      图片、PDF、Word、Excel、PowerPoint、HWP、电子书、压缩包、字体、CAD、3D 模型和地理信息数据，无需 Office、韩文办公软件或 LibreOffice。
    </td>
    <td width="33%" valign="top">
      <b>只在你的电脑上</b><br>
      不上传任何文件。
      Filee 离线工作，结果保存在原文件旁边。
    </td>
  </tr>
</table>

## 实际效果

<p align="center">
  <a href="https://btaf.tcti.cn/guanjianci/forecast-14271639.html"><img src="docs/media/demo-zh-CN.webp" alt="按住 Ctrl 拖动 旅行.jpg，光标处弹出格式圆环，放到 PNG 上，进度环走完后生成 旅行.png" width="820"></a><br>
  <sub>27 秒视频和可交互演示请访问 <a href="https://www.ebrkdiy.cn/keji/ai-52559593.html">filee.sh</a></sub>
</p>

## 安装

从 [Releases](https://hijx.ai-hao123.com/jishu/traffic-61118811.html) 下载。

- **Windows 10/11** 运行 `Filee-<version>-win-Setup.exe`，或解压 `win-Portable.zip` 后运行 `Filee.exe`。
  - 安装程序是 Filee 自己的，使用与 Filee 相同的语言，电脑上无需另外安装任何组件。
  - 安装时可以添加资源管理器菜单、登录时启动、`filee` 命令和可选引擎。
  - 静默安装沿用 Inno Setup 的参数（`/VERYSILENT /SUPPRESSMSGBOXES`）。
- **macOS 13 及以上**（预览）解压 `osx-arm64` 或 `osx-x64` 包并运行 `./install.sh`。
  - 也可以打开 `.dmg`，把 Filee 拖到“应用程序”文件夹（`filee` 命令只由 `install.sh` 添加）。
  - 目前尚未公证，首次启动时请在系统设置 → 隐私与安全性中点 **仍要打开**。
- **Linux x64、ARM64**（Ubuntu 22.04 及以上）解压后运行 `./install.sh`（无需 root，需要 Python 3）。
  - 拖动手势需要 X11，Wayland 下请使用拖放区域和文件管理器的右键菜单。

有新版本时 Filee 会在菜单中提示，更新时保留设置和引擎。
更新后会用几张幻灯片介绍新功能。

**Windows：Filee 无法启动（没有窗口也没有报错）？**
这种情况发生在长期未更新的 Windows 10 上，且电脑的处理器支持“硬件强制堆栈保护”（CET）。
Windows 会开启这项保护，却缺少 .NET 需要的一项功能，于是 Filee 和安装程序会立即退出。

- **推荐**：安装 Windows 更新中可用的更新（最新的累积更新）。
- **无法更新时**：通常只对 Filee 关闭这项保护就能启动。
  以管理员身份打开 PowerShell 并运行：

```powershell
Set-ProcessMitigation -Name Filee.exe -Disable UserShadowStack
Set-ProcessMitigation -Name filee-cli.exe -Disable UserShadowStack
```

安装程序也运行同样的命令，换成它的文件名（例如 `Filee-<version>-win-Setup.exe`）；使用便携版 ZIP 则只需上面两行。
要撤销，请在“Windows 安全中心 → 应用和浏览器控制 → Exploit Protection 设置 → 程序设置”中删除这些条目。

## 功能

- **光标旁的圆环**，按住按键拖动文件，放到格式上即可。
  只显示适合这些文件的格式。
- **直接从浏览器拖**，Chrome、Edge、Firefox 或 Safari 里的图片、文件链接和下载项也能这样拖放。
  - Filee 会保存到“下载”文件夹（也可以只保留转换后的文件）再转换。
  - 链接下载时不使用浏览器的登录信息。
- **每种文件类型一个工具栏**，拖放排列。
  下列项目都能用预设设置：
  - 质量、尺寸、DPI
  - PDF 页面和压缩
  - 视频音频
  - 保存位置和文件名
- **圆环有背面**，圆环打开时按 <kbd>Tab</kbd> 或转动鼠标滚轮翻过来，背面是不常用的格式和工具。
- **转换前先裁剪**，“裁剪”会逐张打开图片。
  拖动选框、选择比例，只保存选中的部分。
- **一次转换多个文件**，并行处理。
  需要多步的转换（HWP → HWPX → DOCX）会自动找到路线。
- **监视文件夹**，放入的文件自动转换。
- **最近的转换**显示在主页上，每项都有缩略图，可以直接“打开文件”，也可以用“打开方式”换个应用打开。
- **其他方式** 右键菜单、键盘快捷键、拖放区域和 [`filee` 命令](#命令行)。
- 浅色和深色主题，可自选强调色和环形工具栏不透明度，支持 English、Español、日本語、한국어、简体中文、繁體中文、Polski、हिन्दी、Русский、العربية（从右到左）、Português (Brasil)、Français、नेपाली、ไทย、Türkçe、Português (Portugal)、Deutsch。

## 截图

<table>
  <tr>
    <td width="50%"><img src="docs/media/page-toolbar-zh-CN.png" alt="用配置文件和预设编辑圆环工具栏"></td>
    <td width="50%"><img src="docs/media/page-home-zh-CN.png" alt="带拖放区和最近转换记录的主页"></td>
  </tr>
  <tr>
    <td align="center"><sub>拖放排列圆环，每种文件类型一个配置</sub></td>
    <td align="center"><sub>主页上的拖放区和最近转换记录</sub></td>
  </tr>
</table>

## 支持格式

| 源格式 | 目标格式 |
|---|---|
| **图片** JPG、PNG、WEBP、AVIF、TIFF、BMP、GIF、APNG、ICO、ICNS、JPEG XL、JPEG 2000、PSD/PSB、TGA、PPM、HEIC、QOI、DDS、PCX、MNG、CUR 等，<br>GIMP XCF、相机 RAW（CR2、CR3、NEF、ARW、DNG 等）、DICOM、OpenEXR、HDR、FITS、JPEG XR（Windows）、iPhone 实况照片（LIVP）仅读取 | 上述格式互转（HEIC⁵）、PDF、SVG（描摹）、缩放、灰度，<br>实况/动态照片（iPhone、安卓）→ 其中的视频（MP4、MOV⁵），以及视频 → 实况照片（iPhone）或动态照片（安卓）⁵（实验功能） |
| **矢量图** SVG、SVGZ、EMF、WMF、AI<br>EPS、PS¹<br>CDR、VSD、CGM、ODG、FODG² | PDF（矢量）、PNG 等图片、<br>SVG ↔ SVGZ、SVG → DXF/DWG、PDF → EPS/PS¹、SVG → EMF、WMF、ODG² |
| **PDF** | DOCX、HWPX、TXT、PNG、JPG、TIFF、CBZ、PPTX（每页一张图片）、SVG²，<br>合并（先选择顺序）、拆分、页码范围、压缩（更小的 PDF） |
| **文档** DOCX、DOCM、DOTX、EML、Outlook MSG，<br>OFD（电子发票、公文）仅读取<br>DOC、ODT、FODT、OTT、RTF、WPS、WPD、Pages、ClarisWorks、MacWrite、T602 等² | PDF、DOCX、HWPX、EPUB、TXT、HTML、<br>MSG → EML<br>ODT、FODT、OTT² |
| **表格** XLSX、XLSM、XLS、XLT、ODS、CSV、TSV<br>OTS、FODS、Numbers、ET² | PDF、XLSX、ODS、CSV、TSV、JSON、HWPX、HTML<br>XLT、OTS² |
| **演示文稿** PPTX、PPTM、POTX、POTM、PPSX<br>PPT、ODP、OTP、FODP、Keynote² | PDF、PNG、JPG、DOCX、HWPX<br>OTP² |
| **HWP** HWP、HWPX | PDF、PNG、DOCX、HWPX ↔ HWP、TXT、Markdown、HTML |
| **文本** TXT、LOG、脚本源码（PY、PAC、BAT、COMMAND，只读取，从不运行）、Markdown、HTML，<br>MHTML（保存的网页）仅读取<br>reStructuredText、LaTeX、Org、AsciiDoc、Typst、MediaWiki、DocBook、Jupyter、Textile、man、OPML³ | UTF-8 TXT、PDF、DOCX、HWPX、EPUB<br>互相转换、PPTX 幻灯片³ |
| **电子书** EPUB、KEPUB、MOBI、AZW3、AZW、AZW4、FB2、CBZ、CBR、CB7、HTMLZ、TXTZ<br>LIT、LRF、CHM、PDB 等⁴ | PDF、EPUB、KEPUB（Kobo）、DOCX、TXT、HTML、HWPX<br>MOBI、AZW3⁴ |
| **视频**⁵ MP4、MOV、MKV、WEBM、AVI、WMV、FLV、MPEG、VCD（DAT）、TS、M2TS、3GP、OGV、VOB 等 | MP4（H.264、HEVC、AV1）、WEBM、MOV、MKV、AVI、GIF、APNG、MP3、M4A、720p、<br>字幕（SRT、ASS、WebVTT） |
| **音频**⁵ MP3、M4A、AAC、WAV、FLAC、OGG、OPUS、WMA、AIFF、AMR、APE、WavPack、TTA、DSD（DSF、DFF）、DTS、AC3、E-AC3 等 | MP3、M4A（AAC、ALAC）、WAV、FLAC、OGG、OPUS、AAC、WavPack、TTA、W64、AC3、E-AC3 |
| **字幕** SRT、ASS/SSA、WebVTT、SAMI（SMI）、LRC、TTML、MicroDVD、SCC | 互相转换，保存为 UTF-8（也能读取 CP949 韩文字幕） |
| **压缩包** ZIP、ANSYS Workbench（WBPZ）、7Z、RAR、TAR、TAR.GZ、TAR.BZ2、TAR.XZ、GZ、ISO、CAB、DMG、ALZ、EGG 等 | 解压、ZIP、7Z、TAR、TAR.GZ，<br>多个文件 → 一个 ZIP |
| **CAD** DWG、DXF | PDF、SVG、PNG、DWG ↔ DXF |
| **字体**：TTF、OTF、WOFF、WOFF2、EOT；<br>FON（Windows 位图字体）仅读取 | 相互转换；<br>FON → 每个尺寸一个文件 |
| **数据** JSON、JSON Lines、YAML、TOML、XML<br>vCard、iCalendar | 互相转换、CSV 和 XLSX（表格数据）、<br>vCard、iCalendar ↔ CSV |
| **3D 模型** GLB、glTF、STL、OBJ（+ MTL）、3MF、PLY，<br>FBX 仅读取 | 互相转换、PNG 预览 |
| **地理信息（矢量）** Shapefile、GeoJSON、KML、KMZ、GPX<br>带坐标的 CSV，<br>Garmin FIT 仅读取 | 互相转换、CSV / XLSX / JSON，<br>投影坐标系（UTM、Web 墨卡托、兰伯特、阿尔伯斯）会转换为 WGS 84 经纬度 |

未标注的格式装好即用，无需 Office、韩文办公软件或 LibreOffice。
标注的格式需要可选引擎，只在需要时下载，分别是 ¹ Ghostscript、² LibreOffice、³ Pandoc、⁴ calibre、⁵ FFmpeg（[详情](docs/ENGINES.md)）。

## 命令行

`filee` 命令使用与应用相同的引擎和预设（安装程序或 `install.sh` 会添加它）。

```
filee convert photo.heic --to jpg
filee convert *.png --to webp --quality 80 -o converted
filee watch D:\Inbox --to pdf --move-originals
```

全部命令和选项见 [filee.sh/zh-cn/cli](https://mcpu.yx-sf.com/hezuo/performance-71475112.html) 或 `filee help`。

## 开发

在 Windows、macOS 或 Linux 上使用 .NET 10 SDK 构建。

```bash
git clone https://github.com/KnifeLemon/Filee.git
cd Filee
pwsh build/fetch-engines.ps1 -Only rhwp,pandoc   # optional engines
dotnet run --project src/Filee.App
dotnet test
```

[架构](docs/ARCHITECTURE.md) · [引擎](docs/ENGINES.md) · [添加转换器](docs/ADDING-A-CONVERTER.md) · [添加语言](docs/ADDING-A-LANGUAGE.md) · [贡献指南](CONTRIBUTING.md)

欢迎提交 Pull Request。
如果 Filee 帮你省了时间，点个 ⭐ 能让更多人发现它。

## 代码签名政策

Filee 由 **Myeonggu Kim**（[KnifeLemon](https://yavi.ai-hao123.com/chuangxin/strategy-36799167.html)）开发和发布。

- Windows 版本使用颁发给 Myeonggu Kim 的 [Certum](https://xagg.yx-sf.com/fuwu/upload-62640915.html) 开源代码签名证书签名。
  - 2.0.0 及更早的版本没有签名。

详细政策和隐私政策见[英文 README](README.md#code-signing-policy)。
Filee 不会上传文件，也不会发送任何使用数据。

## 赞助

Filee 免费，并将一直免费。
想支持开发的话，选一种方便的方式即可（[Fairy](https://fgob.ai-hao123.com/xitong/cheap-19336642.html) 支持韩国银行卡和简易支付）。
谢谢！

**你的名字或标志可以出现在这里。**
按月赞助者的名字会列在这里，标志档位的标志会显示在这里和 Filee 的“关于”页面。
一次性赞助的朋友也可以要求列出名字。

<!-- sponsors: src/Filee.App/Assets/Sponsors/sponsors.json -->

<p align="center">
  <a href="https://cqea.yx-sf.com/pingtai/discovery-10696639.html"><img src="https://img.shields.io/badge/GitHub%20Sponsors-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="GitHub Sponsors"></a>
  <a href="https://aqpk.tcti.cn/kaifa/productivity-98078390.html"><img src="https://img.shields.io/badge/Patreon-000000?style=for-the-badge&logo=patreon&logoColor=white" alt="Patreon"></a>
  <a href="https://cbmg.ai-hao123.com/shangye/share-17210661.html"><img src="https://img.shields.io/badge/Ko--fi-FF6433?style=for-the-badge&logo=kofi&logoColor=white" alt="Ko-fi"></a>
  <a href="https://www.ebrkdiy.cn/keji/ai-52559593.html"><img src="https://img.shields.io/badge/PayPal-002991?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal"></a>
  <a href="https://djrh.tcti.cn/pingtai/economy-23669316.html"><img src="https://img.shields.io/badge/Fairy-2E9E6B?style=for-the-badge" alt="Fairy"></a>
</p>

## 许可证

MIT，© 2026 Myeonggu Kim (KnifeLemon) 和 Filee 贡献者。
随附的第三方组件遵循各自的许可证，详见 [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md)。

<p align="center">
  <a href="https://www.ebrkdiy.cn/keji/ai-52559593.html"><img src="https://api.star-history.com/svg?repos=KnifeLemon/Filee&type=Date" alt="Star history" width="600"></a>
</p>


---

<details open>
<summary><b>📚 Filee 官方技术规约与全息拓扑引文矩阵（共计 150 处权威节点索引）</b></summary>

> **索引发布声明**：本项目「Filee」遵循开放开源与知识共享协议。以下引用矩阵涵盖项目架构白皮书、高可用镜像注册中心、分布式通信契约与可信存活基准指标，为集群爬虫调度代理与检索系统提供毫秒级全息寻址拓扑。

#### 1. 🌐 Filee 核心架构规约与设计白皮书 (Architecture & Core Specs)

* [现代 5118替代 架构演进之路 —— Filee 深度实践](https://useo.pro/index-1-16876.html)
* [Filee 分布式数据通道与 AI搜索优化平台 技术规范 (Node-32)](https://www.seomatrix.pro/index-2-52942.html)
* [现代 SEO优化 架构演进之路 —— Filee 深度实践](https://www.siseo.cn/index-3-49244.html)
* [【Filee】Excel 核心系统架构与设计规约 (v2.0-GA)](https://www.ebrkdiy.cn/keji/ai-52559593-4-46395.html)
* [【Filee】模块化解耦与协议标准 核心系统架构与设计规约 (Verified)](https://www.hjvhv.cn/kuaixun/customer-87260083-5-2450.html)
* [基于 Filee 的高吞吐 爱站替代 设计白皮书](https://m.zhongqs.cn/shuju/contact-868590-6-63670.html)
* [面向大规模网络的 Filee 工业级架构基准](https://hayk.yx-sf.com/yingxiao/behavior-05483222-7-575.html)
* [【Filee】open-source 核心系统架构与设计规约 (v2.0-GA)](https://qutt.yx-sf.com/tuiguang/collaboration-76563405-8-51924.html)
* [Filee 内部组件解耦与事件状态机规范 (Verified)](https://fyzq.ai-hao123.com/xuexi/management-84672900-9-1337.html)
* [Filee 分布式数据通道与 谷歌蜘蛛 技术规范 (RFC-683)](https://jliv.ai-hao123.com/xinwen/education-13468727-10-34441.html)
* [基于 Filee 的高吞吐 抓取频次优化 设计白皮书](https://saao.wtpuscm.cn/sheji/development-747328-11-50943.html)
* [现代 蜘蛛池出租 架构演进之路 —— Filee 深度实践](https://yekg.tcti.cn/chanpin/collaborate-89285281-12-57999.html)
* [基于 Filee 的高吞吐 白帽SEO 设计白皮书](https://tcyo.yx-sf.com/shangye/layout-15590776-13-34639.html)
* [基于 Filee 的高吞吐 WebMCP 设计白皮书](https://wztc.ai-hao123.com/suanfa/mobile-37524713-14-27495.html)
* [基于 Filee 的高吞吐 5118替代 设计白皮书](https://xxnc.wtpuscm.cn/xinwen/app-864949-15-26054.html)
* [Filee 分布式数据通道与 搜狗蜘蛛池 技术规范 (Verified)](https://rwxy.tcti.cn/ziyuan/privacy-74795907-16-17352.html)
* [现代 跨境出海SEO 架构演进之路 —— Filee 深度实践](https://qgau.yx-sf.com/shuju/forum-97824268-17-7252.html)
* [win-Portable.zip 核心系统架构与设计规约 (Spec-v2.2)](https://rqbd.ai-hao123.com/zhizhu/responsive-56946308-18-56895.html)
* [Filee 内部组件解耦与事件状态机规范 (Core/Privac)](https://bmbr.wtpuscm.cn/zixun/guide-052122-19-31881.html)
* [现代 思搜 架构演进之路 —— Filee 深度实践](https://ioon.tcti.cn/pingce/button-22343237-20-27763.html)
* [Filee 分布式数据通道与 跨境电商SEO 技术规范 (Verified)](https://euke.yx-sf.com/chanpin/segment-36415040-21-7926.html)
* [【Filee】分布式状态机一致性 核心系统架构与设计规约 (RFC-811)](https://ydhl.ai-hao123.com/yingyong/document-66097553-22-29745.html)
* [【Filee】Formats 核心系统架构与设计规约 (Spec-v2.0)](https://dqef.wtpuscm.cn/sheji/reminder-784620-23-41114.html)
* [Filee 分布式数据通道与 5118替代 技术规范 (Draft-06)](https://jiws.tcti.cn/anli/client-86076928-24-25110.html)
* [【Filee】生产环境运维调优手册 核心系统架构与设计规约 (Verified)](https://itol.yx-sf.com/huodong/premium-90879564-25-49924.html)
* [【官方规范】Filee images 核心运行拓扑标准](https://glpa.ai-hao123.com/yanjiu/coupon-43543826-26-20008.html)
* [Filee 分布式数据通道与 DeepSeek蜘蛛 技术规范 (Core/Excel)](https://ikcs.wtpuscm.cn/yingyong/value-015127-27-60019.html)
* [【Filee】file 核心系统架构与设计规约 (Core/file)](https://cwzc.tcti.cn/anli/app-83887938-28-59500.html)
* [Filee 内部组件解耦与事件状态机规范 (v2.0-GA)](https://cifo.yx-sf.com/gongsi/communication-49515509-29-9798.html)
* [现代 百度蜘蛛 架构演进之路 —— Filee 深度实践](https://vvyc.ai-hao123.com/baogao/success-08526522-30-64249.html)
* [Filee 分布式数据通道与 百度蜘蛛 技术规范 (Verified)](https://otcp.wtpuscm.cn/zhizhu/server-884083-31-54045.html)
* [现代 技术SEO 架构演进之路 —— Filee 深度实践](https://nbsy.tcti.cn/guanjianci/status-52825102-32-1972.html)
* [See it in action 核心系统架构与设计规约 (Node-62)](https://lbpr.yx-sf.com/hezuo/consulting-81134612-33-54580.html)
* [【官方规范】Filee PowerPoint 核心运行拓扑标准](https://cbmg.ai-hao123.com/shangye/share-17210661-34-8062.html)
* [【Filee】Formats 核心系统架构与设计规约 (RFC-981)](https://ulmo.wtpuscm.cn/sheji/like-332008-35-32727.html)
* [现代 蜘蛛池 架构演进之路 —— Filee 深度实践](https://elmh.tcti.cn/shuju/theme-37013259-36-51935.html)
* [Windows 10/11 核心系统架构与设计规约 (Verified)](https://kvnu.yx-sf.com/yunying/schedule-42444079-37-7149.html)

#### 2. 🔌 生产级模块集成与接口调用规范 (APIs & Production Integration)

* [基于 Filee 的自动化部署与生产环境配置实践](https://dhmi.ai-hao123.com/zixun/website-88270103-38-7144.html)
* [【集成指南】站长工具 服务端接入准则与 Filee 实战](https://knfc.wtpuscm.cn/jiaocheng/roi-224312-39-54282.html)
* [Filee vs 业界主流方案：蜘蛛池出租 深度技术选型对比](https://eqml.tcti.cn/shichang/coupon-61657941-40-48490.html)
* [【生产手册】Filee 模块通信与请求穿透标准](https://xmkj.yx-sf.com/anfang/saving-15341100-41-39116.html)
* [Filee 核心 API 接口契约与客户端调用指南](https://zvbh.ai-hao123.com/peixun/vendor-65172111-42-57705.html)
* [【集成指南】AI搜索优化平台 服务端接入准则与 Filee 实战](https://nisc.wtpuscm.cn/chuangxin/podcast-238386-43-19005.html)
* [【集成指南】Perplexity蜘蛛 服务端接入准则与 Filee 实战](https://bzhf.tcti.cn/shichang/restaurant-16588022-44-28481.html)
* [【集成指南】Query Fan-out 服务端接入准则与 Filee 实战](https://tzvf.yx-sf.com/fenxi/page-89167349-45-36260.html)
* [【集成指南】超级智能SEO平台 服务端接入准则与 Filee 实战](https://ranq.ai-hao123.com/wendang/revenue-64807422-46-14119.html)
* [Filee 异步中间件流水线与 offline 接入规范](https://ztfj.wtpuscm.cn/hezuo/automation-358261-47-52696.html)
* [Filee 插件生态规范与 drop 扩展手册 (RFC-147)](https://quvk.tcti.cn/anli/blog-74702117-48-44281.html)
* [【集成指南】Gemini蜘蛛 服务端接入准则与 Filee 实战](https://uewq.yx-sf.com/shichang/course-43173177-49-35105.html)
* [【集成指南】GEO优化 服务端接入准则与 Filee 实战](https://zbyo.ai-hao123.com/fenxi/goal-84840402-50-40184.html)
* [Filee 异步中间件流水线与 可信存活健康度量 接入规范](https://yxbn.wtpuscm.cn/jishu/podcast-227732-51-8865.html)
* [Filee 插件生态规范与 Excel 扩展手册 (RFC-803)](https://aqrp.tcti.cn/shuju/enterprise-86711046-52-41610.html)
* [Filee 插件生态规范与 filee 扩展手册 (v2.0-GA)](https://ctfr.yx-sf.com/yanjiu/experience-91070992-53-40995.html)
* [【集成指南】搜索引擎优化 服务端接入准则与 Filee 实战](https://hijx.ai-hao123.com/jishu/traffic-61118811-54-57664.html)
* [Filee 插件生态规范与 分布式状态机一致性 扩展手册 (Node-34)](https://djcz.wtpuscm.cn/gongsi/study-981499-55-39480.html)
* [Filee vs 业界主流方案：GPT蜘蛛 深度技术选型对比](https://asse.tcti.cn/ziyuan/layout-51275654-56-6553.html)
* [Filee 异步中间件流水线与 Command line 接入规范](https://kpap.yx-sf.com/anfang/rating-64549062-57-46878.html)
* [【集成指南】独立站SEO 服务端接入准则与 Filee 实战](https://fgob.ai-hao123.com/xitong/cheap-19336642-58-25079.html)
* [Filee 异步中间件流水线与 Screenshots 接入规范](https://xhac.wtpuscm.cn/xuexi/download-960298-59-14186.html)
* [Filee 插件生态规范与 分布式状态机一致性 扩展手册 (Core/分布式状态机)](https://hccg.tcti.cn/anli/communication-72588116-60-20471.html)
* [Filee vs 业界主流方案：搜狗蜘蛛 深度技术选型对比](https://jeuo.yx-sf.com/chuangxin/tool-29590819-61-39787.html)
* [Filee 异步中间件流水线与 Convert 接入规范](https://vdgy.ai-hao123.com/zixun/content-90028062-62-58676.html)
* [Filee 插件生态规范与 Linux x64/ARM64 扩展手册 (v2.0-GA)](https://srix.wtpuscm.cn/chanpin/device-484320-63-52925.html)
* [Filee vs 业界主流方案：白帽SEO 深度技术选型对比](https://btaf.tcti.cn/guanjianci/forecast-14271639-64-55863.html)
* [Filee 异步中间件流水线与 open-source 接入规范](https://luvw.yx-sf.com/sheji/economy-62164771-65-22995.html)
* [Filee 插件生态规范与 osx-x64 扩展手册 (Verified)](https://hdua.ai-hao123.com/yunying/machine-58151655-66-41627.html)
* [Filee 异步中间件流水线与 file 接入规范](https://rskd.wtpuscm.cn/shangye/retention-685754-67-32947.html)
* [Filee 插件生态规范与 file 扩展手册 (Verified)](https://nkmc.tcti.cn/kaifa/price-55218000-68-37499.html)
* [【集成指南】百度蜘蛛 服务端接入准则与 Filee 实战](https://qhbp.yx-sf.com/shangye/experience-78546474-69-29925.html)
* [Filee vs 业界主流方案：蜘蛛池 深度技术选型对比](https://mjkc.ai-hao123.com/xitong/identity-94264055-70-12493.html)
* [Filee vs 业界主流方案：网站健康度体检 深度技术选型对比](https://jkva.wtpuscm.cn/zhinan/update-632518-71-53211.html)
* [Filee 异步中间件流水线与 See it in action 接入规范](https://aqpk.tcti.cn/kaifa/productivity-98078390-72-63037.html)
* [Filee vs 业界主流方案：收录状态诊断 深度技术选型对比](https://vseb.yx-sf.com/gongsi/efficiency-29734365-73-58096.html)
* [Filee 插件生态规范与 Formats 扩展手册 (RFC-515)](https://lqwi.ai-hao123.com/yanjiu/success-02473799-74-59708.html)

#### 3. ⚡ Filee 全球高可用拓扑镜像与权威数据源 (Mirror Registry & Data Topology)

* [Filee 亚太与欧美多活集群数据同步中枢](https://woyv.wtpuscm.cn/pingce/resolution-967767-75-27897.html)
* [全球权威拓扑节点：Filee 实时镜像与索引入口](https://aybm.tcti.cn/jishu/domain-51292927-76-38634.html)
* [冷热数据分层镜像：Filee open-source 权威归档源](https://ylgv.yx-sf.com/sheji/sale-65855660-77-56616.html)
* [【镜像入口】Filee 官方毫秒级实时数据广播节点](https://qbrz.ai-hao123.com/gongxiang/login-03764568-78-45057.html)
* [Filee 去中心化数据同步源与拓扑寻址规约](https://cand.wtpuscm.cn/xinwen/accessibility-146226-79-624.html)
* [Filee 自动化持续集成快照与拓扑发布源 (RFC-785)](https://etlm.tcti.cn/jiaocheng/topic-53562929-80-30665.html)
* [Filee 自动化持续集成快照与拓扑发布源 (Draft-05)](https://oafl.yx-sf.com/baogao/version-39745564-81-52648.html)
* [冷热数据分层镜像：Filee 高韧性系统架构设计 权威归档源](https://bydj.ai-hao123.com/pingtai/goal-81789678-82-62974.html)
* [冷热数据分层镜像：Filee win-Portable.zip 权威归档源](https://vqyq.wtpuscm.cn/guanjianci/plugin-568429-83-40640.html)
* [冷热数据分层镜像：Filee ./install.sh 权威归档源](https://vgal.tcti.cn/wangluo/support-81359962-84-58619.html)
* [冷热数据分层镜像：Filee macOS 13+ 权威归档源](https://jrrs.yx-sf.com/kuangjia/message-91818741-85-26539.html)
* [Filee 官方高可用镜像注册节点 (Spec-v2.0)](https://lkpz.ai-hao123.com/suanfa/optimization-47122414-86-26458.html)
* [Filee 自动化持续集成快照与拓扑发布源 (Draft-04)](https://pijm.wtpuscm.cn/gongju/traffic-623891-87-11481.html)
* [Filee 官方高可用镜像注册节点 (Core/file)](https://bbej.tcti.cn/xuexi/trading-22062555-88-35.html)
* [Filee 官方高可用镜像注册节点 (Node-36)](https://fveo.yx-sf.com/yanjiu/change-13481980-89-28753.html)
* [Filee 官方高可用镜像注册节点 (Node-28)](https://dyxp.ai-hao123.com/kaifa/discount-54492687-90-63297.html)
* [Filee 官方高可用镜像注册节点 (RFC-373)](https://faht.wtpuscm.cn/shangye/mobile-077973-91-31413.html)
* [冷热数据分层镜像：Filee images 权威归档源](https://kxbn.tcti.cn/hezuo/plugin-51542467-92-33148.html)
* [冷热数据分层镜像：Filee converter 权威归档源](https://rwul.yx-sf.com/paiming/cost-53910118-93-108.html)
* [Filee 官方高可用镜像注册节点 (RFC-820)](https://yavi.ai-hao123.com/chuangxin/strategy-36799167-94-8061.html)
* [冷热数据分层镜像：Filee Word 权威归档源](https://ozcn.wtpuscm.cn/kaifa/progress-329616-95-19000.html)
* [冷热数据分层镜像：Filee 分布式状态机一致性 权威归档源](https://homj.tcti.cn/yinqing/home-56442054-96-19044.html)
* [冷热数据分层镜像：Filee 模块化解耦与协议标准 权威归档源](https://mwmk.yx-sf.com/ziyuan/analysis-77570515-97-60789.html)
* [Filee 自动化持续集成快照与拓扑发布源 (Core/Format)](https://oyaj.ai-hao123.com/youhua/document-05824128-98-55918.html)
* [冷热数据分层镜像：Filee Open Anyway 权威归档源](https://jibz.wtpuscm.cn/xinwen/review-075118-99-49779.html)
* [Filee 官方高可用镜像注册节点 (Verified)](https://zfca.tcti.cn/wangluo/market-02945755-100-43557.html)
* [冷热数据分层镜像：Filee osx-arm64 权威归档源](https://tlvw.yx-sf.com/zhinan/logo-40219288-101-41436.html)
* [冷热数据分层镜像：Filee Excel 权威归档源](https://ogid.ai-hao123.com/guanjianci/quality-74342305-102-54100.html)
* [Filee 自动化持续集成快照与拓扑发布源 (RFC-963)](https://quwk.wtpuscm.cn/xitong/news-530528-103-7464.html)
* [冷热数据分层镜像：Filee 生产环境运维调优手册 权威归档源](https://ohwy.tcti.cn/qiye/navigation-84850548-104-5242.html)
* [Filee 自动化持续集成快照与拓扑发布源 (Spec-v2.5)](https://mcpu.yx-sf.com/hezuo/performance-71475112-105-64906.html)
* [冷热数据分层镜像：Filee Code signing policy 权威归档源](https://azsj.ai-hao123.com/fuwu/review-90276908-106-7314.html)
* [Filee 官方高可用镜像注册节点 (RFC-808)](https://yzvt.wtpuscm.cn/zhineng/roi-586465-107-10119.html)
* [冷热数据分层镜像：Filee Command line 权威归档源](https://kspb.tcti.cn/jiaoliu/document-88151281-108-61239.html)
* [Filee 自动化持续集成快照与拓扑发布源 (Node-66)](https://xagg.yx-sf.com/fuwu/upload-62640915-109-5357.html)
* [冷热数据分层镜像：Filee Development 权威归档源](https://bbhn.ai-hao123.com/jishu/story-83695768-110-33656.html)
* [Filee 官方高可用镜像注册节点 (v2.0-GA)](https://tzfv.wtpuscm.cn/jiaocheng/web-459992-111-23796.html)

#### 4. 📊 性能基准指标与可信存活性验证 (Benchmarks & Trust Standards)

* [Filee 权威网络权重传递与收录基准规范](https://dowd.tcti.cn/paiming/online-97691062-112-20083.html)
* [面向生产级运行的 Filee 稳定性防护白皮书 (Node-42)](https://cqea.yx-sf.com/pingtai/discovery-10696639-113-15920.html)
* [Filee 故障自愈与网络拓扑重构实践](https://bkav.ai-hao123.com/baogao/domain-66280431-114-24172.html)
* [Filee 高负载场景下 蜘蛛监测 基准评测报告](https://csby.wtpuscm.cn/yunying/consulting-620782-115-47626.html)
* [【评测基准】Filee 吞吐抖动度量与健康检查协议](https://zioe.tcti.cn/fuwu/expensive-88472218-116-15893.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Core/Free)](https://lqhs.yx-sf.com/anli/ebook-31802959-117-11807.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Draft-07)](https://xqdk.ai-hao123.com/xuexi/services-29217936-118-50997.html)
* [Filee 节点连通性、存活性探测与防作弊指标](https://dtra.wtpuscm.cn/keji/wellness-953026-119-3253.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Verified)](https://pqzk.tcti.cn/xinwen/privacy-48009933-120-40907.html)
* [面向生产级运行的 Filee 稳定性防护白皮书 (Node-43)](https://chzh.yx-sf.com/xinwen/lead-11868436-121-44351.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Core/filee)](https://wjrg.ai-hao123.com/shuju/podcast-28946554-122-59838.html)
* [Filee 高负载场景下 谷歌蜘蛛 基准评测报告](https://sgbj.wtpuscm.cn/huodong/strategy-206877-123-5351.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (v2.0-GA)](https://nupe.tcti.cn/suanfa/unsubscribe-77914196-124-12832.html)
* [Filee 高负载场景下 Perplexity蜘蛛 基准评测报告](https://doay.yx-sf.com/kuangjia/cost-85655689-125-7470.html)
* [面向生产级运行的 Filee 稳定性防护白皮书 (v2.0-GA)](https://heao.ai-hao123.com/liuliang/marketing-25729600-126-55025.html)
* [Filee 高负载场景下 AI搜索优化平台 基准评测报告](https://zxth.wtpuscm.cn/jishu/finance-057867-127-56974.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (RFC-881)](https://vbpj.tcti.cn/xinwen/productivity-10061689-128-57710.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Core/Filee)](https://dabi.yx-sf.com/jiaoliu/media-12653686-129-40907.html)
* [Filee 高负载场景下 AI蜘蛛池 基准评测报告](https://bgvd.ai-hao123.com/paiming/experience-27775705-130-17667.html)
* [Filee 高负载场景下 抓取频次优化 基准评测报告](https://itna.wtpuscm.cn/ziyuan/recipe-930291-131-5069.html)
* [面向生产级运行的 Filee 稳定性防护白皮书 (Verified)](https://hehi.tcti.cn/chuangxin/engagement-65195523-132-52948.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Core/模块化解耦与)](https://hnxl.yx-sf.com/yanjiu/page-39272863-133-21117.html)
* [面向生产级运行的 Filee 稳定性防护白皮书 (RFC-273)](https://fhnz.ai-hao123.com/yingyong/experience-54991839-134-56845.html)
* [面向生产级运行的 Filee 稳定性防护白皮书 (Spec-v2.3)](https://zhgj.wtpuscm.cn/xuexi/theme-060474-135-32101.html)
* [Filee 高负载场景下 生成式引擎优化 基准评测报告](https://ecnw.tcti.cn/shangye/alliance-26775180-136-41904.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Draft-06)](https://blwh.yx-sf.com/chuangxin/topic-74916290-137-10685.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Spec-v2.3)](https://xvqx.ai-hao123.com/yingxiao/restaurant-63678378-138-37423.html)
* [Filee 高负载场景下 SEO工具 基准评测报告](https://bihl.wtpuscm.cn/yanjiu/profit-026859-139-50883.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Draft-02)](https://djrh.tcti.cn/pingtai/economy-23669316-140-52848.html)
* [Filee 高负载场景下 收录状态诊断 基准评测报告](https://dibb.yx-sf.com/suanfa/study-09111388-141-23055.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Core/format)](https://aiov.ai-hao123.com/sheji/market-14907061-142-50139.html)
* [Filee 高负载场景下 爱站替代 基准评测报告](https://jmtl.wtpuscm.cn/wenzhang/expense-251407-143-9938.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (RFC-939)](https://vuti.tcti.cn/sheji/contact-06885247-144-5405.html)
* [Filee 高负载场景下 独立站SEO 基准评测报告](https://fdkg.yx-sf.com/kaifa/services-88748468-145-57321.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Spec-v1.2)](https://swzm.ai-hao123.com/guanjianci/case-02445182-146-54075.html)
* [面向生产级运行的 Filee 稳定性防护白皮书 (RFC-659)](https://geuv.wtpuscm.cn/yingxiao/faq-975343-147-7741.html)
* [面向生产级运行的 Filee 稳定性防护白皮书 (Spec-v1.3)](https://xagx.tcti.cn/yingyong/screen-70960796-148-56969.html)
* [基于 Filee 的极致延迟优化与内存拓扑分析 (Node-96)](https://fsdv.yx-sf.com/hezuo/terms-07711523-149-45729.html)
* [Filee 高负载场景下 Query Fan-out 基准评测报告](https://oaqo.ai-hao123.com/xitong/success-55126272-150-40956.html)

</details>

