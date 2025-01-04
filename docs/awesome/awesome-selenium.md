<div class="github-widget" data-repo="christian-bromann/awesome-selenium"></div>
## Awesome Selenium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Test Awesome List](https://github.com/christian-bromann/awesome-selenium/actions/workflows/test.yaml/badge.svg)](https://github.com/christian-bromann/awesome-selenium/actions/workflows/test.yaml)

> A curated list of delightful [Selenium](http://www.seleniumhq.org/) [resources](#resources).

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Resources


### Tools

#### Javascript

- [selenium-webdriver](https://github.com/SeleniumHQ/selenium/wiki/WebDriverJs) - The official WebDriver JavaScript bindings from the Selenium project.
- [WD](https://github.com/admc/wd) - WebDriver/Selenium 2 node.js client.
- [WebdriverIO](http://webdriver.io) - better implementation of WebDriver bindings with predefined 50+ actions.
- [Zombie.js](http://zombie.js.org/) - Insanely fast, headless full-stack testing.
- [SlimerJS](http://slimerjs.org/) - A scriptable browser for Web developers.
- [Nightwatch](http://nightwatchjs.org/) - efficient and straightforward Javascript End-to-End tests.
- [Karma](http://karma-runner.github.io/0.12/index.html) - Brings a productive testing environment to developers for unit testing (mostly AngularJS).
- [Protractor](https://angular.github.io/protractor/) - Protractor is an end-to-end test framework for AngularJS applications.
- [CodeceptJS](http://codecept.io/) - Modern Era Acceptance Testing Framework for NodeJS.

#### Ruby

- [Selenium with Ruby](http://seleniumhq.github.io/selenium/docs/api/rb/index.html) - Selenium Ruby bindings
- [Watir](http://watir.github.io) - Automated testing that doesn’t hurt
- [Anemone](https://github.com/chriskite/anemone) - Anemone web-spider framework.
- [Mechanize](http://docs.seattlerb.org/mechanize/) - automating interaction with websites.
- [Spidr](https://github.com/postmodern/spidr) - web spidering library that can spider a site, multiple domains, certain links or infinitely.
- [cobweb](https://rubygems.org/gems/cobweb) - web crawler that can use resque to cluster crawls to quickly crawl extremely large sites.
- [Capybara](https://rubygems.org/gems/capybara) - an integration testing tool for rack based web applications. It simulates how a user would interact with a website.

#### PHP
- [Facebook WebDriver](https://github.com/facebook/php-webdriver) - A PHP client for webdriver.
- [Selenium Setup](https://github.com/bogdananton/Selenium-Setup) - A tool for PHP developers to start their own Selenium server.
- [Steward](https://github.com/lmc-eu/steward) - A test runner integrating php-webdriver with PHPUnit.

#### Python

- [Selenium with Python](http://selenium-python.readthedocs.io/) - Selenium Python bindings
- [Helium](https://github.com/mherrmann/selenium-python-helium) - Helium makes Selenium easier and faster to use
- [Selene](https://github.com/yashaka/selene) - Selenide-inspired concise and readable automated test framework, supports Ajax well like Selenide.
- [mechanize](http://wwwsearch.sourceforge.net/mechanize/) - Stateful programmatic web browsing.
- [Robot](http://robotframework.org/) - Robot Framework is a generic test automation framework for acceptance testing and ATDD.
- [behave-webdriver](https://github.com/spyoungtech/behave-webdriver) behavior driven testing with Selenium and Python.

#### Java

- [Selenium with Java](http://seleniumhq.github.io/selenium/docs/api/java/index.html) - Selenium Java bindings
- [Conductor](http://conductor.ddavison.io) - Turbo-boosted Selenium framework that makes test writing a breeze.
- [darcy](https://github.com/darcy-framework/darcy-webdriver) - Page object framework for structured, maintainable automation.
- [Selenide](https://github.com/codeborne/selenide) - A framework for writing easy-to-read and easy-to-maintain automated tests using a Fluent API. Selenide has a magic trick that resolves most problems with Ajax and timeouts.
- [Galen Framework](http://galenframework.com/) - Automated testing of look and feel for your responsive websites.
- [Serenity](http://www.thucydides.info/) - It is an open source library for writing better quality automated acceptance tests faster. (Formerly Thucydides).
- [seleniumQuery](https://github.com/seleniumQuery/seleniumQuery) - jQuery-like cross-driver interface in Java for WebDriver. Designed as a thin layer, it can be used alone or on top of your favorite framework just to make some cases (e.g. asserting/waiting) simpler when needed.
- [WebDriverManager](https://github.com/bonigarcia/webdrivermanager) - Automatic management of Selenium WebDriver binaries.
- [Lightning](https://github.com/aerokube/lightning-java) - Lightweight and lightning fast WebDriver client.

#### C#

- [Selenium with C#](http://seleniumhq.github.io/selenium/docs/api/dotnet/index.html) - Selenium C# bindings
- [Atata](https://github.com/atata-framework/atata) - Automated web testing full featured framework based on Selenium WebDriver.
- [Strontium](https://github.com/jimevans/strontium) - A .NET implementation (but outdated) for Selenium/WebDriver (Remote) Server

#### Groovy

- [Geb](http://www.gebish.org/) - It can be used for scripting, scraping and general automation — or equally as a functional/web/acceptance testing solution via integration with testing frameworks such as Spock, JUnit & TestNG.

#### Dart

- [dart.webdriver](https://github.com/google/webdriver.dart) - Provides WebDriver bindings for Dart. These use the WebDriver JSON interface, and as such, require the use of the WebDriver remote server.

### CSS Regression Testing

- [WebdriverCSS](https://github.com/webdriverio/webdrivercss) - Regression testing tool for [WebdriverIO](http://webdriver.io) (currently deprecated, please use [wdio-screenshot](https://www.npmjs.com/package/wdio-screenshot) for the time being).

### Containers

#### Docker

- [elgalu/docker-selenium](https://github.com/elgalu/docker-selenium) - Selenium in Docker with Chrome & Firefox plus video recording support.
- [Ggr](https://github.com/aerokube/ggr) - A lightweight load balancer used to create big Selenium clusters.
- [SeleniumHQ/docker-selenium](https://github.com/SeleniumHQ/docker-selenium) - Docker images for Selenium Standalone Server, Hub, and Node configurations with Chrome and Firefox.
- [Selenoid](https://github.com/aerokube/selenoid) - A lightweight Selenium hub implementation launching browsers in Docker containers.
- [zalando/zalenium](https://github.com/zalando/zalenium) - Allows anyone to have a disposable and flexible Selenium Grid infrastructure
- [bravostudiodev/bravo-grid](https://github.com/bravostudiodev/bravo-grid) - Docker image/setup for Selenium Grid Extras (see under Selenium Grid section), for providing remote Sikuli test/automation execution and grid node file upload/download support.

#### Kubernetes
- [kubernetes/examples](https://github.com/kubernetes/examples/tree/master/staging/selenium) - Example deployment of Selenium Hub and Nodes on a Kubernetes cluster
- [Moon](https://github.com/aerokube/moon) - A commercial closed-source enterprise Selenium implementation using Kubernetes to launch browsers
- [Callisto](https://github.com/wrike/callisto) - An open-source tool to launch browsers in Kubernetes. Separate is created for each selenium session.
- [WebGrid](https://github.com/TilBlechschmidt/WebGrid) - An open-source, decentralized, scalable and robust selenium-grid equivalent.

### Driver

#### Desktop (browsers)

- [Firefox](https://github.com/SeleniumHQ/selenium/wiki/FirefoxDriver) - Firefox driver (for FF < v48) is included in the selenium-server-standalone.jar available in the downloads.
- [Geckodriver](https://github.com/mozilla/geckodriver) - Firefox driver (for FF > v48), supported with Selenium >= v3
- [Chrome](https://sites.google.com/a/chromium.org/chromedriver/home) - ChromeDriver is a standalone server which implements WebDriver's wire protocol for Chromium.
- [Internet Explorer](https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver) - The InternetExplorerDriver is a standalone server which implements WebDriver's wire protocol.
- [Edgedriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/) - Microsoft Webdriver server for Edge
- [Safari](https://github.com/SeleniumHQ/selenium/wiki/SafariDriver) - The SafariDriver is implemented as a Safari browser extension. The driver inverts the traditional client/server relationship and communicates with the WebDriver client using WebSockets (only supported for Safari <= v9, all new Safari version comming with macOS Sierra come with an integrated SafariDriver that is closed source by Apple).
- [Opera](https://github.com/operasoftware/operachromiumdriver/blob/master/README.md) - OperaDriver is a vendor-supported WebDriver implementation developed by Opera Software and volunteers that implements WebDriver API for Opera.

#### Mobile (browsers and apps)

- [Appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps. It drives iOS, Android Apps using the WebDriver protocol.
- [Selendroid](http://selendroid.io/mobileWeb.html) - Selendroid is based on the Android instrumentation framework.
- [ios-driver](http://ios-driver.github.io/ios-driver/) - Test any IOS native, hybrid, or mobile web application using Selenium / WebDriver.
- [WebDriverAgent](https://github.com/manishPatwari/WebDriverAgent) - a WebDriver server for iOS to remote control devices via WebDriver API.

#### Desktop GUI Automation (non-browser-centric)

- [WinAppDriver](https://github.com/Microsoft/WinAppDriver) - Microsoft's WebDriver implementation for Windows application automation.
- [Winium](https://github.com/2gis/Winium) - Automation framework for Windows platforms. It is free. It is opensource. It is Selenium-based. Supports: Windows Desktop (WPF, WinForms); Windows Store or Universal Apps for Windows Phone; Windows Phone Silverlight Apps.
- [QtWebDriver](https://github.com/cisco-open-source/qtwebdriver) - For using WebDriver to automate Qt-based GUI applications.
- [AutoItDriverServer](https://github.com/daluu/AutoItDriverServer) - Selenium server to control/drive AutoIt via (Remote)WebDriver API.
- [AutoPyDriverServer](https://github.com/daluu/AutoPyDriverServer) - Selenium server to control/drive AutoPy via (Remote)WebDriver API.
- [Appium for Mac](https://github.com/christian-bromann/awesome-selenium/blob/master/[https://appium.io/docs/en/drivers/mac/](https://github.com/appium/appium-mac2-driver)) - Appium/WebDriver implementation for automating Mac OS X desktop.
- [SilkAppDriver](https://github.com/MicroFocus/SilkAppDriver) - Selenium server to control/drive the commercial SilkTest platform via (Remote)WebDriver API.

### Desktop Tools

- [SWET](https://github.com/sergueik/SWET) - A successor to SWD Page Recorder, for the same functionality.
- [Looking Glass](https://github.com/dmolchanenko/LookingGlass) - Java application that offers a cross-browser element inspector and Selenium code generator.
- [Silk WebDriver](https://www.microfocus.com/products/silk-portfolio/silk-webdriver/) - A Selenium IDE alternative for record, playback, and script export, from the creators of SilkTest.
- [Fire IE Selenium](https://code.google.com/archive/p/fire-ie-selenium/) - Microsoft Excel-based tool providing element inspection for Internet Explorer browser.

### Selenium Grid

- [Selenium Grid Extras](https://github.com/groupon/Selenium-Grid-Extras) - A framework that provides additional features beyond the basic Selenium Grid like video recording.
- [SeLion](https://github.com/paypal/SeLion) - A (Java) framework for running Selenium tests with additional features beyond the basic Selenium Grid functionality, particularly like stability improvements, etc.
- [Selenium Grid Extensions](https://github.com/sterodium/selenium-grid-extensions) - A set of extensions for Selenium Grid that provide additional features like running Sikuli tests/automation remotely, upload/download files on a grid node.

### Cloud Services

- [Sauce Labs](https://saucelabs.com) - Cross browser testing made awesome. Selenium testing, mobile testing, JS unit testing on 300+ OS/browser platforms. Get started for free.
- [HeadSpin](https://www.headspin.io/) - Test your website for cross browser compatibility on thousands of real device running real browsers. Get instant access to multiple desktop and mobile browsers on the cloud. Get Free Trial.
- [Browserstack](https://www.browserstack.com/) - Test your website for cross browser compatibility on real browsers. Instant access to multiple desktop and mobile browsers. Get Free Trial.
- [TestGrid](https://www.testgrid.io/) - End to End testing of mobile apps & websites on 1000+ real browsers & OS. Request Free Trial.
- [LambdaTest](https://www.lambdatest.com/selenium-automation) - Test your website for cross browser compatibility on 2000+ real browsers & OS. Get Free Trial.
- [TestingBot](https://testingbot.com) - TestingBot provides easy cross browser testing with Selenium in the cloud.
- [Moon Cloud](https://aerokube.com/moon-cloud/) - Your dedicated Selenium cluster in public cloud platform with per-minute billing and unlimited number of browsers.
- [Mail7](https://www.mail7.io/) - Disposable email service to automate the email workflow testing, [This document](https://docs.mail7.io/tutorials/registration-and-login-automation-using-selenium-with-disposable-email) explains how to implement Mail7 with Selenium
- [Thundra Foresight](https://www.thundra.io/foresight) - A visibility tool into your test suites by spotting test failures in no time.
- [Hyperbrowser](https://hyperbrowser.ai/) - Browser infrastructure and automation for running and scaling Selenium automations with headless Chrome with advanced features like proxies, captcha solving, and session recording.

### Device Farms

- [OpenSTF](https://github.com/DeviceFarmer/stf) - A framework for running your own device farm, geared toward Android, but also iOS.

### Web Scraping / Mining

- [Scrapy](http://scrapy.org) - **Python**, mainly a scraper/miner - fast, well documented and, can be linked with [Django Dynamic Scraper](http://django-dynamic-scraper.readthedocs.org/en/latest/) for nice mining deployments, or [Scrapy Cloud](http://scrapinghub.com/scrapy-cloud.html) for PaaS (server-less) deployment, works in terminal or an server stand-alone process, can be used with **Celery**, built on top of **Twisted**.
- [Node-Crawler](https://github.com/sylvinus/node-crawler) - **Node.js** Web Crawler/Spider for NodeJS + server-side jQuery.

### Specifications

- [The WebDriver Wire Protocol](https://www.selenium.dev/documentation/legacy/json_wire_protocol/) - All implementations of WebDriver that communicate with the browser, or a RemoteWebDriver server shall use a common wire protocol.
- [WebDriver](http://www.w3.org/TR/webdriver/) - This specification defines the WebDriver API, a platform and language-neutral interface and associated wire protocol that allows programs or scripts to introspect into, and control the behavior of, a web browser.

### Blogs

- [Official Selenium Blog](https://www.selenium.dev/blog/) - The official blog by SeleniumHQ.
- [Elemental Selenium](http://elementalselenium.com/) - A free, once-weekly e-mail on how to use Selenium like a Pro.
- [SauceLabs Blog](https://saucelabs.com/blog) - Blog curated by SauceLabs.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christian Bromann](http://www.christian-bromann.com/) has waived all copyright and related or neighboring rights to this work.
