## Awesome WebExtensions [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;精选资源的精选列表 [WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) 发展.

 WebExtensions是一个用于开发浏览器加载项的跨浏览器系统.  在很大程度上系统与之兼容 [extension API](https://developer.chrome.com/extensions)  由谷歌Chrome和Opera支持.  为这些浏览器编写的扩展程序在大多数情况下都可以在Firefox或Firefox中运行 [Microsoft Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/documentation/extensions/) 只是 [a few changes](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Porting_a_Google_Chrome_extension).

## Contents

- [Getting Started](#getting-started)
- [Community](#community)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Tools](#tools)
- [Boilerplates](#boilerplates)
- [Sample Extensions](#sample-extensions)

## Getting started

- [Chrome Extensions documentation](https://developer.chrome.com/extensions) - 原始Chrome扩展模型的文档.
- [Chrome Extensions API](https://developer.chrome.com/extensions/api_index) -  Chrome提供的原始API的综合文档.
- [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) -  WebExtensions API的MDN wiki.
- [Browser support for WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs) - 适用于Chrome，Edge，Firefox和Opera的兼容性表.
- [Microsoft Edge API support](https://docs.microsoft.com/en-us/microsoft-edge/extensions/api-support/extension-api-roadmap) - 详细的WebExtensions支持Edge.
- [Safari Extensions documentation](https://developer.apple.com/safari/extensions/) - 有关构建Safari扩展的开发人员文档
- [Opera API support](https://dev.opera.com/extensions/apis/) - 详细的WebExtensions支持Opera.
- [Porting Chrome Extensions to Firefox](https://hacks.mozilla.org/2015/10/porting-chrome-extensions-to-firefox-with-webextensions/) - 准备，安装和调试要在Firefox中移植的Chrome扩展程序的指南.
- [Browser Extension Standard](https://browserext.github.io/browserext/) -  API的标准，由Mozilla，Opera和Microsoft支持.

## Community

- [Google Groups](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions) - 讨论.
- [Mozilla Discourse](https://discourse.mozilla.org/c/add-ons) - 讨论.
- [`#webextensions`](https://wiki.mozilla.org/IRC) -  Mozilla的IRC频道.
- [`google-chrome-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/google-chrome-extension) - 相关问题.
- [`firefox-webextensions` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/firefox-webextensions) - 相关问题.
- [`microsoft-edge-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-edge-extension) - 相关问题.

## Libraries and Frameworks

代码意味着成为扩展的一部分.

- [webext-options-sync](https://github.com/bfred-it/webext-options-sync) - 帮助您管理和自动保存您的分机选项.
- [webext-inject-on-install](https://github.com/bfred-it/webext-inject-on-install)   - 安装扩展时自动将内容脚本添加到现有选项卡.  Chrome + Firefox.
- [redux-webext](https://github.com/ivantsov/redux-webext) - 用途 [redux](https://github.com/reactjs/redux) 用于管理WebExtension的状态
- [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) -  Polyfill支持`browser`命名空间中基于标准化promise的API.

## Tools

可帮助您管理扩展程序的应用.

- [Chrome Webstore Upload](https://github.com/DrewML/chrome-webstore-upload-cli) - 通过cli（或Travis，自动）将扩展程序上传到Chrome网上应用店.
- [mozilla/web-ext](https://github.com/mozilla/web-ext) 用于帮助构建，运行和测试WebExtensions的命令行工具.
- [chromepet](https://github.com/ZenHubIO/chromepet) - 在您的新版本发布时收到通知.
- [chrome-ext-downloader](https://github.com/jiripospisil/chrome-ext-downloader) - 在Chrome网上应用店下载任何扩展程序，了解他们是如何做到的.
- [unzip-crx](https://github.com/peerigon/unzip-crx) - 解压谷歌Chrome（crx）文件.
- [chrome-store-api](https://github.com/acvetkov/chrome-store-api) -  Chrome Web Store API包装器.
- [Chrome extension source viewer](https://github.com/Rob--W/crxviewer) -  WebExtension直接在商店中查看扩展的源代码.
- [@wext/shipit](https://github.com/LinusU/wext-shipit) - 自动发布到Chrome网上应用店，Mozilla插件和Opera插件的工具.
- [web-ext-translator](https://github.com/Lusito/web-ext-translator) - 用于管理i18n messages.json的翻译工具.

## Testing

- [sinon-chrome](https://github.com/acvetkov/sinon-chrome) - 模拟Chrome扩展程序API以进行测试.
- [addons-validator](https://github.com/mozilla/addons-validator) - 根据Mozilla的指南验证扩展.

## Boilerplates

- [create-webextension](https://github.com/rpl/create-webextension) -  Yarn WebExtension生成器.
- [extensionizr.com](http://extensionizr.com) -  Web UI，可帮助您创建初始配置和文件.
- [generator-web-extension](https://github.com/HaNdTriX/generator-web-extension) -  WebExtension生成器，可以创建跨浏览器Web扩展开发所需的一切.
- [react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) - 使用热重新加载反应样板.

## Sample Extensions

这些是简单而现代的WebExtensions存储库，可以帮助您确定工作的位置，包括通过Travis CI自动部署.

- [npmhub](https://github.com/npmhub/npmhub)
- [Hide Files on GitHub](https://github.com/sindresorhus/hide-files-on-github)
- [Refined GitHub](https://github.com/sindresorhus/refined-github)
- [mdn/webextension-examples](https://github.com/mdn/webextensions-examples) - 为MDN文档策划的各种示例扩展.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Federico Brigante](http://bfred.it) 已放弃对此作品的所有版权及相关或相邻权利.
