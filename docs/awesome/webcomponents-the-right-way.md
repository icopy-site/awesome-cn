<div class="github-widget" data-repo="mateusortiz/webcomponents-the-right-way"></div>
## Web Components the Right Way

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

&gt;精选的Web组件资源的精选列表.

[Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) - 一套不同的技术，允许您创建可重复使用的自定义元素 - 其功能与其他代码封装在一起 - 并在您的Web应用程序中使用它们.



&gt;网络组件正确的方式是由爱 [Mateus Ortiz](https://twitter.com/mteusortiz) 并维护 [Serhii Kulykov](https://twitter.com/serhiikulykov)

## Specifications

### Standards

-  **自定义元素**为作者提供了一种构建自己的全功能DOM元素的方法.
  - [HTML Living Standard](https://html.spec.whatwg.org/multipage/custom-elements.html)
  - [DOM Living Standard](https://dom.spec.whatwg.org/#concept-element)
  - [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements)
  - [Chrome Platform Status metrics](https://chromestatus.com/metrics/feature/timeline/popularity/1689)

-  ** Shadow DOM **描述了一种将多个DOM树组合成一个层次结构的方法，以及这些树如何在文档中相互交互，从而实现更好的DOM组合.
  - [DOM Living Standard](https://dom.spec.whatwg.org/#shadow-trees)，第4.2.2节：影子树
  - [DOM Living Standard](https://dom.spec.whatwg.org/#interface-shadowroot)，第4.8节：接口`ShadowRoot`
  - [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/shadow-dom)
  - [Chrome Platform Status metrics](https://chromestatus.com/metrics/feature/timeline/popularity/804)

  -  **` <template>  `**元素用于声明可以通过脚本克隆并插入到文档中的HTML片段.
  - [HTML Living Standard](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element)
  - [Chrome Platform Status metrics](https://chromestatus.com/metrics/feature/timeline/popularity/2769)

### Proposals

#### CSS Shadow Parts

- [W3C First Public Working Draft](https://www.w3.org/TR/css-shadow-parts-1/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/css/css-shadow-parts)
- [Explainer: CSS Shadow ::part and ::theme](https://github.com/fergald/docs/blob/master/explainers/css-shadow-parts-1.md)
- [::part and ::theme pseudo elements on shadow hosts](https://www.chromestatus.com/features/5763933658939392) -  Chrome平台状态功能.
- [Mozilla issue: Implement CSS Shadow Parts](https://bugzilla.mozilla.org/show_bug.cgi?id=1505489)
- [WebKit issue: Add the support for the CSS shadow parts](https://bugs.webkit.org/show_bug.cgi?id=149443)

#### Form-associated Custom Elements

- [Form Participation API Explained](https://docs.google.com/document/d/1JO8puctCSpW-ZYGU8lF-h4FWRIDQNDVexzHoOQ2iQmY/edit?usp=sharing) -  Google Chrome小组提供的文档.
- [Form-associated custom elements](https://www.chromestatus.com/features/4708990554472448) -  Chrome平台状态功能.
- [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements/form-associated)

#### Constructable Stylesheet Objects

- [Specification Draft](https://wicg.github.io/construct-stylesheets/)
- [web-platform-tests](https://github.com/web-platform-tests/wpt/blob/master/css/cssom/CSSStyleSheet-constructable.html)
- [Explainer](https://github.com/WICG/construct-stylesheets/blob/gh-pages/explainer.md)
- [Constructable Stylesheets](https://www.chromestatus.com/feature/5394843094220800) -  Chrome平台状态功能.

#### Builtin Modules

- [std-switch](https://github.com/tkent-google/std-switch)   - 提议` <std-switch>  `实现&#39;switch&#39;控件的HTML元素.
- [std-toast](https://github.com/jackbsteinberg/std-toast)   - 提议` <std-toast>  `HTML元素实现&#39;toast&#39;弹出通知.
  - [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/std-toast)

### Polyfills

#### @webcomponents

下面的polyfills由Polymer团队维护.

- [@webcomponents/custom-elements](https://github.com/webcomponents/polyfills/tree/master/packages/custom-elements) - 用于HTML自定义元素v1的Polyfill.
- [@webcomponents/shadydom](https://github.com/webcomponents/polyfills/tree/master/packages/shadydom) -  ShadowDOM v1垫片.
- [@webcomponents/shadycss](https://github.com/webcomponents/polyfills/tree/master/packages/shadycss) -  ShadowDOM样式封装垫片.
- [@webcomponents/template](https://github.com/webcomponents/polyfills/tree/master/packages/template)   - `的最小polyfill <template>  `.

#### @ungap

下面的polyfill由维护 [ungap project](https://ungap.github.io).

- [@ungap/custom-elements-builtin](https://github.com/ungap/custom-elements-builtin) - 内置自定义元素的polyfill扩展.

## Articles

### Introduction

- [The Holy Grail Of Reusable Components: Custom Elements, Shadow DOM, And NPM](https://www.smashingmagazine.com/2018/07/reusable-components-custom-elements-shadow-dom-npm/)
- [The Power of Web Components](https://hacks.mozilla.org/2018/11/the-power-of-web-components/)
- [The Case for Web Components](https://alankent.me/2019/02/20/the-case-for-web-components/)
- [Styling a Web Component](https://css-tricks.com/styling-a-web-component/)
- [Web Components 101: An Introduction to Web Components](https://www.telerik.com/blogs/web-components-101-an-introduction-to-web-components)
- [Web Components in 2018](https://www.sitepen.com/blog/2018/07/06/web-components-in-2018/)
- [Web Components Introduction: Creating Custom HTML Elements in 2018](https://www.grapecity.com/en/blogs/web-components-introduction-creating-custom-html-elements-2018)
- [Web Components in 2019: An Overview of the Most Exciting Proposals for the Web Platform Related to Web Components](https://scotch.io/bar-talk/an-overview-of-the-most-exciting-proposals-for-the-web-platform-related-to-web-components?utm_source=scotch&utm_campaign=share&utm_medium=twitter)

### Custom Elements

- [Custom Elements v1: Reusable Web Components](https://developers.google.com/web/fundamentals/web-components/customelements)
- [Custom Elements Everywhere](https://custom-elements-everywhere.com)
- [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements)
- [Introducing Custom Elements (WebKit)](https://webkit.org/blog/7027/introducing-custom-elements/)
- [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439)
- [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133)
- [Custom Elements That Work Anywhere](https://robdodson.me/interoperable-custom-elements/)
- [Using Custom Elements (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
- [A Guide to Custom Elements for React Developers](https://css-tricks.com/a-guide-to-custom-elements-for-react-developers/)

### Shadow DOM

- [Shadow DOM v1: Self-Contained Web Components](https://developers.google.com/web/fundamentals/web-components/shadowdom)
- [What is the Shadow DOM?](https://bitsofco.de/what-is-the-shadow-dom/)
- [The Rise of Shadow DOM](https://medium.com/front-end-hacking/the-rise-of-shadow-dom-84aa1f731e82)
- [Shadow DOM in depth](https://github.com/praveenpuglia/shadow-dom-in-depth)
- [What's New in Shadow DOM v1 (by examples)](http://hayato.io/2016/shadowdomv1/)
- [Introducing Slot-Based Shadow DOM API (WebKit)](https://webkit.org/blog/4096/introducing-shadow-dom-api/)
- [Using Shadow DOM (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
- [Open vs. Closed Shadow DOM](https://blog.revillweb.com/open-vs-closed-shadow-dom-9f3d7427d1af)

### HTML Templates

- [&lt;template&gt;: The Content Template element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
- [Using templates and slots (MDN)](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots))

### Best Practices

- [Custom Element Best Practices](https://developers.google.com/web/fundamentals/web-components/best-practices)
- [Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)
- [Guidelines for creating web platform compatible components](https://w3ctag.github.io/webcomponents-design-guidelines/)
- [HowTo: Components](https://developers.google.com/web/fundamentals/web-components/examples/)
- [Open Web Components Recommendations](https://open-wc.org)

### Accessibility

- [Styling Accessibility: A Web Components Approach](https://medium.com/@cfscorreia/styling-accessibility-a-web-components-approach-dc2aa8123eb2)
- [The future of accessibility for custom elements](https://robdodson.me/the-future-of-accessibility-for-custom-elements/)
- [Web components still need to be accessible](https://www.24a11y.com/2018/web-components-still-need-to-be-accessible/)

### Use Cases

- [Bringing Order to Web Design Chaos (with Web Components)](https://dev.to/thatjoemoore/bringing-order-to-web-design-chaos--3fhb)
- [ING ❤ Web Components](https://dev.to/thepassle/ing--web-components-aef)
- [Lessons Learned, making our app with Web Components](https://medium.com/samsung-internet-dev/lessons-learned-making-our-app-with-web-components-bf55379cfcda)
- [Making Web Components Work](https://engineering.mixpanel.com/2018/06/12/making-web-components-work/)
- [Micro Frontends — extending the microservice idea to frontend development](https://micro-frontends.org)
- [Web Components — the right way](https://equinsuocha.io/blog/web-components-the-right-way/)
- [Reasons Web Components are perfect for a big company](https://medium.com/@sergicontre/reasons-web-components-are-perfect-for-a-big-company-28790d712ad5)

## Libraries

### Class Based

- [Corpuscule](https://github.com/corpusculejs/corpuscule) - 基于装饰器的小型Web组件框架.
- [LitElement](https://lit-element.polymer-project.org)   - 用于创建快速，轻量级Web组件的简单基类.  聚合物项目的一部分.
- [Lightning Web Components](https://github.com/salesforce/lwc) - 超快速，企业级Web组件基础.
- [Omi](https://github.com/Tencent/omi) -  4kb JavaScript中的下一代Web框架（Web组件+ JSX +代理+存储+路径更新）.
- [Polymer](https://polymer-library.polymer-project.org) -  Polymer Project作者的原始Web组件库.
- [Skate](https://github.com/skatejs/skatejs) -  Web组件库，专注于功能渲染管道和小占用空间.
- [slim.js](https://github.com/slimjs/slim.js) - 基于现代标准的快速，强大的前端微框架.
- [Smart Custom Element](https://github.com/HTMLElements/smart-custom-element) - 用于使用简单API创建自定义元素的UI库.

### Functional

- [atomico](https://github.com/atomicojs/atomico) - 使用函数和钩子创建基于Web组件的接口的小型库.
- [haunted](https://github.com/matthewp/haunted) - 针对Web组件实现的React的Hooks API.
- [hybrids](https://github.com/hybridsjs/hybrids) - 用于使用简单和功能API创建Web组件的UI库.
- [reLift-HTML](https://github.com/mardix/relift-html) - 小型（3kb）视图库，允许创建Web组件并使HTML页面具有反应性.
- [osagai](https://github.com/HenriqueLimas/osagai) - 以功能方式创建Web组件的小型库.
- [Switzerland](https://github.com/Wildhoney/Switzerland) - 允许通过中间件功能以功能方式创建Web组件的库.
- [ullr](https://github.com/aggre/ullr) - 用于使用函数式编程构建Web组件的库.

### Compilers

- [Stencil](https://stenciljs.com) - 生成Web组件的编译器.
- [Svelte](https://svelte.dev) -  Cyber​​netically增强的Web应用程序（可以选择生成Web组件）.

### Other

- [custom-element-ts](https://github.com/geocine/custom-elements-ts) - 使用Typescript创建本机自定义元素，而不使用任何第三方库.
- [preact-custom-element](https://github.com/bspaulding/preact-custom-element) - 从预执行组件生成/注册自定义元素.
- [remount](https://github.com/rstacruz/remount) - Mount React components to the DOM using custom elements.

## Component Libraries

- [Amber Components](https://github.com/bitrockteam/amber-components) -  Amber Design System的Web Components实现.
- [AMP HTML](https://github.com/ampproject/amphtml) - 用于构建具有可靠和快速性能的Web页面的Web组件库.
- [carbon-custom-elements](https://github.com/carbon-design-system/carbon-custom-elements) - 使用Custom Elements和Shadow DOM构建的Carbon Design System的实验变体.
- [Elix](https://github.com/elix/elix) - 用于常见用户界面模式的高质量，可定制的Web组件.
- [LRNWebComponents](https://github.com/elmsln/lrnwebcomponents/) -  ELMS：LN为任何项目生成Web组件.
- [Material Web Components](https://github.com/material-components/material-components-web-components) - 作为Web组件实现的Material Design.
- [PatternFly Elements](https://github.com/patternfly/patternfly-elements) - 灵活轻量级Web组件的集合，以及构建它们的工具.
- [UI5 Web Components](https://github.com/SAP/ui5-webcomponents) - 组件库，在本机API之上提供企业级糖.
- [Vaadin components](https://github.com/vaadin/vaadin) - 用于构建业务Web应用程序的不断发展的高质量Web组件集.
- [Wired Elements](https://github.com/wiredjs/wired-elements) - 具有手绘，粗略外观的常见UI元素集.

## Frameworks

### Overview

- [JavaScript frameworks, meet Web Components](https://www.voorhoede.nl/nl/blog/javascript-frameworks-meet-web-components/)
- [Web Components: Seamlessly interoperable](https://medium.com/@sergicontre/web-components-seamlessly-interoperable-82efd6989ca4)

### Angular

- [Angular Elements Overview](https://angular.io/guide/elements)
- [Angular Elements, Part I: A Dynamic Dashboard In Four Steps With Web Components](https://www.softwarearchitekt.at/post/2018/07/13/angular-elements-part-i-a-dynamic-dashboard-in-four-steps-with-web-components.aspx)
- [Angular Elements, Part II: Lazy And External Web Components](https://www.softwarearchitekt.at/post/2018/07/29/angular-elements-part-ii-lazy-and-external-web-components.aspx)
- [Angular Elements, Part III: Angular Elements Without Zone.Js](https://www.softwarearchitekt.at/post/2018/07/06/angular-elements-without-zone-js.aspx)
- [Angular Elements, Part IV: Content Projection with Slots in Angular Elements (>=7)](https://www.softwarearchitekt.at/post/2018/10/31/content-projection-with-slots-in-angular-elements-7.aspx)
- [Angular Elements, Part V: Your Options For Building Angular Elements With The CLI](https://www.softwarearchitekt.at/post/2019/01/27/building-angular-elements-with-the-cli.aspx)
- [Building Custom Elements / Web Components with Angular 6](https://medium.com/@tomsu/building-web-components-with-angular-elements-746cd2a38d5b)
- [Web Components With Angular Ivy In 6 Steps](https://www.softwarearchitekt.at/post/2019/05/18/web-components-custom-elements-with-angular-ivy-in-6-steps.aspx)

### Vue

- [Create & Publish Web Components With Vue CLI 3](https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/)
- [Get started with Vue web components](https://medium.com/@royprins/get-started-with-vue-web-components-593b3d5b3200)

### Aurelia

- [Aurelia Web Components plugin](https://github.com/aurelia/web-components)

## Books

- [Web Components in Action](https://www.manning.com/books/web-components-in-action) - 由Ben Farrell预订，可在Manning早期发布计划中找到.
- [Web Component Essentials](https://leanpub.com/web-component-essentials) - 由Cory Rylan预订，Leanpub提供早期预览版.

## Tutorials

- “**让我们构建Web组件！**” [Benny Powers](https://github.com/bennypowers)
  - [Part 1: The Standards](https://dev.to/bennypowers/lets-build-web-components-part-1-the-standards-3e85)
  - [Part 2: The Polyfills](https://dev.to/bennypowers/lets-build-web-components-part-2-the-polyfills-dkh)
  - [Part 3: Vanilla Components](https://dev.to/bennypowers/lets-build-web-components-part-3-vanilla-components-4on3)
  - [Part 4: Polymer Library](https://dev.to/bennypowers/lets-build-web-components-part-4-polymer-library-4dk2)
  - [Part 5: LitElement](https://dev.to/bennypowers/lets-build-web-components-part-5-litelement-906)
  - [Part 6: Gluon](https://dev.to/bennypowers/lets-build-web-components-part-6-gluon-27ll)

- “** Web组件：从零到英雄**”由 [Pascal Schilp](https://github.com/thepassle)
  - [Part 1: An introduction to writing raw Web Components](https://dev.to/thepassle/web-components-from-zero-to-hero-4n4m)
  - [Part 2: Supercharging Web Components with lit-html](https://dev.to/thepassle/web-components-from-zero-to-hero-part-two-38p4)
  - [Part 3: Web Components hero with LitElement](https://dev.to/thepassle/web-components-from-zero-to-hero-part-three-3c5h)

-  ** CSS技巧**文章系列 [Caleb Williams](https://css-tricks.com/author/calebdwilliams/)
  - [Part 1: An Introduction to Web Components](https://css-tricks.com/an-introduction-to-web-components/)
  - [Part 2: Crafting Reusable HTML Templates](https://css-tricks.com/crafting-reusable-html-templates/)
  - [Part 3: Creating a Custom Element from Scratch](https://css-tricks.com/creating-a-custom-element-from-scratch)
  - [Part 4: Encapsulating Style and Structure with Shadow DOM](https://css-tricks.com/encapsulating-style-and-structure-with-shadow-dom/)
  - [Part 5: Advanced Tooling for Web Components](https://css-tricks.com/advanced-tooling-for-web-components/)

## Miscellaneous

- [bruck](https://github.com/Heydon/bruck) - 使用Web组件和Houdini Paint API构建的原型系统.
- [webcomponents.dev](https://webcomponents.dev) - 您的Web组件工作室.
- [webcomponents.org](http://webcomponents.org/) - 讨论和分享网络组件.
- [webcomponents.news](http://webcomponents.news) - 展示Web组件的文章，教程，微库和网站的集合.
- [web-components-benchmark](https://github.com/vogloblinsky/web-components-benchmark) - 使用各种Web组件技术的Todo列表应用程序的基准测试.
- [web-components-examples](https://github.com/mdn/web-components-examples) - 与MDN Web组件文档相关的一系列Web组件示例.
- [web-components-todo](https://github.com/shprink/web-components-todo) - 使用各种Web组件技术构建的简单待办事项列表.

## History

下面的文章代表了标准化过程中Web组件规范的长篇故事.
其中一些涉及早期的，所谓的“v0”Shadow DOM和自定义元素规范，以及废弃的HTML Imports规范.
这些材料仅出于历史原因，按年份分组并按时间顺序列出.

### 2017

- [Web Components: The Long Game](https://infrequently.org/2017/10/web-components-the-long-game/)
- [The broken promise of Web Components](https://dmitriid.com/blog/2017/03/the-broken-promise-of-web-components/)
- [Regarding the broken promise of Web Components](http://robdodson.me/regarding-the-broken-promise-of-web-components/)

### 2016

- [Demythstifying Web Components](http://www.backalleycoder.com/2016/08/26/demythstifying-web-components/)
- [Understanding Web Components](https://medium.com/the-ui-files/understanding-web-components-d051baa66019)

### 2015

- [Web Components and their role in the future of web development](http://kaytcat.github.io/web-components/)
- [Microsoft Edge and Web Components](https://blogs.windows.com/msedgedev/2015/07/15/microsoft-edge-and-web-components/)
- [Bringing componentization to the web: An overview of Web Components](https://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/)
- [The state of Web Components](https://hacks.mozilla.org/2015/06/the-state-of-web-components/)

### 2014

- [A No-Nonsense Guide to Web Components](http://cbateman.com/blog/a-no-nonsense-guide-to-web-components-part-1-the-specs/)
- [Mozilla and Web Components: Update](https://hacks.mozilla.org/2014/12/mozilla-and-web-components/)
- [The State of the Componentised Web](https://www.leggetter.co.uk/2014/08/06/state-componentised-web.html)
- [Web Components and you – dangers to avoid](https://christianheilmann.com/2014/04/18/web-components-and-you-dangers-to-avoid/)
- [The Web's Declarative, Composable Future](https://addyosmani.com/blog/the-webs-declarative-composable-future/)

### 2013

- [A Guide to Web Components](https://css-tricks.com/modular-future-web-components/)

### 2012

- [Notes on Web Components + ARIA](https://developer.paciellogroup.com/blog/2012/07/notes-on-web-components-aria/)
- [Introduction to Web Components](https://www.w3.org/TR/2012/WD-components-intro-20120522/)

### 2011

- [Web Components and Model Driven Views by Alex Russell](https://fronteers.nl/congres/2011/sessions/web-components-and-model-driven-views-alex-russell)
- [What the Heck is Shadow DOM?](https://glazkov.com/2011/01/14/what-the-heck-is-shadow-dom/)

## Who To Follow

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://twitter.com/ChromiumDev">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1065986962467647489/Qrc3K-jZ_80x80.jpg">
          <div> Chrome开发者</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/polymer">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1063502058337136640/RmlG_bbW_80x80.jpg">
          <div>聚合物</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/MSEdgeUpdates">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/984976713351356416/YtUr94vb_80x80.jpg">
          <div>边缘平台更新</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/web_components">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/836671393844572160/eRcwt6Fw_80x80.jpg">
          <div> Web组件</div>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://twitter.com/shadow_hayato">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/448411087294046208/Nd6c9fr-_80x80.png">
          <div>隼人伊藤</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/rob_dodson">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1031947699019427840/xl6p8ZBu_80x80.jpg">
          <div>罗布多德森</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/ebidel">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/955031454781616129/JRpZOp1l_80x80.jpg">
          <div>埃里克·比德曼</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/justinfagnani">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/378800000808710206/2dbdaa1cb7b0db02f997aea5b40f29b8_80x80.jpeg">
          <div>贾斯汀法加尼</div>
        </a>
      </td>
    </tr>
  <tbody>
</table>

## License

版权所有2014-2018，保留所有权利.

根据以下许可的代码：
[MIT license](http://mateusortiz.mit-license.org)

@author Mateus Ortiz <mteusortiz@gmail.com>
