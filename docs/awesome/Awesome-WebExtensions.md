<div class="github-widget" data-repo="fregante/Awesome-WebExtensions"></div>
## Awesome WebExtensions [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for WebExtensions development.

WebExtensions are a cross-browser system for developing browser add-ons. To a large extent the system is compatible with the extension API supported by Google Chrome. Extensions written for this browser will in most cases run in Firefox with just [a few changes](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Porting_a_Google_Chrome_extension).

Follow [@fregante](https://fregante.com) for more webext-related news.



## Getting started

- [Chrome Extensions documentation](https://developer.chrome.com/docs/extensions/reference) - Documentation for the original Chrome extension model.
- [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) - MDN wiki for the WebExtensions API.
- [Browser support for WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs) - Compatibility table for Chrome, Edge, Firefox, and Opera.
- [Safari Extensions documentation](https://developer.apple.com/safari/extensions/) - Developer documentation on building Safari extensions. Technically not WebExtensions, the API is completely different.
- [Opera API support](https://dev.opera.com/extensions/apis/) - Detailed WebExtensions support for Opera.
- [Browser Extension Standard](https://browserext.github.io/browserext/) - Standard for the API, supported by Mozilla, Opera and Microsoft.

## Community

- [Google Groups](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions) - Discussions.
- [Mozilla Discourse](https://discourse.mozilla.org/c/add-ons) - Discussions.
- [`#addons:mozilla.org`](https://matrix.to/#/#addons:mozilla.org) - Matrix channel by Mozilla.
- [`google-chrome-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/google-chrome-extension) - Relevant questions.
- [`firefox-addon-webextensions` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/firefox-addon-webextensions) - Relevant questions.
- [`microsoft-edge-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-edge-extension) - Relevant questions.

## Libraries and Frameworks

Code meant become part of the extension.

- [webext-options-sync](https://github.com/fregante/webext-options-sync) - Helps you manage and autosave your extension's options.
- [webext-storage-cache](https://github.com/fregante/webext-storage-cache) - Map-like promised cache storage with expiration.
- [webext-dynamic-content-scripts](https://github.com/fregante/webext-dynamic-content-scripts) - Automatically inject your `content_scripts` on custom domains.
- [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) - Polyfill to support the standardized promise based API in the `browser` namespace.
- [@types/firefox-webext-browser](https://www.npmjs.com/package/@types/firefox-webext-browser) - Supplies TypeScript types for the `browser` namespace.
- [redux-webext](https://github.com/ivantsov/redux-webext) - Uses Redux for managing the state of your WebExtension.
- [ExtPay](https://github.com/Glench/ExtPay) - Take secure payments in extensions without needing to run a server backend.
- [inject-react-anywhere](https://github.com/OlegWock/inject-react-anywhere) - Inject React components into 3rd party sites with convenient API and styles isolation.
- [More…](https://github.com/fregante/webext-fun)

## Tools

Apps that help you manage your extensions.

- [Chrome Webstore Upload](https://github.com/fregante/chrome-webstore-upload-cli) - Upload the extension to the Chrome Web Store via cli (or on Travis, automatically).
- [mozilla/web-ext](https://github.com/mozilla/web-ext) - Command line tool to help build, run, and test WebExtensions.
- [chromepet](https://github.com/ZenHubIO/chromepet) - Get notified when your new version has been published.
- [chrome-ext-downloader](https://github.com/jiripospisil/chrome-ext-downloader) - Download any extension on Chrome Web Store to see how they do it.
- [chrome-store-api](https://github.com/acvetkov/chrome-store-api) - Chrome Web Store API wrapper.
- [Chrome extension source viewer](https://github.com/Rob--W/crxviewer) - WebExtension to view source code of extensions directly on the store.
- [@wext/shipit](https://github.com/LinusU/wext-shipit) - Tool to automatically publish to Chrome Web Store, Mozilla Addons and Opera Addons.
- [wext-manifest-loader](https://github.com/abhijithvijayan/wext-manifest-loader) - Webpack loader that lets you specify `manifest.json` properties to appear only in specific browsers.
- [webextension-manifest-loader](https://github.com/jsmnbom/webextension-manifest-loader) - Webpack loader that loads browser tailored manifest.json. It also imports all importable properties, allowing you to have 'manifest.json' as your only webpack entry point.
- [webpack-extension-reloader](https://github.com/rubenspgcavalcante/webpack-extension-reloader) - A Webpack plugin to automatically reload browser extensions during development.
- [webpack-target-webextension](https://github.com/awesome-webextension/webpack-target-webextension) - Adds code-splitting support to WebExtensions build with Webpack.
- [Extension.js](https://github.com/cezaraugusto/extension.js) - Plug-and-play, zero-config, cross-browser extension development tool.

## Testing

- [sinon-chrome](https://github.com/acvetkov/sinon-chrome) - Mocks the Chrome Extensions API for testing.
- [addons-linter](https://github.com/mozilla/addons-linter) - Validate an extension against Mozilla's guidelines.
- [webextensions-jsdom](https://github.com/stoically/webextensions-jsdom) - Load popup, sidebar and background with JSDOM based on the manifest.json.
- [webextensions-api-fake](https://github.com/stoically/webextensions-api-fake) - In-memory WebExtensions API Fake Implementation (includes TypeScript types).
- [webextensions-api-mock](https://github.com/stoically/webextensions-api-mock) - WebExtensions API as sinon stubs (includes TypeScript types).
- [webextensions-schema](https://github.com/stoically/webextensions-schema) - Programmatically consume the WebExtensions Schema JSON files.

## Boilerplates

- [browser-extension-template](https://github.com/fregante/browser-extension-template) - Barebones boilerplate with parcel, options handler and auto-publishing.
- [create-webextension](https://github.com/rpl/create-webextension) - Yarn WebExtension generator.
- [generator-web-extension](https://github.com/webextension-toolbox/generator-web-extension) - WebExtension generator that creates everything you need to get started with cross-browser web-extension development.
- [WXT](https://github.com/wxt-dev/wxt) - Next-gen framework for developing web extensions

## Sample Extensions

These are simple and modern WebExtensions repositories that could help you figure out where pieces go, including automatic deployment via Travis CI.

- [npmhub](https://github.com/npmhub/npmhub)
- [Hide Files on GitHub](https://github.com/sindresorhus/hide-files-on-github)
- [mdn/webextension-examples](https://github.com/mdn/webextensions-examples) - Various example extensions curated for the MDN documentation.
