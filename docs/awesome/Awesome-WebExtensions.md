<div class="github-widget" data-repo="fregante/Awesome-WebExtensions"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome WebExtensions [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt; 精选的精彩资源列表 [WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) 发展.

 WebExtensions 是一个用于开发浏览器插件的跨浏览器系统. 该系统在很大程度上兼容 [extension API](https://developer.chrome.com/extensions) 由 Google Chrome 和 Opera 支持. 为这些浏览器编写的扩展程序在大多数情况下会在 Firefox 或 [Microsoft Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/documentation/extensions/) 只是 [a few changes](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Porting_a_Google_Chrome_extension).



## Getting started

- [Chrome Extensions documentation](https://developer.chrome.com/extensions) - 原始 Chrome 扩展模型的文档.
- [Chrome Extensions API](https://developer.chrome.com/extensions/api_index) - 有关 Chrome 提供的原始 API 的综合文档.
- [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) - 用于 WebExtensions API 的 MDN wiki.
- [Browser support for WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs) - Chrome、Edge、Firefox 和 Opera 的兼容性表.
- [Microsoft Edge API support](https://docs.microsoft.com/en-us/microsoft-edge/extensions/api-support/extension-api-roadmap) - 对 Edge 的详细 WebExtensions 支持.
- [Safari Extensions documentation](https://developer.apple.com/safari/extensions/)  - 有关构建 Safari 扩展的开发人员文档. 从技术上讲不是 WebExtensions，API 是完全不同的.
- [Opera API support](https://dev.opera.com/extensions/apis/) - 对 Opera 的详细 WebExtensions 支持.
- [Porting Chrome Extensions to Firefox](https://hacks.mozilla.org/2015/10/porting-chrome-extensions-to-firefox-with-webextensions/) - 准备、安装和调试要移植到 Firefox 中的 Chrome 扩展程序的指南.
- [Browser Extension Standard](https://browserext.github.io/browserext/) - API 标准，由 Mozilla、Opera 和 Microsoft 支持.

## Community

- [Google Groups](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions) - 讨论.
- [Mozilla Discourse](https://discourse.mozilla.org/c/add-ons) - 讨论.
- [`#addons:mozilla.org`](https://matrix.to/#/#addons:mozilla.org) - Mozilla 的矩阵频道.
- [`google-chrome-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/google-chrome-extension) - 相关问题.
- [`firefox-webextensions` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/firefox-webextensions) - 相关问题.
- [`microsoft-edge-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-edge-extension) - 相关问题.

## Libraries and Frameworks

代码意味着成为扩展的一部分.

- [webext-options-sync](https://github.com/fregante/webext-options-sync) - 帮助您管理和自动保存扩展程序的选项.
- [webext-storage-cache](https://github.com/fregante/webext-storage-cache) - 类似地图的承诺缓存存储过期.
- [webext-dynamic-content-scripts](https://github.com/fregante/webext-dynamic-content-scripts) - 在自定义域上自动注入您的“content_scripts”.
- [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) - Polyfill 支持 `browser` 命名空间中基于标准化承诺的 API.
- [@types/firefox-webext-browser](https://www.npmjs.com/package/@types/firefox-webext-browser) - 为 `browser` 命名空间提供 TypeScript 类型.
- [redux-webext](https://github.com/ivantsov/redux-webext) - 用途 [redux](https://github.com/reactjs/redux) 用于管理 WebExtension 的状态.
- [ExtPay](https://github.com/Glench/ExtPay) - 在扩展中进行安全支付，而无需运行服务器后端.

## Tools

帮助您管理扩展程序的应用程序.

- [Chrome Webstore Upload](https://github.com/DrewML/chrome-webstore-upload-cli) - 通过 cli（或自动在 Travis 上）将扩展程序上传到 Chrome 网上应用店.
- [mozilla/web-ext](https://github.com/mozilla/web-ext) - 帮助构建、运行和测试 WebExtensions 的命令行工具.
- [chromepet](https://github.com/ZenHubIO/chromepet) - 在您的新版本发布时收到通知.
- [chrome-ext-downloader](https://github.com/jiripospisil/chrome-ext-downloader) - 在 Chrome 网上应用店下载任何扩展程序，看看他们是如何做到的.
- [chrome-store-api](https://github.com/acvetkov/chrome-store-api) - Chrome 网上应用店 API 包装器.
- [Chrome extension source viewer](https://github.com/Rob--W/crxviewer) - WebExtension 可直接在商店中查看扩展的源代码.
- [@wext/shipit](https://github.com/LinusU/wext-shipit) - 自动发布到 Chrome Web Store、Mozilla Addons 和 Opera Addons 的工具.
- [wext-manifest-loader](https://github.com/abhijithvijayan/wext-manifest-loader) - Webpack 加载器，可让您指定`manifest.json` 属性仅出现在特定浏览器中.
- [webextension-manifest-loader](https://github.com/jsmnbom/webextension-manifest-loader)  - 加载浏览器定制 manifest.json 的 Webpack 加载器. 它还导入所有可导入的属性，允许您将 &#39;manifest.json&#39; 作为您唯一的 webpack 入口点.

## Testing

- [sinon-chrome](https://github.com/acvetkov/sinon-chrome) - 模拟 Chrome 扩展 API 进行测试.
- [addons-validator](https://github.com/mozilla/addons-validator) - 根据 Mozilla 的指南验证扩展.
- [webextensions-jsdom](https://github.com/stoically/webextensions-jsdom) - 使用基于 manifest.json 的 JSDOM 加载弹出窗口、侧边栏和背景.
- [webextensions-api-fake](https://github.com/stoically/webextensions-api-fake) - 内存中 WebExtensions API 假实现（包括 TypeScript 类型）.
- [webextensions-api-mock](https://github.com/stoically/webextensions-api-mock) - WebExtensions API 作为 sinon 存根（包括 TypeScript 类型）.
- [webextensions-schema](https://github.com/stoically/webextensions-schema) - 以编程方式使用 WebExtensions 架构 JSON 文件.

## Boilerplates

- [browser-extension-template](https://github.com/notlmn/browser-extension-template) - 带有 webpack、选项处理程序和自动发布的准系统样板.
- [create-webextension](https://github.com/rpl/create-webextension) - 纱线 WebExtension 生成器.
- [extensionizr.com](https://extensionizr.com) - 可帮助您创建初始配置和文件的 Web UI.
- [generator-web-extension](https://github.com/HaNdTriX/generator-web-extension) - WebExtension 生成器，可创建开始跨浏览器 Web 扩展开发所需的一切.
- [vue-web-extension](https://github.com/Kocal/vue-web-extension) - Vue CLI 3+ 预设，用于使用 Vue、Babel、ESLint 等快速启动 Web 扩展！

## Sample Extensions

这些是简单而现代的 WebExtensions 存储库，可以帮助您确定各个部分的去向，包括通过 Travis CI 进行自动部署.

- [npmhub](https://github.com/npmhub/npmhub)
- [Hide Files on GitHub](https://github.com/sindresorhus/hide-files-on-github)
- [mdn/webextension-examples](https://github.com/mdn/webextensions-examples) - 为 MDN 文档策划的各种示例扩展.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Federico Brigante](https://bfred.it) 已放弃本作品的所有版权和相关或邻接权.
