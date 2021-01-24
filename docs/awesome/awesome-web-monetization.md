<div class="github-widget" data-repo="thomasbnt/awesome-web-monetization"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<img src="https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/wm_icon_animated.svg?sanitize=true" alt="Logo Web Monetization" align="right" width="120px" />

## Awesome Web Monetization [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

 &gt;关于Web货币化的真棒材料. 了解更多信息，检查模块和其他工具.

**网络获利**是一项网络服务，可让您直接在浏览器中汇款.
这是一个JavaScript浏览器API，允许创建从用户代理到网站的付款流



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
- [Coil : Web monetized content in your browser while supporting sites you love in real time.](https://coil.com)

## How to start monetize my website

如果您想通过自己的内容获利，则必须拥有电子钱包和提供商帐户. 请参阅下面允许您使用它们的平台.

<details><summary>在这里更多细节</summary>
<p>

 |  **钱包** |  |  |  |  |
| :---------: | :------------------------------: | :-----------------------------------------------------: | :------------------------------------------: | :--------------------------------------------------: |
 | 姓名|  [！[坚持] [坚持徽标]] [坚持] |  [！[GateHub] [gatehub-logo]] [gatehub] |  [！[Stronghold] [stronghold-logo]] [stronghold] |  [新钱包？<br> 创建问题！] [new-wallet-issue] |
 | 费用| 无|  SEPA：1.00欧元&lt;50,000欧元<br>电汇：每分钟$ 15（最高$ 150）|  \ $ 3提款费|  |

[new-wallet-issue]：https://github.com/thomasbnt/awesome-web-monetization/issues/new?assignees=thomasbnt&amp;labels=Wallet%2C+%E2%86%94+WM+repository&amp;template=new-wallet. md＆title =％5BWa％5D
[gatehub]：https：//gatehub.net/
[gatehub-logo]：https://webmonetization.org/img/gatehub_logo.svg
[stronghold]: https://stronghold.co/real-time-payments#coil
[stronghold-logo]：https://webmonetization.org/img/stronghold_logo.svg
[坚持]：https://uphold.com/
[uphold-logo]：https：//webmonetization.org/img/uphold_logo.svg

如果您已经在使用XRP Tipbot， [check here to migrate on Uphold](https://webmonetization.org/docs/xrptipbot).

 |  **付款** |  |
| ------------ |   --------------------------------------------------------------------------      |
| Name         | [![Coil](https://webmonetization.org/img/coil_logo.svg)](https://coil.com/signup) |

</p>
</details>

在您的网页上，在meta上插入您的`monetization`标签

```html
<meta name="monetization" content="$ilp.example.com/123456789" />
```

并检测是否可以货币化，然后开始工作

```js
如果（document.monetization）{
  document.monetization.addEventListener（“ monetizationstart”，（）=&gt; {
    console.log（
      “太棒了！您可以使用Web获利.\ n更多信息https://webmonetization.org”
    );
  });
}
```

## Resources

### Packages

_任何包/模块和插件_

- [svelte-monetization](https://github.com/sorxrob/svelte-monetization)  -Web Monetization API的最小且轻巧的包装器.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/svelte.png）
- [monetize.js](https://github.com/sunchayn/monetize.js)  -一个事件驱动的库，用于管理和模拟Web货币化.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png）
- [types-wm](https://github.com/dacioromero/types-wm) -用于网络获利的TypeScript定义！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/typescript.png）
- [ngx-monetization](https://github.com/CDDelta/ngx-monetization)  -Angular的Web货币化API.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/angular.png）
- [react-hook-wm](https://github.com/dacioromero/react-hook-wm)  -用于与Web货币化集成的React挂钩.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/react.png）
- [react-monetize](https://github.com/guidovizoso/react-monetize)  -帮助程序和挂钩可以加快您与Web货币化API的集成.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/react.png）
- [ep_monetization](https://github.com/ISNIT0/ep_monetization)  -用于将付款指针元标记应用于Etherpad网站的插件.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png）
- [wp-connect-coil](https://wordpress.org/plugins/wp-connect-coil/)  -用于将Coil付款指针元标记应用于WordPress网站的插件.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/wordpress.png）
- [xrptipbot-wordpress-widget](https://wordpress.org/plugins/widget-xrptipbot/)  -基于XRPTIPBOT的Wordpress Widget嵌入代码以捐赠内容创建者.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/wordpress.png）
- [eleventy-plugin-monetization](https://github.com/DanCanetti/eleventy-plugin-monetization)  -Eleventy插件，用于通过帖子和网站内容获利.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/11ty.png）
- [web-monetization-components](https://github.com/philnash/web-monetization-components)  -您可以在通过网络获利的网站上使用的Web组件的集合.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png）
- [revshare](https://github.com/kewbish/revshare)  -用于收益分享的JS库.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png）
- [web-monetized-video](https://github.com/Jasmin2895/web-monetized-video)  -试用网络获利API.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png）
- [web-monetization-proxy](https://github.com/tcdowney/web-monetization-proxy) - Simple Go proxy for injecting Web Monetization meta tags. ![](https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/go.png)
- [gridsome-plugin-monetization](https://github.com/Sergix/gridsome-plugin-monetization)  -Gridsome的网络货币化.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/gridsome.png）
- [vuepress-plugin-web-monetization](https://github.com/spekulatius/vuepress-plugin-web-monetization)  -将网络获利的元标记添加到您的VuePress网站.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/vuejs.png）
- [jekyll-web_monetization](https://github.com/philnash/jekyll-web_monetization)  -Jekyll插件，用于将Web MonetizationAPI付款指针添加到您的网站.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/jekyll.png）
- [Monetization](https://github.com/KNawm/monetization)  -围绕Web获利API的包装器，用于通过应用获利.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/dart.png）
- [react-webmonetization-meta](https://github.com/uchibeke/react-webmonetization-meta)  -用于React的Web货币化元标记管理器.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/react.png）
- [web-monetization-electron-app](https://github.com/Jasmin2895/web-monetization-electron-app)  -项目演示了用于在Electron App中启用网络获利的基本设置.  ！[]（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/electron.png）
- [web-monetized-video](https://github.com/Jasmin2895/web-monetized-video)  -具有播放和付款政策的网络组件，并向您收取观看视频的费用.  []（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png）
- [web-monetization-polyfill](https://github.com/immers-space/web-monetization-polyfill/)  -即使在启用了内容安全策略的环境中，也要确保JavaScript Web获利API可用.  []（https://raw.githubusercontent.com/thomasbnt/awesome-web-monetization/master/assets/small_icons/javascript.png）

### Tutorials

- [Getting started](https://webmonetization.org/docs/getting-started) -来自webmonetization.org的正式文档.
- [Exclusive content](https://webmonetization.org/docs/exclusive-content) -在您的网站上放独家内容.
- [Exclusive content in a Godot web game](https://innkeepergames.com/how-to-monetize-a-godot-game-with-web-monetization) -将独家内容放入使用Godot Game Engine制作的网络游戏中.
- ['A Web Monetization Story'](https://esse-dev.github.io/a-web-monetization-story/) -面向在线创作者的交互式，基于故事的Web货币化教程.
- [Web Monetization like I'm 5](https://dev.to/hacksultan/web-monetization-like-i-m-5-1418) -通过网络获利！

### Articles

- [Monetizing Content in View](https://dev.to/godwinagedah/monetizing-content-in-view-paying-for-what-you-see-462a) -支付您所看到的.
- [Web Components](https://dev.to/philnash/web-components-for-the-web-monetization-api-4ed9) -对于Web获利API（系列）.

### Newsletters

- [Newsletter of grantfortheweb.org](https://www.grantfortheweb.org/signup) -注册电子邮件更新.

### Tools

- [Is web monetized](https://github.com/jkga/is-web-monetized) -一个非常简单的工具，用于检查是否启用了网络获利.

- [Paytrackr](https://github.com/sorxrob/paytrackr) -将小额付款跟踪和管理到一个地方.

  &gt; PayTrackr是拥有网络货币化提供商会员资格的最简单，最安全的跟踪和管理您通过网络货币化的网站的小额付款的方法.

- [Akita](https://github.com/esse-dev/akita) -一个浏览器扩展程序，可让您深入了解Web货币化的参与.

  &gt;秋田介绍您访问量最大的获利网站，您在这些网站上花费的时间以及为它们做出的贡献（或可能做出的贡献）.

- [Open Monetization Wallet](https://github.com/signalnerve/openmonetizationwallet) -用于管理个性化网络货币钱包的工具.

   &gt; Open Monetization Wallet（OMW）使使用Web Monetization API大规模接受付款变得更加容易. 一些功能：
  >
  &gt;-自定义钱包URL：拥有自己的“付款指针”，例如$ wallet.signalnerve.com，而不是$ pay.stronghold.co / abcdef123
  &gt;-在没有停机的情况下在钱包/提供商之间进行切换
  &gt;-收款请求日志
  &gt;-多个钱包之间的收益共享，例如多个团队成员
  &gt;-借助无服务器技术无限扩展
  &gt;-免费和开源

### Community

- [grantfortheweb.org forum](https://forum.grantfortheweb.org/)
- [@GrantForTheWeb on Twitter](https://twitter.com/GrantForTheWeb)
- [@Coil on Twitter](https://twitter.com/Coil)
- [@CinnamonVideo on Twitter](https://twitter.com/CinnamonVideo)
- [Web Monetization tag on DEV](https://dev.to/t/webmonetization)

---

## Contribute

欢迎捐款！ 阅读 [contribution guidelines](https://github.com/thomasbnt/awesome-web-monetization/blob/master/contributing.md) 第一.
您也可以与朋友共享该存储库和Web货币化. 

如果要添加新的小图标，则高度必须为** 16px **. 放入`assets / small_icons / NAME.png`. 仅接受格式PNG.
