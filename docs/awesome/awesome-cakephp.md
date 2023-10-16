<div class="github-widget" data-repo="friendsofcake/awesome-cakephp"></div>
## Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome **CakePHP 4.x+** plugins, resources and shiny things.

Plugins with the "🍰" icon have CakePHP 5 compatible release too (minimum "beta").

If you are looking for previous CakePHP resources please visit:
- the [CakePHP 2.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake2) of this awesome list
- the [CakePHP 3.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake3) of this awesome list
- this wiki with a [list of not-yet upgraded plugins](https://github.com/FriendsOfCake/awesome-cakephp/wiki#plugins-not-yet-upgraded-from-2x-to-3x)

Additional lists you might find useful:
- [CakePHP Plugins](https://plugins.cakephp.org)
- [Awesome PHP](https://github.com/ziadoz/awesome-php)
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness)

> For those wondering; this list differs from plugins.cakephp.org by supporting
> plugin subparts (instead of only the whole plugin/repo), more granular
> grouping and the primary focus on task-specific functionality.



## Plugins

## APM
*Plugins for Application Performance Monitoring.*


## Architecture

- 🍰 [Burzum/CakeServiceLayer plugin](https://github.com/burzum/cakephp-service-layer) - Service layer and domain/business model implementation.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

- 🍰 [AssetCompress plugin](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.
- 🍰 [AssetMix plugin](https://github.com/ishanvyas22/asset-mix) - Provides integration with [Laravel Mix](https://laravel-mix.com) asset compilation.

## Auditing / Logging
*Plugins for auditing and logging.*

- [AuditStash plugin](https://github.com/lorenzo/audit-stash) - Flexible and rock solid audit log tracking.
- 🍰 [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - Simple and stand-alone logging to database instead of files.
- 🍰 [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) - Plugin to allow passing currently logged in user to model layer.
- [Version plugin](https://github.com/josegonzalez/cakephp-version) - A plugin that facilitates versioned database entities.

## Authentication and Authorization
*Plugins and libraries for implementing authentication and authorization.*

- [Acl plugin](https://github.com/cakephp/acl/) - Managing ACL as database approach.
- [ADmad/JwtAuth plugin](https://github.com/ADmad/cakephp-jwt-auth) - A plugin for authenticating using JSON Web Tokens.
- 🍰 [ADmad/SocialAuth plugin](https://github.com/ADmad/cakephp-social-auth) - A plugin which allows you to authenticate using social providers like Facebook/Google/Twitter etc. using [SocialConnect/auth](https://github.com/SocialConnect/auth) social sign on library.
- [ApiTokenAuthenticator plugin](https://github.com/rrd108/api-token-authenticator) - A simple token authentication plugin for CakePHP REST APIs.
- 🍰 [Authentication plugin](https://github.com/cakephp/authentication) - Official CakePHP authentication middleware plugin.
- 🍰 [Authorization plugin](https://github.com/cakephp/authorization) - Official CakePHP authorization stack.
- 🍰 [CakeDC/Users plugin](https://github.com/CakeDC/users) - Complete user management (admin panel, remember me, etc), Social login (FB, Twitter, LinkedIn, Google, Instagram), RBAC, API and more.
- [Muffin/Tokenize plugin](https://github.com/UseMuffin/Tokenize) - Event driven behavior for easily generating single-use security tokens.
- 🍰 [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) - Authentication and role based (single/multi) authorization as very light-weight approach.
- 🍰 [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - Containing [Passwordable behavior](https://github.com/dereuromark/cakephp-tools/blob/master/docs/Behavior/Passwordable.md) for a DRY approach on password hashing.
- [TwoFactorAuth plugin](https://github.com/andrej-griniuk/cakephp-two-factor-auth) - Allows two factor authentication using Google Authenticator or similar app to generate one-time codes. Based on [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) library.

## Caching
*Plugins for caching data.*

- [Cache plugin](https://github.com/dereuromark/cakephp-cache) - For caching views (HTML, CSV, JSON, XML, ...) as static cache files.

## Code Analysis
*Plugins for analysing, parsing and manipulation codebases.*

- 🍰 [CakeDC/PHPStan](https://github.com/CakeDC/cakephp-phpstan) - A PHPStan extension to resolve CakePHP magic around getter return types for the static analyzer.
- 🍰 [IdeHelper plugin](https://github.com/dereuromark/cakephp-ide-helper) - Helps to make IDE support better by adding annotations to your existing code similar to what baking does to new code.
- 🍰 [IdeHelperExtra plugin](https://github.com/dereuromark/cakephp-ide-helper-extra) - Useful IdeHelper addons for other plugins or custom use cases.
- [TestHelper plugin](https://github.com/dereuromark/cakephp-test-helper) - Provides testing enhancements and TDD support as browser backend.

## Debugging
*Plugins for debugging and local development.*

- [AssociationsDebugger plugin](https://github.com/zunnu/associations-debugger) - A plugin that draws your model associations as diagram.
- 🍰 [CakephpWhoops plugin](https://github.com/dereuromark/cakephp-whoops) - PHP errors and exceptions for cool kids with [filp/whoops](https://github.com/filp/whoops).
- 🍰 [DebugKit plugin](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging.
- [Execution order](https://github.com/dereuromark/executionorder) - A demo app to display the execution order of files, methods and callbacks.
- 🍰 [Sentry plugin](https://github.com/lordsimal/cakephp-sentry) A plugin to seamlessly integrate Sentry for errors and exceptions.
- 🍰 [Setup plugin](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing debugging and maintenance tools.

## Dependency Injection
*Plugins that implement the dependency injection design pattern.*


## E-commerce
*Plugins and applications for taking payments and building online e-commerce stores.*


## Email
*Plugins for sending and parsing email.*

- [EmailQueue plugin](https://github.com/lorenzo/cakephp-email-queue) - Email queue plugin with a preview and sender shell.
- [Mailgun plugin](https://github.com/narendravaghela/cakephp-mailgun) - Email transport plugin for sending email via Mailgun.
- 🍰 [Queue plugin](https://github.com/dereuromark/cakephp-queue) - A dependency-free queue-based mail solution using Mailer/Email class, allowing re-queue on (network) failure.

## Environment
*Plugins for environment.*


## File Manipulation
*Plugins for file manipulation.*

- [FileStorage plugin](https://github.com/dereuromark/cakephp-file-storage) - Flexible file storage and upload plugin.
- [Josbeir/Filesystem plugin](https://github.com/josbeir/cakephp-filesystem) - Abstract [Flysystem](https://flysystem.thephpleague.com/) + file entity based upload plugin.
- 🍰 [Josegonzalez/Upload plugin](https://github.com/FriendsOfCake/cakephp-upload) - A customisable plugin that uses [Flysystem](https://flysystem.thephpleague.com/) to write to multiple backends (Dropbox, FTP, S3, Local, etc.).

## Filtering and Validation
*Plugins for filtering and validating data.*


## Geolocation
*Plugins for geocoding addresses and working with latitudes and longitudes.*

- 🍰 [Geo plugin](https://github.com/dereuromark/cakephp-geo) - Containing [Geocoder behavior](https://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMaps helper](https://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).

## HTTP
*Plugins for HTTP and client abstraction*

- [Http/Adapter/Cake library](https://github.com/php-http/cakephp-adapter) - Adapter for [HTTPlug](https://github.com/php-http/httplug) HTTP client abstraction.

## I18n
*Plugins for I18n (Internationalization) and L10n (Localization).*

- 🍰 [ADmad/I18n plugin](https://github.com/ADmad/cakephp-i18n) - A plugin with I18n related tools.
- [Cake/Localized plugin](https://github.com/cakephp/localized) - Localized validation and ready-to-use translation PO files.
- [Translate plugin](https://github.com/dereuromark/cakephp-translate) - Manage translations of your static content the easy way via web backend, incl. import from POT files, auto-suggest and auto-translate via API.

## Imagery
*Plugins for manipulating images.*

- 🍰 [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) - A plugin for using [Glide](https://glide.thephpleague.com/) image manipulation library.

## Libs
*Useful libraries or tools that don't fit in any of the other categories.*

- [Capcake](https://github.com/jadb/capcake) - Deploy CakePHP applications using Capistrano.
- [Chronos](https://github.com/cakephp/chronos) - A simple standalone DateTime API extension (successor of Carbon).
- [Composer Installers](https://github.com/composer/installers) - A multi framework Composer library installer.
- [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - A package and dependency manager.
- [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
- [Rocketeer](https://github.com/rocketeers/rocketeer) - PHP task runner and deployment package.
- 🍰 [makallio85/YamlRoute plugin](https://github.com/makallio85/yaml-route) - Configure routes with simple YAML files.

## Markup
*Plugins for working with markup.*

- 🍰 [Markup plugin](https://github.com/dereuromark/cakephp-markup) - Allows to use PHP or JS based syntax highlighting.

## Migration
*Plugins and resources around migration and upgrading.*

- 🍰 [Migrations plugin](https://github.com/cakephp/migrations) - (DB) Migration plugin.
- [Upgrade app](https://github.com/cakephp/upgrade) - Official upgrade app for 2.x=>3.x and 3.x=>4.x.
- [Upgrade app (extended)](https://github.com/dereuromark/upgrade) - An extended upgrade app for 2.x=>3.x, between 3.x and some 4.x snippets.
- [Upgrade/Migration Guide](https://book.cakephp.org/4.0/en/appendices.html) - Official migration guide.

## Miscellaneous
*Misc plugins and libraries.*

- 🍰 [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) - A plugin to ease handling AJAX requests.
- 🍰 [CakeDC/Enum plugin](https://github.com/CakeDC/enum) - A plugin to add enumeration list support to your app.
- 🍰 [CakeDto plugin](https://github.com/dereuromark/cakephp-dto) - Quickly generate useful data transfer objects for your app (mutable/immutable), replacing messy arrays and leveraging your IDE through typehinting and autocomplete.
- [CakeImpersonate plugin](https://github.com/jomweb/CakeImpersonate) - A component that stores the current authentication session and creates new session for impersonating Users. User can revert back to original authentication sessions without the need to re-login.
- 🍰 [Calendar plugin](https://github.com/dereuromark/cakephp-calendar) - For generating basic calendars. Includes IcalView for ICS calendar file generation.
- 🍰 [Feedback plugin](https://github.com/dereuromark/cakephp-feedback) - Allow visitors to send quick and easy feedback incl. a screenshot via sidebar form.
- 🍰 [Flash plugin](https://github.com/dereuromark/cakephp-flash) - More powerful flash messages for your application.
- 🍰 [OPCache Preloader](https://github.com/cnizzardini/cakephp-preloader) - An OPCache Preloader for CakePHP applications. 
- 🍰 [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) - Maintenance shell to go into maintenance mode for all requests with optional IP whitelisting.
- 🍰 [Shim plugin](https://github.com/dereuromark/cakephp-shim) - A plugin containing useful shims and improvements as basis for your application.
- 🍰 [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing lots of useful libs, helpers, behaviors, components, shells and more.

## Navigation
*Tools for building navigation structures.*

- 🍰 [Icings/Menu plugin](https://github.com/icings/menu) - A [KnpMenu](https://github.com/KnpLabs/KnpMenu) seasoned menu plugin for CakePHP.

## NoSQL
*Plugins for working with "NoSQL" backends.*

## Notifications
*Plugins for working with notification software.*


## ORM / Database / Datamapping
*Plugins that implement object-relational mapping or data-mapping techniques.*

- 🍰 [ADmad/Sequence plugin](https://github.com/ADmad/cakephp-sequence) - Behavior for maintaining ordered list of records.
- 🍰 [CakeDecimal plugin](https://github.com/dereuromark/cakephp-decimal) - A value object approach on handling decimals.
- 🍰 [Duplicatable plugin](https://github.com/riesenia/cakephp-duplicatable) - Behavior for duplicating entities including related data.
- [Lampager/Cake plugin](https://github.com/lampager/lampager-cakephp) - Rapid pagination without using OFFSET.
- 🍰 [Muffin/Orderly plugin](https://github.com/usemuffin/orderly) - Allows setting default order for your tables.
- [Muffin/Sti plugin](https://github.com/UseMuffin/Sti) - Single Table Inheritance for CakePHP. 
- 🍰 [Muffin/Trash plugin](https://github.com/usemuffin/trash) - Soft-delete behavior for CakePHP.
- [Robotusers/TableInheritance plugin](https://github.com/robotusers/cakephp-table-inheritance) - Singe Table Inheritance (STI) plugin.
- [RowLocker plugin](https://github.com/lorenzo/row-locker) - Exclusive locks for rows in your tables.
- [Muffin/Webservices ORM plugin](https://github.com/usemuffin/webservice) - An ORM like interface for webservices.
- [Connehito/CakephpMasterReplica plugin](https://github.com/Connehito/cakephp-master-replica) - Switch master/replica database connections.
- [Itosho/EasyQuery plugin](https://github.com/itosho/easy-query) - Behavior for easily generating some complicated queries like (bulk) insert/upsert etc.
- 🍰 [Icings/Partitionable plugin](https://github.com/icings/partitionable) - Partitionable associations allowing for basic limiting per group.

## PDF
*Plugins and software for working with PDF files.*

- 🍰 [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - A plugin around PDF generation.

## Queue
*Plugins for working with event and task queues.*

- [CakeQueuesadilla plugin](https://github.com/josegonzalez/cakephp-queuesadilla) - A plugin that provides queueing integration with a variety of backends (BeanstalkD, MySQL, Redis, etc.).
- 🍰 [Queue plugin](https://github.com/dereuromark/cakephp-queue) - A minimal and dependency-free queue solution.
- 🍰 [Queue plugin](https://github.com/cakephp/queue) - CakePHP core queue system for the [php-queue](https://php-enqueue.github.io) queue library.

## REST and API
*Plugins and web tools for developing REST-ful APIs.*

- 🍰 [CRUD plugin](https://github.com/FriendsOfCake/crud) - CakePHP Application development on steroids - rapid prototyping / scaffolding & production-ready code.
- [Alt3/Swagger plugin](https://github.com/alt3/cakephp-swagger) - Swagger 2.0 documentation for your CakePHP APIs using swagger-php and swagger-ui.
- 🍰 [CakeDC/Api plugin](https://github.com/CakeDC/cakephp-api) - All-in-one solution to provide a complete API. It includes versioning, renderers, CRUD, authentication, extensions (paginate, filter, HATEOAS), and much more.
- [FractalTransformerView plugin](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) - A plugin which allows using [Fractal transformers](https://fractal.thephpleague.com/transformers/) for your API output.
- [MixerApi](https://mixerapi.com) - Streamline development of modern RESTful APIs for your team's CakePHP project.
- [SwaggerBake plugin](https://github.com/cnizzardini/cakephp-swagger-bake) - This plugin automatically builds OpenAPI from your existing models and routes for display in Swagger and Redoc.

## Search
*Plugins and software for indexing and performing search queries on data.*

- 🍰 [Cake/ElasticSearch plugin](https://github.com/cakephp/elastic-search) - Alternative ORM using [Elasticsearch](https://www.elastic.co/) as its backend.
- 🍰 [PlumSearch plugin](https://github.com/skie/plum_search) - Implements custom, flexible and extendable search strategies. Implements PRG pattern.
- 🍰 [Search plugin](https://github.com/FriendsOfCake/search) - Provides easy searching/filtering for paginated views using PRG pattern.
- 🍰 [Tags plugin](https://github.com/dereuromark/cakephp-tags) - For tagging and finding tagged records.

## Security
*Plugins and information around security, preventing vulnerabilities and protection against XSS and alike.*

- [Bruteforce](https://github.com/Ali1/cakephp-bruteforce/) - Simple way to add Brute Force Protection to your installation without involving database.
- 🍰 [Captcha plugin](https://github.com/dereuromark/cakephp-captcha) - Simple, unobtrusive and extendable captcha solution providing by default an image based math captcha.
- 🍰 [Expose plugin](https://github.com/dereuromark/cakephp-expose) - Expose entities through additional UUIDs instead of their AIID primary keys to obfuscate those IDs and data associated with these numerically ordered values.
- 🍰 [Muffin/Obfuscate plugin](https://github.com/usemuffin/obfuscate) - Primary key obfuscation/shortening using UUIDs, HashIds, Optimus, Tiny and/or custom obfuscation strategies.
- 🍰 [Muffin/Throttle plugin](https://github.com/usemuffin/throttle) - A plugin for rate limiting (API) requests.
- [Recaptcha plugin](https://github.com/ctlabvn/Recaptcha) - Simple, lightweight Google Recaptcha v2.

## SEO
*Search Engine Optimization.*

- 🍰 [Muffin/Slug plugin](https://github.com/UseMuffin/Slug) - A plugin for generating slugs and finding records by slug. Uses a pluggable architecture which allows using your own slug generator class.
- 🍰 [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - Containing Slugged behavior to auto-generate URL-compatible slugs from titles.

## Skeleton
*Plugins and repositories around app skeletons.*

- [App template](https://github.com/cakephp/app) - An empty CakePHP project for use with composer.

## Social
*Plugins around social features.*

- 🍰 [Ratings plugin](https://github.com/dereuromark/cakephp-ratings) - Allows users to rate records and displays ratings.

## Templating
*Plugins for templating and lexing.*

- 🍰 [Bake plugin](https://github.com/cakephp/bake) - Provides code generation functionality.
- 🍰 [BootstrapUI plugin](https://github.com/friendsofcake/bootstrap-ui) - Bootstrap 4/5 integration.
- 🍰 [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - A view class to easily generate CSV.
- 🍰 [Feed plugin](https://github.com/dereuromark/cakephp-feed) - Containing an RssView class to easily generate (complex) RSS feeds.
- 🍰 [Meta plugin](https://github.com/dereuromark/cakephp-meta) - Makes handling meta tags and SEO-relevant HTML markup DRY and easy.
- 🍰 [Tools:Tree](https://github.com/dereuromark/cakephp-tools) - Tree helper to work with Core Tree behavior and handle tree structure output.
- 🍰 [TwigView plugin](https://github.com/cakephp/twig-view) - A plugin to use the Twig Templating Language for views.

## Testing
*Plugins/Tools for testing codebases and generating test data.*

- [CakePHP Codeception module](https://github.com/cakephp/codeception) - The official CakePHP integration with [Codeception](https://codeception.com).
- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - The official CakePHP CS rules.
- 🍰 [CakephpFixtureFactories plugin](https://github.com/pakacuda/cakephp-fixture-factories) - Create your fixtures dynamically on a test basis, accelerate the writing and maintenance of your tests.
- [Faker plugin](https://github.com/gourmet/faker) - [Faker](https://github.com/fzaninotto/Faker) support for CakePHP fixtures.
- [Fixtures plugin](https://github.com/LubosRemplik/CakePHP-Fixtures) - Fixtures plugin to read existing fixtures and create table/insert data for quick start with app.
- 🍰 [FriendsOfCake/Fixturize plugin](https://github.com/FriendsOfCake/fixturize) - More efficient inserting fixtures when running test suites by decreasing amount of inserts (mysql only).

## Third Party APIs
*Plugins for accessing third party APIs.*


## Software
*Software for creating a development environment.*

## Development Environment
*Software and tools for creating a sandboxed development environment.*

- 🍰 [CakePHP Docker](https://github.com/cnizzardini/cakephp-docker) - A cakephp/app template for docker.
- [CakePHP Vagrant Setup](https://github.com/cpierce/cakephp-vagrant-setup) - Tool for spinning up multiple CakePHP vanilla dev environments.
- [Devilbox](https://devilbox.readthedocs.io/en/latest/) - A docker development environment for (CakePHP) apps to be auto-setup including a lot of tools.
- [Docker](https://github.com/stefanvangastel/docker-cakephp) - CakePHP in a docker container environment.
- 🍰 [Galley](https://gitlab.com/amayer5125/galley) - A small Docker dev environment for CakePHP development which includes a simple command line utility.
- [NetBeans](https://github.com/junichi11/cakephp3-netbeans) -  This package provides support for CakePHP in NetBeans 8.1+.
- [Oven](https://github.com/CakeDC/oven) - Setup your favorite framework with 1 file and 1 click.
- [Puppet](https://puppetlabs.com/) - A server automation framework and application.
- [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.

IDE specific compatibility information and tips can be found [here](https://github.com/dereuromark/cakephp-ide-helper/wiki#ide-support-and-tips).

## Web Applications

## CMS and applications built on CakePHP

- [baserCMS](https://github.com/baserproject/basercms) - This is a website development framework with RESTful APIs. Installable as a plugin for CakePHP 4.x.
- [Croogo](https://croogo.org) - CMS software (see 5.0 branch).

## Demo
*Web-based (demo) applications and tools.*

- [BlogMVC](https://github.com/Kareylo/BlogMVC-CakePHP3) - A simple Blog example with CakePHP based on [BlogMVC Project](https://github.com/Grafikart/BlogMVC).
- [Bookmarkr](https://github.com/lorenzo/cakephp3-bookmarkr) A bookmarking application built with the CRUD plugin.
- [CakeFest](http://cakefest.dereuromark.de/) - Demo application around the annual CakePHP Conference "CakeFest".
- [Fluentd + Grafana Loki demo application](https://github.com/ishanvyas22/cakephp-loki-demo) - A demo application to send CakePHP docker container logs to [Grafana Loki](https://grafana.com/logs/) via [Fluentd](https://www.fluentd.org/).
- [RealWorld](https://github.com/gothinkster/cakephp-realworld-example-app) - Example CakePHP codebase containing real world examples (CRUD, auth, advanced patterns and more) that adheres to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) spec and API.
- [Sandbox](https://sandbox.dereuromark.de) - A sandbox CakePHP application with lots of demos and plugin showcasings.
- [Query Examples](https://github.com/lorenzo/cakephp3-examples) Advanced query building examples.
- [Xeta](https://github.com/XetaIO/Xeta) - A resource to help people starting with CakePHP.
- [Vue.js Demo App](https://github.com/ishanvyas22/cakephpvue-spa) - A CakePHP + VueJS single page application skeleton.

## Resources
Various resources, such as books, websites and articles, for improving your CakePHP development skills and knowledge.

## Help
*Where to get help.*

- [CakePHP-FR.org](http://cakephp-fr.org) - The french community website.
- [Official CakePHP Forum](https://discourse.cakephp.org/) - This is for generic questions and alike.
- [IRC Channel](https://www.dereuromark.de/2013/01/27/irc-cakephp-channel/) - Live chat/discussion with other devs and core devs.
- [stackoverflow.com/questions/tagged/cakephp](https://stackoverflow.com/questions/tagged/cakephp) - This is for specific questions, ideally along with some example code.

## CakePHP Websites
*Useful and current CakePHP-related websites and blogs.*

- [CakeDC](http://www.cakedc.com/articles) - Articles around CakePHP.
- [dereuromark.de](https://www.dereuromark.de) - An extensive CakePHP core dev blog.
- [jedistirfry.co.uk](http://jedistirfry.co.uk) - A CakePHP related dev blog.
- [josediazgonzalez.com](http://josediazgonzalez.com/) - A mainly CakePHP related core dev blog.
- [mark-story.com](http://mark-story.com) - CakePHP lead dev blog.

## CakePHP Books and Articles
*Fantastic CakePHP-related (e)books and other reading material.*

## CakePHP Videos
*Fantastic CakePHP-related videos.*

- [CakePHP](https://www.youtube.com/user/CakePHP) - Channel about CakePHP videos.


## CakePHP Tutorials
*Must-do tutorials.*

- [Official Blog tutorial](https://book.cakephp.org/4.0/en/tutorials-and-examples/blog/blog.html)
- [Official Content Management Tutorial](https://book.cakephp.org/4/en/tutorials-and-examples/cms/installation.html)

## CakePHP Reading and Listening
*Documentation and CakePHP-related reading and listening materials.*

- [CakePHP Cookbook(!)](https://book.cakephp.org/) - The official CakePHP documentation.

## CakePHP Internals Reading
*Reading materials related to the CakePHP internals and decisions.*

- [Top 10 (and more) core contributors](https://github.com/cakephp/cakephp/graphs/contributors) - Give 'em a hand.

## Conferences

## Official
*International conference.*

- [cakefest.org](https://cakefest.org/) - Annual CakePHP Conference.

## MeetUps
*Regional meet-ups.*

- [CakePHP-DE](https://www.meetup.com/CakePHP-DE) - MeetUps in Germany.

## Contributing
Please see [CONTRIBUTING](https://github.com/friendsofcake/awesome-cakephp/blob/master/CONTRIBUTING.md) for details.

## Credits
awesome-cakephp has been created by [dereuromark](https://github.com/dereuromark) and is currently maintained by him and the FriendsOfCake group. Thank you to all [contributors](https://github.com/FriendsOfCake/awesome-cakephp/graphs/contributors), too.
