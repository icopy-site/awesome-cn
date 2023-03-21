<div class="github-widget" data-repo="hothero/awesome-rails-gem"></div>
## Awesome Rails Gem [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
用于 Rails 开发的一组很棒的 Ruby Gems.

目标是帮助每个 Rails 开发人员构建出色的 Rails 产品/服务.


## User

### Authentication
* [Devise](https://github.com/plataformatec/devise/) - Devise is a flexible authentication solution for Rails based on Warden.
* [Knock](https://github.com/nsarno/knock) - Rails API 的无缝 JWT 身份验证.
* [Clearance](https://github.com/thoughtbot/clearance) - 使用电子邮件和密码进行 Rails 身份验证.
* [Devise token auth](https://github.com/lynndylanhurley/devise_token_auth) - 用于 Rails JSON API 的基于令牌的身份验证.
* [Sorcery](https://github.com/Sorcery/sorcery)  - Rails 的神奇身份验证. 支持 ActiveRecord、DataMapper、Mongoid 和 MongoMapper.

### Authorization
* [Pundit](https://github.com/elabs/pundit) - Pundit 提供了一组帮助程序，可指导您利用常规 Ruby 类和面向对象的设计模式来构建一个简单、健壮且可扩展的授权系统.
* [cancancan](https://github.com/CanCanCommunity/cancancan)  - CanCan 的延续，Ruby on Rails 的授权 Gem.CanCan 是 Ruby on Rails 的授权库，它限制了允许给定用户访问的资源. 所有权限都在一个位置（Ability 类）定义，并且不会跨控制器、视图和数据库查询重复.
* [rolify](https://github.com/RolifyCommunity/rolify) - 具有资源范围的角色管理库.
* [acl9](https://github.com/be9/acl9/) - Acl9 是一个基于角色的授权系统，它提供了一个简洁的 DSL 来保护您的 Rails 应用程序.


### Omniauth
* [omniauth-facebook](https://github.com/mkdynamic/omniauth-facebook)
* [omniauth-google-oauth2](https://github.com/zquestz/omniauth-google-oauth2)
* [omniauth-weibo-oauth2](https://github.com/beenhero/omniauth-weibo-oauth2)
* [omniauth-twitter](https://github.com/arunagw/omniauth-twitter)
* [omniauth-github](https://github.com/intridea/omniauth-github)
* [omniauth-linkedin-oauth2](https://github.com/decioferreira/omniauth-linkedin-oauth2)

## Active Record
* [Enumerize](https://github.com/brainspec/enumerize)  - 支持 I18n 和 ActiveRecord/Mongoid 的枚举属性. 它可以与 Simple Form 集成.
* [counter_culture](https://github.com/magnusvk/counter_culture)  - 为您的 Rails 应用程序提供涡轮增压计数器缓存. 对 Rails 标准计数器缓存的巨大改进.
* [custom_counter_cache](https://github.com/cedric/custom_counter_cache) - 创建可跨多个模型使用的自定义计数器缓存的简单方法.
* [Sequenced](https://github.com/djreimer/sequenced) - Sequenced 是一个简单的 gem，它为 ActiveRecord 模型生成范围内的顺序 ID.
* [FriendlyId](https://github.com/norman/friendly_id)  - FriendlyId 是 ActiveRecord 的 slugging 和永久链接插件的“瑞士陆军推土机”. 它允许您创建漂亮的 URL 并使用人性化的字符串，就好像它们是 ActiveRecord 模型的数字 ID 一样.
* [AASM](https://github.com/aasm/aasm) - Ruby 类的状态机（普通 Ruby、Rails Active Record、Mongoid）.
* [PaperTrail](https://github.com/airblade/paper_trail)  - PaperTrail 可让您跟踪模型数据的变化. 它适用于审计或版本控制.
* [paranoia](https://github.com/rubysherpas/paranoia) - ActiveRecord 插件允许您隐藏和恢复记录而不实际删除它们.
* [Validates](https://github.com/kaize/validates) - Validates 为 Rails 应用程序提供有用的自定义验证器集合，包括：
  * 邮箱验证器
  * 网址验证器
  * 弹头验证器
  * 货币验证器
  * 验证器
  * 关联长度验证器
  * 绝对路径验证器
  * UriComponentValidator
  * 颜色验证器
  * EanValidator (EAN-8 &amp; EAN-13)
* [globalize](https://github.com/globalize/globalize) - 用于 ActiveRecord 模型/数据转换的 Rails I18n 事实上的标准库.
* [deep_cloneable](https://github.com/moiristo/deep_cloneable) - 此 gem 为每个 ActiveRecord::Base 对象提供了执行包含用户指定关联的深度克隆的可能性.
* [social_shares](https://github.com/Timrael/social_shares) - 检查 url 在社交网络中共享的次数.
* [public_activity](https://github.com/chaps-io/public_activity) - 模型的轻松活动跟踪 - 类似于 Github 的公共活动.
* [goldiloader](https://github.com/salsify/goldiloader) - 自动 ActiveRecord 预加载以减少应用程序运行的数据库查询的数量.
* 标记
  * [ActsAsTaggableOn](https://github.com/mbleigh/acts-as-taggable-on) - 允许沿动态上下文自定义标记的 Rails 应用程序的标记插件.
  * [closure_tree](https://github.com/mceachen/closure_tree) - 轻松高效地使您的 ActiveRecord 模型支持层次结构.
* [ActionStore](https://github.com/rails-engine/action-store) - 通过 ActiveRecord Polymorphic Association 在一张表中存储不同类型的操作（喜欢、关注、收藏、阻止...）.

## Plugins
* [Spreadsheet](https://github.com/zdavatz/spreadsheet) - 库旨在读取和写入电子表格文档.
* [Chartkick](https://github.com/ankane/chartkick) - Chartkick 帮助您使用一行 Ruby 创建漂亮的 Javascript 图表.
* [kaminari](https://github.com/amatsuda/kaminari) - 基于范围和引擎的、干净、强大、可定制和复杂的 Rails 3 和 4 分页器.
* [Slack Notifier](https://github.com/stevenosloan/slack-notifier) 是一个简单的包装器，用于发送通知 [Slack](https://slack.com/) 网络钩子.
* [Rails ERD](https://github.com/voormedia/rails-erd) - 为 Rails 应用程序生成实体关系图.
* [Parity](https://github.com/thoughtbot/parity) - 用于 Heroku 应用程序的开发、暂存和生产奇偶校验的 Shell 命令.
* [Airbrussh](https://github.com/mattbrictson/airbrussh) - Airbrussh 美化您的 SSHKit 和 Capistrano 输出

## API
* [Grape](https://github.com/ruby-grape/grape) - 在 Ruby 中创建 REST-ful API 的微框架.
* [ActiveModel::Serializers](https://github.com/rails-api/active_model_serializers) - 序列化程序为您的 JSON 生成带来了对配置的约定.
* [Jbuilder](https://github.com/rails/jbuilder)  - Jbuilder 为您提供了一个简单的 DSL，用于声明 JSON 结构，这胜过处理巨大的哈希结构. 当生成过程充满条件和循环时，这尤其有用.
* [rest-client](https://github.com/rest-client/rest-client) - 用于 Ruby 的简单 HTTP 和 REST 客户端，灵感来自用于指定操作的微框架语法.
* [has_scope](https://github.com/plataformatec/has_scope) - 将传入的控制器参数映射到资源中的命名范围.
* 文档
	* [Grape Swagger](https://github.com/ruby-grape/grape-swagger) - 自动生成有关 Grape API 的文档.
	* [Grape Swagger UI](https://github.com/swagger-api/swagger-ui) - 显示使用 Grape Swagger 生成的文档.
	* [apiary](https://apiary.io/) - 协同工作以快速设计、制作原型、记录和测试 API.
	* [apiblueprint](https://apiblueprint.org) - 具有强大工具的 API 文档.

## Email
* [letter_opener](https://github.com/ryanb/letter_opener) - 在浏览器中预览邮件而不是发送.

## File Uploading
* [Carrierwave](https://github.com/carrierwaveuploader/carrierwave) - Carrierwave 是用于 Rails、Sinatra 和其他 Ruby 网络框架的文件上传的更经典解决方案.
  * [carrierwave_backgrounder](https://github.com/lardawge/carrierwave_backgrounder) - 使用 Delayed Job、Resque、Sidekiq、Qu、Queue Classic 或 Girl Friday 将 CarrierWave 的图像处理和存储卸载到后台进程.
  * [CarrierWave Crop](https://github.com/kirtithorat/carrierwave-crop/) - 使用带预览的 Jcrop 插件裁剪上传图像的 Carrierwave 扩展.
  * [CarrierWave ImageOptimizer](https://github.com/jtescher/carrierwave-imageoptimizer) - 这个 gem 允许您使用 image_optimizer gem 通过 jpegoptim 或 optipng 简单地优化 CarrierWave 图像.
* [remotipart](https://github.com/JangoSteve/remotipart) - Rails jQuery 文件通过标准 Rails“remote: true”形式上传.
* [MiniMagick](https://github.com/minimagick/minimagick) - MiniMagick 是 ImageMagick 或 GraphicsMagick 命令行的红宝石包装器.
* [fog](https://github.com/fog/fog) - Fog 是 Ruby 云服务库，从上到下.
* [refile](https://github.com/refile/refile)  - Refile 是用于 Ruby 应用程序的现代文件上传库. 它很简单，但功能强大.
* [Paperclip](https://github.com/thoughtbot/paperclip) - ActiveRecord 的简单文件附件管理.
* [Dragonfly](http://markevans.github.io/dragonfly) - Dragonfly 用于即时文件处理 - 适用于图像或其他附件
* [shrine](https://github.com/janko-m/shrine) -Ruby 应用程序的文件附件工具包  

## Searching
* [ransack](https://github.com/activerecord-hackery/ransack) - Ransack 可以为您的 Ruby on Rails 应用程序创建简单和高级搜索表单.
* [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) - ActiveModel/Record 和 Ruby on Rails 的 Elasticsearch 集成.
* [Chewy](https://github.com/toptal/chewy) - 基于官方 elasticsearch-ruby 客户端的高级 Elasticsearch Ruby 框架.
* [pg_search](https://github.com/Casecommons/pg_search) - pg_search 构建 ActiveRecord 命名范围，利用 PostgreSQL 的全文搜索
* [sunspot](https://github.com/sunspot/sunspot)  - Sunspot 是一个 Ruby 库，用于与 Solr 搜索引擎进行富有表现力的强大交互.  Sunspot 建立在 RSolr 库之上，它为 Solr 交互提供了一个低级接口；  Sunspot 提供了一个简单、直观、富有表现力的 DSL，由强大的对象索引和搜索功能支持.
* [searchkick](https://github.com/ankane/searchkick) - 使用 Rails 和 Elasticsearch 轻松实现智能搜索.

## Scheduled/Recurrence Jobs
* [Whenever](https://github.com/javan/whenever) - Whenever 是一个 Ruby gem，它为编写和部署 cron 作业提供了清晰的语法.
* [Resque](https://github.com/resque/resque) - Redis 支持的 Ruby 库，用于创建后台作业，将它们放在多个队列中，并在以后处理它们.
* [Rufus-Scheduler](https://github.com/jmettraux/rufus-scheduler)  - Rufus-scheduler 是一个用于调度代码片段（作业）的 Ruby gem. 它了解在特定时间、在特定时间、每 x 次或仅通过 CRON 语句运行作业.
* [Delayed Job](https://github.com/collectiveidea/delayed_job) - 基于数据库的异步优先队列系统.
* [Sidekiq](https://github.com/mperham/sidekiq) - 简单、高效的 Ruby 后台处理.
  * [sidetiq](https://github.com/tobiassvn/sidetiq) - sidekiq 的重复工作.
  * [sidekiq-cron](https://github.com/ondrejbartas/sidekiq-cron) - Sidekiq 作业的调度程序/Cron
  * [sidekiq-scheduler](https://github.com/Moove-it/sidekiq-scheduler) - Sidekiq 的轻量级作业调度程序扩展
* [Sucker Punch](https://github.com/brandonhilkert/sucker_punch) - Sucker punch 是一个单进程的 Ruby 异步处理库.

## View Helper
* [formtastic](https://github.com/justinfrench/formtastic) - Formtastic 是一个 Rails FormBuilder DSL（还有其他一些好东西），可以更容易地在你的 Rails 应用程序中创建漂亮、语义丰富、语法很棒、易于设置样式和非常易于访问的 HTML 表单
* [Simple Form](https://github.com/plataformatec/simple_form)  - 简单的表单旨在尽可能灵活，同时帮助您使用强大的组件来创建您的表单.  Simple Form 的基本目标是不触及您定义布局的方式，让您找到更适合您眼睛的设计.
* [Nested Form](https://github.com/ryanb/nested_form)  - 这是一个 Rails gem，用于以单一形式方便地管理多个嵌套模型. 它通过 jQuery 或 Prototype 以一种不显眼的方式做到这一点. 它还可以与 Simple Form 集成.
* [meta-tags](https://github.com/kpumuk/meta-tags) - 用于 Ruby on Rails 应用程序的搜索引擎优化 (SEO) 插件.
* [active_link_to](https://github.com/comfy/active_link_to) - active_link_to 将 css &#39;active&#39; 类添加到您的链接.
* [cells](https://github.com/apotonick/cells)  - 单元格允许您将部分 UI 封装到视图模型中的组件中. 视图模型或单元格是可以呈现模板的简单 ruby​​ 类.
* [i18n Country Code Select](https://github.com/onomojo/i18n_country_select) - I18n 国家代码选择 Rails 3 和 4 的表单助手.
* [Subdivision Select](https://github.com/cllns/subdivision_select) - 用于从 country_select 填充州/省选择框的 Rails 插件.
* [cocoon](https://github.com/nathanvda/cocoon) - 使用 jQuery 的动态嵌套表单变得简单

## Environment Variables
* [Config](https://github.com/railsconfig/config) - 多环境 YAML 样式配置，有助于以简单易用的方式轻松管理环境特定设置.
* [Figaro](https://github.com/laserlemon/figaro) - Figaro 非常简单，使用 ENV 和单个 YAML 文件对 Heroku 友好的 Rails 应用程序配置.
* [dotenv](https://github.com/bkeepers/dotenv) - Dotenv 是一个 gem，它允许您在 .env 文件中设置环境变量，并将其加载到 ENV 中.
* [opsworks-dotenv](https://github.com/mikamai/opsworks-dotenv) - Opsworks-dotenv 让您可以使用 OpsWorks、Chef 和 Dotenv 为您的 Rails 应用程序配置环境.

## Admin Panel
* [ActiveAdmin](http://activeadmin.info) - ActiveAdmin 是 Ruby on Rails 应用程序的管理框架.
  - [active_skin](https://github.com/rstgroup/active_skin)：适合活跃管理员的扁平皮肤.
* [RailsAdmin](https://github.com/sferik/rails_admin) - RailsAdmin 是一个 Rails 引擎，它提供了一个易于使用的界面来管理您的数据.
* [administrate](https://github.com/thoughtbot/administrate) - 一个 Rails 引擎，可帮助您组合一个超级灵活的管理仪表板.
* [Trestle](https://github.com/TrestleAdmin/trestle) - 用于 Ruby on Rails 的现代响应式管理框架

## Logging
* [Impressionist](https://github.com/charlotte-ruby/impressionist)  - 印象派可以记录页面印象（技术上的动作印象），但不限于此. 您可以为每个请求多次记录印象. 您还可以将其附加到模型上. 该项目的目标是提供可在您的应用程序中立即访问的可自定义统计信息，而不是使用 Google Analytics 并使用其 API 提取数据.
* [Ahoy](https://github.com/ankane/ahoy) - Ahoy 为跟踪 Ruby、JavaScript 和本机应用程序中的访问和事件提供了坚实的基础.
* [Lograge](https://github.com/roidrage/lograge) - 尝试驯服 Rails 的默认策略以记录所有内容.

## Debug
* [byebug](https://github.com/deivid-rodriguez/byebug) - Byebug 是一个简单易用、功能丰富的 Ruby 2 调试器.它使用新的 TracePoint API 进行执行控制，并使用新的 Debug Inspector API 进行调用堆栈导航，因此它不依赖于内部核心源.
  * [pry-byebug](https://github.com/deivid-rodriguez/pry-byebug) - 通过 byebug 窥探导航命令.
* [pry-rails](https://github.com/rweng/pry-rails)  - 避免重复自己，使用 pry-rails 而不是将初始化程序复制到每个 rails 项目. 这是一个小宝石，它会导致 Rails 控制台打开撬. 因此，它取决于撬.
* [awesome_print](https://github.com/awesome-print/awesome_print) - Awesome Print 是一个 Ruby 库，它以全彩色漂亮地打印 Ruby 对象，并通过适当的缩进暴露其内部结构.
* [web-console](https://github.com/rails/web-console) - Web 控制台是用于 Ruby on Rails 应用程序的调试工具.
* [spring](https://github.com/rails/spring)  - Spring 是一个 Rails 应用程序预加载器. 它通过让你的应用程序在后台运行来加速开发，这样你就不需要在每次运行测试、rake 任务或迁移时都启动它.
* [rails-footnotes](https://github.com/josevalim/rails-footnotes) - Rails footnotes 在您的应用程序中显示脚注，以便于调试，例如会话、请求参数、cookie、过滤器链、路由、查询等.
* [g](https://github.com/jugyo/g) - 通过使用终端通知程序或咆哮，Kernel.g 的工作方式与 Kernel.p 类似.
* [terminal-notifier](https://github.com/julienXX/terminal-notifier) - terminal-notifier 是一个命令行工具，用于发送 Mac OS X 用户通知，可在 Mac OS X 10.8 及更高版本中使用.
* [letter_opener](https://github.com/ryanb/letter_opener)  - 在默认浏览器中预览电子邮件而不是发送它. 这意味着您不需要在您的开发环境中设置电子邮件发送，您也不再需要担心不小心将测试电子邮件发送到其他人的地址.
* [Better Errors](https://github.com/charliesome/better_errors) - 更好的错误将标准 Rails 错误页面替换为更好、更有用的错误页面.
  * 如果您想使用 Better Errors 的高级功能（REPL、本地/实例变量检查、漂亮的堆栈框架名称），您需要添加 [binding_ _of__caller](https://github.com/banister/binding_of_caller).
* [RailsPanel](https://github.com/dejan/rails_panel) - RailsPanel 是用于 Rails 开发的 Chrome 扩展，它将结束您对 development.log 的跟踪.

## Coding Style
* [RuboCop](https://github.com/bbatsov/rubocop)  - Rubocop 是一个 Ruby 静态代码分析器. 开箱即用，它将执行社区中概述的许多准则 [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide).
* [Rails Best Practice](https://github.com/railsbp/rails_best_practices) - Rails 最佳实践是一种代码度量工具，用于检查 Rails 代码的质量.
* [Metric Fu](https://github.com/hothero/awesome-rails-gem/blob/master/ https://github.com/metricfu/metric_fu) - 充满代码指标的拳头
* [Pronto](https://github.com/mmozuras/pronto) - 对您的更改进行快速自动代码审查

## Testing
* [rspec-rails](https://github.com/rspec/rspec-rails) - Rspec-rails 是 Rails 3.x 和 4.x 的测试框架.
* [Capybara](https://github.com/jnicklas/capybara)  - Capybara 通过模拟真实用户如何与您的应用程序交互来帮助您测试 Web 应用程序. 和司机：
  - [capybara-webkit](https://github.com/thoughtbot/capybara-webkit) - Capybara-webkit 是一个通过 QtWebkit 使用 Webkit 的水豚驱动程序.
  - [selenium-webdriver](https://github.com/vertis/selenium-webdriver) - Selenium-webdriver 为 WebDriver 提供 ruby​​ 绑定.
  - [poltergeist](https://github.com/teampoltergeist/poltergeist) - Poltergeist 允许您在 PhantomJS 提供的无头 WebKit 浏览器上运行您的 Capybara 测试.
  - [page-object](https://github.com/cheezy/page-object) - Page-object 是一个简单的 gem，可帮助创建灵活的页面对象以测试基于浏览器的应用程序.
* [factory_bot](https://github.com/thoughtbot/factory_bot) - Factory_bot 是一种固定装置替代品，具有简单的定义语法，支持多种构建策略（保存的实例、未保存的实例、属性哈希和存根对象），并支持同一类的多个工厂（用户、admin_user 等） ，包括工厂继承.
* [factory_bot_rails](https://github.com/thoughtbot/factory_bot_rails) - Factory_bot_rails 为 factory_bot 提供 Rails 集成.
* [factory_factory_girl](https://github.com/st0012/factory_factory_girl) - FactoryFactoryGirl 让您使用命名规则更高效地生成工厂文件.
* [Database Cleaner](https://github.com/DatabaseCleaner/database_cleaner) - Database Cleaner 是一组用于在 Ruby 中清理数据库的策略.支持 ActiveRecord、DataMapper、Sequel、MongoMapper、Mongoid、CouchPotato、Ohm 和 Redis.
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - Shoulda-matchers 提供了几个匹配器来测试常见的 Rails 功能.
* [ResponseCodeMatchers](https://github.com/r7kamura/response_code_matchers) - ResponseCodeMatchers 提供 rspec 匹配器来匹配 http 响应代码.
* [SimpleCov](https://github.com/colszowka/simplecov) - SimpleCov is a code coverage analysis tool for Ruby.
* [Timecop](https://github.com/travisjeffery/timecop) - 提供“时间旅行”和“时间冻结”功能的 gem，使测试时间相关代码变得非常简单.
* [VCR](https://github.com/vcr/vcr) - 记录您的测试套件的 HTTP 交互并在未来的测试运行期间重播它们以进行快速、确定性、准确的测试.

### Security
* [brakeman](https://github.com/presidentbeef/brakeman) - Brakeman 是一种静态分析工具，用于检查 Ruby on Rails 应用程序是否存在安全漏洞.
* [bundle-audit](https://github.com/rubysec/bundler-audit) - bundler-audit 是 Bundler 的补丁级验证工具，用于检查 gem 的易受攻击版本和不安全的 gem 源.
* [Secure Headers](https://github.com/twitter/secureheaders) - 安全标头将自动应用多个与安全相关的标头.

## Production
* [Capistrano](https://github.com/capistrano/capistrano) - 远程多服务器自动化工具.
* [Slowpoke](https://github.com/ankane/slowpoke)  - Rack::Timeout 很棒.  Slowpoke 让它变得更好.
* [Rack Attack](https://github.com/kickstarter/rack-attack) - 用于阻塞和节流的机架中间件.
* [Responders](https://github.com/plataformatec/responders) - 一组 Rails 响应器来干掉你的应用程序.
* [production_rails](https://github.com/ankane/production_rails) - 在生产中运行 Rails 的最佳实践.
* [Mina](https://github.com/mina-deploy/mina) - 快速部署和服务器自动化工具.

## Error Logging
* [Rollbar](https://github.com/rollbar/rollbar-gem) - 从 Ruby 到 Rollbar 的异常跟踪和日志记录.
* [Airbrake](https://github.com/airbrake/airbrake) - 用于将应用程序与 Airbrake 集成的通知程序 gem
* [Errbit](https://github.com/errbit/errbit) - 与 Airbrake 兼容的开源通知程序 gem.

## Database
* [rails_db](https://github.com/igorkasyanchuk/rails_db) - Rails 数据库查看器和 SQL 查询运行器

## Asset Pipeline
* [Alaska](https://github.com/mavenlink/alaska) - 与 nodejs 持久连接的 ExecJS 运行时，在开发和部署期间加速您的 coffeescript 编译过程.

## Contribute

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/hothero/awesome-rails-gem/blob/master/contributing.md) 第一的.
