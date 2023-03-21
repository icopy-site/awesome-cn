<div class="github-widget" data-repo="sindresorhus/quick-look-plugins"></div>
## Quick Look plugins [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 有用的列表 [Quick Look](https://en.wikipedia.org/wiki/Quick_Look) 开发者插件

## Install

### Using [Homebrew](https://brew.sh)

 - 运行`brew 安装<package> `

#### Install all

```
brew 安装 qlcolorcode qlstephen qlmarkdown quicklook-json qlimagesize 可疑包外观 quicklookase qlvideo
```

##### Catalina notes

要让插件在 Catalina 中工作，您需要删除隔离属性.

运行此命令以查看属性：

```
xattr -r ~/图书馆/QuickLook
```

并运行它以删除属性：

```
xattr -d -r com.apple.quarantine ~/Library/QuickLook
```

### Manually

- 点击“手动下载”
- 将下载的 .qlgenerator 文件移动到 `~/Library/QuickLook`
- 运行`qlmanage -r`

## Plugins

### [QLColorCode](https://github.com/anthonygelibert/QLColorCode)

&gt; 使用语法高亮预览源代码文件

运行 `brew install qlcolorcode` 或 [download manually](https://github.com/anthonygelibert/QLColorCode/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QLColorCode.png)](https://github.com/anthonygelibert/QLColorCode)

### [QLStephen](https://github.com/whomwah/qlstephen)

 &gt; 预览没有或带有未知文件扩展名的纯文本文件. 示例：README、CHANGELOG、index.styl 等.

运行 `brew install qlstephen` 或 [download manually](https://github.com/whomwah/qlstephen/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QLStephen.png)](https://github.com/whomwah/qlstephen)

### [QLMarkdown](https://github.com/toland/qlmarkdown)

&gt; 预览 Markdown 文件

运行 `brew install qlmarkdown` 或 [download manually](https://github.com/downloads/toland/qlmarkdown/QLMarkdown-1.3.zip)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QLMarkdown.png)](https://github.com/toland/qlmarkdown)

### [QuickLookJSON](http://www.sagtau.com/quicklookjson.html)

&gt; 预览 JSON 文件

运行 `brew install quicklook-json` 或 [download manually](http://www.sagtau.com/media/QuickLookJSON.qlgenerator.zip)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QuickLookJSON.png)](http://www.sagtau.com/quicklookjson.html)

### [BetterZipQL](https://macitbetter.com/downloads/)

&gt; 预览档案

&gt; 注意：BetterZipQL 插件已与 BetterZip 应用程序集成.

运行“brew install betterzip”来安装 BetterZip 应用程序及其 Quick Look 插件或 [download manually](https://macitbetter.com/BetterZip.zip)

遗留的 BetterZipQL 插件可以是 [downloaded here](https://macitbetter.com/dl/BetterZipQL-1.5.zip).

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/BetterZipQL.png)](https://macitbetter.com/BetterZip-Quick-Look-Generator/)

### [qlImageSize](https://github.com/Nyx0uf/qlImageSize)

&gt; 显示图像大小和分辨率

运行“brew install qlimagesize”或 [download manually](https://github.com/Nyx0uf/qlImageSize#installation)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/qlImageSize.png)](https://github.com/Nyx0uf/qlImageSize)

### [Suspicious Package](https://www.mothersruin.com/software/SuspiciousPackage/)

&gt; 预览标准 Apple 安装程序包的内容

运行 `brew install suspicious-package` 或 [download manually](https://www.mothersruin.com/software/downloads/SuspiciousPackage.xip)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/SuspiciousPackage.png)](https://www.mothersruin.com/software/SuspiciousPackage/)

### [Apparency](https://www.mothersruin.com/software/Apparency/)

&gt; 预览 macOS 应用程序的内容

运行“brew install apparency”或 [download manually](https://mothersruin.com/software/downloads/Apparency.dmg)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/Apparency.png)](https://mothersruin.com/software/Apparency/)

### [QuickLookASE](https://github.com/rsodre/QuickLookASE)

&gt; 预览使用 Adob​​e Photoshop、Adobe Illustrator、 [Adobe Color CC](https://color.adobe.com), [Spectrum](http://www.eigenlogik.com/spectrum/mac), [COLOURlovers](https://www.colourlovers.com), [Prisma](http://www.codeadventure.com)，等等.

运行“brew install quicklookase”或 [download manually](https://github.com/rsodre/QuickLookASE/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QuickLookASE.png)](https://github.com/rsodre/QuickLookASE)

### [QLVideo](https://github.com/Marginal/QLVideo)

&gt; 预览大多数类型的视频文件，以及它们的缩略图、封面艺术和元数据

运行 `brew install qlvideo` 或 [download manually](https://github.com/Marginal/QLVideo/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QLVideo.png)](https://github.com/Marginal/QLVideo)

## More

*这些不包括在 [Install all](#install-all).*

### [Peek](https://bigzlabs.com/peek) 💰

&gt; Peek 允许您在 300 多个文件扩展名的快速查看预览中复制和查找文本、跳转到行号、使用生成的目录呈现 Github 风格的 Markdown、恢复滚动位置、突出显示语法等.

购买于 [Mac App Store](https://apps.apple.com/app/peek-quick-look-extension/id1554235898)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/Peek.png)](https://bigzlabs.com/peek)

### [ProvisionQL](https://github.com/ealeksandrov/ProvisionQL)

&gt; 预览 iOS / macOS 应用程序和配置信息

运行 `brew install provisionql` 或 [download manually](https://github.com/ealeksandrov/ProvisionQL/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/ProvisionQL.png)](https://github.com/ealeksandrov/ProvisionQL)

### [QuickLookAPK](https://github.com/hezi/QuickLookAPK)

&gt; 预览 Android APK 文件

运行“brew install quicklookapk”或 [download manually](https://github.com/hezi/QuickLookAPK/blob/master/QuickLookAPK.qlgenerator.zip)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/QuickLookAPK.png)](https://github.com/hezi/QuickLookAPK)

### [quicklook-pat](https://github.com/pixelrowdies/quicklook-pat)

&gt; 预览 Adob​​e Photoshop 图案文件

运行 `brew install quicklook-pat` 或 [download manually](https://github.com/pixelrowdies/quicklook-pat/releases)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/quicklook-pat.png)](https://github.com/pixelrowdies/quicklook-pat)

### [WebP](https://github.com/dchest/webp-quicklook)

&gt; 预览 WebP 图像

&gt; 注意：这已经包含在 `qlImageSize` 中，所以这里列出这个插件只是为了防止您不喜欢 `qlImageSize`.

运行“brew install webpquicklook”或 [download manually](https://github.com/dchest/webp-quicklook/releases/latest)

[![](https://raw.githubusercontent.com/sindresorhus/quick-look-plugins/master/screenshots/WebP.png)](https://github.com/dchest/webp-quicklook)

### [SourceCodeSyntaxHighlight](https://github.com/sbarex/SourceCodeSyntaxHighlight)

&gt; 预览许多不同的源代码文件

运行“brew install --cask --no-quarantine syntax-highlight”或 [download manually](https://github.com/sbarex/SourceCodeSyntaxHighlight/releases/latest)

[![](https://user-images.githubusercontent.com/8471055/118415204-5f53fc80-b6a9-11eb-93d8-b88c442c5744.png)](https://github.com/sbarex/SourceCodeSyntaxHighlight)

**注意：** 这可能会覆盖其他一些 Quick Look 插件.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Sindre Sorhus](https://sindresorhus.com) 已放弃该作品的所有版权和相关或邻接权.
