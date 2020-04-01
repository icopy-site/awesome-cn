<div class="github-widget" data-repo="fregante/Awesome-WebExtensions"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome WebExtensions [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

&gt;精选的精选资源列表 [WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) 发展.

 WebExtensions是用于开发浏览器附加组件的跨浏览器系统.  该系统在很大程度上与 [extension API](https://developer.chrome.com/extensions)  受Google Chrome和Opera支持.  在大多数情况下，为这些浏览器编写的扩展程序将在Firefox或 [Microsoft Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/documentation/extensions/) 只是 [a few changes](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Porting_a_Google_Chrome_extension).



## Getting started

- [Chrome Extensions documentation](https://developer.chrome.com/extensions) -原始Chrome扩展程序模型的文档.
- [Chrome Extensions API](https://developer.chrome.com/extensions/api_index) -有关Chrome提供的原始API的全面文档.
- [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) -WebExtensions API的MDN Wiki.
- [Browser support for WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs) -适用于Chrome，Edge，Firefox和Opera的兼容性表.
- [Microsoft Edge API support](https://docs.microsoft.com/en-us/microsoft-edge/extensions/api-support/extension-api-roadmap) -对Edge的详细WebExtensions支持.
- [Safari Extensions documentation](https://developer.apple.com/safari/extensions/)  -有关构建Safari扩展的开发人员文档.  从技术上讲，不是WebExtensions，而是完全不同的API.
- [Opera API support](https://dev.opera.com/extensions/apis/) -对Opera的详细WebExtensions支持.
- [Porting Chrome Extensions to Firefox](https://hacks.mozilla.org/2015/10/porting-chrome-extensions-to-firefox-with-webextensions/) -准备，安装和调试要在Firefox中移植的Chrome扩展程序的指南.
- [Browser Extension Standard](https://browserext.github.io/browserext/) -API的标准，由Mozilla，Opera和Microsoft支持.

## Community

- [Google Groups](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions) -讨论.
- [Mozilla Discourse](https://discourse.mozilla.org/c/add-ons) -讨论.
- [`#addons:mozilla.org`](https://matrix.to/#/#addons:mozilla.org) -Mozilla的矩阵频道.
- [`google-chrome-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/google-chrome-extension) -相关问题.
- [`firefox-webextensions` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/firefox-webextensions) -相关问题.
- [`microsoft-edge-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-edge-extension) -相关问题.

## Libraries and Frameworks

代码意味着成为扩展的一部分.

- [webext-options-sync](https://github.com/fregante/webext-options-sync) -帮助您管理和自动保存扩展程序的选项.
- [webext-storage-cache](https://github.com/fregante/webext-storage-cache) -类似于地图的承诺缓存存储，具有到期时间.
- [webext-dynamic-content-scripts](https://github.com/fregante/webext-dynamic-content-scripts) -自动将您的`content_scripts`注入自定义域.
- [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) -Polyfill支持`browser`命名空间中基于标准化Promise的API.
- [redux-webext](https://github.com/ivantsov/redux-webext) -用途 [redux](https://github.com/reactjs/redux) 用于管理WebExtension的状态.

## Tools

可以帮助您管理扩展程序的应用程序.

- [Chrome Webstore Upload](https://github.com/DrewML/chrome-webstore-upload-cli) -通过cli（或自动在Travis上）将扩展程序上传到Chrome网上应用店.
- [mozilla/web-ext](https://github.com/mozilla/web-ext) -命令行工具，可帮助构建，运行和测试WebExtensions.
- [chromepet](https://github.com/ZenHubIO/chromepet) -发布新版本时获得通知.
- [chrome-ext-downloader](https://github.com/jiripospisil/chrome-ext-downloader) -在Chrome网上应用店下载任何扩展程序，以了解其操作方法.
- [chrome-store-api](https://github.com/acvetkov/chrome-store-api) -Chrome Web Store API包装器.
- [Chrome extension source viewer](https://github.com/Rob--W/crxviewer) -WebExtension，可直接在商店上查看扩展的源代码.
- [@wext/shipit](https://github.com/LinusU/wext-shipit) -自动发布到Chrome网上应用店，Mozilla插件和Opera插件的工具.
- [web-ext-translator](https://github.com/Lusito/web-ext-translator) -管理i18n messages.json的翻译器工具.
- [wext-manifest](https://github.com/abhijithvijayan/wext-manifest) -可让您指定“ manifest.json”属性，使其仅出现在特定的浏览器中.

## Testing

- [sinon-chrome](https://github.com/acvetkov/sinon-chrome) -修改Chrome扩展程序API进行测试.
- [addons-validator](https://github.com/mozilla/addons-validator) -根据Mozilla的指南验证扩展.
- [webextensions-jsdom](https://github.com/stoically/webextensions-jsdom) -根据manifest.json使用JSDOM加载弹出窗口，侧边栏和背景.
- [webextensions-api-fake](https://github.com/stoically/webextensions-api-fake) -内存中的WebExtensions API伪实现（包括TypeScript类型）.
- [webextensions-api-mock](https://github.com/stoically/webextensions-api-mock) -作为sinon存根的WebExtensions API（包括TypeScript类型）.
- [webextensions-schema](https://github.com/stoically/webextensions-schema) -以编程方式使用WebExtensions架构JSON文件.

## Boilerplates

- [browser-extension-template](https://github.com/notlmn/browser-extension-template) -带webpack，选项处理程序和自动发布的准系统样板.
- [create-webextension](https://github.com/rpl/create-webextension) -纱线WebExtension生成器.
- [extensionizr.com](https://extensionizr.com) -Web UI，可帮助您创建初始配置和文件.
- [generator-web-extension](https://github.com/HaNdTriX/generator-web-extension) -WebExtension生成器，创建跨浏览器Web扩展开发入门所需的一切.

## Sample Extensions

这些是简单而现代的WebExtensions存储库，可以帮助您确定组件的运行方向，包括通过Travis CI自动部署.

- [npmhub](https://github.com/npmhub/npmhub)
- [Hide Files on GitHub](https://github.com/sindresorhus/hide-files-on-github)
- [mdn/webextension-examples](https://github.com/mdn/webextensions-examples) -为MDN文档精选了各种示例扩展.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Federico Brigante](https://bfred.it) 已放弃此作品的所有版权以及相关或邻近的权利.
