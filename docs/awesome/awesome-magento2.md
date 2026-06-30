<div class="github-widget" data-repo="DavidLambauer/awesome-magento2"></div>
## Awesome Magento 2

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Enrich](https://github.com/run-as-root/awesome-magento2/actions/workflows/enrich.yml/badge.svg)](https://github.com/run-as-root/awesome-magento2/actions/workflows/enrich.yml)
[![Discover](https://github.com/run-as-root/awesome-magento2/actions/workflows/discover.yml/badge.svg)](https://github.com/run-as-root/awesome-magento2/actions/workflows/discover.yml)
[![Last commit](https://img.shields.io/github/last-commit/run-as-root/awesome-magento2)](https://github.com/run-as-root/awesome-magento2/commits/master)

<div align="center">
	<a href="https://vshymanskyy.github.io/StandWithUkraine">
		<img width="500" height="350" src="https://raw.githubusercontent.com/DavidLambauer/awesome-magento2/master/media/logo-ua.svg?sanitize=true" alt="Awesome">
		<img src="https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg">
	</a>
	<br>
	<br>
	<br>
	<br>
	<hr>
</div>


> A curated list of awesome Magento 2 Extensions & Resources.

> Tracking **231** projects · **57** actively maintained · **9** 🔥 hot · **43** 🪦 on the graveyard shelf.

- [What is an awesome list?](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
- [Contribution guide](https://github.com/DavidLambauer/awesome-magento2/blob/master/contributing.md) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/DavidLambauer/awesome-magento2/issues)

---



---

## Legend

Signals are refreshed weekly by an automated pipeline. Each badge reflects the current state of an entry:

- 🔥 **Hot** — one of the top-10% most-starred GitHub repos in its category (requires at least 5 GitHub entries in the category).
- 🫡 **Actively maintained** — last commit within 90 days and a release within the last year.
- 🪦 **Graveyard** — archived on GitHub or no commits/releases in the last three years. Graveyard entries live in a collapsed block at the bottom of their section and are kept for historical reference. Pinned entries are never moved here.

---

## What is Magento?

Magento is an open-source e-commerce application that allows you to create webshops. We often speak of a frontend (the
storefront where customers buy products) and a backend (the Magento Admin Panel where customers and products are being
managed). The open source bit refers to the fact that the source code of Magento (PHP, HTML, CSS, JS, XML, and others)
is distributed under an open-source license (OSLv3) that allows anyone to reuse the code and make changes to it. This
open-source aspect has led to the massive popularity of the product Magento so that we often use the word Magento to
refer to either the product, the community around it or both.

Magento was started by a company called Varien, and with Magento version 1 (first released in 2008), popularity began to grow.
Magento version 2 was first released in November 2015 but faced a problematic adoption because of its complex
architecture and outdated features (KnockoutJS, RequireJS, Zend Framework 1). On the storefront part,
this led to various new frontends. In 2018, Magento was acquired by Adobe. Later, Magento Enterprise was integrated
into the Adobe cloud as Adobe Commerce Cloud, while the Magento Community Edition was relabeled Magento Open Source. In
the community, there was uncertainty whether Adobe would maintain Magento Open Source in the long run in the way
the community would see fit. This uncertainty led to a community initiative called Mage-OS.

Also see:

- [en.wikipedia.org/wiki/Magento](https://en.wikipedia.org/wiki/Magento)

## Events: Meet the community

- [MageUnconference Netherlands](https://mageunconference.nl/) 🫡 - Magento unconference held in the Netherlands.
- [Meet Commerce](https://www.meetcommerce.com/) 🫡 - Global series of conferences focused on commerce and innovation.
- [MageUnconference Germany](https://www.mageunconference.org/) - Magento unconference held in Germany.

### Meet Magento

[Meet Magento events](https://www.meet-magento.com/) bring together everyone from merchants through developers, solution and technology providers, and marketers—and we continue to expand.

- [Meet Magento Brazil](https://meetmagentobrasil.org/) 🫡 - Meet Magento event series — Brazil.
- [Meet Magento Florida](https://meetmagentofl.com/) 🫡 - Meet Magento event series — Florida.
- [Meet Magento India](https://www.meetmagento.in/) 🫡 - Meet Magento event series — India.
- [Meet Magento Netherlands](https://nl.meet-magento.com/) 🫡 - Meet Magento event series — Netherlands.
- [Meet Magento New York City](https://meetmagentonyc.com/) 🫡 - Meet Magento event series — NYC.
- [Meet Magento UK](https://meet-magento.co.uk/) 🫡 - Meet Magento event series — UK.
- [Meet Magento Malaysia](https://www.meetmagento.asia/) - Meet Magento event series — Malaysia.
- [Meet Magento Romania](https://ro.meet-magento.com/) - Meet Magento event series — Romania.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [Meet Magento Baltics](https://meetmagentobaltics.com/) - Meet Magento event series — Baltics.
- [Meet Magento Poland](https://meetmagento.pl/) - Meet Magento event series — Poland.
- [Meet Magento Singapore](https://meetmagento.sg/) - Meet Magento event series — Singapore.

</details>

## Front-ends

The storefront of Magento 2 can be styled in numerous ways:

- [Adobe PWA Studio](https://developer.adobe.com/commerce/pwa-studio/) - Adobe's headless React frontend. GraphQL client; offers Venia theme, Peregrine hooks, Buildpack (Webpack) and UPWARD (SSR/image middleware).
- [Magento Luma](https://developer.adobe.com/commerce/frontend-core/guide/) - Magento 2's default demo theme (extends Magento/blank). The name also refers to the whole Luma stack: XML layout + blocks/containers + PHTML templates, enriched with LESS-compiled CSS and RequireJS/KnockoutJS/jQuery.
- [Alokai](https://github.com/vuestorefront/vue-storefront) - Formerly Vue Storefront — headless frontend framework.
- [ScandiPWA](https://github.com/scandipwa/scandipwa) - React/Redux PWA theme for Magento 2.3+.
- [Breeze Evolution](https://breezefront.com/themes) - Lightweight Luma-compatible theme targeting 100 PageSpeed.
- [Front-Commerce](https://www.front-commerce.com/) - French PWA front-end solution for Magento.
- [Hyvä](https://hyva.io/) - Luma replacement using TailwindCSS and AlpineJS. Commercial license. Active compatibility-module ecosystem.

## Tools

- [PhpInsights](https://github.com/nunomaduro/phpinsights) 🔥 🫡 - PHP quality checks with Magento 2 presets.
- [DDEV](https://github.com/ddev/ddev) 🔥 🫡 - Open source tool for launching local web development environments in minutes. Supports PHP, Node.js and Python.
- [markshust/docker-magento](https://github.com/markshust/docker-magento) 🫡 - Mark Shust's Docker configuration for Magento.
- [n98-magerun2](https://github.com/netz98/n98-magerun2) 🫡 - The CLI Swiss Army Knife for Magento 2.
- [Warden](https://github.com/wardenenv/warden) 🫡 - CLI utility for working with docker-compose environments by David Alger.
- [PhpStorm Magento2 Extension](https://github.com/magento/magento2-phpstorm-plugin) 🫡 - Official PhpStorm Magento 2 extension.
- [Magento 2 Url Data Integrity Checker](https://github.com/baldwin-agency/magento2-module-url-data-integrity-checker) 🫡 - Magento 2 module that finds potential URL-related problems in your catalog data.
- [Mage](https://github.com/GrimLink/mage) 🫡 - Simplifies bin/magento commands with shortcuts and productivity helpers.
- [MageForge](https://github.com/OpenForgeProject/mageforge) 🫡 - Magento 2 CLI automatic theme builder (Hyvä ready).
- [Mage Chrome Toolbar](https://github.com/magespecialist/mage-chrome-toolbar) - Chrome extension for Magento 2 development by MageSpecialist.
- [AmpersandHQ/ampersand-magento2-upgrade-patch-helper](https://github.com/AmpersandHQ/ampersand-magento2-upgrade-patch-helper) - Helper script to aid upgrading Magento 2 websites by detecting overrides.
- [MageSpecialist DevTools for Magento 2](https://github.com/magespecialist/m2-MSP_DevTools) - Developer toolbar for Magento 2.
- [Tango](https://github.com/roma-glushko/tango) - CLI for analyzing access logs.
- [Migrate DB Magento 2 Commerce to Magento 2 Open-Source](https://github.com/opengento/magento2-downgrade-ee-ce) - Migrate a Magento 2 Commerce database to Magento 2 Open Source.
- [Magento 2 Database Synchronizer](https://github.com/jellesiderius/mage-db-sync) - Database synchronizer for Magento 2 (and WordPress), based on Magerun2. Keeps development, staging and production in sync.
- [RabbitMQ Retry Mechanism](https://github.com/run-as-root/magento2-message-queue-retry) - Magento 2 extension that brings possibility to retry RabbitMQ failed messages.
- [Mage Wizard](https://github.com/clickAndMortar/mage-wizard) - Local web UI to view and create modules, plugins, configs, observers, commands, crontabs directly in a Magento 2 codebase.
- [magento2docker](https://github.com/aliuosio/magento2docker) - MariaDB, PHP, Redis, ElasticSearch in one Dockerfile for fast demo/development environments.
- [Mage2Gen](https://mage2gen.com/) - Online module creator.
- [Magento 2 Composer patches helper](https://chrome.google.com/webstore/detail/magento-2-composer-patche/gfndadbceejgfjahpfaijcacnmdloiad) - Chrome extension to create copy-pastable composer patch definitions for vaimo/composer-patches.
- [Magento Log Viewer (VS Code extension)](https://marketplace.visualstudio.com/items?itemName=MathiasElle.magento-log-viewer) - VS Code extension to view, watch and manage Magento log files and reports directly in your workspace.
- [Tablerates Generator](https://www.tableratesgenerator.com/) - Generate tablerates online.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [Pestle](https://github.com/astorm/pestle) - Code generation tool by Alan Storm.
- [Masquerade](https://github.com/elgentos/masquerade) - Faker-driven, configuration-based, platform-agnostic, locale-compatible data faker tool.
- [Subodha Magento2 Gulp Integration](https://github.com/subodha/magento-2-gulp) - Magento 2 Gulp integration.
- [Documentation Search for Alfred](https://github.com/DavidLambauer/Alfred-Workflow-Magento-2-DevDocs-Search) - Alfred workflow integrating the official Magento 2 documentation search.

</details>

## Open Source Extensions

### Development Utilities

- [Magento Cache Clean](https://github.com/mage2tv/magento-cache-clean) 🔥 - A faster drop-in replacement for bin/magento cache:clean with file watcher by Vinai Kopp.
- [Magewire PHP](https://github.com/magewirephp/magewire) 🫡 - A Laravel Livewire port for building complex AJAX-based components with ease. Used by the Hyvä Checkout.
- [Config ImportExport](https://github.com/semaio/Magento2-ConfigImportExport) 🫡 - CLI-based config management.
- [bitExpert/phpstan-magento](https://github.com/bitExpert/phpstan-magento) 🫡 - Magento-specific extension for PHPStan.
- [Whoops Exceptions](https://github.com/yireo/Yireo_Whoops) 🫡 - PHP Exceptions for Cool Kids in Magento 2.
- [graycoreio/magento2-cors](https://github.com/graycoreio/magento2-cors) 🫡 - Enables configurable CORS headers on the Magento GraphQL API.
- [Magento 2 Prometheus Exporter](https://github.com/run-as-root/magento2-prometheus-exporter) 🫡 - Prometheus Exporter for common Magento data.
- [Yireo LokiComponents](https://github.com/yireo/Yireo_LokiComponents) 🫡 - A library for building AJAX-driven form components with ease. Used by the Yireo Loki Checkout.
- [Developer Toolbar](https://github.com/mgtcommerce/Mgt_Developertoolbar) - Magento 2 Developer Toolbar.
- [Advanced Template Hints](https://github.com/ho-nl/magento2-Ho_Templatehints) - Magento 2 Template Hints Helper.
- [MageVulnDB](https://github.com/gwillem/magevulndb) - Central repository for third-party Magento extensions with known security issues.
- [Magento 2 Configurator](https://github.com/ctidigital/magento2-configurator) - A Magento module initially created by CTI Digital to create and maintain database variables using files.
- [Cypress Testing Suite](https://github.com/elgentos/magento2-cypress-testing-suite/) - A community-driven Cypress testing suite for Magento 2.
- [Scope Hints](https://github.com/avstudnitz/AvS_ScopeHint2) - Displays additional information in the Store Configuration by Andreas von Studnitz.
- [Auto Cache Flush](https://github.com/yireo/Yireo_AutoFlushCache) - Magento 2 module to automatically flush the cache.
- [Dot Env](https://github.com/zepgram/magento-dotenv) - Magento 2 Environment Variable Component implementing Symfony Dotenv.
- [Rest Client](https://github.com/zepgram/module-rest) - Technical Magento 2 module providing simple development pattern, configurations and optimizations to make REST API requests toward external services based on Guzzle Client.
- [Magento 2 Model Generator / CRUD Generator](https://www.model-generator.com/) - A more up-to-date version of a Magento 2 Model & CRUD Generator by Michiel Gerritsen.
- [Simon's Troubleshooting Guide](https://gist.github.com/ProcessEight/000245eac361cbcfeb9daf6de3c1c2e4) - A list with the most common errors you encounter during development.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [Magento 2 PHPStorm File Templates](https://github.com/lfolco/phpstorm-m2-filetemplates) - PHPStorm Magento 2 File Templates.

</details>

### Deployment

- [Deployer Magento2 Recipe](https://github.com/deployphp/deployer/blob/master/recipe/magento2.php) 🫡 - Magento 2 deployment recipe for deployer.
- [easyaudit-cli](https://github.com/crealoz/easyaudit-cli) 🫡 - Static analysis CLI tool for Magento 2 codebases - detects anti-patterns, code quality issues, and architectural problems. SARIF output for CI/CD integration.
- [Github Actions for Magento2](https://github.com/extdn/github-actions-m2) - GitHub Actions for Magento 2 Extensions.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [Magento 2 Deployer Plus](https://github.com/jalogut/magento2-deployer-plus) - Tool based on deployer.org to perform zero-downtime deployments of Magento 2 projects.

</details>

### Localization

- [de_DE](https://github.com/splendidinternet/Magento2_German_LocalePack_de_DE) 🔥 - German Language Package.
- [pl_PL](https://github.com/SnowdogApps/magento2-pl_pl) - Polish Language Package.
- [it_IT](https://github.com/mageplaza/magento-2-italian-language-pack) - Italian Language Package.
- [nl_NL](https://github.com/magento-l10n/language-nl_NL) - Dutch Language Package.
- [da_DK](https://magentodanmark.dk/) - Danish Language Package.
- [fi_FL](https://github.com/mageplaza/magento-2-finnish-language-pack) - Finnish Language Package.
- [hr_HR](https://marketplace.magento.com/inchoo-language-hr-hr.html) - Croatian Language Package.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [pt_BR](https://github.com/rafaelstz/traducao_magento2_pt_br) - Portuguese Brazil Language Package.
- [fr_FR](https://github.com/Imaginaerum/magento2-language-fr-fr) - French Language Package.
- [tr_TR](https://github.com/hidonet/magento2-language-tr_tr) - Turkish Language Package.
- [es_ES](https://github.com/eusonlito/magento2-language-es_es) - Spanish Language Package.
- [sl_SI](https://github.com/symfony-si/magento2-sl-si) - Slovenian Language Package.
- [ro_RO](https://github.com/EaDesgin/magento2-romanian-language-pack) - Romanian Language Package.
- [de_CH](https://github.com/staempfli/magento2-language-de-ch) - Swiss Language Package.
- [ko_KR](https://github.com/mageplaza/magento-2-korean-language-pack) - Korean Language Package.
- [en_GB](https://github.com/cubewebsites/magento2-language-en-gb) - British Language Package.
- [es_AR](https://github.com/SemExpert/Magento2-language-es_ar) - Spanish (Argentina) Language Package.
- [sk_SK](https://github.com/mageplaza/magento-2-slovak-language-pack) - Slovakian Language Package.

</details>

### Search

- [Elastic Suite Integration](https://github.com/Smile-SA/elasticsuite/) 🫡 - Elastic Suite Integration.
- [Algolia Search Integration](https://github.com/algolia/algoliasearch-magento-2) 🫡 - Algolia Search (SaaS) Integration.
- [FastSimpleImport2](https://github.com/firegento/FireGento_FastSimpleImport2) 🫡 - Wrapper for Magento 2 ImportExport functionality, which imports products and customers from arrays.
- [Disable Search Engine](https://github.com/zepgram/module-disable-search-engine) - Disable Elasticsearch and fulltext indexing for category search.
- [magento2-module-meilisearch](https://github.com/walkwizus/magento2-module-meilisearch) - The Meilisearch extension for Magento 2 enables replacing Magento's default search engine (OpenSearch) with Meilisearch.

### CMS

- [Magento 2 Blog Extension by Magefan](https://github.com/magefan/module-blog) 🔥 - Free Blog module for Magento 2 with unlimited blog posts and categories, SEO friendly, lazy load and AMP support.
- [Mageplaza Blog Extension](https://github.com/mageplaza/magento-2-blog-extension) 🫡 - Simple but well-working Blog Extension.
- [magento-2-seeder](https://github.com/run-as-root/magento-2-seeder) 🫡 - Laravel-style database seeder for Magento 2 / Mage-OS. Generate realistic products (all types), categories, customers, orders (all states), CMS pages, and reviews via bin/magento db:seed.
- [module-page-builder-widget](https://github.com/mage-os/module-page-builder-widget) 🫡 - Native Magento Page Builder support for CMS Widgets
- [Opengento GDPR](https://github.com/opengento/magento2-gdpr) - Magento 2 GDPR module to help be GDPR compliant.
- [hyva-ai-tools](https://github.com/hyva-themes/hyva-ai-tools) - AI-powered skills for Magento 2 development with Hyva Theme. These skills extend AI coding assistants with specialized knowledge for creating Hyva themes, modules, and CMS components.

### Marketing

- [Google Tag Manager](https://github.com/magepal/magento2-google-tag-manager) 🫡 - Google Tag Manager (GTM) with Data Layer for Magento 2.
- [MagePlaza Seo](https://github.com/mageplaza/magento-2-seo-extension) 🫡 - Well-documented multi-purpose SEO Extension.
- [magento2-withdrawl](https://github.com/Zwernemann/magento2-withdrawl) - Magento 2 module providing a compliant EU withdrawal button required from June 19, 2026 (§356a BGB / Directive (EU) 2023/2673). Enables customers and guests to revoke orders via a simple form (name, order number, email), sends automatic confirmation emails, and allows admin management in the backend.
- [module-blog](https://github.com/mage-os-lab/module-blog) - Blog module for Mage-OS / Magento 2 with posts, categories, tags, authors, scheduled publishing, SEO, RSS, sitemap, 6 widgets, and a full GraphQL API. Luma + Hyvä.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [Magento 2 PDF](https://github.com/staempfli/magento2-module-pdf) - PDF Generator based on wkhtmltopdf.

</details>

### Adminhtml / Backend

- [Menu Editor](https://github.com/SnowdogApps/magento2-menu) 🔥 🫡 - Provides a powerful menu editor to replace category-based menus in Magento 2.
- [Custom SMTP](https://github.com/magepal/magento2-gmail-smtp-app) 🫡 - Configure Magento 2 to send all transactional email using Google App, Gmail, Amazon SES, Microsoft Office 365 and other SMTP servers.
- [Sentry.io](https://github.com/justbetter/magento2-sentry) 🫡 - Application monitoring and error tracking software for Magento 2.
- [magento2-hyva-admin](https://github.com/hyva-themes/magento2-hyva-admin) 🫡 - This module aims to make creating grids and forms in the Magento 2 adminhtml area joyful and fast.
- [FireGento Fast Simple Import](https://github.com/firegento/FireGento_FastSimpleImport2) 🫡 - Wrapper for Magento 2 ImportExport functionality, which imports products and customers from arrays.
- [Preview Checkout Success Page](https://github.com/magepal/magento2-preview-checkout-success-page) 🫡 - Quickly and easily preview and test your order confirmation page, without the need to place a new order each time.
- [Guest to Customer](https://github.com/magepal/magento2-guest-to-customer) 🫡 - Quickly and easily convert existing guest checkout customers to registered customers.
- [theme-adminhtml-m137](https://github.com/mage-os/theme-adminhtml-m137) 🫡 - M137 Admin Theme for Magento/Mage-OS
- [Disable Stock Reservation](https://github.com/AmpersandHQ/magento2-disable-stock-reservation) - Disables the inventory reservation logic introduced as part of MSI in Magento 2.3.3.
- [Customer Force Login](https://github.com/bitExpert/magento2-force-login) - Forces customers to log in before accessing certain pages.
- [Clean Admin Menu](https://github.com/redchamps/clean-admin-menu) - Merges 3rd-party extensions into a single menu.
- [Magento 2 Import Framework](https://github.com/techdivision/import) - A library supporting generic Magento 2 import functionality.
- [Checkout Tester](https://github.com/yireo/Yireo_CheckoutTester2) - Extension to quickly test Checkout changes.
- [PageNotFound](https://github.com/experius/Magento-2-Module-PageNotFound) - Saves upcoming 404s in your database with the possibility to create a redirect.
- [Reset UI Bookmarks](https://github.com/magenizr/Magenizr_ResetUiBookmarks) - Allows admin users to reset their own UI bookmarks such as filter state, column positions and applied sorting (e.g. Sales > Orders).
- [Product Links Navigator](https://github.com/elninotech/ElNino_ProductLinksNavigator) - Enhances admin product-to-product navigation. Adds direct frontend/backend links to products in grids and modals, and a "Parent Products" tab.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [shkoliar/magento-grid-colors](https://github.com/shkoliar/magento-grid-colors) - Magento 2 Grid Colors module for colorizing admin grids. Supports saving of states with the help of grid bookmarks by Dmitry Shkoliar.
- [extdn/extension-dashboard-m2](https://github.com/extdn/extension-dashboard-m2) - A Magento 2 dashboard to display installed extensions by the Magento Extension Developers Network.
- [Reset Customer Password](https://github.com/Vinai/module-customer-password-command) - Set a customer password with bin/magento by Vinai Kopp.
- [hivecommerce/magento2-content-fuzzyfyr](https://github.com/hivecommerce/magento2-content-fuzzyfyr) - The Content Fuzzyfyr module for Magento 2 replaces real content with dummy content — useful for development, test data, and matching GDPR restrictions.

</details>

### Security

- [Magento Quality Patches](https://experienceleague.adobe.com/tools/commerce-quality-patches/index.html) - Every Magento / Adobe Commerce patch you need all in one place.

### Payment Service Provider

- [PAYONE](https://github.com/PAYONE-GmbH/magento-2) 🫡 - PAYONE Payment Integration.
- [Braintree Payments](https://marketplace.magento.com/paypal-module-braintree.html) - Official Braintree Integration for Magento 2.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [Stripe](https://github.com/pmclain/module-stripe) - Stripe Payments for Magento 2.

</details>

### Infrastructure

- [Ethan3600/magento2-CronjobManager](https://github.com/Ethan3600/magento2-CronjobManager) 🔥 - Cron Job Manager for Magento 2.
- [magento-cache-clean](https://github.com/mage-os/magento-cache-clean) 🫡 - A faster drop in replacement for bin/magento cache:clean with file watcher
- [module-theme-optimization](https://github.com/mage-os/module-theme-optimization) 🫡 - bfcache, speculative loading, and view transitions for Magento
- [Fastly Extension](https://github.com/fastly/fastly-magento2) - Magento 2 Fastly integration.
- [Interceptor Optimization](https://github.com/creatuity/magento2-interceptors) - New interceptors approach for Magento 2.
- [Clean Media](https://github.com/sivaschenko/magento2-clean-media) - A module that provides information about media files and potential removal options.
- [Magento 2 Ngrok](https://github.com/shkoliar/magento-ngrok) - Magento 2 Ngrok Integration.

### Proprietary Extensions

- [Commercebug Debugging Extension](http://store.pulsestorm.net/products/commerce-bug-3) - A Magento 2 Debug Extension.
- [Magicento](http://magicento.com/) - PHPStorm plugin to add Magento 2 related functionality.

### Progressive Web Application

- [ScandiPWA Theme](https://github.com/scandipwa/base-theme) 🔥 - Magento 2.3+ PWA theme based on React and Redux.
- [graphcommerce](https://github.com/graphcommerce-org/graphcommerce) 🫡 - GraphCommerce® is a headless storefront replacement for Magento 2 (PWA), that delivers a faster, better user experience. Fully customizable (React, Next.js) and open-source.
- [magento2-default-theme](https://github.com/hyva-themes/magento2-default-theme) - A Magento theme built with Tailwind
- [magento2-theme-module](https://github.com/hyva-themes/magento2-theme-module) - Magento Tailwind Theme companion module
- [magento2-default-theme-csp](https://github.com/hyva-themes/magento2-default-theme-csp) - A strict CSP compatible Magento theme built with Tailwind and Alpine.js

---

## Blogs

### Personal Blogs

- [Jigar Karangiya](https://jigarkarangiya.com/) 🫡 - Personal blog on Magento 2 and Adobe Commerce development.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [Alan Storm](http://alanstorm.com/category/magento-2/) - Deep Magento 2 technical writeups.
- [Fabian Schmengler](https://www.schmengler-se.de/) - Personal blog covering Magento 2 architecture and process.

</details>

### Company Blogs

- [Atwix](https://www.atwix.com/blog/) 🫡 - Magento development agency blog.
- [Classy Llama](https://www.classyllama.com/blog) 🫡 - Magento agency blog.
- [FireBear Studio](https://firebearstudio.com/blog) 🫡 - FireBear Studio's Magento development blog.
- [inchoo](http://inchoo.net/category/magento-2/) 🫡 - Inchoo's Magento development blog.
- [dev98](https://dev98.de/) - German Magento agency blog.
- [M.academy](https://m.academy/blog/) - Blog from the M.academy team.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [bitExpert AG](https://blog.bitexpert.de/blog/tags/magento) - bitExpert's Magento-tagged blog posts.
- [Fooman](http://store.fooman.co.nz/blog) - Fooman's Magento extension and development blog.
- [integer_net blog](https://www.integer-net.com/blog/) - integer_net's technical Magento blog.
- [MageComp](https://magecomp.com/blog/category/magento-2/) - MageComp's Magento 2 tutorials and tips.
- [OneStepCheckout](https://blog.onestepcheckout.com/) - OneStepCheckout's Magento blog.

</details>

### Other

- [MageTalk](http://magetalk.com/) - Community podcast by Kalen Jordan and Phillip Jackson.

## Podcasts

- [MageTalk](https://magetalk.com/) - Weekly Magento podcast hosted by Phillip Jackson and Kalen Jordan covering Magento news, interviews, and community topics.
- [Talk Commerce](https://talk-commerce.com/podcasts/) - Brent Peterson's interviews with digital commerce practitioners, merchants, and platform experts.
- [The JetRails Podcast](https://jetrails.com/podcast/) - Ecommerce-focused podcast from JetRails covering hosting, performance, and platform strategy.

## Newsletters

- [M Bytes Newsletter](https://m.academy/newsletter/) - Weekly developer newsletter from M.academy delivering three free Magento video lessons every Thursday.
- [Mage Dispatch](https://www.magedispatch.com/) - Community-driven newsletter collecting links the Magento community should know about.
- [Mageres Monthly Digest](https://mailchi.mp/6a498018d9ef/mageres) - Hand-curated monthly newsletter by Alessandro Ronchi collecting useful Magento resources.
- [The Devletter](https://www.maxpronko.com/the-devletter/) - Free weekly email digest by Max Pronko covering Magento 2 development tips and news.

## Community

- [Dutchento](https://www.dutchento.org/) - The Magento community in the Netherlands.
- [ExtDN](https://extdn.org/) - A network of leading Magento extension developers committed to quality and best practices.
- [Firegento](https://firegento.com/) - A group of Magento enthusiasts developing open-source modules and organizing hackathons.
- [Mage-OS Association](https://mage-os.org/) - The community alliance ensuring the accessibility, longevity, and success of Magento Open Source.
- [Magento Association](https://www.magentoassociation.org/home) - The open and powerful Magento ecosystem association.
- [Magento Stack Exchange](https://magento.stackexchange.com/) - Q&A site for users and developers of the Magento e-Commerce platform.
- [OpenGento](https://opengento.fr/) - The Magento community in France.
- [Reddit r/Magento](https://www.reddit.com/r/Magento/) - Magento community on Reddit — questions, news, and discussion.

## Learning

- [Max Pronko DevChannel](https://www.youtube.com/channel/UCxbWGz6h6KNQsi2ughRUV2Q) 🫡 - Max Pronko's YouTube channel for Magento 2 development.
- [M.academy](https://m.academy/) - Video lessons and courses for Magento 2 and Adobe Commerce.
- [Mage2.tv](https://www.mage2.tv) - Magento 2 developer screencasts by Vinai Kopp.
- [Max Bucknell — Magento 2 JavaScript](https://www.youtube.com/watch?v=tHxebA-jOSo) - Max Bucknell's talk on Magento 2's JavaScript stack.
- [Yireo Training](https://www.yireo.com/training) - Magento 2 backend and frontend development courses.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [magento-notes/magento2-exam-notes](https://github.com/magento-notes/magento2-exam-notes) - Preparation notes for the Magento 2 Certified Professional Developer exam.
- [fisheye-academy/m2cpfed-training](https://github.com/fisheye-academy/m2cpfed-training) - Resources for the Magento 2 Certified Professional Front End Developer exam.
- [magento-notes/magento2-cloud-developer-notes](https://github.com/magento-notes/magento2-cloud-developer-notes) - Preparation notes for the Magento 2 Certified Professional Cloud Developer exam.
- [roma-glushko/magento2-dev-plus-exam](https://github.com/roma-glushko/magento2-dev-plus-exam) - Preparation notes for the Magento 2 Certified Professional Developer Plus exam.
- [MageTitans Italia 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVP3Fm_c4HfNPK5JdRD6DIDl) - MageTitans Italia 2016 conference recordings.
- [MageTitans MCR 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVMOnBRS49ICbNWOU5jhNNWC) - MageTitans Manchester 2016 conference recordings.
- [MageTitans USA/Texas 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVOLU7LPRNL4lAmJeAv7HQ-b) - MageTitans USA/Texas 2016 conference recordings.
- [The Magento 2 Beginner Tutorial Class](https://www.youtube.com/playlist?list=PLtaXuX0nEZk9eL59JGE3ny-_GAU-z5X5D) - Free YouTube series for learning Magento 2.
- [Vinai Kopp Mage2Katas](https://www.youtube.com/channel/UCRFDWo7jTlrpEsJxzc7WyPw) - Vinai Kopp's Mage2Katas YouTube channel.

</details>

---

## Platforms

- [StackExchange](http://magento.stackexchange.com/) - Q&A forum for Magento developers.

---

## Official Resources

- [Magento GitHub Repository](https://github.com/magento/magento2) 🫡 - Magento 2 GitHub repository.
- [Magento Coding Standards](https://github.com/magento/magento-coding-standard) - Official Magento 2 advanced ruleset for PHP_CodeSniffer.
- [Magento 2 data migration tool](https://github.com/magento/data-migration-tool) - Official Magento 1 → Magento 2 migration tool.
- [Magento 2 Architecture](https://github.com/magento/architecture) - Architectural discussions about Magento 2.
- [Magento Developer Blog](https://community.magento.com/t5/Magento-DevBlog/bg-p/devblog) - Developer blog run by Magento.
- [Magento Developer Documentation](http://devdocs.magento.com/) - Official developer documentation.
- [Magento Forum](https://community.magento.com/) - Community forum run by Magento.
- [Magento Official Website](https://www.magento.com) - Magento's official website.

---

## List of trustworthy Extension Developers

- [CustomGento](https://www.customgento.com/extensions/) - Quality-focused Magento 2 extension vendor; member of ExtDN.
- [Hyva Themes](https://www.hyva.io/) - Creators of the Hyva frontend framework for Magento 2; open-sourced in November 2025.
- [integer_net](https://www.integer-net.com/) - German Magento agency and extension vendor; ExtDN member; known for Solr search and code quality tooling.
- [Modulwerft](https://www.modulwerft.com/) - German Magento 2 extension vendor.
- [Paradox Labs](https://www.paradoxlabs.com/) - Magento 2 extensions for subscriptions, tokenized payments, and customer account management.
- [ProxiBlue](https://www.proxiblue.com.au/) - Australian Magento 2 extension vendor specializing in promotions and dynamic categories.
- [run-as-root](https://www.run-as-root.sh/) - German Magento agency and open-source contributor; maintainer of awesome-magento2 and multiple community extensions.
- [Smile.io](https://smile.io/) - Loyalty and rewards platform with Magento 2 integration (formerly Sweet Tooth).
- [Yireo](https://www.yireo.com/) - Dutch Magento 2 extension vendor and training provider; Hyva and GraphQL specialist; ExtDN member.

> **Magento Extension Developers Network (ExtDN)**
> The Magento Extension Developers Network (ExtDN) is a vetted network of extension developers whose core business is to
> develop and sell quality Magento extensions. I founded ExtDN to bring accountability and trust to the Magento extension
> market. ExtDN members agree to hold themselves accountable to high standards of coding, copyright and business conduct.

Explanation
by [Fooman](http://store.fooman.co.nz/blog/how-to-find-trustworthy-information-about-magento-extensions.html)

---

## Influencing People

Community members worth following — talks, blog posts, open-source maintenance, and training material.

- [Alessandro Ronchi](https://github.com/aleron75) - Mage-OS Documentation Working Group member; maintainer of Mageres; co-founder of ExtDN; Engineering Manager at Hyva Themes.
- [Andreas von Studnitz](https://github.com/avstudnitz) - Mage-OS Technical Working Group member; Magento architect at Hyva Themes; 2x Magento Master; formerly co-owner of integer_net.
- [David Lambauer](https://www.davidlambauer.de) - Vice President of Mage-OS; Adobe Certified Master Architect; creator of Mage-OS DevDocs; founder of run-as-root GmbH.
- [Fabrizio Balliano](https://fabrizioballiano.com) - Mage-OS Technical Working Group member; release manager for the Mage-OS 2.0 distribution; 5x Magento certified freelance engineer.
- [Jisse Reitsma](https://www.yireo.com/blog) - Vice President of the Magento Association; 3x Magento Master; founder of Yireo; trainer on Hyva, GraphQL, and Loki Checkout; Mage-OS Open Source Task Force member.
- [Mark Shust](https://markshust.com/) - Creator of markshust/docker-magento (the most-starred Magento-specific GitHub repo); educator at M.academy with 600+ video lessons.
- [Noah Oken-Berg](https://www.abovethefray.com) - Chair of the Magento Association Board of Directors; CEO of Above The Fray; focused on community governance and sustainable ecosystem growth.
- [Peter Jaap Blaakmeer](https://github.com/peterjaap) - CTO at elgentos; Mage-OS founding signatory; prolific open-source contributor to Magento 2 and Mage-OS.
- [Ryan Hoerr](https://github.com/rhoerr) - Mage-OS board member and Technical Working Group contributor; primary release engineer for Mage-OS distributions throughout 2025–2026; ParadoxLabs.
- [Sanne Bolkenstein](https://www.hyva.io/about) - Commercial Director and Partner at Hyva Themes; chairs Mage-OS Netherlands.
- [Sergej Derzap](https://amasty.com) - Treasurer of the Magento Association; CEO and CPO of Amasty, one of the largest Magento 2 extension vendors; 18+ years in the ecosystem.
- [Vinai Kopp](https://mage2.tv/) - President of Mage-OS; Technical Director at Hyva Themes; 3x Magento Master; creator of Mage2Katas; lead of the Mage-OS Technical Working Group.
- [Willem Poortman](https://wpoortman.nl) - Senior Developer at Hyva Themes; creator of the Magewire framework for server-side Magento 2 components.
- [Willem Wigman](https://www.hyva.io/blog/author/willemwigman) - Founder and CEO of Hyva Themes; creator of the Hyva frontend framework for Magento 2; released Hyva as open source in November 2025.

---

## Other Magento 2 related Awesome Lists

- [Awesome PHP](https://github.com/ziadoz/awesome-php) - A curated list of awesome PHP resources.
- [Mageres](https://github.com/aleron75/mageres) - Alessandro Ronchi's list of resources for Magento 1 and Magento 2.

<details>
<summary>🪦 Graveyard — projects no longer recommended</summary>

- [Awesome Magento](https://github.com/sunel/awesome-magento) - An awesome Magento list with mixed M1 and M2 content by sunel.

</details>

---

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, David Lambauer has waived all copyright and related or neighboring rights to this
work.

---

Thanks [Anna Völkl](https://github.com/avoelkl) & [Sander Mangel](https://github.com/sandermangel) for collecting all
the language packs!

---

Thanks [MageTitans](http://www.magetitans.co.uk/) for sharing the Talks on YouTube.
