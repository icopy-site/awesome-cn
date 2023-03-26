<div class="github-widget" data-repo="thomasbnt/awesome-web-monetization"></div>
<img src="https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/wm_icon_animated.svg?sanitize=true" alt="Logo Web Monetization" align="right" width="120px" />

## Awesome Web Monetization [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

 &gt; 关于 Web Monetization 的精彩内容. 了解更多信息，检查模块和其他工具.

**Web Monetization** 是一项网络服务，可让您直接在浏览器中汇款.
这是一个 JavaScript 浏览器 API，允许创建从用户代理到网站的支付流



## About Web Monetization

- [Webmonetization.org](https://webmonetization.org/)
- [Documentation](https://webmonetization.org/docs/getting-started)
- [How Web Monetization work for paying payments](https://webmonetization.org/docs/sending)
- [How Web Monetization work for receiving payments](https://webmonetization.org/docs/receiving)
- [Specifications](https://webmonetization.org/specification.html)
- [ILP Forum](https://forum.interledger.org/)
- [Grant For The Web](https://www.grantfortheweb.org/)

---

- [Interledger : Open protocol suite for sending payments across different ledgers](https://interledger.org/)

## How to start monetize my website

如果您想通过您的内容获利，您必须拥有电子钱包和提供商帐户. 请参阅下面允许您使用它们的平台.

<details><summary>有关钱包和提供商帐户的更多详细信息</summary>
<p>

---

 |  **钱包** |  |  |  |  |
| :---------: | :-------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
 | 名称 | [![Uphold](https://webmonetization.org/img/uphold_logo.svg)](https://uphold.com/) | [![GateHub](https://webmonetization.org/img/gatehub_logo.svg)](https://gatehub.net/) | [![Stronghold](https://webmonetization.org/img/stronghold_logo.svg)](https://stronghold.co/real-time-payments) | [New Wallet ?<br>Create a issue !](https://github.com/thomasbnt/awesome-web-monetization/issues/new?assignees=thomasbnt&labels=Wallet%2C+%E2%86%94+WM+repository&template=new-wallet.md&title=%5BWa%5D) |
 | 费用 | 无 |  SEPA：1.00 欧元 &lt; 50,000 欧元<br>电汇：最低 15 美元（最高 150 美元）|  \$3 取款费 |  |

如果您已经在使用 XRP Tipbot， [check here to migrate on Uphold](https://webmonetization.org/docs/xrptipbot).

 |  **付款** |  |
| ------------ | ------ |
 | 名称 | 空的.  |

---

</p>
</details>

在您的网页上，将您的“货币化”标签整合到元数据中

```html
<meta name="monetization" content="$ilp.example.com/123456789" />
```

并检测是否可以“货币化”，然后开始工作

```js
如果（文件.货币化）{
  document.monetization.addEventListener(&quot;货币化开始&quot;, () =&gt; {
    控制台日志（
      “太棒了！您使用 Web Monetization.\n更多信息 https://webmonetization.org”
    );
  });
}
```

## Resources

### Packages

_任何包/模块和插件_

- [svelte-monetization](https://github.com/wobsoriano/svelte-monetization)  - Web Monetization API 的最小轻量级包装器.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/svelte.png)
- [monetize.js](https://github.com/sunchayn/monetize.js)  - 一个事件驱动的库来管理和模拟网络货币化.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [types-wm](https://github.com/dacioromero/types-wm) - Web 货币化的 TypeScript 定义！[](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/typescript.png)
- [ngx-monetization](https://github.com/CDDelta/ngx-monetization)  - Angular 的网络货币化 API.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/angular.png)
- [react-hook-wm](https://github.com/dacioromero/react-hook-wm)  - 用于与 Web Monetization 集成的 React 挂钩.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/react.png)
- [react-monetize](https://github.com/guidovizoso/react-monetize)  - 帮助程序和挂钩可加快您与 Web Monetization API 的集成.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/react.png)
- [ep_monetization](https://github.com/ISNIT0/ep_monetization)  - 用于将支付指针元标记应用于 Etherpad 站点的插件.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [wp-connect-coil](https://wordpress.org/plugins/wp-connect-coil/)  - 用于将 Coil 支付指针元标记应用于 WordPress 站点的插件.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/wordpress.png)
- [xrptipbot-wordpress-widget](https://wordpress.org/plugins/widget-xrptipbot/)  - 基于 XRPTIPBOT 嵌入代码的 Wordpress Widget 来捐赠内容创作者.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/wordpress.png)
- [eleventy-plugin-monetization](https://github.com/DanCanetti/eleventy-plugin-monetization)  - 用于通过帖子和网站内容获利的 Eleventy 插件.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/11ty.png)
- [web-monetization-components](https://github.com/philnash/web-monetization-components)  - 您可以在您的网络货币化网站上使用的网络组件集合.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [revshare](https://github.com/kewbish/revshare)  - 用于收益共享的 JS 库.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [web-monetization-proxy](https://github.com/tcdowney/web-monetization-proxy)  - 用于注入 Web Monetization 元标记的简单 Go 代理.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/go.png)
- [gridsome-plugin-monetization](https://github.com/Sergix/gridsome-plugin-monetization)  - Gridsome 的网络货币化.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/gridsome.png)
- [vuepress-plugin-web-monetization](https://github.com/spekulatius/vuepress-plugin-web-monetization)  - 将网络货币化元标记添加到您的 VuePress 网站.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/vuejs.png)
- [jekyll-web_monetization](https://github.com/philnash/jekyll-web_monetization)  - 一个 Jekyll 插件，用于将 Web MonetizationAPI 支付指针添加到您的站点.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/jekyll.png)
- [Monetization](https://github.com/KNawm/monetization)  - 一个围绕 Web Monetization API 的包装器，用于通过应用程序获利.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/dart.png)
- [react-webmonetization-meta](https://github.com/uchibeke/react-webmonetization-meta)  - React 的网络货币化元标记管理器.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/react.png)
- [web-monetization-electron-app](https://github.com/Jasmin2895/web-monetization-electron-app)  - 项目演示了在 Electron App 中启用网络货币化的基本设置.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/electron.png)
- [web-monetized-video](https://github.com/Jasmin2895/web-monetized-video)  - 具有播放和付费政策的网络组件，并根据观看的视频量向您收费.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [web-monetization-polyfill](https://github.com/immers-space/web-monetization-polyfill/)  - 确保 JavaScript Web Monetization API 可用，即使在启用了内容安全策略的环境中也是如此.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [web-monetization-video-ads](https://www.npmjs.com/package/web-monetization-video-ads)  - 将 Web Monetization 与视频广告联系起来，以允许为 Web Monetization 实施免费增值业务模型.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [web-monetization-revenue-share](https://www.npmjs.com/package/web-monetization-revenue-share)  - 通过智能合约自动将资金重新分配给社区.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [awesome-jsgames](https://github.com/proyecto26/awesome-jsgames) - 精彩 JavaScript 游戏精选列表！[](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [mediadisclosures](https://github.com/oofdere/mediadisclosures)  - 一个开源的、不断发展的、通用的内容评级系统.  ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [web-monetization-demo](https://github.com/peter279k/web-monetization-demo) - 这是一个网络货币化演示！[](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)
- [money-chat](https://github.com/dfoderick/money-chat) - 网络货币化聊天应用程序！[](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png)

### Tutorials

- [Getting started](https://webmonetization.org/docs/getting-started) - 来自 webmonetization.org 的官方文件.
- [Exclusive content](https://webmonetization.org/docs/exclusive-content) - 将独家内容放在您的网站上.
- [Exclusive content in a Godot web game](https://innkeepergames.com/how-to-monetize-a-godot-game-with-web-monetization) - 将独家内容放入使用 Godot 游戏引擎制作的网页游戏中.
- ['A Web Monetization Story'](https://esse-dev.github.io/a-web-monetization-story/) - 面向在线创作者的交互式、基于故事的 Web 货币化教程.
- [Web Monetization like I'm 5](https://dev.to/hacksultan/web-monetization-like-i-m-5-1418) - 通过网络获利！

### Articles

- [Monetizing Content in View](https://dev.to/godwinagedah/monetizing-content-in-view-paying-for-what-you-see-462a) - 为你所看到的付出代价.
- [Web Components](https://dev.to/philnash/web-components-for-the-web-monetization-api-4ed9) - 对于 Web Monetization API（系列）.

### Newsletters

- [Newsletter of grantfortheweb.org](https://www.grantfortheweb.org/signup) - 注册电子邮件更新.

### Tools

- [Is web monetized](https://github.com/jkga/is-web-monetized) - 一个非常简单的工具，用于检查是否启用了 Web Monetization.

  &gt;```狂欢
  &gt; npm 安装是-web-货币化-g
  &gt; 货币化 example.com
  > ```
  >
  &gt; 您也可以测试您的网站 [with the dependency](https://github.com/jkga/is-web-monetized#usage).

- [Paytrackr](https://github.com/sorxrob/paytrackr) - 在一个地方跟踪和管理您的小额支付.

  &gt; PayTrackr 是跟踪和管理您对网络货币化网站的小额支付的最简单和最安全的方式，拥有网络货币化提供商会员资格.

- [Akita](https://github.com/esse-dev/akita) - 一个浏览器扩展，让您深入了解您对网络货币化的参与.

  &gt; Akita 展示了您最常访问的货币化网站、您在这些网站上花费的时间以及您正在（或可能）为它们做出的贡献.

- [Open Monetization Wallet](https://github.com/signalnerve/openmonetizationwallet) - 用于管理您的虚荣网络货币化钱包的工具.

   &gt; Open Monetization Wallet (OMW) 使大规模接受 Web Monetization API 付款变得更加容易. 一些特点：
  >
  &gt; - 自定义钱包 URL：拥有自己的“支付指针”，例如 $wallet.signalnerve.com，而不是 $pay.stronghold.co/abcdef123
  &gt; - 无需停机即可在钱包/供应商之间切换
  &gt; - 收到付款请求的日志
  &gt; - 多个钱包之间的收入共享，例如多个团队成员
  &gt; - 使用无服务器技术无限扩展
  &gt; - 免费和开源

### Community

- [Web Monetization Community](https://community.interledger.org/)
- [@GrantForTheWeb on Twitter](https://twitter.com/GrantForTheWeb)
- [@CinnamonVideo on Twitter](https://twitter.com/CinnamonVideo)
- [Web Monetization tag on DEV](https://dev.to/t/webmonetization)

---

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/thomasbnt/awesome-web-monetization/blob/master/contributing.md) 第一的.
您还可以做出贡献，与您的朋友共享此存储库和 Web Monetization.

如果要添加新的小图标，高度必须是**16px**. 放入 `assets/small_icons/NAME.png`. 只接受 PNG 格式.

&gt; **由 Netlify 提供支持** ✨

Netlify 供电 [the website](https://awesomewebmonetization.netlify.app/). Thanks to them! 💚

[![Deploys by Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://netlify.com)

## Donate

随时提供帮助 [me](https://github.com/thomasbnt) 为了维护这个项目！
感谢所有 **GitHub 上的赞助商**！

[![GitHub Sponsors](https://cdn.jsdelivr.net/gh/thomasbnt/sponsors/sponsors.svg)](https://github.com/sponsors/thomasbnt)

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor%20me-%23EA54AE.svg?&style=for-the-badge&logo=github-sponsors&logoColor=white)](https://github.com/sponsors/thomasbnt) [![Support me on Buy Me a Coffee](https://img.shields.io/badge/Support%20me-on%20Buy%20Me%20a%20Coffee-white?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black&labelColor=%23FFDD00)](https://www.buymeacoffee.com/thomasbnt?via=thomasbnt)
