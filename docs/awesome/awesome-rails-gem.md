<div class="github-widget" data-repo="hothero/awesome-rails-gem"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Rails Gem [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
一系列令人敬畏的Ruby Gems for Rails开发.

目标是帮助每个Rails开发人员构建一个非常棒的Rails产品/服务.


## User

### Authentication
* [Devise](https://github.com/plataformatec/devise/) - Devise is a flexible authentication solution for Rails based on Warden.
* [Knock](https://github.com/nsarno/knock) -  Rails API的无缝JWT身份验证.
* [Clearance](https://github.com/thoughtbot/clearance) - 使用电子邮件和密码进行Rails身份验证
* [Devise token auth](https://github.com/lynndylanhurley/devise_token_auth) - 针对Rails JSON API的基于令牌的身份验证.
* [Sorcery](https://github.com/Sorcery/sorcery)   -  Rails的神奇身份验证.  支持ActiveRecord，DataMapper，Mongoid和MongoMapper.

### Authorization
* [Pundit](https://github.com/elabs/pundit) -  Pundit提供了一组帮助程序，指导您利用常规Ruby类和面向对象的设计模式来构建简单，强大且可扩展的授权系统.
* [cancancan](https://github.com/CanCanCommunity/cancancan)   -  CanCan的延续，Ruby on Rails.CanCan的授权Gem是Ruby on Rails的授权库，它限制了允许给定用户访问的资源.  所有权限都在一个位置（Ability类）中定义，并且不会跨控制器，视图和数据库查询重复.
* [rolify](https://github.com/RolifyCommunity/rolify) - 具有资源范围的角色管理库.
* [acl9](https://github.com/be9/acl9/) -  Acl9是一个基于角色的授权系统，它提供了一个简洁的DSL来保护您的Rails应用程序.


### Omniauth
* [omniauth-facebook](https://github.com/mkdynamic/omniauth-facebook)
* [omniauth-google-oauth2](https://github.com/zquestz/omniauth-google-oauth2)
* [omniauth-weibo-oauth2](https://github.com/beenhero/omniauth-weibo-oauth2)
* [omniauth-twitter](https://github.com/arunagw/omniauth-twitter)
* [omniauth-github](https://github.com/intridea/omniauth-github)
* [omniauth-linkedin-oauth2](https://github.com/decioferreira/omniauth-linkedin-oauth2)

## Active Record
* [Enumerize](https://github.com/brainspec/enumerize)   - 具有I18n和ActiveRecord / Mongoid支持的枚举属性.  它可以与Simple Form集成.
* [counter_culture](https://github.com/magnusvk/counter_culture)   - 适用于Rails应用程序的Turbo-counter计数器缓存.  对Rails标准计数器缓存的巨大改进.
* [custom_counter_cache](https://github.com/cedric/custom_counter_cache) - 创建可在多个模型中使用的自定义计数器缓存的简单方法.
* [Sequenced](https://github.com/djreimer/sequenced) -  Sequenced是一个简单的gem，可为ActiveRecord模型生成范围的顺序ID.
* [FriendlyId](https://github.com/norman/friendly_id)   -  FriendlyId是ActiveRecord的段塞和永久插件的“瑞士军队推土机”.  它允许您创建漂亮的URL并使用人性化的字符串，就像它们是ActiveRecord模型的数字ID一样.
* [AASM](https://github.com/aasm/aasm) -  Ruby类的状态机（纯Ruby，Rails Active Record，Mongoid）.
* [PaperTrail](https://github.com/airblade/paper_trail)   -  PaperTrail可让您跟踪模型数据的变化.  它适用于审计或版本控制.
* [paranoia](https://github.com/rubysherpas/paranoia) -  ActiveRecord插件允许您隐藏和恢复记录而不实际删除它们.
* [Validates](https://github.com/kaize/validates) -  Validates为Rails应用程序提供有用的自定义验证器集合，包括：
  * EmailValidator
  * UrlValidator
  * SlugValidator
  * MoneyValidator
  * IpValidator
  * AssociationLengthValidator
  * AbsolutePathValidator
  * UriComponentValidator
  * ColorValidator
  * EanValidator（EAN-8和EAN-13）
* [globalize](https://github.com/globalize/globalize) -  Rails I18n事实上是ActiveRecord模型/数据转换的标准库.
* [deep_cloneable](https://github.com/moiristo/deep_cloneable) - 这个gem为每个ActiveRecord :: Base对象提供了进行包含用户指定关联的深度克隆的可能性.
* [social_shares](https://github.com/Timrael/social_shares) - 检查社交网络中共享网址的次数.
* [public_activity](https://github.com/chaps-io/public_activity) - 模型的简单活动跟踪 - 类似于Github的公共活动.
* [goldiloader](https://github.com/salsify/goldiloader) - 自动ActiveRecord预先加载，以减少应用程序运行的数据库查询的数量.
*标记
  * [ActsAsTaggableOn](https://github.com/mbleigh/acts-as-taggable-on) -  Rails应用程序的标记插件，允许在动态上下文中自定义标记.
  * [closure_tree](https://github.com/mceachen/closure_tree) - 轻松高效地使您的ActiveRecord模型支持层次结构.
* [ActionStore](https://github.com/rails-engine/action-store) - 通过ActiveRecord Polymorphic Association在一个表中存储不同类型的操作（Like，Follow，Star，Block ...）.

## Plugins
* [Spreadsheet](https://github.com/zdavatz/spreadsheet) - 库旨在读写电子表格文档.
* [Chartkick](https://github.com/ankane/chartkick) -  Chartkick帮助您使用一行Ruby创建漂亮的Javascript图表.
* [kaminari](https://github.com/amatsuda/kaminari) - 适用于Rails 3和4的基于范围和引擎的，干净，强大，可定制和复杂的分页器.
* [Slack Notifier](https://github.com/stevenosloan/slack-notifier) 是一个发送通知的简单包装器 [Slack](https://slack.com/) 网络挂接.
* [Rails ERD](https://github.com/voormedia/rails-erd) - 为Rails应用程序生成实体关系图.
* [Parity](https://github.com/thoughtbot/parity) - 用于Heroku应用程序的开发，登台和生产奇偶校验的Shell命令.
* [Airbrussh](https://github.com/mattbrictson/airbrussh) -  Airbrussh为你的SSHKit和Capistrano输出做好准备

## API
* [Grape](https://github.com/ruby-grape/grape) - 用于在Ruby中创建REST-ful API的微框架.
* [ActiveModel::Serializers](https://github.com/rails-api/active_model_serializers) -  Serializer为您的JSON生成带来了约定优于配置.
* [Jbuilder](https://github.com/rails/jbuilder)   -  Jbuilder为您提供了一个简单的DSL，用于声明按摩巨型哈希结构的JSON结构.  当生成过程充满条件和循环时，这尤其有用.
* [rest-client](https://github.com/rest-client/rest-client) -  Ruby的简单HTTP和REST客户端，受微框架语法的启发，用于指定操作.
* [has_scope](https://github.com/plataformatec/has_scope) - 将传入的控制器参数映射到资源中的命名范围.
*文件
	* [Grape Swagger](https://github.com/ruby-grape/grape-swagger) - 自动生成Grape API的文档.
	* [Grape Swagger UI](https://github.com/swagger-api/swagger-ui) - 显示使用Grape Swagger生成的文档.
	* [apiary](https://apiary.io/) - 共同努力，快速设计，制作原型，记录和测试API.
	* [apiblueprint](https://apiblueprint.org) - 具有强大工具的API文档.

## Email
* [letter_opener](https://github.com/ryanb/letter_opener) - 在浏览器中预览邮件而不是发送.

## File Uploading
* [Carrierwave](https://github.com/carrierwaveuploader/carrierwave) -  Carrierwave是Rails，Sinatra和其他Ruby Web框架文件上传的更加经典的解决方案.
  * [carrierwave_backgrounder](https://github.com/lardawge/carrierwave_backgrounder) - 使用Delayed Job，Resque，Sidekiq，Qu，Queue Classic或Girl Friday将CarrierWave的图像处理和存储卸载到后台进程.
  * [CarrierWave Crop](https://github.com/kirtithorat/carrierwave-crop/) -  Carrierwave扩展，使用带预览的Jcrop插件裁剪上传的图像.
  * [CarrierWave ImageOptimizer](https://github.com/jtescher/carrierwave-imageoptimizer) - 此宝石允许您使用image_optimizer gem通过jpegoptim或optipng简单优化CarrierWave图像.
* [remotipart](https://github.com/JangoSteve/remotipart) - 通过标准Rails“remote：true”表单上传RQuery jQuery文件.
* [MiniMagick](https://github.com/minimagick/minimagick) -  MiniMagick是ImageMagick或GraphicsMagick命令行的ruby包装器.
* [fog](https://github.com/fog/fog) - 雾是Ruby云服务库，从上到下.
* [refile](https://github.com/refile/refile)   -  Refile是Ruby应用程序的现代文件上传库.  它很简单，但功能强大.
* [Paperclip](https://github.com/thoughtbot/paperclip) -  ActiveRecord的简易文件附件管理.
* [Dragonfly](http://markevans.github.io/dragonfly) -  Dragonfly用于即时文件处理 - 适用于图像或其他附件
* [shrine](https://github.com/janko-m/shrine) - 用于Ruby应用程序的文件附件工具包  

## Searching
* [ransack](https://github.com/activerecord-hackery/ransack) -  Ransack支持为Ruby on Rails应用程序创建简单和高级搜索表单.
* [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) -  ActiveModel / Record和Ruby on Rails的Elasticsearch集成.
* [Chewy](https://github.com/toptal/chewy) - 基于官方elasticsearch-ruby客户端的高级Elasticsearch Ruby框架.
* [pg_search](https://github.com/Casecommons/pg_search) -  pg_search构建了ActiveRecord命名范围，利用PostgreSQL的全文搜索
* [sunspot](https://github.com/sunspot/sunspot)   -  Sunspot是一个Ruby库，用于与Solr搜索引擎进行富有表现力的强大交互.  太阳黑子建立在RSolr库之上，为Solr交互提供了一个低级接口;  Sunspot提供了一个简单，直观，富有表现力的DSL，其功能强大，可用于索引对象并搜索对象.
* [searchkick](https://github.com/ankane/searchkick) - 使用Rails和Elasticsearch轻松实现智能搜索.

## Scheduled/Recurrence Jobs
* [Whenever](https://github.com/javan/whenever) - 每当Ruby gem为编写和部署cron作业提供清晰的语法时.
* [Resque](https://github.com/resque/resque) -  Redis支持的Ruby库，用于创建后台作业，将它们放在多个队列中，以后再处理.
* [Rufus-Scheduler](https://github.com/jmettraux/rufus-scheduler)   -  Rufus-scheduler是一个用于安排代码片段（作业）的Ruby gem.  它了解在某个时间，在某个时间，每个x时间或仅通过CRON语句运行作业.
* [Delayed Job](https://github.com/collectiveidea/delayed_job) - 基于数据库的异步优先级队列系统
* [Sidekiq](https://github.com/mperham/sidekiq) - 简单，高效的Ruby后台处理.
  * [sidetiq](https://github.com/tobiassvn/sidetiq) -  sidekiq的重复工作.
  * [sidekiq-cron](https://github.com/ondrejbartas/sidekiq-cron) -  Sidekiq工作的Scheduler / Cron
  * [sidekiq-scheduler](https://github.com/Moove-it/sidekiq-scheduler) -  Sidekiq的轻量级作业调度程序扩展
* [Sucker Punch](https://github.com/brandonhilkert/sucker_punch) -  Sucker punch是一个单进程Ruby异步处理库.

## View Helper
* [formtastic](https://github.com/justinfrench/formtastic) - Formtastic is a Rails FormBuilder DSL (with some other goodies) to make it far easier to create beautiful, semantically rich, syntactically awesome, readily stylable and wonderfully accessible HTML forms in your Rails applications
* [Simple Form](https://github.com/plataformatec/simple_form)   - 简单的表单旨在尽可能灵活，同时帮助您使用强大的组件来创建表单.  Simple Form的基本目标是不触及定义布局的方式，让您找到更好的设计.
* [Nested Form](https://github.com/ryanb/nested_form)   - 这是一个Rails gem，可以方便地在一个表单中管理多个嵌套模型.  它通过jQuery或Prototype以不引人注目的方式实现.  它也可以与Simple Form集成.
* [meta-tags](https://github.com/kpumuk/meta-tags) -  Ruby on Rails应用程序的搜索引擎优化（SEO）插件.
* [active_link_to](https://github.com/comfy/active_link_to) -  active_link_to将css&#39;active&#39;类添加到您的链接.
* [cells](https://github.com/apotonick/cells)   - 单元格允许您将UI的一部分封装到视图模型中.  查看模型或单元格是可以呈现模板的简单ruby类.
* [i18n Country Code Select](https://github.com/onomojo/i18n_country_select) -  I18n国家代码选择Rails 3和4的表单助手.
* [Subdivision Select](https://github.com/cllns/subdivision_select) - 一个Rails插件，用于填充country_select中的州/省选择框.
* [cocoon](https://github.com/nathanvda/cocoon) - 使用jQuery的动态嵌套表单变得简单

## Environment Variables
* [Config](https://github.com/railsconfig/config) - 多环境YAML样式配置，可以轻松，有效地轻松管理特定于环境的设置.
* [Figaro](https://github.com/laserlemon/figaro) -  Figaro非常简单，使用ENV和单个YAML文件的Heroku友好的Rails app配置.
* [dotenv](https://github.com/bkeepers/dotenv) -  Dotenv是一个gem，允许您在.env文件中设置环境变量，并将其加载到ENV中.
* [opsworks-dotenv](https://github.com/mikamai/opsworks-dotenv) -  Opsworks-dotenv允许您使用OpsWorks，Chef和Dotenv为您的Rails应用程序配置环境.

## Admin Panel
* [ActiveAdmin](http://activeadmin.info) -  ActiveAdmin是Ruby on Rails应用程序的管理框架.
  - [active_skin](https://github.com/rstgroup/active_skin)：活动管理的平坦皮肤.
* [RailsAdmin](https://github.com/sferik/rails_admin) -  RailsAdmin是一个Rails引擎，提供易于使用的界面来管理您的数据.
* [administrate](https://github.com/thoughtbot/administrate) - 一个Rails引擎，可以帮助您组建一个超灵活的管理仪表板.
* [Trestle](https://github.com/TrestleAdmin/trestle) -  Ruby on Rails的现代响应式管理框架

## Logging
* [Impressionist](https://github.com/charlotte-ruby/impressionist)   - 印象派可以记录页面展示次数（技术上的动作展示次数），但不仅限于此.  您可以针对每个请求多次记录展示次数.  您还可以将其附加到模型中.  此项目的目标是提供可在您的应用程序中立即访问的可自定义统计信息，而不是使用Google Analytics并使用其API提取数据.
* [Ahoy](https://github.com/ankane/ahoy) -  Ahoy为跟踪Ruby，JavaScript和本机应用程序中的访问和事件提供了坚实的基础.
* [Lograge](https://github.com/roidrage/lograge) - 试图驯服Rails的默认策略来记录所有内容.

## Debug
* [byebug](https://github.com/deivid-rodriguez/byebug) -  Byebug是一个易于使用，功能丰富的Ruby 2调试器.它使用新的TracePoint API进行执行控制，并使用新的Debug Inspector API进行调用堆栈导航，因此它不依赖于内部核心源.
  * [pry-byebug](https://github.com/deivid-rodriguez/pry-byebug) - 通过byebug撬导航命令.
* [pry-rails](https://github.com/rweng/pry-rails)   - 避免重复自己，使用pry-rails而不是将初始化程序复制到每个rails项目.  这是一个小宝石，导致rails控制台打开撬.  因此，它取决于撬.
* [awesome_print](https://github.com/awesome-print/awesome_print) -  Awesome Print是一个Ruby库，它可以完美地打印出全彩色的Ruby对象，并通过适当的缩进来暴露其内部结构.
* [web-console](https://github.com/rails/web-console) -  Web Console是Ruby on Rails应用程序的调试工具.
* [spring](https://github.com/rails/spring)   -  Spring是一个Rails应用程序预加载器.  它通过让您的应用程序在后台运行来加速开发，因此您不必在每次运行测试，rake任务或迁移时都启动它.
* [rails-footnotes](https://github.com/josevalim/rails-footnotes) -  Rails脚注在您的应用程序中显示脚注，以便于调试，例如会话，请求参数，cookie，过滤器链，路由，查询等.
* [g](https://github.com/jugyo/g) - 使用terminal-notifier或growl，与Kernel.p类似的Kernel.g.
* [terminal-notifier](https://github.com/julienXX/terminal-notifier) -  terminal-notifier是一个发送Mac OS X用户通知的命令行工具，可在Mac OS X 10.8及更高版本中使用.
* [letter_opener](https://github.com/ryanb/letter_opener)   - 在默认浏览器中预览电子邮件而不是发送它.  这意味着您无需在开发环境中设置电子邮件传递，也不必担心将测试电子邮件意外发送到其他人的地址.
* [Better Errors](https://github.com/charliesome/better_errors) - 更好的错误将标准的Rails错误页面替换为更好，更有用的错误页面.
  *如果您想使用Better Errors的高级功能（REPL，本地/实例变量检查，漂亮的堆栈帧名称），您需要添加 [binding_ _of__caller](https://github.com/banister/binding_of_caller).
* [RailsPanel](https://github.com/dejan/rails_panel) -  RailsPanel是Rails开发的Chrome扩展，它将结束您对development.log的拖尾.

## Coding Style
* [RuboCop](https://github.com/bbatsov/rubocop)   -  Rubocop是一个Ruby静态代码分析器.  开箱即用它将强制执行社区中列出的许多准则 [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide).
* [Rails Best Practice](https://github.com/railsbp/rails_best_practices) -  Rails最佳实践是一种代码度量工具，用于检查rails代码的质量.
* [Metric Fu](https://github.com/hothero/awesome-rails-gem/blob/master/ https://github.com/metricfu/metric_fu) - 充满代码指标的拳头
* [Pronto](https://github.com/mmozuras/pronto) - 对您的更改进行快速自动代码审查

## Testing
* [rspec-rails](https://github.com/rspec/rspec-rails) -  Rspec-rails是Rails 3.x和4.x的测试框架.
* [Capybara](https://github.com/jnicklas/capybara)   -  Capybara通过模拟真实用户与您的应用互动的方式来帮助您测试Web应用程序.  和司机：
  - [capybara-webkit](https://github.com/thoughtbot/capybara-webkit) -  Capybara-webkit是一个通过QtWebkit使用Webkit的水豚驱动程序.
  - [selenium-webdriver](https://github.com/vertis/selenium-webdriver) -  Selenium-webdriver为WebDriver提供ruby绑定.
  - [poltergeist](https://github.com/teampoltergeist/poltergeist) -  Poltergeist允许您在PhantomJS提供的无头WebKit浏览器上运行Capybara测试.
  - [page-object](https://github.com/cheezy/page-object) -  Page-object是一个简单的gem，可以帮助创建灵活的页面对象来测试基于浏览器的应用程序.
* [factory_bot](https://github.com/thoughtbot/factory_bot) -  Factory_bot是一个灯具替代品，具有简单的定义语法，支持多个构建策略（保存的实例，未保存的实例，属性哈希和存根对象），并支持同一个类的多个工厂（user，admin_user等） ，包括工厂继承.
* [factory_bot_rails](https://github.com/thoughtbot/factory_bot_rails) -  Factory_bot_rails为factory_bot提供Rails集成.
* [factory_factory_girl](https://github.com/st0012/factory_factory_girl) -  FactoryFactoryGirl允许您使用命名规则更有效地生成工厂文件.
* [Database Cleaner](https://github.com/DatabaseCleaner/database_cleaner) -  Database Cleaner是一套用于在Ruby.Support ActiveRecord，DataMapper，Sequel，MongoMapper，Mongoid，CouchPotato，Ohm和Redis中清理数据库的策略.
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) -  Shoulda-matchers提供了几个用于测试常见Rails功能的匹配器.
* [ResponseCodeMatchers](https://github.com/r7kamura/response_code_matchers) -  ResponseCodeMatchers提供rspec匹配器以匹配http响应代码.
* [SimpleCov](https://github.com/colszowka/simplecov) -  SimpleCov是Ruby的代码覆盖率分析工具.
* [Timecop](https://github.com/travisjeffery/timecop) - 提供“时间旅行”和“时间冻结”功能的宝石，使得测试与时间相关的代码变得简单.
* [VCR](https://github.com/vcr/vcr) - 记录测试套件的HTTP交互并在将来的测试运行期间重放它们，以进行快速，确定，准确的测试.

### Security
* [brakeman](https://github.com/presidentbeef/brakeman) -  Brakeman是一个静态分析工具，可检查Ruby on Rails应用程序的安全漏洞.
* [bundle-audit](https://github.com/rubysec/bundler-audit) -  bundler-audit是Bundler的补丁级验证工具，用于检查宝石和不安全宝石源的易受攻击版本.
* [Secure Headers](https://github.com/twitter/secureheaders) - 安全标头将自动应用与安全性相关的多个标头.

## Production
* [Capistrano](https://github.com/capistrano/capistrano) - 远程多服务器自动化工具.
* [Slowpoke](https://github.com/ankane/slowpoke)   -  Rack :: Timeout很棒.  Slowpoke让它变得更好.
* [Rack Attack](https://github.com/kickstarter/rack-attack) - 将中间件托架到阻塞和限制.
* [Responders](https://github.com/plataformatec/responders) - 一组Rails响应程序来干扰您的应用程序.
* [production_rails](https://github.com/ankane/production_rails) - 在生产中运行Rails的最佳实践.
* [Mina](https://github.com/mina-deploy/mina) - 快速部署和服务器自动化工具.

## Error Logging
* [Rollbar](https://github.com/rollbar/rollbar-gem) - 从Ruby到Rollbar的异常跟踪和日志记录.
* [Airbrake](https://github.com/airbrake/airbrake) - 用于将应用程序与Airbrake集成的Notifier gem
* [Errbit](https://github.com/errbit/errbit) - 符合Airbrake的开源通知器gem.

## Database
* [rails_db](https://github.com/igorkasyanchuk/rails_db) -  Rails数据库查看器和SQL查询运行器

## Asset Pipeline
* [Alaska](https://github.com/mavenlink/alaska) - 与nodejs持久连接的ExecJS运行时，在开发和部署期间加快了coffeescript编译过程.

## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/hothero/awesome-rails-gem/blob/master/contributing.md) 第一.
