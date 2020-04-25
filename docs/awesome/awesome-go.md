<div class="github-widget" data-repo="avelino/awesome-go"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Go

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinorun)

对Awesome Go的财务支持

**我们没有每月费用** _，但我们有员工**努力工作**，以维持Awesome Go，筹集的资金可以偿还每个相关人员的努力！_

 精选的Go框架，库和软件的精选清单.  受启发 [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

请快速浏览一下 [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md)  第一.  谢谢大家 [contributors](https://github.com/avelino/awesome-go/graphs/contributors) ;  你摇滚！

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*





## Audio and Music

*用于处理音频的库.

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - EasyMidi is a simple and reliable library for working with standard midi file (SMF).
* [flac](https://github.com/mewkiz/flac) -支持FLAC流的Native Go FLAC编码器/解码器.
* [gaad](https://github.com/Comcast/gaad) -本机Go AAC比特流解析器.
* [go-sox](https://github.com/krig/go-sox) -go的libsox绑定.
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) -go的libmediainfo绑定.
* [gosamplerate](https://github.com/dh1tw/gosamplerate) -libsamplerate绑定.
* [id3v2](https://github.com/bogem/id3v2) -用于Go的快速，稳定的ID3解析和编写库.
* [malgo](https://github.com/gen2brain/malgo) -迷你音频库.
* [minimp3](https://github.com/tosone/minimp3) -轻巧的MP3解码器库.
* [mix](https://github.com/go-mix/mix) -用于音乐应用程序的基于序列的Go-native音频混合器.
* [mp3](https://github.com/tcolgate/mp3) -本机Go MP3解码器.
* [music-theory](https://github.com/go-music-theory/music-theory) -Go中的音乐理论模型.
* [Oto](https://github.com/hajimehoshi/oto) -一个低级库，可在多个平台上播放声音.
* [PortAudio](https://github.com/gordonklaus/portaudio) -绑定PortAudio音频I / O库.
* [portmidi](https://github.com/rakyll/portmidi) -绑定PortMidi.
* [taglib](https://github.com/wtolson/go-taglib) -为taglib绑定.
* [vorbis](https://github.com/mccoyst/vorbis) -“本机” Go Vorbis解码器（使用CGO，但没有依赖项）.
* [waveform](https://github.com/mdlayher/waveform) -Go软件包能够从音频流生成波形图像.

## Authentication and OAuth

*用于实施身份验证方案的库.*

* [authboss](https://github.com/volatiletech/authboss)  -用于网络的模块化身份验证系统.  它尝试删除尽可能多的样板文件和“硬东西”，以便每次在Go中启动新的Web项目时，都可以将其插入，配置并开始构建应用程序，而不必每次都构建身份验证系统.
* [branca](https://github.com/hako/branca) -Branca令牌的实现.
* [casbin](https://github.com/hsluoyz/casbin) -支持访问控制模型（如ACL，RBAC，ABAC）的授权库.
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) -提供cookies.txt文件格式的解析器.
* [go-jose](https://github.com/square/go-jose) -完全完整地实现了JOSE工作组的JSON Web令牌，JSON Web签名和JSON Web加密规范.
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) -使用Golang编写的独立的，符合规范的OAuth2服务器.
* [gologin](https://github.com/dghubble/gologin) -用于使用OAuth1和OAuth2身份验证提供程序登录的可链接处理程序.
* [gorbac](https://github.com/mikespook/gorbac) -在Golang中提供了基于角色的轻量级访问控制（RBAC）实现.
* [goth](https://github.com/markbates/goth)  -提供了一种简单，干净且惯用的方式来使用OAuth和OAuth2.  开箱即用地处理多个提供程序.
* [httpauth](https://github.com/goji/httpauth) -HTTP身份验证中间件.
* [jeff](https://github.com/abraithwaite/jeff) -具有可插入后端的简单，灵活，安全和惯用的Web会话管理.
* [jwt](https://github.com/robbert229/jwt) -JSON Web令牌（JWT）的清洁易用实现.
* [jwt](https://github.com/pascaldekloe/jwt) -轻量级JSON Web令牌（JWT）库.
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) -用于Golang http服务器的JWT中间件，具有许多配置选项.
* [jwt-go](https://github.com/dgrijalva/jwt-go) -JSON Web令牌（JWT）的实现.
* [loginsrv](https://github.com/tarent/loginsrv) -具有可插入后端的JWT登录微服务，例如OAuth2（Github），htpasswd，osiam.
* [oauth2](https://github.com/golang/oauth2)  -goauth2的后继者.  JWT，Google API，Compute Engine和App Engine支持随附的通用OAuth 2.0程序包.
* [osin](https://github.com/openshift/osin) -键入OAuth2服务器库.
* [paseto](https://github.com/o1egl/paseto) -与平台无关的安全令牌（PASETO）的Golang实现.
* [permissions2](https://github.com/xyproto/permissions2)  -用于跟踪用户，登录状态和权限的库.  使用安全的cookie和bcrypt.
* [rbac](https://github.com/zpatrick/rbac) -用于Go应用程序的简约RBAC软件包.
* [scope](https://github.com/SonicRoshan/scope) -在Go中轻松管理OAuth2范围.
* [scs](https://github.com/alexedwards/scs) -HTTP服务器的会话管理器.
* [securecookie](https://github.com/chmike/securecookie) -高效的安全cookie编码/解码.
* [session](https://github.com/icza/session) -Web服务器的Go会话管理（包括对Google App Engine-GAE的支持）.
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) -使用SessionGate Redis模块进行会话管理.
* [sessions](https://github.com/adam-hanna/sessions) -用于go http服务器的简单，高性能，高度可定制的会话服务.
* [sessionup](https://github.com/swithek/sessionup) -简单而有效的HTTP会话管理和标识包.
* [signedvalue](https://github.com/sashka/signedvalue) -签名并带有时间戳记的字符串与 [Tornado's](https://github.com/tornadoweb/tornado) “ create_signed_value”，“ decode_signed_value”以及“ set_secure_cookie”和“ get_secure_cookie”.
* [sjwt](https://github.com/brianvoe/sjwt) -简单的jwt生成器和解析器.

## Bot Building

*用于构建和使用机器人的库.*

* [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) -Discord机器人，用于根据语音通道成员的存在来管理临时角色.
* [go-chat-bot](https://github.com/go-chat-bot/bot) -用Go编写的IRC，Slack和Telegram机器人.
* [go-joe](https://joe-bot.net) -受Hubot启发但用Go编写的通用bot库.
* [go-sarah](https://github.com/oklahomer/go-sarah) -为所需的聊天服务（包括LINE，Slack，Gitter等）构建机器人的框架.
* [go-tgbot](https://github.com/olebedev/go-tgbot) -从swagger文件，基于会话的路由器和中间件生成的纯Golang Telegram Bot API包装器.
* [go-twitch-irc](https://github.com/gempir/go-twitch-irc) -库为twitch.tv聊天写机器人
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) -基于控制台的交易机器人的golang实现，用于进行加密货币交换.
* [govkbot](https://github.com/nikepan/govkbot) -简单的去 [VK](https://vk.com) bot库.
* [hanu](https://github.com/sbstjn/hanu) -编写Slack机器人的框架.
* [Kelp](https://github.com/stellar/kelp) -官方交易和做市机器人 [Stellar](https://www.stellar.org/)  敏捷  开箱即用，用Golang编写，可与集中交易和自定义交易策略兼容.
* [margelet](https://github.com/zhulik/margelet) -构建Telegram机器人的框架.
* [micha](https://github.com/onrik/micha) -前往电报Bot API的库.
* [olivia](https://github.com/olivia-ai/olivia) -使用人工神经网络构建的聊天机器人.
* [slacker](https://github.com/shomali11/slacker) -易于使用的框架来创建Slack机器人.
* [slackscot](https://github.com/alexandre-normand/slackscot) -用于构建Slack机器人的另一个框架.
* [tbot](https://github.com/yanzay/tbot) -具有类似于net / http的API的Telegram bot服务器.
* [telebot](https://github.com/tucnak/telebot) -用Go编写的Telegram机器人框架.
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) -简单干净的Telegram机器人客户端.
* [Tenyks](https://github.com/kyleterry/tenyks) -使用Redis和JSON进行消息传递的面向服务的IRC机器人.

## Command Line

### Standard CLI

*用于构建标准或基本命令行应用程序的库.

* [1build](https://github.com/gopinath-langote/1build) -命令行工具，可轻松管理特定于项目的命令.
* [argparse](https://github.com/akamensky/argparse) -受Python的argparse模块启发的命令行参数解析器.
* [argv](https://github.com/cosiner/argv) -转到库以使用bash语法将命令行字符串拆分为参数数组.
* [cli](https://github.com/mkideal/cli) -基于golang struct标签的功能丰富且易于使用的命令行包.
* [cli](https://github.com/teris-io/cli) -用于在Go中构建命令行界面的简单而完整的API.
* [cli-init](https://github.com/tcnksm/gcli) -开始构建Golang命令行应用程序的简单方法.
* [climax](http://github.com/tucnak/climax) -遵循Go命令的精神，具有“人脸”功能的替代CLI.
* [clîr](https://github.com/leaanthony/clir)  -简单明了的CLI库.  无依赖关系.
* [cmd](https://github.com/posener/cmd) -扩展了标准`flag`软件包，以支持子命令，并且以idomatic方式提供更多支持.
* [cmdr](https://github.com/hedzr/cmdr) -POSIX / GNU样式，类似于getopt的命令行UI Go库.
* [cobra](https://github.com/spf13/cobra) -用于现代Go CLI交互的指挥官.
* [commandeer](https://github.com/jaffee/commandeer) -开发友好的CLI应用程序：根据结构字段和标签设置标志，默认值和用法.
* [complete](https://github.com/posener/complete) -在Go + Go命令bash完成中编写bash完成.
* [Dnote](https://github.com/dnote/dnote) -具有多设备同步功能的简单命令行笔记本.
* [docopt.go](https://github.com/docopt/docopt.go) -命令行参数解析器，会让您微笑.
* [env](https://github.com/codingconcepts/env) -基于标记的结构环境配置.
* [flag](https://github.com/cosiner/flag) -Go支持子命令的简单但功能强大的命令行选项解析库.
* [flaggy](https://github.com/integrii/flaggy) -强大且惯用的标志包，具有出色的子命令支持.
* [flagvar](https://github.com/sgreben/flagvar) -Go的标准`flag`包的标志参数类型的集合.
* [go-arg](https://github.com/alexflint/go-arg) -Go中基于结构的参数解析.
* [go-commander](https://github.com/yitsushi/go-commander) -转到库以简化CLI工作流程.
* [go-flags](https://github.com/jessevdk/go-flags) -转到命令行选项解析器.
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) -Go选项解析器启发了Perl的GetOpt :: Long的灵活性.
* [gocmd](https://github.com/devfacet/gocmd) -用于构建命令行应用程序的库.
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) -具有自动配置和依赖项注入的cli应用程序框架.
* [job](https://github.com/liujianping/job) -工作，将您的短期命令作为一项长期工作.
* [kingpin](https://github.com/alecthomas/kingpin) -命令行和标志解析器支持子命令.
* [liner](https://github.com/peterh/liner) -使用类似于readline的命令行界面库.
* [mitchellh/cli](https://github.com/mitchellh/cli) -用于实现命令行界面的Go库.
* [mow.cli](https://github.com/jawher/mow.cli) -Go库，用于使用复杂的标志和参数解析和验证来构建CLI应用程序.
* [ops](https://github.com/nanovms/ops) -Unikernel生成器/协调器.
* [pflag](https://github.com/spf13/pflag) -替换Go的标志包，实现POSIX / GNU样式的--flags.
* [readline](https://github.com/chzyer/readline) -纯粹的golang实现，根据MIT许可在GNU-Readline中提供大多数功能.
* [sand](https://github.com/Zaba505/sand) -用于创建解释器的简单API等.
* [sflags](https://github.com/octago/sflags) -基于结构的标志生成器，用于标志，urfave / cli，pflag，眼镜蛇，主销和其他库.
* [strumt](https://github.com/antham/strumt) -库创建提示链.
* [ts](https://github.com/liujianping/ts) -时间戳转换和比较工具.
* [ukautz/clif](https://github.com/ukautz/clif) -小型命令行界面框架.
* [urfave/cli](https://github.com/urfave/cli) -用于在Go中构建命令行应用程序的简单，快速且有趣的软件包（以前为codegangsta / cli）.
* [wlog](https://github.com/dixonwille/wlog) -支持跨平台颜色和并发性的简单日志记录界面.
* [wmenu](https://github.com/dixonwille/wmenu) -cli应用程序易于使用的菜单结构，提示用户做出选择.

### Advanced Console UIs

*用于构建控制台应用程序和控制台用户界面的库.

* [asciigraph](https://github.com/guptarohit/asciigraph) -转到软件包，以在命令行应用程序中制作轻量级的ASCII线图╭┈╯，而无需其他依赖项.
* [aurora](https://github.com/logrusorgru/aurora) -支持fmt.Printf / Sprintf的ANSI终端颜色.
* [cfmt](https://github.com/mingrammer/cfmt) -受引导颜色类启发的上下文功能.
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* [colourize](https://github.com/TreyBastian/colourize) -在终端中转到ANSI颜色文本的库.
* [ctc](https://github.com/wzshiming/ctc) -非侵入性跨平台终端颜色库不需要修改Print方法.
* [go-ataman](https://github.com/workanator/go-ataman) -用于在终端中呈现ANSI彩色文本模板的库.
* [go-colorable](https://github.com/mattn/go-colorable) -Windows的彩色书写器.
* [go-colortext](https://github.com/daviddengcn/go-colortext) -转到库以在终端中输出颜色.
* [go-isatty](https://github.com/mattn/go-isatty) -golang的饱腹感.
* [go-prompt](https://github.com/c-bata/go-prompt) -受启发的图书馆，用于构建功能强大的交互式提示 [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
* [gocui](https://github.com/jroimartin/gocui) -极简主义Go库，旨在创建控制台用户界面.
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) -样式终端文字.
* [gookit/color](https://github.com/gookit/color) -终端色彩渲染工具库，支持16色，256色，RGB色彩渲染输出，与Windows兼容.
* [mpb](https://github.com/vbauerster/mpb) -终端应用程序的多进度条.
* [progressbar](https://github.com/schollz/progressbar) -适用于每个操作系统的基本线程安全进度条.
* [simpletable](https://github.com/alexeyco/simpletable) -使用Go在终端中创建简单表.
* [tabby](https://github.com/cheynewallace/tabby) -一个用于超级简单Golang表的小型库.
* [tabular](https://github.com/InVisionApp/tabular) -从命令行实用程序中打印ASCII表，而无需将大量数据传递给API.
* [termbox-go](https://github.com/nsf/termbox-go) -Termbox是用于创建跨平台基于文本的界面的库.
* [termdash](https://github.com/mum4k/termdash) -基于** termbox-go **并受灵感启发的终端仪表板 [termui](https://github.com/gizak/termui).
* [termui](https://github.com/gizak/termui) -基于** termbox-go **并受灵感启发的终端仪表板 [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* [uilive](https://github.com/gosuri/uilive) -用于实时更新终端输出的库.
* [uiprogress](https://github.com/gosuri/uiprogress) -灵活的库，可在终端应用程序中呈现进度条.
* [uitable](https://github.com/gosuri/uitable) -利用表格数据提高终端应用程序可读性的库.
* [yacspin](https://github.com/theckman/yacspin) -另一个CLi Spinner软件包，用于与终端旋转器一起使用.

## Configuration

*用于配置解析的库.*

* [cleanenv](https://github.com/ilyakaznacheev/cleanenv) -简约的配置读取器（来自文件，ENV，以及您想要的任何位置）.
* [config](https://github.com/golobby/config) -Go项目的轻量级功能强大的配置包.
* [config](https://github.com/JeremyLoy/config)  -云原生应用程序配置.  仅两行将ENV绑定到结构.
* [config](https://github.com/olebedev/config) -带有环境变量和标志解析的JSON或YAML配置包装器.
* [configuration](https://github.com/BoRuDar/configuration) -用于从环境变量，文件，标志和“默认”标记初始化配置结构的库.
* [configure](https://github.com/paked/configure) -通过多个来源提供配置，包括JSON，标志和环境变量.
* [configuro](https://github.com/sherifabdlnaby/configuro) -ENV和Files的自以为是的配置加载和验证框架，专注于12因子兼容应用程序.
* [confita](https://github.com/heetch/confita) -将配置从多个后端级联加载到结构中.
* [conflate](https://github.com/the4thamigo-uk/conflate) -用于合并来自任意URL的多个JSON / YAML / TOML文件，针对JSON模式进行验证以及应用模式中定义的默认值的库/工具.
* [env](https://github.com/caarlos0/env) -将环境变量解析为Go结构（具有默认值）.
* [envcfg](https://github.com/tomazk/envcfg) -将环境变量解编为Go结构.
* [envconf](https://github.com/ian-kent/envconf) -从环境配置.
* [envconfig](https://github.com/vrischmann/envconfig) -从环境变量中读取您的配置.
* [envh](https://github.com/antham/envh) -帮助者管理环境变量.
* [gcfg](https://github.com/go-gcfg/gcfg)  -将INI样式的配置文件读取到Go结构中；  支持用户定义的类型和子节.
* [genv](https://github.com/sakirsensoy/genv) -通过dotenv支持轻松读取环境变量.
* [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) -Go实用程序，用于从AWS SSM（参数存储）加载配置参数.
* [go-up](https://github.com/ufoscout/go-up) -一个简单的配置库，具有递归占位符解析度并且没有魔术.
* [goConfig](https://github.com/crgimenes/goConfig) -将结构解析为输入，并使用命令行，环境变量和配置文件中的参数填充此结构的字段.
* [godotenv](https://github.com/joho/godotenv) -转到Ruby的dotenv库的端口（从`.env`加载环境变量）.
* [gofigure](https://github.com/ian-kent/gofigure) -轻松进行应用程序配置.
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf)  -模块化JSON配置.  在不牺牲完整的配置序列化的情况下，使您的配置结构以及它们配置的代码以及将解析委派给子模块的过程.
* [gookit/config](https://github.com/gookit/config)  -应用程序配置管理（加载，获取，设置）.  支持JSON，YAML，TOML，INI，HCL.  多文件加载，数据覆盖合并.
* [harvester](https://github.com/beatlabs/harvester) -Harvester，易于使用的静态和动态配置包，支持iged播种，env vars和Consul集成.
* [hjson](https://github.com/hjson/hjson-go)  -Human JSON，人类的配置文件格式.  轻松的语法，更少的错误，更多的注释.
* [hocon](https://github.com/gurkankaymak/hocon) -用于使用HOCON（一种对人类友好的JSON超集）格式的配置库，支持诸如环境变量，引用其他值，注释和多个文件之类的功能.
* [ingo](https://github.com/schachmat/ingo) -标志保存在类似ini的配置文件中.
* [ini](https://github.com/go-ini/ini) -转到程序包以读取和写入INI文件.
* [joshbetz/config](https://github.com/joshbetz/config) -Go的小型配置库，可解析环境变量，JSON文件，并在SIGHUP上自动重新加载.
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) -Go库，用于管理环境变量中的配置数据.
* [koanf](https://github.com/knadh/koanf)  -轻巧，可扩展的库，用于在Go应用程序中读取配置.  内置对JSON，TOML，YAML，env，命令行的支持.
* [konfig](https://github.com/lalamove/konfig) -在分布式处理时代，Go的可组合，可观察和高性能配置处理.
* [mini](https://github.com/sasbury/mini) -Golang软件包，用于解析ini样式的配置文件.
* [nasermirzaei89/env](https://github.com/nasermirzaei89/env) -用于读取环境变量的简单有用的程序包.
* [onion](http://github.com/goraz/onion) -Go的基于层的配置，支持JSON，TOML，YAML，属性，etcd，env和使用PGP加密.
* [sprbox](https://github.com/oblq/sprbox) -建立环境意识的工具箱工厂和不可知的配置解析器（YAML，TOML，JSON和环境变量）.
* [store](https://github.com/tucnak/store) -Go的轻量级配置管理器.
* [viper](https://github.com/spf13/viper) -使用毒牙进行配置.
* [xdg](https://github.com/OpenPeeDeeP/xdg) -遵循以下内容的跨平台软件包 [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## Continuous Integration

*持续集成帮助工具.*

* [CDS](https://github.com/ovh/cds) -企业级CI / CD和DevOps自动化开源平台.
* [drone](https://github.com/drone/drone) -Drone是一个基于Go编写的基于Docker的持续集成平台.
* [duci](https://github.com/duck8823/duci) -简单的CI服务器无需域特定语言.
* [gomason](https://github.com/nikogura/gomason) -在干净的工作区中测试，构建，签名和发布go二进制文件.
* [goveralls](https://github.com/mattn/goveralls) -集成Coveralls.io连续代码覆盖率跟踪系统.
* [overalls](https://github.com/go-playground/overalls) -多包goover项目Coverprofile，用于管理工具.
* [roveralls](https://github.com/LawrenceWoodman/roveralls) -递归覆盖率测试工具.

## CSS Preprocessors

*用于预处理CSS文件的库.*

* [gcss](https://github.com/yosssi/gcss) -Pure Go CSS预处理器.
* [go-libsass](https://github.com/wellington/go-libsass) -包装到100％Sass兼容的libsass项目.

## Data Structures

* Go中的通用数据结构和算法.

* [algorithms](https://github.com/shady831213/algorithms) -算法和数据结构.CLRS研究.
* [binpacker](https://github.com/zhuangsirui/binpacker) -二进制打包程序和解压缩程序可帮助用户构建自定义二进制流.
* [bit](https://github.com/yourbasic/bit) -Golang设置数据结构，具有额外的位旋转功能.
* [bitset](https://github.com/willf/bitset) -打包实现位集的软件包.
* [bloom](https://github.com/zhenjl/bloom) -Go中实现的Bloom过滤器.
* [bloom](https://github.com/yourbasic/bloom) -布隆过滤器实现.
* [boomfilters](https://github.com/tylertreat/BoomFilters) -用于处理连续无界流的概率数据结构.
* [concurrent-writer](https://github.com/free/concurrent-writer) -高度并行替换bufio.Writer.
* [conjungo](https://github.com/InVisionApp/conjungo) -一个小型，强大而灵活的合并库.
* [count-min-log](https://github.com/seiflotfy/count-min-log) -执行Count-Min-Log草图：使用近似计数器进行近似计数（类似于Count-Min草图，但使用较少的内存）.
* [crunch](https://github.com/superwhiskers/crunch) -Go包实现了用于轻松处理各种数据类型的缓冲区.
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) -布谷鸟过滤器：Go中实现的计数布隆过滤器的很好替代.
* [deque](https://github.com/edwingeng/deque) -高度优化的双端队列.
* [deque](https://github.com/gammazero/deque) -快速的环形缓冲区双端队列（双端队列）.
* [dict](https://github.com/srfrog/dict) -Go的类Python字典（dict）.
* [encoding](https://github.com/zhenjl/encoding) -用于Go的整数压缩库.
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) -实施自适应基数树.
* [go-datastructures](https://github.com/Workiva/go-datastructures) -收集有用的，高性能的和线程安全的数据结构.
* [go-ef](https://github.com/amallia/go-ef) -Elias-Fano编码的Go实现.
* [go-geoindex](https://github.com/hailocab/go-geoindex) -内存地理索引.
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache)  -快速的内存键：值存储/缓存库.  指针缓存.
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) -具有有效点定位和邻居发现功能的区域四叉树.
* [gocache](https://github.com/eko/gocache) -完整的Go缓存库，具有多个存储（内存，memcache，redis等），可链接，可加载，指标缓存等.
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) -并发FIFO队列.
* [gods](https://github.com/emirpasic/gods)  -数据结构.  容器，集合，列表，堆栈，地图，BidiMap，树，HashSet等.
* [gofal](https://github.com/xxjwxc/gofal) -Go的小数api.
* [golang-set](https://github.com/deckarep/golang-set) -Go的线程安全和非线程安全高性能集.
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* [goskiplist](https://github.com/ryszard/goskiplist) -在Go中跳过列表实施.
* [gostl](https://github.com/liyue201/gostl) -用于go的数据结构和算法库，旨在提供类似于C ++ STL的功能.
* [gota](https://github.com/kniren/gota) -实现Go的数据框，序列和数据整理方法.
* [hide](https://github.com/emvi/hide) -带有进出哈希的封送的ID类型，以防止将ID发送给客户端.
* [hilbert](https://github.com/google/hilbert) -Go软件包，用于在空间填充曲线（例如希尔伯特曲线和Peano曲线）之间来回映射值.
* [hyperloglog](https://github.com/axiomhq/hyperloglog) -HyperLogLog实施，具有稀疏，LogLog-Beta偏差校正和TailCut空间减少功能.
* [iter](https://github.com/disksing/iter) -实现C ++ STL迭代器和算法.
* [levenshtein](https://github.com/agext/levenshtein) -Levenshtein距离和相似性指标，带有可自定义的编辑费用，以及通用前缀的类似于Winkler的奖金.
* [levenshtein](https://github.com/agnivade/levenshtein) -在Go中计算levenshtein距离的实现.
* [mafsa](https://github.com/smartystreets/mafsa) -具有最小完美哈希的MA-FSA实现.
* [mspm](https://github.com/BlackRabbitt/mspm) -用于信息检索的多字符串模式匹配算法.
* [null](https://github.com/emvi/null) -可与JSON编组/解组的Nullable Go类型.
* [parsefields](https://github.com/MonaxGT/parsefields) -用于解析类似JSON的日志的工具，以收集唯一的字段和事件.
* [pipeline](https://github.com/hyfather/pipeline) -具有扇入和扇出的管道实施.
* [ptrie](https://github.com/viant/ptrie) -前缀树的实现.
* [remember-go](https://github.com/rocketlaunchr/remember-go) -用于缓存慢速数据库查询的通用接口（由redis，memcached，ristretto或内存支持）.
* [ring](https://github.com/TheTannerRyan/ring) -实施高性能，线程安全的布隆过滤器.
* [roaring](https://github.com/RoaringBitmap/roaring) -实施压缩位集的软件包.
* [set](https://github.com/StudioSol/set) -使用LinkedHashMap在Go中简单设置数据结构.
* [skiplist](https://github.com/MauriceGit/skiplist) -快速执行Go Skiplist.
* [skiplist](https://github.com/gansidui/skiplist) -Go中的Skiplist实现.
* [timedmap](https://github.com/zekroTJA/timedmap) -具有过期的键/值对的地图.
* [treap](https://github.com/perdata/treap) -使用树堆的持久，快速排序的地图.
* [trie](https://github.com/derekparker/trie) -在Go中实现Trie.
* [ttlcache](https://github.com/diegobernardes/ttlcache) -内存中的LRU string-interface {}映射，其中包含golang的到期时间.
* [typ](https://github.com/gurukami/typ) -空类型，安全的原始类型转换和从复杂结构中获取值.
* [willf/bloom](https://github.com/willf/bloom) -实施Bloom过滤器的软件包.

## Database

*在Go中实现的数据库.

* [badger](https://github.com/dgraph-io/badger) -在Go中快速存储键值.
* [bbolt](https://github.com/etcd-io/bbolt) -Go的嵌入式键/值数据库.
* [bcache](https://github.com/iwanbk/bcache) -最终一致的分布式内存缓存Go库.
* [BigCache](https://github.com/allegro/bigcache) -高效的键/值缓存，用于千兆字节的数据.
* [Bitcask](https://github.com/prologic/bitcask) -Bitcask是使用纯Go编写的可嵌入，持久且快速的键值（KV）数据库，由于使用了bitcask磁盘布局（LSM + WAL），因此具有可预测的读/写性能，低延迟和高吞吐量.
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [cache](https://github.com/akyoto/cache) -内存中键：具有到期时间，0个依存关系，&lt;100 LoC，100％覆盖率的值存储.
* [cache2go](https://github.com/muesli/cache2go) -内存键：值缓存，支持基于超时的自动失效.
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) -具有集群支持和单个项目到期的BigCache.
* [cockroach](https://github.com/cockroachdb/cockroach) -可扩展，地理复制，事务性数据存储.
* [Coffer](https://github.com/claygod/coffer) -支持交易的简单ACID键值数据库.
* [couchcache](https://github.com/codingsince1985/couchcache) -由Couchbase服务器支持的RESTful缓存微服务.
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) -CovenantSQL是区块链上的SQL数据库.
* [Databunker](https://github.com/paranoidguy/databunker) -建立符合GDPR和CCPA的个人身份信息（PII）存储服务.
* [dgraph](https://github.com/dgraph-io/dgraph) -可扩展，分布式，低延迟，高吞吐量图形数据库.
* [diskv](https://github.com/peterbourgon/diskv) -本地磁盘支持的键值存储.
* [eliasdb](https://github.com/krotik/eliasdb) -具有REST API，短语搜索和类似SQL的查询语言的无依赖关系的事务图数据库.
* [fastcache](https://github.com/VictoriaMetrics/fastcache)  -大量条目的快速线程安全内存缓存.  最大限度地减少GC开销.
* [GCache](https://github.com/bluele/gcache) -缓存库，支持过期的缓存，LFU，LRU和ARC.
* [go-cache](https://github.com/pmylund/go-cache) -用于Go的内存中键：值存储/缓存（类似于Memcached）库，适用于单机应用程序.
* [goleveldb](https://github.com/syndtr/goleveldb) -实施 [LevelDB](https://github.com/google/leveldb) Go中的键/值数据库.
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) -Gorocksdb是一个包装 [RocksDB](https://rocksdb.org) 用Go编写.
* [gostore](https://github.com/twharmon/gostore) -Gostore是用Go语言编写的一种简单，持久的嵌入式键值存储引擎.
* [groupcache](https://github.com/golang/groupcache) -Groupcache是​​一个缓存和缓存填充库，在许多情况下可以替代memcached.
* [influxdb](https://github.com/influxdb/influxdb) -可扩展的数据存储，用于度量标准，事件和实时分析.
* [Kivik](https://github.com/go-kivik/kivik) -Kivik为CouchDB，PouchDB和类似数据库提供了通用的Go和GopherJS客户端库.
* [ledisdb](https://github.com/siddontang/ledisdb) -Ledisdb是像基于LevelDB的Redis一样的高性能NoSQL.
* [levigo](https://github.com/jmhodges/levigo) -Levigo是LevelDB的Go包装器.
* [moss](https://github.com/couchbase/moss) -Moss是用100％Go编写的简单LSM键值存储引擎.
* [nutsdb](https://github.com/xujiajun/nutsdb)  -Nutsdb是用纯Go编写的简单，快速，可嵌入的持久键/值存储.  它支持完全可序列化的事务和许多数据结构，例如列表，集合，排序集合.
* [piladb](https://github.com/fern4lvarez/piladb) -基于堆栈数据结构的轻量级RESTful数据库引擎.
* [prometheus](https://github.com/prometheus/prometheus) -监控系统和时间序列数据库.
* [pudge](https://github.com/recoilme/pudge) -使用Go的标准库编写的快速简单的键/值存储.
* [rqlite](https://github.com/rqlite/rqlite) -建立在SQLite上的轻型，分布式，关系数据库.
* [Scribble](https://github.com/nanobox-io/golang-scribble) -小型平面文件JSON存储.
* [slowpoke](https://github.com/recoilme/slowpoke) -具有持久性的键值存储.
* [tempdb](https://github.com/rafaeljesus/tempdb) -临时项目的键值存储.
* [tidb](https://github.com/pingcap/tidb)  -TiDB是分布式SQL数据库.  受到Google F1设计的启发.
* [tiedot](https://github.com/HouzuoGuo/tiedot) -由Golang提供支持的NoSQL数据库.
* [tracedb](https://github.com/unit-io/tracedb)  -用于物联网，实时消息传递应用程序的快速时间序列数据库.  使用github.com/unit-io/trace应用程序通过tcp或websocket通过pubsub访问tracedb.
* [Vasto](https://github.com/chrislusf/vasto)  -分布式高性能键值存储.  在磁盘上.  最终一致.  哈.  能够增长或收缩而不会中断服务.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)  -快速，资源有效且可扩展的开源时间序列数据库.  可用作Prometheus的长期远程存储.  支持PromQL.

*数据库架构迁移.*

* [avro](https://github.com/khezen/avro)  -发现SQL模式并将其转换为AVRO模式.  将SQL记录查询为AVRO字节.
* [darwin](https://github.com/GuiaBolso/darwin) -Go的数据库架构演化库.
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) -用于Golang出色的内置数据库/ sql库的Django样式固定装置.
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) -Go软件包，可帮助编写go-pg / pg的迁移文件.
* [gondolier](https://github.com/emvi/gondolier) -使用结构修饰符的数据库迁移库.
* [goose](https://github.com/steinbacher/goose)  -数据库迁移工具.  您可以通过创建增量SQL或Go脚本来管理数据库的演变.
* [gormigrate](https://github.com/go-gormigrate/gormigrate) -Gorm ORM的数据库架构迁移帮助器.
* [migrate](https://github.com/golang-migrate/migrate)  -数据库迁移.  CLI和Golang库.
* [migrator](https://github.com/lopezator/migrator) -死掉的简单的Go数据库迁移库.
* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.
* [schema](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
* [skeema](https://github.com/skeema/skeema) -用于MySQL的纯SQL模式管理系统，支持分片和外部在线模式更改工具.
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) -MySQL，PostgreSQL和SQLite的数据库迁移，创建，ORM等.
* [sql-migrate](https://github.com/rubenv/sql-migrate)  -数据库迁移工具.  允许使用go-bindata将迁移嵌入到应用程序中.

*数据库工具*

* [bucket](https://github.com/PumpkinSeed/bucket) -针对Couchbase的优化数据结构框架，专门用于一个存储桶.
* [chproxy](https://github.com/Vertamedia/chproxy) -ClickHouse数据库的HTTP代理.
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) -收集小信息并将大请求发送到ClickHouse服务器.
* [datagen](https://github.com/codingconcepts/datagen) -快速的数据生成器，支持多表并支持多行DML.
* [dbbench](https://github.com/sj14/dbbench) -数据库基准测试工具，支持多个数据库和脚本.
* [go-mysql](https://github.com/siddontang/go-mysql) -使用工具集来处理MySQL协议和复制.
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) -将您的MySQL数据自动同步到Elasticsearch.
* [kingshard](https://github.com/flike/kingshard) -kingshard是由Golang支持的MySQL的高性能代理.
* [myreplication](https://github.com/2tvenom/myreplication)  -MySql二进制日志复制侦听器.  支持基于语句和行的复制.
* [octillery](https://github.com/knocknote/octillery) -用于分片数据库的Go软件包（支持每个ORM或原始SQL）.
* [orchestrator](https://github.com/github/orchestrator) -MySQL复制拓扑管理器和可视化器.
* [pgweb](https://github.com/sosedoff/pgweb) -基于Web的PostgreSQL数据库浏览器.
* [prep](https://github.com/hexdigest/prep) -使用准备好的SQL语句而不更改代码.
* [pREST](https://github.com/nuveo/prest) -从任何PostgreSQL数据库提供RESTful API.
* [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
* [vitess](https://github.com/youtube/vitess) -vitess提供了有助于大规模数据库服务扩展MySQL数据库的服务器和工具.

* SQL查询生成器，用于构建和使用SQL的库.*

* [buildsqlx](https://github.com/arthurkushman/buildsqlx) -使用PostgreSQL的数据库查询构建器库.
* [dbq](https://github.com/rocketlaunchr/dbq) -Go的零样本数据库操作.
* [Dotsql](https://github.com/gchaincl/dotsql) -Go库可帮助您将sql文件保存在一个位置，并轻松使用它们.
* [gendry](https://github.com/didi/gendry) -非侵入式SQL构建器和强大的数据绑定器.
* [godbal](https://github.com/xujiajun/godbal)  -数据库抽象层（dbal）.  支持SQL Builder，轻松获得结果.
* [goqu](https://github.com/doug-martin/goqu) -惯用的SQL构建器和查询库.
* [gosql](https://github.com/twharmon/gosql) -具有更好的null值支持的SQL查询构建器.
* [igor](https://github.com/galeone/igor) -PostgreSQL的抽象层，支持高级功能并使用类似于gorm的语法.
* [jet](https://github.com/go-jet/jet) -在Go中编写类型安全的SQL查询的框架，能够轻松将数据库查询结果转换为所需的任意对象结构.
* [mpath](https://github.com/spacetab-io/mpath-go) -用于SQL记录的MPTT（修改的预购树遍历）包-物化路径的实现.
* [ormlite](https://github.com/pupizoid/ormlite) -轻量级软件包，包含一些类似于ORM的功能和sqlite数据库的帮助程序.
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) -强大的数据检索方法以及与数据库无关的查询构建功能.
* [qry](https://github.com/HnH/qry) -使用原始SQL查询从文件生成常量的工具.
* [sqlf](https://github.com/leporo/sqlf) -快速的SQL查询生成器.
* [sqrl](https://github.com/elgris/sqrl) -SQL查询生成器，Squirrel的分支，具有改进的性能.
* [Squalus](https://gitlab.com/qosenergy/squalus) -Go SQL包上的薄层，使执行查询变得更加容易.
* [Squirrel](https://github.com/Masterminds/squirrel) -Go库可帮助您构建SQL查询.
* [xo](https://github.com/knq/xo) -根据现有的架构定义或支持PostgreSQL，MySQL，SQLite，Oracle和Microsoft SQL Server的自定义查询为数据库生成惯用的Go代码.

## Database Drivers

*用于连接和操作数据库的库.

*关系数据库
    * [avatica](https://github.com/apache/calcite-avatica-go) -用于数据库/ sql的Apache Avatica / Phoenix SQL驱动程序.
    * [bgc](https://github.com/viant/bgc) -BigQuery的数据存储连接.
    * [firebirdsql](https://github.com/nakagami/firebirdsql) -用于Go的Firebird RDBMS SQL驱动程序.
    * [go-adodb](https://github.com/mattn/go-adodb) -使用数据库/ sql的go的Microsoft ActiveX Object DataBase驱动程序.
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) -用于Go的Microsoft MSSQL驱动程序.
    * [go-oci8](https://github.com/mattn/go-oci8) -使用数据库/ sql的go的Oracle驱动程序.
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) -Go的MySQL驱动程序.
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) -使用数据库/ sql的go SQLite3驱动程序.
    * [gofreetds](https://github.com/minus5/gofreetds)  -Microsoft MSSQL驱动程序.  去包装 [FreeTDS](http://www.freetds.org).
    * [goracle](https://github.com/go-goracle/goracle) -使用ODPI-C驱动程序的Go的Oracle驱动程序.
    * [pgx](https://github.com/jackc/pgx) -PostgreSQL驱动程序支持的功能超出了数据库/ sql所公开的功能.
    * [pq](https://github.com/lib/pq) -用于数据库/ sql的Pure Go Postgres驱动程序.

* NoSQL数据库
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) -Go语言的Aerospike客户.
    * [arangolite](https://github.com/solher/arangolite) -用于ArangoDB的轻型golang驱动程序.
    * [asc](https://github.com/viant/asc) -用于Aerospike的数据存储连接.
    * [dynago](https://github.com/underarmour/dynago) -Dynago是DynamoDB的最少惊喜客户端的原则.
    * [forestdb](https://github.com/couchbase/goforestdb) -为ForestDB进行绑定.
    * [go-couchbase](https://github.com/couchbase/go-couchbase) -Go中的Couchbase客户端.
    * [go-pilosa](https://github.com/pilosa/go-pilosa) -前往Pilosa的客户端库.
    * [go-rejson](https://github.com/nitishm/go-rejson)  -使用Redigo golang客户端的Redislabs ReJSON模块的Golang客户端.  轻松将结构作为JSON对象存储和操作在Redis中.
    * [gocb](https://github.com/couchbase/gocb) -官方Couchbase Go SDK.
    * [gocql](http://gocql.github.io) -Apache Cassandra的Go语言驱动程序.
    * [godis](https://github.com/piaohao/godis) -受jedis启发，golang的redis客户端工具.
    * [godscache](https://github.com/defcronyke/godscache) -Google Cloud Platform Go数据存储区包装的包装，该包装使用memcached添加了缓存.
    * [gomemcache](https://github.com/bradfitz/gomemcache/) -用于Go编程语言的memcache客户端库.
    * [gorethink](https://github.com/dancannon/gorethink) -RethinkDB的Go语言驱动程序.
    * [goriak](https://github.com/zegl/goriak) -Riak KV的语言驱动程序.
    * [mgm](https://github.com/kamva/mgm) -Go的基于MongoDB模型的ODM（基于官方的MongoDB驱动程序）.
    * [mgo](https://github.com/globalsign/mgo) -（无需维护）用于Go语言的MongoDB驱动程序，该驱动程序遵循标准的Go习惯用法，在非常简单的API下实现了功能丰富且经过测试的精选功能.
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) -Go语言的官方MongoDB驱动程序.
    * [neo4j](https://github.com/cihangir/neo4j) -用于Golang的Neo4j Rest API绑定.
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) -Golang中的Neo4j REST客户端.
    * [neoism](https://github.com/jmcvetta/neoism) -Golang的Neo4j客户端.
    * [redeo](https://github.com/bsm/redeo) -与Redis协议兼容的TCP服务器/服务.
    * [redigo](https://github.com/gomodule/redigo) -Redigo是Redis数据库的Go客户端.
    * [redis](https://github.com/go-redis/redis) -Golang的Redis客户端.
    * [xredis](https://github.com/shomali11/xredis) -类型安全，可自定义，干净且易于使用的Redis客户端.

*搜索和分析数据库.
    * [bleve](https://github.com/blevesearch/bleve) -可以使用的现代文本索引库.
    * [elastic](https://github.com/olivere/elastic) -Go的Elasticsearch客户端.
    * [elasticsql](https://github.com/cch123/elasticsql) -在Go中将sql转换为elasticsearch dsl.
    * [elastigo](https://github.com/mattbaird/elastigo) -Elasticsearch客户端库.
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) -Go的官方Elasticsearch客户.
    * [goes](https://github.com/OwnLocal/goes) -与Elasticsearch交互的库.
    * [riot](https://github.com/go-ego/riot) -开源，分布式，简单高效的搜索引擎.
    * [skizze](https://github.com/seiflotfy/skizze) -概率数据结构服务和存储.

*多个后端.
    * [cachego](https://github.com/fabiorphp/cachego) -用于多个驱动程序的Golang缓存组件.
    * [cayley](https://github.com/google/cayley) -支持多个后端的图形数据库.
    * [dsc](https://github.com/viant/dsc) -SQL，NoSQL，结构化文件的数据存储连接.
    * [gokv](https://github.com/philippgille/gokv) -Go的简单键值存储抽象和实现（Redis，Consul，etcd，bbolt，BadgerDB，LevelDB，Memcached，DynamoDB，S3，PostgreSQL，MongoDB，CockroachDB等）.

## Date and Time

*用于处理日期和时间的库.*

* [carbon](https://github.com/uniplaces/carbon) -从PHP Carbon库移植的具有许多util方法的简单时间扩展.
* [cronrange](https://github.com/1set/cronrange) -解析Cron风格的时间范围表达式，检查给定时间是否在任何范围内.
* [date](https://github.com/rickb777/date) -扩展时间，用于处理日期，日期范围，时间跨度，期间和一天中的时间.
* [dateparse](https://github.com/araddon/dateparse) -在不知道格式的情况下解析日期.
* [durafmt](https://github.com/hako/durafmt) -Go的持续时间格式库.
* [feiertage](https://github.com/wlbr/feiertage)  -一组计算德国公共假期的功能，包括  德国（Bundesländer）州的专业.  复活节，五旬节，感恩节等
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) -Go（golang）中的波斯（Solar Hijri）日历的实现.
* [go-str2duration](https://github.com/xhit/go-str2duration)  -将字符串转换为持续时间.  支持时间.持续时间返回了字符串等.
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) -计算给定位置的日出和日落时间.
* [go-week](https://github.com/stoewer/go-week) -与ISO8601星期日期兼容的有效软件包.
* [iso8601](https://github.com/relvacode/iso8601) -无需使用正则表达式即可有效解析ISO8601日期时间.
* [kair](https://github.com/GuilhermeCaruso/kair) -日期和时间-Golang格式库.
* [now](https://github.com/jinzhu/now) -现在是用于golang的时间工具包.
* [NullTime](https://github.com/kirillDanshin/nulltime) -时间为空.
* [strftime](https://github.com/awoodbeck/strftime) -与C99兼容的strftime格式化程序.
* [timespan](https://github.com/SaidinWoT/timespan) -用于与时间间隔进行交互，定义为开始时间和持续时间.
* [timeutil](https://github.com/leekchan/timeutil) -有用的扩展（Timedelta，Strftime等），用于golang的时间包.
* [tuesday](https://github.com/osteele/tuesday) -兼容Ruby的Strftime函数.

## Distributed Systems

*有助于构建分布式系统的软件包.

* [celeriac](https://github.com/svcavallar/celeriac.v1) -用于在Go中添加对交互和监视Celery工作人员，任务和事件的支持的库.
* [consistent](https://github.com/buraksezer/consistent) -具有有限负载的一致哈希.
* [dht](https://github.com/anacrolix/dht) -BitTorrent Kademlia DHT实施.
* [digota](https://github.com/digota/digota) -grpc电子商务微服务.
* [dot](https://github.com/dotchain/dot/) -使用操作转换/ OT进行分布式同步.
* [doublejump](https://github.com/edwingeng/doublejump) -改良版Google的跳转一致性哈希.
* [dragonboat](https://github.com/lni/dragonboat) -Go中功能齐全的高性能多组Raft库.
* [drmaa](https://github.com/dgruber/drmaa) -基于DRMAA标准的集群调度程序的作业提交库.
* [dynamolock](https://cirello.io/dynamolock) -DynamoDB支持的分布式锁定实现.
* [dynatomic](https://github.com/tylfin/dynatomic) -使用DynamoDB作为原子计数器的库.
* [emitter-io](https://github.com/emitter-io/emitter) -使用MQTT，Websockets和love构建的高性能，分布式，安全和低延迟的发布-订阅平台.
* [flowgraph](https://github.com/vectaport/flowgraph) -基于流的编程包.
* [gleam](https://github.com/chrislusf/gleam) -用Go和Luajit编写的快速，可扩展的分布式地图/缩减系统，结合了Go的高并发性和Luajit的高性能，可独立运行或分布式.
* [glow](https://github.com/chrislusf/glow) -易于使用的可扩展的分布式大数据处理，Map-Reduce，DAG执行，全部在纯Go中进行.
* [go-health](https://github.com/InVisionApp/go-health) -用于在服务中启用异步依赖项运行状况检查的库.
* [go-jump](https://github.com/dgryski/go-jump) -Google的“跳转”一致性哈希函数端口.
* [go-kit](https://github.com/go-kit/kit) -支持服务发现，负载平衡，可插拔传输，请求跟踪等的微服务工具包
* [go-pdu](https://github.com/pdupub/go-pdu) -分散的基于身份的社交网络.
* [go-sundheit](https://github.com/AppsFlyer/go-sundheit) -建立用于为定义golang服务的异步服务运行状况检查提供支持的库.
* [gorpc](https://github.com/valyala/gorpc) -简单，快速和可扩展的RPC库，可实现高负载.
* [grpc-go](https://github.com/grpc/grpc-go)  -gRPC的Go语言实现.  基于HTTP / 2的RPC.
* [hprose](https://github.com/hprose/hprose-golang) -非常新颖的RPC库，现在支持25种以上的语言.
* [jsonrpc](https://github.com/osamingo/jsonrpc) -jsonrpc软件包可帮助实现JSON-RPC 2.0.
* [jsonrpc](https://github.com/ybbus/jsonrpc) -JSON-RPC 2.0 HTTP客户端实现.
* [KrakenD](https://github.com/devopsfaith/krakend) -具有中间件的超高性能API网关框架.
* [liftbridge](https://github.com/liftbridge-io/liftbridge) -用于NATS的轻量级，容错消息流.
* [micro](https://github.com/micro/micro) -可插拔的微服务工具包和分布式系统平台.
* [NATS](https://github.com/nats-io/gnatsd) -用于微服务，物联网和云原生系统的轻量级高性能消息传递系统.
* [outboxer](https://github.com/italolelis/outboxer) -发件箱是执行发件箱模式的go库.
* [pglock](https://cirello.io/pglock) -PostgreSQL支持的分布式锁定实现.
* [raft](https://github.com/hashicorp/raft) -由HashiCorp执行的Raft共识协议的Golang实现.
* [raft](https://github.com/coreos/etcd/tree/master/raft) -由CoreOS执行Raft共识协议.
* [rain](https://github.com/cenkalti/rain) -BitTorrent客户端和库.
* [redis-lock](https://github.com/bsm/redislock) -使用Redis的简化的分布式锁定实现.
* [resgate](https://resgate.io/) -用于构建REST，实时和RPC API的实时API网关，其中所有客户端都可以无缝同步.
* [ringpop-go](https://github.com/uber/ringpop-go) -Go应用程序的可扩展，容错应用程序层分片.
* [rpcx](https://github.com/smallnest/rpcx) -分布式可插拔RPC服务框架，例如阿里巴巴Dubbo.
* [sleuth](https://github.com/ursiform/sleuth) -用于在HTTP服务之间进行无主机p2p自动发现和RPC的库（使用 [ZeroMQ](https://github.com/zeromq/libzmq)).
* [tendermint](https://github.com/tendermint/tendermint) -高性能中间件，可使用Tendermint共识和区块链协议将以任何编程语言编写的状态机转换为拜占庭容错复制状态机.
* [torrent](https://github.com/anacrolix/torrent) -BitTorrent客户端软件包.

## Dynamic DNS

*用于更新动态DNS记录的工具.*

* [DDNS](https://github.com/skibish/ddns) -以Digital Ocean Networking DNS作为后端的个人DDNS客户端.
* [dyndns](https://gitlab.com/alcastle/dyndns) -后台执行流程可定期自动检查您的IP地址，并在您更改地址时更新（一个或多个）Google域的动态DNS记录.
* [GoDNS](https://github.com/timothyye/godns) -动态的DNS客户端工具，支持Go编写的DNSPod和HE.net.

## Email

*实现电子邮件创建和发送的库和工具.*

* [chasquid](https://blitiri.com.ar/p/chasquid) -用Go编写的SMTP服务器.
* [douceur](https://github.com/aymerick/douceur) -用于HTML电子邮件的CSS内衬.
* [email](https://github.com/jordan-wright/email) -强大而灵活的Go Go电子邮件库.
* [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
* [go-imap](https://github.com/emersion/go-imap) -用于客户端和服务器的IMAP库.
* [go-message](https://github.com/emersion/go-message) -Internet邮件格式和邮件的流媒体库.
* [go-premailer](https://github.com/vanng822/go-premailer) -Go中HTML邮件的内联样式.
* [go-simple-mail](https://github.com/xhit/go-simple-mail) -使用SMTP保持活动状态发送电子邮件和两个超时的非常简单的程序包：连接和发送.
* [Hectane](https://github.com/hectane/hectane) -提供HTTP API的轻型SMTP客户端.
* [hermes](https://github.com/matcornic/hermes) -Golang软件包，可生成干净的响应式HTML电子邮件.
* [mailchain](https://github.com/mailchain/mailchain) -将加密的电子邮件发送到用Go编写的区块链地址.
* [mailgun-go](https://github.com/mailgun/mailgun-go) -Go库，用于使用Mailgun API发送邮件.
* [MailHog](https://github.com/mailhog/MailHog) -通过Web和API界面进行电子邮件和SMTP测试.
* [SendGrid](https://github.com/sendgrid/sendgrid-go) -SendGrid的Go库，用于发送电子邮件.
* [smtp](https://github.com/mailhog/smtp) -SMTP服务器协议状态机.

## Embeddable Scripting Languages

*在您的go代码中嵌入其他语言.*

* [anko](https://github.com/mattn/anko) -用Go语言编写的可编写脚本的解释器.
* [binder](https://github.com/alexeyco/binder) -根据以下内容转到Lua绑定库 [gopher-lua](https://github.com/yuin/gopher-lua).
* [cel-go](https://github.com/google/cel-go) -具有渐进式输入功能的快速，便携式，非图灵完整表达评估.
* [expr](https://github.com/antonmedv/expr) -Go语言表达评估引擎：快速，非图灵完整，动态键入，静态键入.
* [gentee](https://github.com/gentee/gentee) -嵌入式脚本编程语言.
* [gisp](https://github.com/jcla1/gisp) -Go中的简单LISP.
* [go-duktape](https://github.com/olebedev/go-duktape) -Go的Duktape JavaScript引擎绑定.
* [go-lua](https://github.com/Shopify/go-lua) -将Lua 5.2 VM移植到纯Go.
* [go-php](https://github.com/deuill/go-php) -用于Go的PHP绑定.
* [go-python](https://github.com/sbinet/go-python) -天真的去绑定到CPython C-API.
* [golua](https://github.com/aarzilli/golua) -为Lua C API进行绑定.
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* [gval](https://github.com/PaesslerAG/gval) -用Go语言编写的高度可定制的表达语言.
* [ngaro](https://github.com/db47h/ngaro) -可嵌入的Ngaro VM实现可在Retro中启用脚本.
* [otto](https://github.com/robertkrimen/otto) -用Go编写的JavaScript解释器.
* [purl](https://github.com/ian-kent/purl) -嵌入在Go中的Perl 5.18.2.
* [tengo](https://github.com/d5/tengo) -用于Go的字节码编译脚本语言.

## Error Handling

*用于处理错误的库.*

* [emperror](https://github.com/emperror/emperror) -Go库和应用程序的错误处理工具和最佳实践.
* [eris](https://github.com/rotisserie/eris)  -在Go中处理，跟踪和记录错误的更好方法.  与标准错误库和github.com/pkg/errors兼容.
* [errlog](https://github.com/snwfdhmp/errlog)  -可破解的软件包，用于确定错误的负责任的源代码（以及其他一些快速调试功能）.  可就地插入任何记录器.
* [errors](https://github.com/emperror/errors)  -直接替换标准库错误包和github.com/pkg/errors.  提供各种错误处理原语.
* [errors](https://github.com/pkg/errors) -提供简单错误处理原语的软件包.
* [errors](https://github.com/neuronlabs/errors) -使用分类原语进行简单的golang错误处理.
* [errors](https://github.com/PumpkinSeed/errors) - The most simple error wrapper with awesome performance and minimal memory overhead.
* [errorx](https://github.com/joomcode/errorx) -具有堆栈跟踪，错误组成等的功能丰富的错误包.
* [Falcon](https://github.com/SonicRoshan/falcon) -一个简单但功能强大的错误处理包.
* [go-multierror](https://github.com/hashicorp/go-multierror) -Go（golang）软件包，用于将错误列表表示为单个错误.
* [tracerr](https://github.com/ztrue/tracerr) -堆栈跟踪和源代码片段出现Golang错误.
* [werr](https://github.com/txgruppi/werr) -错误包装器为Go中的错误类型创建了一个包装器，该包装器捕获了被调用位置的文件，行和堆栈.

## Files

*用于处理文件和文件系统的库.

* [afero](https://github.com/spf13/afero) -Go的FileSystem抽象系统.
* [afs](https://github.com/viant/afs) -Go的抽象文件存储（mem，scp，zip，tar，云：s3，gs）.
* [bigfile](https://github.com/bigfile/bigfile) -文件传输系统，支持使用http api，rpc调用和ftp客户端管理文件.
* [checksum](https://github.com/codingsince1985/checksum) -计算大型文件的消息摘要，例如MD5和SHA256.
* [copy](https://github.com/otiai10/copy) -递归复制目录.
* [flop](https://github.com/homedepot/flop) -文件操作库，旨在与功能镜像相同 [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
* [go-csv-tag](https://github.com/artonge/go-csv-tag) -使用标签加载csv文件.
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) -复制人类文件.
* [go-exiftool](https://github.com/barasher/go-exiftool) -对ExifTool进行绑定，该库是著名的库，用于从文件（图片，PDF，Office等）中提取尽可能多的元数据（EXIF，IPTC等）.
* [go-gtfs](https://github.com/artonge/go-gtfs) -在go中加载gtfs文件.
* [gut/yos](https://github.com/1set/gut) -简单可靠的文件操作包，例如文件，目录和符号链接上的复制/移动/差异/列表.
* [notify](https://github.com/rjeczalik/notify) -具有简单API的文件系统事件通知库，类似于os / signal.
* [opc](https://github.com/qmuntal/opc) -加载Go的开放式包装约定（OPC）文件.
* [parquet](https://github.com/parsyl/parquet) - 读和写 [parquet](https://parquet.apache.org) 文件.
* [pdfcpu](https://github.com/pdfcpu/pdfcpu) -PDF处理器.
* [skywalker](https://github.com/dixonwille/skywalker) -允许一个人同时轻松地通过文件系统的软件包.
* [stl](https://gitlab.com/russoj88/stl)  -读取和写入STL（立体光刻）文件的模块.  并发读取算法.
* [tarfs](https://github.com/posener/tarfs) -实施 [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) 用于tar文件.
* [vfs](https://github.com/C2FO/vfs) -跨多种文件系统类型（例如os，S3和GCS）的Go的一组可插拔，可扩展且自以为是的文件系统功能.

## Financial

*会计和财务软件包.*

* [accounting](https://github.com/leekchan/accounting) -golang的货币和货币格式.
* [currency](https://github.com/bnkamalesh/currency) -高性能和准确的货币计算软件包.
* [decimal](https://github.com/shopspring/decimal) -任意精度定点十进制数字.
* [go-finance](https://github.com/FlashBoys/go-finance) -Go中的综合金融市场数据.
* [go-finance](https://github.com/alpeb/go-finance) -货币时间价值（年金），现金流量，利率转换，债券和折旧计算的财务功能库.
* [go-finance](https://github.com/pieterclaerhout/go-finance) -获取汇率，通过VIES检查增值税号并检查IBAN银行帐号的模块.
* [go-finnhub](https://github.com/m1/go-finnhub)  -来自finnhub.io的股票，外汇和加密数据客户.  访问来自60多个证券交易所，10个外汇经纪人和15多个加密交易所的实时金融市场数据.
* [go-money](https://github.com/rhymond/go-money) -实施福勒的钱模式.
* [ofxgo](https://github.com/aclindsa/ofxgo) -查询OFX服务器和/或解析响应（使用示例命令行客户端）.
* [orderbook](https://github.com/i25959341/orderbook) -Golang限价订单匹配引擎.
* [techan](https://github.com/sdcoffey/techan) -具有高级市场分析和交易策略的技术分析库.
* [transaction](https://github.com/claygod/transaction) -嵌入式事务帐户数据库，以多线程模式运行.
* [vat](https://github.com/dannyvankooten/vat) -增值税号验证和欧盟增值税率.

## Forms

*用于处理表单的库.*

* [bind](https://github.com/robfig/bind) -将表单数据绑定到任何Go值.
* [binding](https://github.com/mholt/binding) -从net / http请求绑定结构和JSON数据到结构.
* [conform](https://github.com/leebenson/conform)  -检查用户输入.  根据struct标签对数据进行整理，清理和清理.
* [form](https://github.com/go-playground/form)  -将url.Values解码为Go值，并将Go值编码为url.Values.  双阵列和全图支持.
* [formam](https://github.com/monoculum/formam) -将表单的值解码为结构.
* [forms](https://github.com/albrow/forms) -与框架无关的库，用于解析和验证支持多部分表单和文件的表单/ JSON数据.
* [gorilla/csrf](https://github.com/gorilla/csrf) -Go Web应用程序和服务的CSRF保护.
* [nosurf](https://github.com/justinas/nosurf) -Go的CSRF保护中间件.
* [queryparam](https://github.com/tomwright/queryparam) -将“ url.Values”解码为标准或自定义类型的可用结构值.

## Functional

*支持Go中功能编程的软件包.*

* [fpGo](https://github.com/TeaEntityLab/fpGo) -用于Golang的Monad功能编程功能.
* [fuego](https://github.com/seborama/fuego) -Go中的功能实验.
* [go-underscore](https://github.com/tobyhede/go-underscore) -有用的Go收集实用程序的有用收集.

## Game Development

*很棒的游戏开发库.*

* [Azul3D](https://github.com/azul3d/engine) -用Go编写的3D游戏引擎.
* [Ebiten](https://github.com/hajimehoshi/ebiten) -Go中已死的简单2D游戏库.
* [engo](https://github.com/EngoEngine/engo)  -Engo是用Go语言编写的开源2D游戏引擎.  它遵循实体组件系统范式.
* [g3n](https://github.com/g3n/engine) -进入3D游戏引擎.
* [go-astar](https://github.com/beefsack/go-astar) -执行A \ *路径查找算法.
* [go-sdl2](https://github.com/veandco/go-sdl2) -去绑定 [Simple DirectMedia Layer](https://www.libsdl.org/).
* [go3d](https://github.com/ungerik/go3d) -面向性能的Go 2D / 3D数学软件包.
* [gonet](https://github.com/xtaci/gonet) -使用golang实现的游戏服务器框架.
* [goworld](https://github.com/xiaonanln/goworld) -可扩展的游戏服务器引擎，具有空间实体框架和热插拔功能.
* [Leaf](https://github.com/name5566/leaf) -轻巧的游戏服务器框架.
* [nano](https://github.com/lonng/nano) -轻巧，便利，基于golang的高性能游戏服务器框架.
* [Oak](https://github.com/oakmound/oak) -Pure Go游戏引擎.
* [Pitaya](https://github.com/topfreegames/pitaya) -可扩展的游戏服务器框架，具有群集支持以及通过C SDK的iOS，Android，Unity等客户端库.
* [Pixel](https://github.com/faiface/pixel) -Go中的手工2D游戏库.
* [prototype](https://github.com/gonutz/prototype) -跨平台（Windows / Linux / Mac）库，用于使用最小的API创建桌面游戏.
* [raylib-go](https://github.com/gen2brain/raylib-go) -去绑定 [raylib](http://www.raylib.com/)，这是一个简单易用的库，用于学习视频游戏编程.
* [termloop](https://github.com/JoelOtter/termloop) -Go的基于终端的游戏引擎，建立在Termbox之上.

## Generation and Generics

*通过代码生成通过泛型等功能增强语言的工具.*

* [efaceconv](https://github.com/t0pep0/efaceconv) -代码生成工具，用于从接口{}到不分配的不可变类型的高性能转换.
* [gen](https://github.com/clipperhouse/gen) -用于类似“泛型”功能的代码生成工具.
* [generis](https://github.com/senselogic/GENERIS) -代码生成工具，提供泛型，自由格式的宏，条件编译和HTML模板.
* [go-enum](https://github.com/abice/go-enum) -从代码注释中为枚举生成代码.
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) -类似于.NET LINQ的Go查询方法.
* [go-xray](https://github.com/pieterclaerhout/go-xray) -使反射更容易使用的助手.
* [goderive](https://github.com/awalterschulze/goderive) -从输入类型派生功能.
* [gotype](https://github.com/wzshiming/gotype) -Golang源代码解析，用法类似于反射包.
* [GoWrap](https://github.com/hexdigest/gowrap) -使用简单的模板为Go界面生成装饰器.
* [interfaces](https://github.com/rjeczalik/interfaces) -用于生成界面定义的命令行工具.
* [jennifer](https://github.com/dave/jennifer) -生成没有模板的任意Go代码.
* [pkgreflect](https://github.com/ungerik/pkgreflect) -对包范围反射进行预处理.
* [typeregistry](https://github.com/xiaoxin01/typeregistry) -动态创建类型的库.

## Geographic

*地理工具和服务器*

* [geocache](https://github.com/melihmucuk/geocache) -适用于基于地理位置的应用程序的内存中缓存.
* [geoserver](https://github.com/hishamkaram/geoserver) -geoserver是Go软件包，用于通过GeoServer REST API操纵GeoServer实例.
* [gismanager](https://github.com/hishamkaram/gismanager) -将GIS数据（矢量数据）发布到PostGIS和Geoserver.
* [mbtileserver](https://github.com/consbio/mbtileserver) -一个简单的基于Go的服务器，用于存储以mbtiles格式存储的地图图块.
* [osm](https://github.com/paulmach/osm) -用于读取，写入和使用OpenStreetMap数据和API的库.
* [pbf](https://github.com/maguro/pbf) -OpenStreetMap PBF编码器/解码器.
* [S2 geojson](https://github.com/pantrif/s2-geojson) -将geojson转换为s2单元并在地图上演示一些S2几何特征.
* [S2 geometry](https://github.com/golang/geo) -Go中的S2几何库.
* [Tile38](https://github.com/tidwall/tile38) -具有空间索引和实时地理围栏的地理位置数据库.
* [WGS84](https://github.com/wroge/wgs84) -坐标转换和转换库（ETRS89，OSGB36，NAD83，RGF93，Web Mercator，UTM）.

## Go Compilers

*用于编译的工具转到其他语言.

* [c4go](https://github.com/Konstantin8105/c4go) -将C代码转换为Go代码.
* [f4go](https://github.com/Konstantin8105/f4go) -将FORTRAN 77代码转换为Go代码.
* [gopherjs](https://github.com/gopherjs/gopherjs) -从Go to JavaScript编译.
* [llgo](https://github.com/go-llvm/llgo) -基于LLVM的Go编译器.
* [tardisgo](https://github.com/tardisgo/tardisgo) -Golang到Haxe到CPP / CSharp / Java / JavaScript转译器.

## Goroutines

*用于管理和使用Goroutines的工具.*

* [ants](https://github.com/panjf2000/ants) -Go中的高性能和低成本goroutine池.
* [artifex](https://github.com/borderstech/artifex) -使用基于工作者的调度，为Golang提供简单的内存中作业队列.
* [async](https://github.com/studiosol/async) -一种异步执行功能的安全方法，以防万一.
* [breaker](https://github.com/kamilsk/breaker) -使执行流程可中断的灵活机制.
* [conexec](https://github.com/ITcathyh/conexec) -并发工具包，可帮助以高效，安全的方式并发执行函数，它支持指定整体超时以避免阻塞，并使用goroutine池提高效率.
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) -用于golang的CyclicBarrier.
* [go-floc](https://github.com/workanator/go-floc) -轻松编排goroutine.
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) -控制goroutine的执行顺序.
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) -使用带有简单API的轻量级库管理goroutine池.
* [go-trylock](https://github.com/subchen/go-trylock) -对Golang的读写锁具有TryLock支持.
* [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) -与`sync.WaitGroup`一样，具有错误处理和并发控制.
* [gohive](https://github.com/loveleshsharma/gohive) -Go的高性能和易于使用的Goroutine池.
* [gollback](https://github.com/vardius/gollback) -异步简单函数实用程序，用于管理闭包和回调的执行.
* [GoSlaves](https://github.com/themester/GoSlaves) -简单和异步Goroutine池库.
* [goworker](https://github.com/benmanns/goworker) -goworker是基于Go的后台工作者.
* [gowp](https://github.com/xxjwxc/gowp) -gowp是并发限制goroutine池.
* [gpool](https://github.com/Sherifabdlnaby/gpool) -管理可调整大小的上下文感知goroutine池以绑定并发.
* [grpool](https://github.com/ivpusic/grpool) -轻巧的Goroutine泳池.
* [hands](https://github.com/duanckham/hands) -用于控制多个goroutine的执行和返回策略的过程控制器.
* [Hunch](https://github.com/AaronJan/Hunch) -Hunch提供了诸如“全部”，“第一”，“重试”，“瀑布”等功能，使异步流控制更加直观.
* [kyoo](https://github.com/dirkaholic/kyoo) -提供无限的作业队列和并发工作池.
* [nursery](https://github.com/arunsworld/nursery) -Go中的结构化并发.
* [oversight](https://cirello.io/oversight) -监督是Erlang监督树的完整实现.
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) -并行运行功能.
* [pond](https://github.com/alitto/pond) -用Go编写的简约高性能Goroutine工作池.
* [pool](https://github.com/go-playground/pool) -有限的消费者goroutine或无限的goroutine池，可更轻松地处理和取消goroutine.
* [queue](https://github.com/AnikHasibul/queue)  -为您提供“ sync.WaitGroup”，例如队列组可访问性.  帮助您限制和限制goroutine，等待所有goroutine结束等等.
* [routine](https://github.com/x-mod/routine) -具有上下文和支持的例行控制：Main，Go，Pool和一些有用的Executors.
* [semaphore](https://github.com/kamilsk/semaphore) -基于通道和上下文的带有锁定/解锁操作超时的信号量模式实现.
* [semaphore](https://github.com/marusama/semaphore) -基于CAS的快速可调整大小的信号量实现（比基于通道的信号量实现更快）.
* [stl](https://github.com/ssgreg/stl) -基于软件交易内存（STM）并发控制机制的软件交易锁.
* [threadpool](https://github.com/shettyh/threadpool) -线程线程实现.
* [tunny](https://github.com/Jeffail/tunny) -Golang的Goroutine池.
* [worker-pool](https://github.com/vardius/worker-pool) -goworker是Go简单的异步工作程序池.
* [workerpool](https://github.com/gammazero/workerpool) -Goroutine池限制了任务执行的并发性，而不是排队的任务数.

## GUI

*用于构建GUI应用程序的库.*

*Toolkits*

* [app](https://github.com/murlokswarm/app)  -打包以使用GO，HTML和CSS创建应用程序.  支持：MacOS，Windows正在开发中.
* [fyne](https://github.com/fyne-io/fyne)  -基于Material Design为Go设计的跨平台本机GUI.  支持：Linux，macOS，Windows，BSD，iOS和Android.
* [go-astilectron](https://github.com/asticode/go-astilectron) -使用GO和HTML / JS / CSS（由Electron支持）构建跨平台的GUI应用.
* [go-gtk](http://mattn.github.io/go-gtk/) -绑定GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter)  -用于Sciter的绑定：用于现代桌面UI开发的可嵌入HTML / CSS / script引擎.  跨平台.
* [gotk3](https://github.com/gotk3/gotk3) -绑定GTK3.
* [gowd](https://github.com/dtylman/gowd)  -使用GO，HTML，CSS和NW.js进行快速，简单的桌面UI开发.  跨平台.
* [qt](https://github.com/therecipe/qt) -Go的Qt绑定（支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi）.
* [ui](https://github.com/andlabs/ui)  -用于Go的平台本地GUI库.  跨平台.
* [Wails](https://wails.app) -使用内置OS HTML渲染器的HTML UI的Mac，Windows，Linux桌面应用程序.
* [walk](https://github.com/lxn/walk) -Windows应用程序库工具包.
* [webview](https://github.com/zserge/webview) -具有简单双向JavaScript绑定的跨平台Webview窗口（Windows / macOS / Linux）.

*Interaction*

* [go-appindicator](https://github.com/dawidd6/go-appindicator) -转到libappindicator3 C库的绑定.
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) -Go的OSX桌面通知库.
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) -OSX库，用于通知您计算机上的任何（可插入）活动.
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) -使用golang的OSX睡眠/唤醒通知.
* [robotgo](https://github.com/go-vgo/robotgo)  -进行本机跨平台GUI系统自动化.  控制鼠标，键盘等.
* [systray](https://github.com/getlantern/systray) -跨平台转到库，以在通知区域中放置图标和菜单.
* [trayhost](https://github.com/shurcooL/trayhost) -跨平台的Go库，用于在主机操作系统的任务栏中放置一个图标.


## Hardware

*用于与硬件交互的库，工具和教程.*

See [go-hardware](https://github.com/rakyll/go-hardware) 以获得完整列表.

## Images

*用于处理图像的库.*

* [bild](https://github.com/anthonynsimon/bild) -在纯Go语言中收集图像处理算法.
* [bimg](https://github.com/h2non/bimg) -小型包装，可使用libvips快速有效地进行图像处理.
* [cameron](https://github.com/aofei/cameron) -Go的头像生成器.
* [canvas](https://github.com/tdewolff/canvas) -将矢量图形转换为PDF，SVG或光栅图像.
* [darkroom](https://github.com/gojek/darkroom) -具有可更改的存储后端的图像代理和注重速度和弹性的图像处理引擎.
* [geopattern](https://github.com/pravj/geopattern) -从字符串创建漂亮的生成图像图案.
* [gg](https://github.com/fogleman/gg) -纯Go中的2D渲染.
* [gift](https://github.com/disintegration/gift) -图像处理滤镜包.
* [gltf](https://github.com/qmuntal/gltf) -高效，强大的glTF 2.0读取器，写入器和验证器.
* [go-cairo](https://github.com/ungerik/go-cairo) -绑定到cairo图形库.
* [go-gd](https://github.com/bolknote/go-gd) -绑定GD库.
* [go-nude](https://github.com/koyachi/go-nude) -使用Go进行裸露检测.
* [go-opencv](https://github.com/lazywei/go-opencv) -为OpenCV进行绑定.
* [go-webcolors](https://github.com/jyotiska/go-webcolors) -webcolors库从Python到Go的移植.
* [gocv](https://github.com/hybridgroup/gocv) -使用OpenCV 3.3+进行计算机视觉的软件包.
* [goimagehash](https://github.com/corona10/goimagehash) -进入感知图像哈希包.
* [goimghdr](https://github.com/corona10/goimghdr) -imghdr模块确定Go文件中包含的图像类型.
* [govatar](https://github.com/o1egl/govatar) -用于生成有趣头像的库和CMD工具.
* [image2ascii](https://github.com/qeesung/image2ascii) -将图像转换为ASCII.
* [imagick](https://github.com/gographics/imagick) -绑定到ImageMagick的MagickWand C API.
* [imaginary](https://github.com/h2non/imaginary) -快速简单的HTTP微服务，用于图像大小调整.
* [imaging](https://github.com/disintegration/imaging) -简单的Go图像处理包.
* [img](https://github.com/hawx/img) -选择图像处理工具.
* [ln](https://github.com/fogleman/ln) -Go中的3D线条艺术渲染.
* [mergi](https://github.com/noelyahan/mergi) -用于图像处理（合并，裁切，调整大小，水印，动画）的Tool＆Go库.
* [mort](https://github.com/aldor007/mort) -用Go编写的存储和图像处理服务器.
* [mpo](https://github.com/donatj/mpo) -用于MPO 3D照片的解码器和转换工具.
* [picfit](https://github.com/thoas/picfit) -用Go编写的图像大小调整服务器.
* [pt](https://github.com/fogleman/pt) -用Go编写的路径跟踪引擎.
* [resize](https://github.com/nfnt/resize) -使用常见的插值方法为Go调整图像大小.
* [rez](https://github.com/bamiaux/rez) -在纯Go和SIMD中调整图像大小.
* [smartcrop](https://github.com/muesli/smartcrop) -查找适合任意图像和尺寸的好作物.
* [steganography](https://github.com/auyer/steganography) -用于LSB隐写术的Pure Go库.
* [stegify](https://github.com/DimitarPetrov/stegify) -用于LSB隐写术的Go工具，能够隐藏图像中的任何文件.
* [svgo](https://github.com/ajstarks/svgo) -用于SVG生成的语言库.
* [tga](https://github.com/ftrvxmtrx/tga) -软件包tga是TARGA图像格式的解码器/编码器.

## IoT (Internet of Things)

*用于IoT编程设备的库.*

* [connectordb](https://github.com/connectordb/connectordb) -量化自我和物联网的开源平台.
* [devices](https://github.com/goiot/devices) -物联网设备库套件，针对x / exp / io进行实验.
* [eywa](https://github.com/xcodersun/eywa) -Project Eywa本质上是一个连接管理器，可跟踪连接的设备.
* [flogo](https://github.com/tibcosoftware/flogo) -Project Flogo是一个用于IoT Edge应用和集成的开源框架.
* [gatt](https://github.com/paypal/gatt) -Gatt是用于构建蓝牙低功耗外设的Go软件包.
* [gobot](https://github.com/hybridgroup/gobot/) -Gobot是机器人技术，物理计算和物联网的框架.
* [huego](https://github.com/amimof/huego) -适用于Go的广泛的Philips Hue客户端库.
* [iot](https://github.com/vaelen/iot/) -物联网是用于实现Google IoT Core设备的简单框架.
* [mainflux](https://github.com/Mainflux/mainflux) -工业物联网消息和设备管理服务器.
* [periph](https://periph.io/) -外围设备I / O，可与低级板卡设备接口.
* [sensorbee](https://github.com/sensorbee/sensorbee) -物联网的轻量级流处理引擎.

## Job Scheduler

*用于计划作业的库.*

* [clockwerk](http://github.com/onatm/clockwerk) -使用简单，流利的语法打包程序以安排定期作业.
* [clockwork](https://github.com/whiteShtef/clockwork) -Go中简单直观的工作计划库.
* [go-cron](https://github.com/rk/go-cron)  -go的简单Cron库，可以在不同的时间间隔执行闭包或函数，从每秒一次到每年一次在特定日期和时间.  主要用于Web应用程序和长期运行的守护程序.
* [gron](https://github.com/roylee0704/gron) -使用简单的Go API定义基于时间的任务，Gron的调度程序将相应地运行它们.
* [JobRunner](https://github.com/bamzi/jobrunner) -智能，功能强大的Cron作业计划程序，内置作业队列和实时监控功能.
* [jobs](https://github.com/albrow/jobs) -持久灵活的后台作业库.
* [leprechaun](https://github.com/kilgaloon/leprechaun) -作业调度程序，支持webhook，cron和经典调度.
* [scheduler](https://github.com/carlescere/scheduler) -Cronjobs安排变得容易.

## JSON

*用于JSON的库.*

* [ajson](https://github.com/spyzhov/ajson) -带有JSONPath支持的用于golang的抽象JSON.
* [ej](https://github.com/lucassscaravelli/ej) -简洁地编写和读取来自不同来源的JSON.
* [gjo](https://github.com/skanehira/gjo) -用于创建JSON对象的小型实用程序.
* [GJSON](https://github.com/tidwall/gjson) -使用一行代码获取JSON值.
* [go-jsonerror](https://github.com/ddymko/go-jsonerror) -Go-JsonError可让我们轻松创建遵循JsonApi规范的json响应错误.
* [go-respond](https://github.com/nicklaw5/go-respond) -Go包，用于处理常见的HTTP JSON响应.
* [gojq](https://github.com/elgs/gojq) -Golang中的JSON查询.
* [gojson](https://github.com/ChimeraCoder/gojson) -根据示例JSON自动生成Go（golang）结构定义.
* [JayDiff](https://github.com/yazgazan/jaydiff) -用Go编写的JSON diff实用程序.
* [jettison](https://github.com/wI2L/jettison) -用于Go的高性能，无反射JSON编码器.
* [JSON-to-Go](https://mholt.github.io/json-to-go/) -将JSON转换为Go结构.
* [json2go](https://github.com/m-zajac/json2go)  -先进的JSON到Go结构转换.  提供可以解析多个JSON文档并创建适合所有JSON的结构的包.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) -根据JSON API错误参考进行绑定.
* [jsonf](https://github.com/miolini/jsonf) -用于突出显示格式和获取JSON的结构查询的控制台工具.
* [jsongo](https://github.com/ricardolonga/jsongo) -Fluent API，可以更轻松地创建Json对象.
* [jsonhal](https://github.com/RichardKnop/jsonhal) -简单的Go软件包，可将自定义结构编组为与HAL兼容的JSON响应.
* [kazaam](https://github.com/Qntfy/kazaam) -用于JSON文档任意转换的API.
* [mapslice-json](https://github.com/mickep76/mapslice-json) -前往MapSlice进行JSON中地图的有序编组/解组.
* [mp](https://github.com/sanbornm/mp)  -简单的CLI电子邮件解析器.  当前，它使用标准输入并输出JSON.

## Logging

*用于生成和使用日志文件的库.

* [distillog](https://github.com/amoghe/distillog) -提纯的日志记录级别（将其视为stdlib +日志级别）.
* [glg](https://github.com/kpango/glg) -glg是用于Go的简单快速的日志记录库.
* [glo](https://github.com/lajosbencz/glo) -具有相同严重性级别的PHP Monolog启发式日志记录工具.
* [glog](https://github.com/golang/glog) -Go的分级执行日志.
* [go-cronowriter](https://github.com/utahta/go-cronowriter) -简单的编写器，可根据当前日期和时间自动旋转日志文件，例如cronolog.
* [go-log](https://github.com/pieterclaerhout/go-log) -具有跟踪跟踪，对象转储和可选时间戳的日志记录库.
* [go-log](https://github.com/subchen/go-log) -在Go中进行简单且可配置的日志记录，包括级别，格式化程序和编写器.
* [go-log](https://github.com/siddontang/go-log) -日志库支持级别和多处理程序.
* [go-log](https://github.com/ian-kent/go-log) -Go中的Log4j实现.
* [go-logger](https://github.com/apsdehal/go-logger) -Go程序的简单记录器，带有级别处理程序.
* [gologger](https://github.com/sadlil/gologger) -简单易用的日志库，可在彩色控制台，简单控制台，文件或Elasticsearch中登录.
* [gomol](https://github.com/aphistic/gomol) -具有可扩展日志输出的Go的多输出，结构化日志.
* [gone/log](https://github.com/One-com/gone/tree/master/log) -快速，可扩展，全功能，std-lib源兼容的日志库.
* [journald](https://github.com/ssgreg/journald) -实施systemd Journal的本机API进行日志记录.
* [log](https://github.com/aerogo/log) -O（1）日志记录系统，允许您将一个日志连接到多个编写器（例如stdout，文件和TCP连接）.
* [log](https://github.com/apex/log) -Go的结构化日志包.
* [log](https://github.com/go-playground/log) -简单，可配置和可扩展的Go结构化日志记录.
* [log](https://github.com/teris-io/log) -Go的结构化日志界面将日志记录外观与其实现完全分开.
* [log-voyage](https://github.com/firstrow/logvoyage) -用golang编写的全功能日志记录saas.
* [log15](https://github.com/inconshreveable/log15) -Go的简单，强大的日志记录.
* [logdump](https://github.com/ewwwwwqm/logdump) -用于多级日志记录的软件包.
* [logex](https://github.com/chzyer/logex) -Golang日志库，支持跟踪和级别，按标准日志库包装.
* [logger](https://github.com/azer/logger) -Go的简约日志记录库.
* [logmatic](https://github.com/borderstech/logmatic) -具有动态日志级别配置的Golang彩色记录器.
* [logo](https://github.com/mbndr/logo) -Golang记录器可用于不同的可配置写入器.
* [logrus](https://github.com/Sirupsen/logrus) -Go的结构化记录器.
* [logrusiowriter](https://github.com/cabify/logrusiowriter) -使用的io.Writer实现 [logrus](https://github.com/sirupsen/logrus) 记录仪.
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) 插件将错误发​​送到 [Loggly](https://www.loggly.com/).
* [logur](https://github.com/logur/logur) -一个自以为是的记录器界面，并收集了带有适配器和知名库集成的最佳记录实践（[logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog)等）.
* [logutils](https://github.com/hashicorp/logutils) -实用程序，用于在Go（Golang）中更好地记录日志，从而扩展了标准记录器.
* [logxi](https://github.com/mgutz/logxi) -快速的12要素应用程序记录器，让您开心.
* [lumberjack](https://github.com/natefinch/lumberjack) -简单的滚动记录器，实现io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) -用于go的简单日志记录模块，具有5个级别，可选的旋转日志文件功能和stdout / stderr输出.
* [onelog](https://github.com/francoispqt/onelog)  -Onelog是一个简单却非常有效的JSON记录器.  在所有情况下，它都是最快的JSON记录器.  而且，它是分配最低的记录器之一.
* [ozzo-log](https://github.com/go-ozzo/ozzo-log)  -高性能日志记录，支持日志严重性，分类和过滤.  可以将过滤后的日志消息发送到各种目标（例如，控制台，网络，邮件）.
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) -RollingWriter是自动旋转的io.Writer实现，具有多种策略来提供日志文件的旋转.
* [seelog](https://github.com/cihub/seelog) -具有灵活的调度，过滤和格式化的日志记录功能.
* [spew](https://github.com/davecgh/go-spew) -为Go数据结构实现了一个深层漂亮的打印机，以帮助调试.
* [stdlog](https://github.com/alexcesaro/log)  -Stdlog是一个面向对象的库，提供了分级日志记录.  这对于cron作业非常有用.
* [tail](https://github.com/hpcloud/tail) -Go软件包努力模拟BSD尾部程序的功能.
* [xlog](https://github.com/xfxdev/xlog) -Go的插件架构和灵活的日志系统，具有ctrl级，多个日志目标和自定义日志格式.
* [xlog](https://github.com/rs/xlog) -结构化的记录器，用于“ net / context”感知的HTTP处理程序，具有灵活的调度功能.
* [zap](https://github.com/uber-go/zap) -在Go中进行快速，结构化，分级的日志记录.
* [zerolog](https://github.com/rs/zerolog) -零分配JSON记录器.

## Machine Learning

*机器学习图书馆.*

* [bayesian](https://github.com/jbrukh/bayesian) -Golang的朴素贝叶斯分类.
* [CloudForest](https://github.com/ryanbressler/CloudForest) -用于纯Go中机器学习的快速，灵活，多线程的决策树集合.
* [eaopt](https://github.com/MaxHalford/eaopt) -进化优化库.
* [evoli](https://github.com/khezen/evoli) -遗传算法和粒子群优化库.
* [fonet](https://github.com/Fontinalis/fonet) -用Go编写的深度神经网络库.
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) -实施k模式和k原型聚类算法.
* [go-deep](https://github.com/patrikeh/go-deep) -Go中功能丰富的神经网络库.
* [go-fann](https://github.com/white-pony/go-fann) -快速人工神经网络（FANN）库的绑定.
* [go-galib](https://github.com/thoj/go-galib) -用Go / golang编写的遗传算法库.
* [go-pr](https://github.com/daviddengcn/go-pr) -Go lang中的模式识别包.
* [gobrain](https://github.com/goml/gobrain) -用go语言编写的神经网络.
* [godist](https://github.com/e-dard/godist) -各种概率分布及相关方法.
* [goga](https://github.com/tomcraven/goga) -Go的遗传算法库.
* [GoLearn](https://github.com/sjwhitworth/golearn) -用于Go的通用机器学习库.
* [golinear](https://github.com/danieldk/golinear) -Go的liblinear绑定.
* [GoMind](https://github.com/surenderthakran/gomind) -Go中的简单神经网络库.
* [goml](https://github.com/cdipaolo/goml) -Go中的在线机器学习.
* [gonet](https://github.com/dathoangnd/gonet) -Go的神经网络.
* [Goptuna](https://github.com/c-bata/goptuna)  -使用Go编写的黑盒函数的贝叶斯优化框架.  一切都会被优化.
* [goRecommend](https://github.com/timkaye11/goRecommend) -用Go编写的推荐算法库.
* [gorgonia](https://github.com/gorgonia/gorgonia) -基于图形的计算库，例如Theano for Go，它提供了用于构建各种机器学习和神经网络算法的原语.
* [gorse](https://github.com/zhenghaoz/gorse) -基于Go编写的协作过滤的离线推荐系统后端.
* [goscore](https://github.com/asafschers/goscore) -用于PMML的评分API.
* [gosseract](https://github.com/otiai10/gosseract) -使用Tesseract C ++库，用于OCR（光学字符识别）的软件包.
* [libsvm](https://github.com/datastream/libsvm) -基于LIBSVM 3.14的libsvm golang版本派生作品.
* [neat](https://github.com/jinyeom/neat) -用于增强拓扑神经进化（NEAT）的即插即用，并行Go框架.
* [neural-go](https://github.com/schuyler/neural-go) -在Go中实现的多层感知器网络，并通过反向传播进行训练.
* [ocrserver](https://github.com/otiai10/ocrserver) -简单的OCR API服务器，非常容易被Docker和Heroku部署.
* [onnx-go](https://github.com/owulveryck/onnx-go) -进入开放式神经网络交换（ONNX）的界面.
* [probab](https://github.com/ThePaw/probab)  -概率分布函数.  贝叶斯推断.  用纯Go语言编写.
* [randomforest](https://github.com/malaschitz/randomForest) -易于使用的随机森林库.
* [regommend](https://github.com/muesli/regommend) -推荐和协作过滤引擎.
* [shield](https://github.com/eaigner/shield) 贝叶斯文本分类器，具有灵活的标记器和Go的存储后端.
* [tfgo](https://github.com/galeone/tfgo)  -易于使用的Tensorflow绑定：简化了官方Tensorflow Go绑定的使用.  在Go中定义计算图，加载并执行经过Python训练的模型.
* [Varis](https://github.com/Xamber/Varis) -神经网络.

## Messaging

*实现消息传递系统的库.*

* [ami](https://github.com/kak-tus/ami) -将客户端转到基于Redis群集流的可靠队列.
* [APNs2](https://github.com/sideshow/apns2) -Go的HTTP / 2 Apple Push Notification提供程序—将推送通知发送到iOS，tvOS，Safari和OSX应用程序.
* [Asynq](https://github.com/hibiken/asynq) -在Redis之上构建的Go的简单，可靠和高效的分布式任务队列.
* [Beaver](https://github.com/Clivern/Beaver) -实时消息传递服务器，用于构建可扩展的应用程序内通知，多人游戏，Web和移动应用程序中的聊天应用程序.
* [Benthos](https://github.com/Jeffail/benthos) -一系列协议之间的消息流桥.
* [Bus](https://github.com/mustafaturan/bus) -用于内部通信的极简消息总线实现.
* [Centrifugo](https://github.com/centrifugal/centrifugo) -Go中的实时消息传递（Websockets或SockJS）服务器.
* [Commander](https://github.com/jeroenrinzema/commander) -由事件驱动的高级消费者/生产者，支持各种“方言”，例如Apache Kafka.
* [dbus](https://github.com/godbus/dbus) -用于D-Bus的Native Go绑定.
* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) 使用二进制，泊坞窗或Drone CI的通知.
* [emitter](https://github.com/olebedev/emitter) -使用Go方式发出事件，并使用通配符，谓词，取消可能性和许多其他好的胜利.
* [event](https://github.com/agoalofalife/event) -模式观察器的实现.
* [EventBus](https://github.com/asaskevich/EventBus) -具有异步兼容性的轻量级事件总线.
* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
* [Glue](https://github.com/desertbit/glue) -健壮的Go和Javascript套接字库（替代Socket.io）.
* [go-notify](https://github.com/TheCreeper/go-notify) -freedesktop通知规范的本地实现.
* [go-nsq](https://github.com/nsqio/go-nsq) -NSQ的官方Go软件包.
* [go-res](https://github.com/jirenius/go-res) -用于构建REST /实时服务的软件包，在其中使用NATS和Resgate无缝同步客户端.
* [go-socket.io](https://github.com/googollee/go-socket.io) -用于golang（实时应用程序框架）的socket.io库.
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) -Viessmann Vitotrol Web服务的客户端库.
* [Gollum](https://github.com/trivago/gollum) -n：m多路复用器，它从不同的来源收集消息并将其广播到一组目标.
* [golongpoll](https://github.com/jcuga/golongpoll) -HTTP longpoll服务器库，使网络发布订阅变得简单.
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) -gopush-cluster是go push服务器群集.
* [gorush](https://github.com/appleboy/gorush) -推送通知服务器使用 [APNs2](https://github.com/sideshow/apns2) 和谷歌 [GCM](https://github.com/google/go-gcm).
* [guble](https://github.com/smancke/guble) -使用推播通知（Google Firebase Cloud Messaging，Apple推播通知服务，SMS）以及websockets，REST API的消息传递服务器，具有分布式操作和消息持久性.
* [hub](https://github.com/leandro-lugaresi/hub) -用于Go应用程序的消息/事件中心，使用发布/订阅模式并支持如RabbitMQ交换之类的别名.
* [jazz](https://github.com/socifi/jazz) -一个简单的RabbitMQ抽象层，用于队列管理以及消息的发布和使用.
* [machinery](https://github.com/RichardKnop/machinery) -基于分布式消息传递的异步任务队列/作业队列.
* [mangos](https://github.com/go-mangos/mangos) -具有传输互操作性的Nanomsg（“可伸缩协议”）的完全实施.
* [melody](https://github.com/olahol/melody) -用于处理websocket会话的简约框架，包括广播和自动ping / pong处理.
* [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
* [messagebus](https://github.com/vardius/message-bus) -messagebus是一种Go简单的异步消息总线，非常适合在进行事件源，CQRS和DDD时用作事件总线.
* [NATS Go Client](https://github.com/nats-io/nats) -轻量级和高性能的发布-订阅和分布式排队消息传递系统-这是Go库.
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) -围绕NSQ主题和渠道的小型包装.
* [oplog](https://github.com/dailymotion/oplog) -REST API的通用oplog /复制系统.
* [pubsub](https://github.com/tuxychandru/pubsub) -简单的pubsub包.
* [rabbus](https://github.com/rafaeljesus/rabbus) -在amqp交换和队列上的小包装.
* [rabtap](https://github.com/jandelgado/rabtap) -RabbitMQ瑞士军刀CLI应用程序.
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) -RapidMQ是用于管理本地消息队列的轻量级且可靠的库.
* [redisqueue](https://github.com/robinjoseph08/redisqueue) -redisqueue提供使用Redis流的队列的生产者和使用者.
* [rmqconn](https://github.com/sbabiv/rmqconn)  -RabbitMQ重新连接.  包装在amqp.Connection和amqp.Dial上.  允许在断开对Close（）方法的调用之前关闭连接时允许重新连接.
* [sarama](https://github.com/Shopify/sarama) -转到Apache Kafka的库.
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) -Redis支持的统一推送服务，用于向移动设备发送服务器端通知.
* [zmq4](https://github.com/pebbe/zmq4) -转到ZeroMQ版本4的界面.也可用于 [version 3](https://github.com/pebbe/zmq3) 和 [version 2](https://github.com/pebbe/zmq2).

## Microsoft Office

* [unioffice](https://github.com/unidoc/unioffice) -用于创建和处理Office Word（.docx），Excel（.xlsx）和Powerpoint（.pptx）文档的纯go库.

### Microsoft Excel

*用于Microsoft Excel的库.*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) -用于读取和写入Microsoft Excel™（XLSX）文件的Golang库.
* [go-excel](https://github.com/szyhf/go-excel) -一个简单而轻便的阅读器，可以将类似于related-db的excel读取为表格.
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) -用于编写XLSX（Microsoft Excel）文件的libxlsxwriter的Golang绑定.
* [xlsx](https://github.com/tealeg/xlsx) -简化阅读Go程序中最新版本的Microsoft Excel使用的XML格式的库.
* [xlsx](https://github.com/plandem/xlsx) -快速安全的方式来读取/更新Go程序中的现有Microsoft Excel文件.

## Miscellaneous

### Dependency Injection

*用于依赖注入的库.*

* [alice](https://github.com/magic003/alice) -Golang的附加依赖项注入容器.
* [container](https://github.com/golobby/container) -功能强大的IoC容器，界面流畅且易于使用.
* [di](https://github.com/goava/di) -用于go编程语言的依赖项注入容器.
* [dig](https://github.com/uber-go/dig) -用于Go的基于反射的依赖项注入工具包.
* [dingo](https://github.com/i-love-flamingo/dingo) -基于Guice的Go依赖注入工具包.
* [fx](https://github.com/uber-go/fx) -用于Go的基于依赖项注入的应用程序框架（建立在dig之上）.
* [gocontainer](https://github.com/vardius/gocontainer) -简单的依赖注入容器.
* [linker](https://github.com/logrange/linker) -基于反射的依赖注入和具有组件生命周期支持的控制库反转.
* [wire](https://github.com/Fs02/wire) -严格的Golang运行时依赖注入.

### Project Layout

*用于构造项目的非官方模式*

* [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) -Go应用样板模板，用于遵循生产最佳实践的快速启动项目.
* [go-sample](https://github.com/zitryss/go-sample) -具有实际代码的Go应用程序项目的示例布局.
* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) -Go生态系统中常见的历史和新兴项目布局模式集.
* [modern-go-application](https://github.com/sagikazarmark/modern-go-application) -进行应用样板并应用现代实践的示例.
* [scaffold](https://github.com/catchplay/scaffold)  -脚手架生成Starter Go项目布局.  让您专注于已实现的业务逻辑.

### Strings

*用于处理字符串的库.*

* [strutil](https://github.com/ozgio/strutil) -字符串实用程序.
* [xstrings](https://github.com/huandu/xstrings) -从其他语言移植的有用的字符串函数的集合.

### Uncategorized

*将这些库放在这里是因为其他类别似乎都不适合.

* [anagent](https://github.com/mudler/anagent) -带有依赖项注入的简约，可插入Golang evloop / timer处理程序.
* [antch](https://github.com/antchfx/antch) -快速，强大且可扩展的Web爬网和抓取框架.
* [archiver](https://github.com/mholt/archiver) -用于制作和提取.zip和.tar.gz档案的库和命令.
* [autoflags](https://github.com/artyom/autoflags) -Go程序包可从结构字段自动定义命令行标志.
* [avgRating](https://github.com/kirillDanshin/avgRating) -根据Wilson得分方程计算平均得分和评分.
* [banner](https://github.com/dimiro1/banner) -在您的Go应用程序中添加漂亮的横幅.
* [base64Captcha](https://github.com/mojocn/base64Captcha) -Base64captch支持数字，数字，字母，算术，音频和数字字母验证码.
* [battery](https://github.com/distatus/battery) -跨平台的标准化电池信息库.
* [bitio](https://github.com/icza/bitio) -高度优化的Go语言位读写器.
* [browscap_go](https://github.com/digitalcrab/browscap_go) -的GoLang图书馆 [Browser Capabilities Project](http://browscap.org/).
* [captcha](https://github.com/steambap/captcha) -验证码套件为生成验证码提供了易于使用且不受质疑的API.
* [conv](https://github.com/cstockton/go-conv) -包转换可在Go类型之间提供快速直观的转换.
* [datacounter](https://github.com/miolini/datacounter) -去读者/作家/http.ResponseWriter计数器.
* [ffmt](https://github.com/go-ffmt/ffmt) -美化人类的数据显示.
* [ghorg](https://github.com/gabrie30/ghorg) -快速将整个组织/用户存储库克隆到一个目录中-支持GitHub，GitLab和Bitbucket.
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) -Golang的通用对象池.
* [go-openapi](https://github.com/go-openapi) -收集软件包以解析和利用开放式API模式.
* [go-resiliency](https://github.com/eapache/go-resiliency) -golang的弹性模式.
* [go-unarr](https://github.com/gen2brain/go-unarr) -用于RAR，TAR，ZIP和7z存档的解压缩库.
* [gofakeit](https://github.com/brianvoe/gofakeit) -用go编写的随机数据生成器.
* [gommit](https://github.com/antham/gommit) -分析git commit消息，以确保它们遵循定义的模式.
* [gopsutil](https://github.com/shirou/gopsutil) -跨平台库，用于检索进程和系统利用率（CPU，内存，磁盘等）.
* [gosh](https://github.com/osamingo/gosh) -提供Go统计处理程序，结构，度量方法.
* [gosms](https://github.com/haxpax/gosms) -Go中您自己的本地SMS网关，可用于发送SMS.
* [gotoprom](https://github.com/cabify/gotoprom) -官方Prometheus客户端的类型安全指标构建器包装器库.
* [gountries](https://github.com/pariz/gountries) -包含国家/地区和细分数据的软件包.
* [health](https://github.com/dimiro1/health) -易于使用的可扩展健康检查库.
* [healthcheck](https://github.com/etherlabsio/healthcheck) -针对RESTful服务的自发的并发运行状况检查HTTP处理程序.
* [hostutils](https://github.com/Wing924/hostutils) -用于打包和解包FQDN列表的golang库.
* [indigo](https://github.com/osamingo/indigo) -使用Sonyflake并由Base58编码的分布式唯一ID生成器.
* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
* [llvm](https://github.com/llir/llvm) -用于在纯Go语言中与LLVM IR交互的库.
* [metrics](https://github.com/pascaldekloe/metrics) -度量工具和Prometheus展示库.
* [morse](https://github.com/alwindoss/morse) -库与莫尔斯电码来回转换.
* [numa](https://github.com/lrita/numa)  -NUMA是实用程序库，它是用go编写的.  它有助于我们编写一些NUMA-AWARED代码.
* [pdfgen](https://github.com/hyperboloide/pdfgen) -HTTP服务，可从Json请求生成PDF.
* [persian](https://github.com/mavihq/persian) -go中的一些波斯语实用程序.
* [sandid](https://github.com/aofei/sandid) -地球上的每一粒沙都有自己的编号.
* [shellwords](https://github.com/Wing924/shellwords) -一个Golang库，用于根据UNIX Bourne shell的单词解析规则来操作字符串.
* [shortid](https://github.com/teris-io/shortid) -分布式生成超短，唯一，非顺序，URL友好的ID.
* [shoutrrr](https://github.com/containrrr/shoutrrr) -通知库，可轻松访问各种消息传递服务，例如松弛，最重要，gotify和smtp等.
* [stateless](https://github.com/qmuntal/stateless) -用于创建状态机的流利库.
* [stats](https://github.com/go-playground/stats) -监视Go MemStats和系统统计信息（例如内存，交换和CPU），并通过UDP发送到您要记录的任何位置等.
* [turtle](https://github.com/hackebrot/turtle) -Go表情符号.
* [url-shortener](https://github.com/pantrif/url-shortener) -具有mysql支持的现代，强大而强大的URL缩短器微服务.
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) -生成样板http输入和输出处理.
* [xdg](https://github.com/rkoesters/xdg) -在Go中实现的FreeDesktop.org（xdg）规范.
* [xkg](https://github.com/go-xkg/xkg) -X Keyboard Grabber.

## Natural Language Processing

*使用人类语言的图书馆.*

* [detectlanguage](https://github.com/detectlanguage/detectlanguage-go)  -语言检测API Go客户端.  支持批量请求，短短语或单词语言检测.
* [getlang](https://github.com/rylans/getlang) -快速的自然语言检测程序包.
* [go-i18n](https://github.com/nicksnyder/go-i18n/) -打包和随附的工具，用于处理本地化文本.
* [go-localize](https://github.com/m1/go-localize) -简单易用的i18n（国际化和本地化）引擎-用于翻译语言环境字符串.
* [go-mystem](https://github.com/dveselov/mystem) -CGo与Yandex.Mystem的绑定-俄罗斯形态分析仪.
* [go-nlp](https://github.com/nuance/go-nlp) -用于处理离散概率分布的实用程序和其他可用于执行NLP工作的工具.
* [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.
* [go-stem](https://github.com/agonopol/go-stem) -实施波特词干算法.
* [go-unidecode](https://github.com/mozillazg/go-unidecode) -Unicode文本的ASCII音译.
* [go2vec](https://github.com/danieldk/go2vec) -用于word2vec嵌入的阅读器和实用程序功能.
* [gojieba](https://github.com/yanyiwu/gojieba) -这是Go的实现 [jieba](https://github.com/fxsjy/jieba) 其中有中文分词算法.
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) -绑定雪球libstemmer库，包括搬运工2.
* [gotokenizer](https://github.com/xujiajun/gotokenizer)  -基于Golang字典和Bigram语言模型的分词器.  （现在仅支持中文细分）
* [gounidecode](https://github.com/fiam/gounidecode) -Go的Unicode音译器（也称为unidecode）.
* [gse](https://github.com/go-ego/gse)  -进行高效的文本分割；  支持英语，中文，日语等.
* [icu](https://github.com/goodsign/icu)  -用于icu4c C库检测和转换功能的Cgo绑定.  保证与版本50.1兼容.
* [kagome](https://github.com/ikawaha/kagome) -用纯Go语言编写的JP形态分析仪.
* [libtextcat](https://github.com/goodsign/libtextcat)  -libtextcat C库的Cgo绑定.  保证与2.2版兼容.
* [MMSEGO](https://github.com/awsong/MMSEGO) -这是GO的实现 [MMSEG](http://technology.chtsai.org/mmseg/) 其中有中文分词算法.
* [nlp](https://github.com/Shixzie/nlp) -从字符串中提取值，并用nlp填充您的结构.
* [nlp](https://github.com/james-bowman/nlp) -支持LSA（潜在语义分析）的自然语言处理库.
* [paicehusk](https://github.com/rookii/paicehusk) -Paice / Husk阻止算法的Golang实现.
* [petrovich](https://github.com/striker2000/petrovich) -彼得罗维奇（Petrovich）是图书馆，在给定的语法情况下使用俄语名称.
* [porter](https://github.com/a2800276/porter) -这是Martin Porter的Porter词干算法的C实现的相当简单的移植.
* [porter2](https://github.com/zhenjl/porter2) -真快，波特2票.
* [prose](https://github.com/jdkato/prose)  -用于文本处理的库，支持标记化，词性标记，命名实体提取等.  仅限英语.
* [RAKE.go](https://github.com/Obaied/RAKE.go) -快速自动关键字提取算法（RAKE）的端口.
* [segment](https://github.com/blevesearch/segment) -按照以下说明执行Unicode文本分段的Go库 [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* [sentences](https://github.com/neurosnap/sentences) -句子标记器：将文本转换为句子列表.
* [shamoji](https://github.com/osamingo/shamoji) -shamoji是用Go编写的单词过滤软件包.
* [snowball](https://github.com/goodsign/snowball)  -Go专用的Snowball stemmer端口（cgo包装器）.  提供词干提取功能 [Snowball native](http://snowball.tartarus.org/).
* [stemmer](https://github.com/dchest/stemmer)  -用于Go编程语言的Stemmer软件包.  包括英语和德语词干.
* [textcat](https://github.com/pebbe/textcat) -Go包，用于基于n-gram的文本分类，并支持utf-8和原始文本.
* [whatlanggo](https://github.com/abadojack/whatlanggo)  -Go的自然语言检测程序包.  支持84种语言和24种脚本（书写系统，例如拉丁语，西里尔字母等）.
* [when](https://github.com/olebedev/when) -具有可插拔规则的自然EN和RU语言日期/时间解析器.

## Networking

*与网络各层配合使用的库.

* [arp](https://github.com/mdlayher/arp) -包arp实现ARP协议，如RFC 826中所述.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) -通过TCP流化协议缓冲区数据变得容易.
* [canopus](https://github.com/zubairhamed/canopus) -CoAP客户端/服务器实施（RFC 7252）.
* [cidranger](https://github.com/yl2chen/cidranger) -Go的快速IP到CIDR查找.
* [dhcp6](https://github.com/mdlayher/dhcp6) -软件包dhcp6实现了DHCPv6服务器，如RFC 3315中所述.
* [dns](https://github.com/miekg/dns) -去使用DNS的库.
* [ether](https://github.com/songgao/ether) -跨平台Go软件包，用于发送和接收以太网帧.
* [ethernet](https://github.com/mdlayher/ethernet) -软件包以太网实现了IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的封送处理.
* [fasthttp](https://github.com/valyala/fasthttp) -软件包fasthttp是Go的快速HTTP实现，比net / http快10倍.
* [fortio](https://github.com/fortio/fortio)  -负载测试库和命令行工具，高级回显服务器和Web UI.  允许指定设置的每秒查询负载，并记录延迟直方图和其他有用的统计数据并对其进行图形化.  Tcp，Http，gRPC.
* [ftp](https://github.com/jlaffaye/ftp) -软件包ftp实现了FTP客户端，如 [RFC 959](http://tools.ietf.org/html/rfc959).
* [gaio](https://github.com/xtaci/gaio) -Proactor模式下用于Golang的高性能async-io网络.
* [gev](https://github.com/Allenxuxu/gev) -gev是基于Reactor模式的轻量级，快速，无阻塞的TCP网络库.
* [gmqtt](https://github.com/DrmagicE/gmqtt) -Gmqtt是一个灵活的高性能MQTT代理库，它完全实现了MQTT协议V3.1.1.
* [gnet](https://github.com/panjf2000/gnet) -`gnet`是一个用纯Go编写的高性能，轻量级，无阻塞，事件驱动的网络框架.
* [gNxI](https://github.com/google/gnxi) -使用gNMI和gNOI协议的网络管理工具的集合.
* [go-getter](https://github.com/hashicorp/go-getter) -转到库，以使用URL从各种来源下载文件或目录.
* [go-powerdns](https://github.com/joeig/go-powerdns) -用于Golang的PowerDNS API绑定.
* [go-stun](https://github.com/ccding/go-stun) -实施STUN客户端（RFC 3489和RFC 5389）.
* [gobgp](https://github.com/osrg/gobgp) -以Go编程语言实现的BGP.
* [golibwireshark](https://github.com/sunwxg/golibwireshark) -软件包golibwireshark使用libwireshark库来解码pcap文件并分析解剖数据.
* [gopacket](https://github.com/google/gopacket) -使用libpcap绑定去库处理包.
* [gopcap](https://github.com/akrennmair/gopcap) -为libpcap进行包装.
* [goshark](https://github.com/sunwxg/goshark) -打包goshark使用tshark解码IP数据包并创建数据结构以分析数据包.
* [gosnmp](https://github.com/soniah/gosnmp) -用于执行SNMP操作的本机Go库.
* [gosocsvr](https://github.com/rakeki/gosocsvr) -套接字服务器变得简单.
* [gotcp](https://github.com/gansidui/gotcp) -Go软件包，用于快速编写tcp应用程序.
* [grab](https://github.com/cavaliercoder/grab) -用于管理文件下载的软件包.
* [graval](https://github.com/koofr/graval) -实验性FTP服务器框架.
* [HTTPLab](https://github.com/gchaincl/httplab) -HTTPLabs可让您检查HTTP请求并伪造响应.
* [httpproxy](https://github.com/wzshiming/httpproxy) -HTTP代理处理程序和拨号程序.
* [iplib](https://github.com/c-robinson/iplib) -受python启发的用于处理IP地址（net.IP，net.IPNet）的库 [ipaddress](https://docs.python.org/3/library/ipaddress.html) 和红宝石 [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
* [jazigo](https://github.com/udhos/jazigo) -Jazigo是用Go语言编写的工具，用于检索多个网络设备的配置.
* [kcp-go](https://github.com/xtaci/kcp-go) -KCP-快速可靠的ARQ协议.
* [kcptun](https://github.com/xtaci/kcptun) -基于KCP协议的极其简单和快速的udp隧道.
* [lhttp](https://github.com/fanux/lhttp) -强大的websocket框架，更轻松地构建IM服务器.
* [linkio](https://github.com/ian-kent/linkio) -用于读取器/写入器接口的网络链接速度仿真.
* [llb](https://github.com/kirillDanshin/llb)  -这是代理服务器的非常简单但快速的后端.  对于零内存分配和快速响应的快速重定向到预定义域很有用.
* [mdns](https://github.com/hashicorp/mdns) -Golang中的简单mDNS（多播DNS）客户端/服务器库.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) -Paho Go客户端提供了一个MQTT客户端库，用于通过TCP，TLS或WebSockets连接到MQTT代理.
* [NFF-Go](https://github.com/intel-go/nff-go) -快速开发用于云和裸机的高性能网络功能的框架（前YANFF）.
* [packet](https://github.com/aerogo/packet)  -通过TCP和UDP发送数据包.  如果需要，它可以缓冲消息和热交换连接.
* [peerdiscovery](https://github.com/schollz/peerdiscovery) -Pure Go库，用于使用UDP多播的跨平台本地对等点发现.
* [portproxy](https://github.com/aybabtme/portproxy) -简单的TCP代理，它将不支持它的API添加到CORS支持中.
* [publicip](https://github.com/polera/publicip) -包publicip返回您的面向公众的IPv4地址（互联网出口）.
* [quic-go](https://github.com/lucas-clemente/quic-go) -在纯Go中实现QUIC协议.
* [raw](https://github.com/mdlayher/raw) -原始数据包可在设备驱动程序级别为网络接口读取和写入数据.
* [sftp](https://github.com/pkg/sftp) -软件包sftp实现了SSH文件传输协议，如https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt中所述.
* [ssh](https://github.com/gliderlabs/ssh) -用于构建SSH服务器的高级API（包装crypto / ssh）.
* [sslb](https://github.com/eduardonunesp/sslb) -这是一个超级简单的负载均衡器，只是一个实现某种性能的小项目.
* [stun](https://github.com/go-rtc/stun) -实施RFC 5389 STUN协议.
* [tcp_server](https://github.com/firstrow/tcp_server) -更快地构建tcp服务器的库.
* [tspool](https://github.com/two/tspool) -TCP库使用工作程序池来提高性能并保护您的服务器.
* [utp](https://github.com/anacrolix/utp) -实施uTP微传输协议.
* [water](https://github.com/songgao/water) -简单的TUN / TAP库.
* [webrtc](https://github.com/pions/webrtc) -WebRTC API的纯Go实现.
* [winrm](https://github.com/masterzen/winrm) -使用WinRM客户端在Windows计算机上远程执行命令.
* [xtcp](https://github.com/xfxdev/xtcp) -具有同步全双工通信，安全关闭，自定义协议的TCP Server Framework.

### HTTP Clients

*用于发出HTTP请求的库.*

* [gentleman](https://github.com/h2non/gentleman) -功能齐全的插件驱动的HTTP客户端库.
* [go-http-client](https://github.com/bozd4g/go-http-client) -简单方便地拨打http.
* [grequests](https://github.com/levigross/grequests) -著名的Requests库的Go“克隆”.
* [heimdall](https://github.com/gojektech/heimdall) -具有重试和hystrix功能的增强型http客户端.
* [httpretry](https://github.com/ybbus/httpretry) -通过重试功能丰富了默认的go HTTP客户端.
* [pester](https://github.com/sethgrid/pester) -通过重试，退避和并发进行HTTP客户端调用.
* [request](https://github.com/monaco-io/request)  -用于golang的HTTP客户端.  如果您有关于axios或请求的经验，则会喜欢的.  没有第三种依赖.
* [resty](https://github.com/go-resty/resty) -受Ruby rest-client启发的Go的简单HTTP和REST客户端.
* [rq](https://github.com/ddo/rq) -更好的golang stdlib HTTP客户端接口.
* [sling](https://github.com/dghubble/sling) -Sling是用于创建和发送API请求的Go HTTP客户端库.

## OpenGL

*在Go中使用OpenGL的库.

* [gl](https://github.com/go-gl/gl) -为OpenGL进行绑定（通过光晕生成）.
* [glfw](https://github.com/go-gl/glfw) -为GLFW 3进行绑定.
* [goxjs/gl](https://github.com/goxjs/gl) -跨平台的OpenGL绑定（OS X，Linux，Windows，浏览器，iOS，Android）.
* [goxjs/glfw](https://github.com/goxjs/glfw) -跨平台的glfw库，用于创建OpenGL上下文并接收事件.
* [mathgl](https://github.com/go-gl/mathgl) -受GLM启发，专门用于3D数学的Pure Go数学软件包.

## ORM

*实现对象关系映射或数据映射技术的库.

* [beego orm](https://github.com/astaxie/beego/tree/master/orm)  -强大的orm框架.  支持：pq / mysql / sqlite3.
* [go-firestorm](https://github.com/jschoedt/go-firestorm) -适用于Google / Firebase Cloud Firestore的简单ORM.
* [go-pg](https://github.com/go-pg/pg) -专注于PostgreSQL特定功能和性能的PostgreSQL ORM.
* [go-queryset](https://github.com/jirfag/go-queryset) -100％类型安全的ORM，具有代码生成功能以及基于GORM的MySQL，PostgreSQL，Sqlite3和SQL Server支持.
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) -灵活而强大的SQL字符串构建器库以及零配置ORM.
* [go-store](https://github.com/gosuri/go-store) -用于Go的简单快速的Redis支持的键值存储库.
* [GORM](https://github.com/jinzhu/gorm) -出色的Golang ORM库，旨在对开发人员友好.
* [gormt](https://github.com/xxjwxc/gormt) -Mysql数据库搜索gorm结构.
* [gorp](https://github.com/go-gorp/gorp) -Go Relational Persistence，用于Go的ORM式库.
* [grimoire](https://github.com/Fs02/grimoire)  -Grimoire是数据库访问层和golang验证.  （支持：MySQL，PostgreSQL和SQLite3）.
* [lore](https://github.com/abrahambotros/lore) -用于Go的简单轻量级的伪ORM /伪结构映射环境.
* [Marlow](https://github.com/dadleyy/marlow) -从项目结构生成的ORM，以确保编译时的安全性.
* [pop/soda](https://github.com/gobuffalo/pop) -MySQL，PostgreSQL和SQLite的数据库迁移，创建，ORM等.
* [QBS](https://github.com/coocood/qbs)  -代表按结构查询.  Go ORM.
* [reform](https://github.com/go-reform/reform) -基于非空接口和代码生成的更好的ORM for Go.
* [rel](https://github.com/Fs02/rel) -用于干净（洋葱）架构的Golang SQL存储库层.
* [SQLBoiler](https://github.com/volatiletech/sqlboiler)  -ORM生成器.  生成针对您的数据库模式量身定制的功能强大且快速的ORM.
* [upper.io/db](https://github.com/upper/db) -用于通过使用包装成熟的数据库驱动程序的适配器与不同数据源进行交互的单一接口.
* [Xorm](https://github.com/go-xorm/xorm) -简单而强大的Go专用ORM.
* [Zoom](https://github.com/albrow/zoom) -基于Redis的快速数据存储和查询引擎.

## Package Management

*用于依赖性和程序包管理的官方工具*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more)  -模块是源代码交换和版本控制的单元.  go命令直接支持使用模块，包括记录和解决对其他模块的依赖性.

*用于软件包管理的官方实验工具*

* [dep](https://github.com/golang/dep) -转到依赖工具.
* [vgo](https://go.googlesource.com/vgo/) -版本化的Go.

*用于软件包和依赖项管理的非官方库.*

* [gigo](https://github.com/LyricalSecurity/gigo) -用于golang的类似PIP的依赖工具，并支持私有存储库和哈希.
* [glide](https://github.com/Masterminds/glide)  -轻松管理您的golang供应商和供应商软件包.  受到Maven，Bundler和Pip等工具的启发.
* [godep](https://github.com/tools/godep) -go的依赖工具，godep通过修复依赖关系来可复制地构建软件包.
* [gom](https://github.com/mattn/gom) -Go Manager-捆绑销售.
* [goop](https://github.com/nitrous-io/goop) -受Bundler启发，用于Go（golang）的简单依赖项管理器.
* [gop](https://github.com/lunny/gop) -在GOPATH之外构建和管理Go应用程序.
* [gopm](https://github.com/gpmgo/gopm) -进入软件包管理器.
* [govendor](https://github.com/kardianos/govendor)  -进入软件包管理器.  使用标准供应商文件的Go供应商工具.
* [gpm](https://github.com/pote/gpm) -Go的准系统依赖管理器.
* [johnny-deps](https://github.com/VividCortex/johnny-deps) -使用Git的最小依赖版本.
* [mvn-golang](https://github.com/raydac/mvn-golang) -该插件提供了自动加载Golang SDK，依赖管理以及在Maven项目基础架构中启动构建环境的方式.
* [nut](https://github.com/jingweno/nut) -Vendor Go依赖项.
* [VenGO](https://github.com/DamnWidget/VenGO) -创建和管理可导出的隔离go虚拟环境.

## Performance

* [jaeger](https://github.com/jaegertracing/jaeger) -分布式跟踪系统.
* [pixie](https://github.com/pixie-labs/pixie) -没有通过eBPF对Golang应用程序进行仪器跟踪.
* [profile](https://github.com/pkg/profile) -Go的简单配置支持包.
* [tracer](https://github.com/kamilsk/tracer) -简单，轻便的跟踪.

## Query Language

* [api-fu](https://github.com/ccbrown/api-fu) -全面的GraphQL实现.
* [gojsonq](https://github.com/thedevsaddam/gojsonq) -通过JSON数据查询的简单Go包.
* [graphql](https://github.com/tmc/graphql) -graphql解析器+实用程序.
* [graphql](https://github.com/neelance/graphql-go) -专注于易用性的GraphQL服务器.
* [graphql-go](https://github.com/graphql-go/graphql) -实施GraphQL for Go.
* [jsonql](https://github.com/elgs/jsonql) -Golang中的JSON查询表达式库.
* [jsonslice](https://github.com/bhmj/jsonslice) -具有高级过滤器的Jsonpath查询.
* [rql](https://github.com/a8m/rql) -REST API的资源查询语言.
* [straf](https://github.com/SonicRoshan/straf) -轻松将Golang结构转换为GraphQL对象.

## Resource Embedding

* [esc](https://github.com/mjibson/esc) -将文件嵌入Go程序，并为它们提供http.FileSystem接口.
* [fileb0x](https://github.com/UnnoTed/fileb0x) -嵌入文件的简单工具，重点放在“自定义”上，易于使用.
* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable.
* [go-resources](https://github.com/omeid/go-resources) -嵌入Go的多余资源.
* [go.rice](https://github.com/GeertJohan/go.rice) -go.rice是一个Go程序包，可轻松处理html，js，css，图像和模板等资源.
* [mule](https://github.com/wlbr/mule)  -将图像，电影等外部资源嵌入Go源代码中，以使用`go generate`创建单个文件二进制文件.  专注于简单性.
* [packr](https://github.com/gobuffalo/packr) -将静态文件嵌入Go二进制文件的简单方法.
* [statics](https://github.com/go-playground/statics) -将静态资源嵌入到go文件中以进行单个二进制编译+与http.FileSystem + symlinks一起使用.
* [statik](https://github.com/rakyll/statik) -将静态文件嵌入Go可执行文件.
* [templify](https://github.com/wlbr/templify) -将外部模板文件嵌入到Go代码中以创建单个文件二进制文件.
* [vfsgen](https://github.com/shurcooL/vfsgen) -生成静态实现给定虚拟文件系统的vfsdata.go文件.

## Science and Data Analysis

*用于科学计算和数据分析的图书馆.

* [assocentity](https://github.com/ndabAP/assocentity) -包关联性返回单词到给定实体的平均距离.
* [bradleyterry](https://github.com/seanhagen/bradleyterry) -提供Bradley-Terry模型进行成对比较.
* [chart](https://github.com/vdobler/chart)  -Go的简单图表绘图库.  支持多种图形类型.
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) -用于机器学习和统计的数据框（类似于熊猫）.
* [evaler](https://github.com/soniah/evaler) -简单的浮点算术表达式评估器.
* [ewma](https://github.com/VividCortex/ewma) -指数加权移动平均线.
* [geom](https://github.com/skelterjohn/geom) -Golang的2D几何.
* [go-dsp](https://github.com/mjibson/go-dsp) -Go的数字信号处理.
* [go-gt](https://github.com/ThePaw/go-gt) -用“ Go”语言编写的图论算法.
* [goent](https://github.com/kzahedi/goent) -实施熵测度.
* [gohistogram](https://github.com/VividCortex/gohistogram) -数据流的近似直方图.
* [gonum](https://github.com/gonum/gonum)  -Gonum是用于Go编程语言的一组数字库.  它包含用于矩阵，统计信息，优化等的库.
* [gonum/plot](https://github.com/gonum/plot) -gonum / plot提供了用于在Go中构建和绘制图的API.
* [goraph](https://github.com/gyuho/goraph) -Pure Go图论库（数据结构，算法可视化）.
* [gosl](https://github.com/cpmech/gosl) -进入科学图书馆，了解线性代数，FFT，几何，NURBS，数值方法，概率，优化，微分方程等.
* [GoStats](https://github.com/OGFris/GoStats) -GoStats是用于数学统计的开源GoLang库，主要用于机器学习领域，它涵盖了大多数统计度量功能.
* [graph](https://github.com/yourbasic/graph) -基本图形算法库.
* [ode](https://github.com/ChristopherRabotin/ode) -常微分方程（ODE）求解器，支持扩展状态和基于通道的迭代停止条件.
* [orb](https://github.com/paulmach/orb) -具有裁剪，GeoJSON和Mapbox Vector Tile支持的2D几何类型.
* [pagerank](https://github.com/alixaxel/pagerank) -在Go中实现的加权PageRank算法.
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) -微小的线性插值库.
* [PiHex](https://github.com/claygod/PiHex) -十六进制数Pi的“ Bailey-Borwein-Plouffe”算法的实现.
* [rootfinding](https://github.com/khezen/rootfinding) -根查找算法库，用于查找二次函数的根.
* [sparse](https://github.com/james-bowman/sparse) -用于线性代数的Go Sparse矩阵格式，支持科学和机器学习应用程序，与gonum矩阵库兼容.
* [stats](https://github.com/montanaflynn/stats) -Golang标准库中缺少常用功能的统计信息包.
* [streamtools](https://github.com/nytlabs/streamtools) -用于处理数据流的通用图形工具.
* [TextRank](https://github.com/DavidBelicza/TextRank) -Golang中的TextRank实现具有可扩展的功能（摘要，加权，短语提取）和多线程（goroutine）支持.
* [triangolatte](https://github.com/tchayen/triangolatte)  -2D三角剖分库.  允许将线和多边形（均基于点）转换为GPU的语言.

## Security

*用于帮助使您的应用程序更安全的库.*

* [acmetool](https://github.com/hlandau/acme) -具有自动续订功能的ACME（我们加密）客户端工具.
* [acra](https://github.com/cossacklabs/acra) -网络加密代理，可保护基于数据库的应用程序免遭数据泄漏：强大的选择性加密，SQL注入预防，入侵检测系统.
* [argon2-hashing](https://github.com/andskur/argon2-hashing) - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
* [argon2pw](https://github.com/raja/argon2pw) -具有恒定时间密码比较的Argon2密码哈希生成.
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) -自动配置让我们加密证书并启动TLS服务器.
* [BadActor](https://github.com/jaredfolkins/badactor) -基于fail2ban精神构建的内存中，应用程序驱动的狱卒.
* [Cameradar](https://github.com/Ullaakut/cameradar) -用于从监控摄像机远程破解RTSP流的工具和库.
* [certificates](https://github.com/mvmaasakkers/certificates) -用于生成tls证书的自带工具.
* [go-generate-password](https://github.com/m1/go-generate-password) -可以在cli上或用作库的密码生成器.
* [go-yara](https://github.com/hillu/go-yara) -去绑定 [YARA](https://github.com/plusvic/yara)，“适用于恶意软件研究人员（以及其他所有人）的模式匹配瑞士刀”.
* [goArgonPass](https://github.com/dwin/goArgonPass) -Argon2密码哈希和验证旨在与现有的Python和PHP实现兼容.
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) -可能是偏执狂的软件包，用于安全地哈希和加密密码.
* [Interpol](https://bitbucket.org/vahidi/interpol) -基于规则的数据生成器，用于模糊测试和渗透测试.
* [lego](https://github.com/xenolf/lego) -Pure Go ACME客户端库和CLI工具（与Let&#39;s Encrypt一起使用）.
* [memguard](https://github.com/awnumar/memguard) -用于处理内存中敏感值的纯Go库.
* [nacl](https://github.com/kevinburke/nacl) -实施NaCL API集.
* [optimus-go](https://github.com/pjebs/optimus-go) -使用Knuth算法的ID哈希和混淆.
* [passlib](https://github.com/hlandau/passlib) -永不过时的密码哈希库.
* [secure](https://github.com/unrolled/secure) -Go的HTTP中间件，有助于快速赢得安全性.
* [secureio](https://github.com/xaionaro-go/secureio) -基于XChaCha20-poly1305，ECDH和ED25519的io.ReadWriteCloser的密钥交换，认证，加密包装器和多路复用器.
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) -带有简单，显而易见的API和内置自动成本校准功能的Scrypt软件包.
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) -使用ssh密钥加密/解密.
* [sslmgr](https://github.com/adrianosela/sslmgr) -通过围绕acme / autocert的高级包装，可以轻松实现SSL证书.

## Serialization

*用于二进制序列化的库和工具.

* [asn1](https://github.com/PromonLogicalis/asn1) -用于golang的Asn.1 BER和DER编码库.
* [bambam](https://github.com/glycerine/bambam) -转到Cap&#39;n Proto模式的生成器.
* [bel](https://github.com/32leaves/bel)  -从Go结构/接口生成TypeScript接口.  对JSON RPC有用.
* [binstruct](https://github.com/ghostiam/binstruct) -Golang二进制解码器，用于将数据映射到结构中.
* [cbor](https://github.com/fxamacker/cbor) -小型，安全和容易的CBOR编码和解码库.
* [colfer](https://github.com/pascaldekloe/colfer) -Colfer二进制格式的代码生成.
* [csvutil](https://github.com/jszwec/csvutil) -高性能，惯用的CSV记录对本地Go结构的编码和解码.
* [elastic](https://github.com/epiclabs-io/elastic) -无论何时，都可以在运行时跨不同类型转换切片，地图或任何其他未知值.
* [fixedwidth](https://github.com/huydang284/fixedwidth) -固定宽度的文本格式（支持UTF-8）.
* [fwencoder](https://github.com/o1egl/fwencoder) -用于Go的固定宽度的文件解析器（编码和解码库）.
* [go-capnproto](https://github.com/glycerine/go-capnproto) -Cap&#39;n Proto库和解析器.
* [go-codec](https://github.com/ugorji/go) -针对msgpack，cbor和json的高性能，功能丰富，惯用的编码，解码和rpc库，并具有基于运行时的OR代码生成支持.
* [gogoprotobuf](https://github.com/gogo/protobuf) -Go with Gadgets的协议缓冲区.
* [goprotobuf](https://github.com/golang/protobuf) -以库和协议编译器插件的形式提供对Google协议缓冲区的支持.
* [jsoniter](https://github.com/json-iterator/go) -高性能100％兼容的“ encoding / json”的替代品.
* [mapstructure](https://github.com/mitchellh/mapstructure) -用于将通用地图值解码为本地Go结构的Go库.
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) -GoLang库，用于处理PHP会话格式和PHP序列化/反序列化功能.
* [pletter](https://github.com/vimeda/pletter) -为消息代理包装原始消息的标准方法.
* [structomap](https://github.com/tuvistavie/structomap) -从静态结构轻松动态地生成地图的库.

## Server Applications

* [algernon](https://github.com/xyproto/algernon) -HTTP / 2 Web服务器，内置对Lua，Markdown，GCSS和Amber的支持.
* [Caddy](https://github.com/mholt/caddy) -Caddy是一种易于配置和使用的备用HTTP / 2 Web服务器.
* [consul](https://www.consul.io/) -Consul是用于服务发现，监视和配置的工具.
* [devd](https://github.com/cortesi/devd) -开发人员的本地网络服务器.
* [discovery](https://github.com/Bilibili/discovery) -一个用于中层负载均衡和故障转移的注册表.
* [dudeldu](https://github.com/krotik/dudeldu) -一个简单的SHOUTcast服务器.
* [etcd](https://github.com/coreos/etcd) -高度可用的键值存储，用于共享配置和服务发现.
* [Fider](https://github.com/getfider/fider) -Fider是一个开放平台，用于收集和组织客户反馈.
* [Flagr](https://github.com/checkr/flagr) -Flagr是一种开源功能标记和A / B测试服务.
* [flipt](https://github.com/markphelps/flipt) -用Go和Vue.js编写的自包含功能标志解决方案
* [jackal](https://github.com/ortuman/jackal) -用Go语言编写的XMPP服务器.
* [lets-proxy2](https://github.com/rekby/lets-proxy2) -通过let-encrypt反向处理带有发出证书的https的反向代理.
* [minio](https://github.com/minio/minio) -Minio是分布式对象存储服务器.
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) -Nginx日志解析器和Prometheus的导出器.
* [nsq](http://nsq.io/) -实时分布式消息传递平台.
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) -将数据库事件从PostgreSQL传输到Kafka.
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) -中继以平衡Riemann事件和/或将其转换为Carbon.
* [RoadRunner](https://github.com/spiral/roadrunner) -高性能PHP应用程序服务器，负载平衡器和进程管理器.
* [SFTPGo](https://github.com/drakkan/sftpgo) -功能齐全且可高度​​配置的SFTP服务器软件.
* [Trickster](https://github.com/Comcast/trickster) -HTTP反向代理缓存和时间序列加速器.
* [yakvs](https://git.sci4me.com/sci4me/yakvs) -小型的网络内存中键值存储.


## Stream Processing

*用于流处理和反应式编程的库和工具.

* [go-streams](https://github.com/reugn/go-streams) -去流处理库.

## Template Engines

*用于模板化和词法化的库和工具.

* [ace](https://github.com/yosssi/ace)  -Ace是Go语言的HTML模板引擎，灵感来自Slim和Jade.  王牌是黄金的提炼.
* [amber](https://github.com/eknkc/amber) -Amber是用于Go编程语言的优雅模板引擎，其灵感来自HAML和Jade.
* [damsel](https://github.com/dskinner/damsel) -标记语言，具有通过CSS选择器进行html概述的功能，可以通过pkg html / template等扩展.
* [ego](https://github.com/benbjohnson/ego)  -轻量级的模板语言，可让您在Go中编写模板.  模板被翻译成Go并被编译.
* [extemplate](https://github.com/dannyvankooten/extemplate) -围绕html / template的微型包装器，可轻松实现基于文件的模板继承.
* [fasttemplate](https://github.com/valyala/fasttemplate)  -简单快速的模板引擎.  替换模板占位符的速度比原来快10倍 [text/template](http://golang.org/pkg/text/template/).
* [gofpdf](https://github.com/jung-kurt/gofpdf) -PDF文档生成器，对文本，图形和图像提供高级支持.
* [gospin](https://github.com/m1/gospin) -文章旋转和spintax / spinning语法引擎，适用于A / B，测试文本/文章并创建更自然的对话.
* [goview](https://github.com/foolin/goview) -Goview是基于golang html / template的轻量级，极简且惯用的模板库，用于构建Go Web应用程序.
* [hero](https://github.com/shiyanhui/hero) -Hero是一款便捷，快速且功能强大的go模板引擎.
* [jet](https://github.com/CloudyKit/jet) -Jet模板引擎.
* [kasia.go](https://github.com/ziutek/kasia.go) -用于HTML和其他文本文档的模板系统-实施.
* [liquid](https://github.com/osteele/liquid) -实施Shopify Liquid模板.
* [maroto](https://github.com/johnfercher/maroto)  -创建PDF的一种maroto方法.  Maroto受Bootstrap启发，并使用gofpdf.  快速简单.
* [mustache](https://github.com/hoisie/mustache) -实施Mustache模板语言.
* [pongo2](https://github.com/flosch/pongo2) -Go的类似Django的模板引擎.
* [quicktemplate](https://github.com/valyala/quicktemplate)  -快速，强大但易于使用的模板引擎.  将模板转换为Go代码，然后进行编译.
* [raymond](https://github.com/aymerick/raymond) -在Go中完整的车把实现.
* [Razor](https://github.com/sipin/gorazor) -Golang的Razor视图引擎.
* [Soy](https://github.com/robfig/soy) -按照以下步骤关闭Go的关闭模板（也称为Soy模板） [official spec](https://developers.google.com/closure/templates/).
* [velvet](https://github.com/gobuffalo/velvet) -在Go中完整的车把实现.

## Testing

*用于测试代码库和生成测试数据的库.

*测试框架
    * [apitest](https://apitest.dev) -用于基于REST的服务或HTTP处理程序的简单和可扩展的行为测试库，支持模拟外部http调用和序列图的呈现.
    * [assert](https://github.com/go-playground/assert) -与本地本机测试一起使用的基本断言库，带有用于自定义断言的构建块.
    * [badio](https://github.com/cavaliercoder/badio) -Go的“测试/ iotest”包的扩展.
    * [baloo](https://github.com/h2non/baloo) -富有表现力和多功能的端到端HTTP API测试变得容易.
    * [biff](https://github.com/fulldump/biff) -分叉测试框架，兼容BDD.
    * [charlatan](https://github.com/percolate/charlatan) -生成用于测试的虚假接口实现的工具.
    * [commander](https://github.com/SimonBaeumer/commander) -在Windows，Linux和osx上测试cli应用程序的工具.
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) -适用于您的测试框架的简单快照测试插件.
    * [dbcleaner](https://github.com/khaiql/dbcleaner) -根据Ruby中的“ database_cleaner”的启发，清理数据库以进行测试.
    * [dsunit](https://github.com/viant/dsunit) -针对SQL，NoSQL，结构化文件的数据存储区测试.
    * [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) -作为另一个Go应用程序或测试的一部分，在Linux，OSX或Windows上本地运行真实的Postgres数据库.
    * [endly](https://github.com/viant/endly) -声明式端到端功能测试.
    * [flute](https://github.com/suzuki-shunsuke/flute) -HTTP客户端测试框架.
    * [frisby](https://github.com/verdverm/frisby) -REST API测试框架.
    * [ginkgo](http://onsi.github.io/ginkgo/) -Go的BDD测试框架.
    * [go-carpet](https://github.com/msoap/go-carpet) -在终端中查看测试覆盖率的工具.
    * [go-cmp](https://github.com/google/go-cmp) -用于比较测试中Go值的软件包.
    * [go-mutesting](https://github.com/zimmski/go-mutesting) -Go源代码的变异测试.
    * [go-testdeep](https://github.com/maxatome/go-testdeep) -非常灵活的golang深度比较，扩展了go测试包.
    * [go-vcr](https://github.com/dnaeon/go-vcr) -记录并重放HTTP交互，以进行快速，确定性和准确的测试.
    * [goblin](https://github.com/franela/goblin) -Mocha像Go一样的测试框架.
    * [gocheck](http://labix.org/gocheck) -更先进的测试框架替代getest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) -具有Web UI和实时重载的BDD样式的框架.
    * [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.
    * [godog](https://github.com/DATA-DOG/godog) -类似于Go的BDD框架的黄瓜或Behat.
    * [gofight](https://github.com/appleboy/gofight) -Golang路由器框架的API处理程序测试.
    * [gogiven](https://github.com/corbym/gogiven) -类似于YATSPEC的Go的BDD测试框架.
    * [gomatch](https://github.com/jfilipczyk/gomatch) -创建用于针对模式测试JSON的库.
    * [gomega](http://onsi.github.io/gomega/) -Rspec，例如匹配器/断言库.
    * [GoSpec](https://github.com/orfjackal/gospec) -用于Go编程语言的BDD样式测试框架.
    * [gospecify](https://github.com/stesla/gospecify)  -这提供了BDD语法来测试您的Go代码.  使用过rspec之类的库的任何人都应该熟悉.
    * [gosuite](https://github.com/pavlo/gosuite) -通过利用Go1.7的子测试，将具有设置/拆卸功能的轻量级测试套件带到“测试”中.
    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) -一组软件包，以增强go测试软件包并支持通用模式.
    * [Hamcrest](https://github.com/rdrdr/hamcrest) -用于声明式Matcher对象的流利框架，将其应用于输入值时，会产生自描述结果.
    * [httpexpect](https://github.com/gavv/httpexpect) -简洁，声明性且易于使用的端到端HTTP和REST API测试.
    * [jsonassert](https://github.com/kinbiko/jsonassert) -用于验证JSON有效负载已正确序列化的软件包.
    * [restit](https://github.com/yookoala/restit) -使用微型框架来帮助编写RESTful API集成测试.
    * [schema](https://github.com/jgroeneveld/schema) -对请求和响应中使用的JSON模式进行快速，轻松的表达式匹配.
    * [testcase](https://github.com/adamluzsi/testcase) -行为驱动开发的惯用测试框架.
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) -Rails的帮手，例如测试装置来测试数据库应用程序.
    * [Testify](https://github.com/stretchr/testify) -对标准go测试包的神圣扩展.
    * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) -将markdown代码段转换为可测试的go代码.
    * [testsql](https://github.com/zhulongcheng/testsql) -在测试之前从SQL文件生成测试数据，并在完成后将其清除.
    * [trial](https://github.com/jgroeneveld/trial) -快速简单的可扩展断言，无需引入太多样板.
    * [Tt](https://github.com/vcaesar/tt) -简单而丰富多彩的测试工具.
    * [wstest](https://github.com/posener/wstest) -Websocket客户端，用于对websocket http.Handler进行单元测试.

*模拟
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) -生成独立模拟对象的工具.
    * [go-localstack](https://github.com/elgohr/go-localstack) -在AWS测试中使用localstack的工具.
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) -模拟SQL驱动程序，用于测试数据库交互.
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) -基于单事务的数据库驱动程序，主要用于测试目的.
    * [gock](https://github.com/h2non/gock) -通用的HTTP模拟变得容易.
    * [gomock](https://github.com/golang/mock) -Go编程语言的模拟框架.
    * [govcr](https://github.com/seborama/govcr) -用于Golang的HTTP模拟：记录和重放HTTP交互以进行离线测试.
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) -HTTP（S）代理，用于使用可扩展的中间件和易于使用的CLI记录和模拟REST / SOAP API.
    * [httpmock](https://github.com/jarcoal/httpmock) -轻松模拟来自外部资源的HTTP响应.
    * [minimock](https://github.com/gojuno/minimock) -Go接口的模拟生成器.
    * [mockhttp](https://github.com/tv42/mockhttp) -Go http.ResponseWriter的模拟对象.
    * [timex](https://github.com/cabify/timex) -原生`time`软件包的测试友好替代品.

*起毛和增量调试/减少/缩小.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) -随机测试系统.
    * [gofuzz](https://github.com/google/gofuzz) -用于填充带有随机值的go对象的库.
    * [Tavor](https://github.com/zimmski/tavor) -通用的模糊和增量调试框架.

*硒和浏览器控制工具.
    * [cdp](https://github.com/mafredri/cdp) -Chrome调试协议的类型安全绑定，可与实现该协议的浏览器或其他调试目标一起使用.
    * [chromedp](https://github.com/knq/chromedp) -一种驱动/测试Chrome，Safari，Edge，Android Webview和其他支持Chrome调试协议的浏览器的方法.
    * [ggr](https://github.com/aerokube/ggr) -轻量级服务器，将Selenium WebDriver请求路由和代理到多个Selenium集线器.
    * [rod](https://github.com/ysmood/rod) -易于使用且安全的Chrome devtools控制器.
    * [selenoid](https://github.com/aerokube/selenoid) -替代的Selenium集线器服务器，可在容器内启动浏览器.

*失败注入
    * [failpoint](https://github.com/pingcap/failpoint) -的实现 [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) 对于Golang.

## Text Processing

*用于解析和处理文本的库.*

*特定格式
    * [align](https://github.com/Guitarbum722/align) -对齐文本的通用应用程序.
    * [allot](https://github.com/sbstjn/allot) -CLI工具和漫游器的占位符和通配符文本解析.
    * [bbConvert](https://github.com/CalebQ42/bbConvert) -将bbCode转换为HTML，使您可以添加对自定义bbCode标记的支持.
    * [blackfriday](https://github.com/russross/blackfriday) -Go中的Markdown处理器.
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) -HTML Sanitizer.
    * [codetree](https://github.com/aerogo/codetree) -解析缩进的代码（python，pixy，scarlet等）并返回树结构.
    * [colly](https://github.com/asciimoo/colly) -Gophers的快速，优雅的Scrap框架.
    * [commonregex](https://github.com/mingrammer/commonregex) -Go常用正则表达式的集合.
    * [dataflowkit](https://github.com/slotix/dataflowkit) -Web抓取框架，可将网站转换为结构化数据.
    * [did](https://github.com/ockam-network/did) -Go中的DID（分散标识符）解析器和Stringer.
    * [doi](https://github.com/hscells/doi) -Go中的文档对象标识符（doi）解析器.
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) -Go的Editorconfig文件解析器和操纵器.
    * [enca](https://github.com/endeveit/enca) -最小的cgo绑定 [libenca](http://cihar.com/software/enca/).
    * [encdec](https://github.com/mickep76/encdec) -包为编码器和解码器提供通用接口.
    * [genex](https://github.com/alixaxel/genex) -计算正则表达式并将其扩展为所有匹配的字符串.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) -GitHub风格的Markdown渲染器（使用blackfriday），带有受保护的代码块突出显示，可单击的标头锚链接.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) -固定宽度的文本格式（带反射的编码器/解码器）.
    * [go-humanize](https://github.com/dustin/go-humanize) -用于将时间，数字和内存大小格式化为人类可读格式的格式化程序.
    * [go-nmea](https://github.com/adrianmo/go-nmea) -用于Go语言的NMEA解析器库.
    * [go-runewidth](https://github.com/mattn/go-runewidth) -获得固定宽度的字符或字符串的函数.
    * [go-slugify](https://github.com/mozillazg/go-slugify) -多种语言支持，使您很轻松.
    * [go-toml](https://github.com/pelletier/go-toml) -使用查询支持和方便的cli工具获取TOML格式的库.
    * [go-vcard](https://github.com/emersion/go-vcard) -解析并格式化vCard.
    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) -Go的零宽度字符检测和删除.
    * [gofeed](https://github.com/mmcdole/gofeed) -在Go中解析RSS和Atom提要.
    * [gographviz](https://github.com/awalterschulze/gographviz) -解析Graphviz DOT语言.
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) -将字节格式化为字符串.
    * [gonameparts](https://github.com/polera/gonameparts) -将人的名字解析成单独的名字部分.
    * [goq](https://github.com/andrewstuart/goq) -使用具有jQuery语法的struct标记对HTML进行声明式解封（使用GoQuery）.
    * [GoQuery](https://github.com/PuerkitoBio/goquery) -GoQuery为Go语言带来了类似于jQuery的语法和一组功能.
    * [goregen](https://github.com/zach-klippenstein/goregen) -用于从正则表达式生成随机字符串的库.
    * [goribot](https://github.com/zhshch2002/goribot) -一个简单的golang蜘蛛/抓取框架，分3行构建一个蜘蛛.
    * [gotext](https://github.com/leonelquinteros/gotext) -Go的GNU gettext实用程序.
    * [guesslanguage](https://github.com/endeveit/guesslanguage) -确定unicode文本的自然语言的功能.
    * [htmlquery](https://github.com/antchfx/htmlquery) -用于HTML的XPath查询包，可让您通过XPath表达式从HTML文档中提取数据或评估.
    * [inject](https://github.com/facebookgo/inject) -包装注入提供基于反射的注入器.
    * [ltsv](https://github.com/Wing924/ltsv) -高性能 [LTSV (Labeled Tab Separeted Value)](http://ltsv.org/) Go的阅读器.
    * [mxj](https://github.com/clbanning/mxj)  -将XML编码/解码为JSON或map [string] interface {}；  使用点符号路径和通配符提取值.  替换x2j和j2x软件包.
    * [podcast](https://github.com/eduncan911/podcast) -Golang中的iTunes兼容和RSS 2.0播客生成器
    * [sdp](https://github.com/gortc/sdp) -SDP：会话描述协议 [[RFC 4566](https://tools.ietf.org/html/rfc4566)].
    * [sh](https://github.com/mvdan/sh) -Shell解析器和格式化程序.
    * [slug](https://github.com/gosimple/slug) -支持URL的Slugify支持多种语言.
    * [Slugify](https://github.com/avelino/slugify) -去处理字符串的slugify应用程序.
    * [syndfeed](https://github.com/zhengchun/syndfeed) -Atom 1.0和RSS 2.0的联合供稿.
    * [toml](https://github.com/BurntSushi/toml) -TOML配置格式（带反射的编码器/解码器）.
* 效用
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) -用于Go的基于消毒的发誓过滤器.
    * [gotabulate](https://github.com/bndr/gotabulate) -使用Go轻松漂亮地打印表格数据.
    * [kace](https://github.com/codemodus/kace) -涵盖常见首字母缩写的常见案例转换.
    * [parseargs-go](https://github.com/nproc/parseargs-go) -理解引号和反斜杠的字符串参数解析器.
    * [parth](https://github.com/codemodus/parth) -URL路径分段解析.
    * [radix](https://github.com/yourbasic/radix) -快速的字符串排序算法.
    * [Tagify](https://github.com/zoomio/tagify) -从给定的来源产生一组标签.
	* [textwrap](https://github.com/isbm/textwrap) -从Python实现`textwrap`模块.
    * [TySug](https://github.com/Dynom/TySug) -关于键盘布局的替代建议.
    * [xj2go](https://github.com/stackerzzq/xj2go) -将xml或json转换为struct.
    * [xurls](https://github.com/mvdan/xurls) -从文本中提取网址.

## Third-party APIs

*用于访问第三方API的库.*

* [airtable](https://github.com/mehanizm/airtable) -转到客户端库 [Airtable API](https://airtable.com/api).
* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) -访问客户端库 [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda](https://github.com/ChimeraCoder/anaconda) -使用Twitter 1.1 API的客户端库.
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) -用于Go编程语言的官方AWS开发工具包.
* [brewerydb](https://github.com/naegelejd/brewerydb) -用于访问BreweryDB API的Go库.
* [cachet](https://github.com/andygrunwald/cachet) -访问客户端库 [Cachet (open source status page system)](https://cachethq.io/).
* [circleci](https://github.com/jszwedko/go-circleci) -用于与CircleCI的API交互的客户端库.
* [clarifai](https://github.com/samuelcouch/clarifai) -用于与Clarifai API接口的客户端库.
* [codeship-go](https://github.com/codeship/codeship-go) -Go客户端库，用于与Codeship的API v2进行交互.
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
* [discordgo](https://github.com/bwmarrin/discordgo) -为Discord Chat API进行绑定.
* [ethrpc](https://github.com/onrik/ethrpc) -以太坊JSON RPC API的绑定.
* [facebook](https://github.com/huandu/facebook) -支持Facebook Graph API的Go库.
* [fcm](https://github.com/maddevsio/fcm) -用于Firebase云消息传递的库.
* [gads](https://github.com/emiddleton/gads) -Google Adwords非官方API.
* [gami](https://github.com/bit4bit/gami) -转到Asterisk Manager界面库.
* [gcm](https://github.com/Aorioli/gcm) -前往Google Cloud Messaging的库.
* [geo-golang](https://github.com/codingsince1985/geo-golang) -去图书馆访问 [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/)和 [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) 地理编码/反向地理编码API.
* [github](https://github.com/google/go-github) -用于访问GitHub REST API v3的Go库.
* [githubql](https://github.com/shurcooL/githubql) -用于访问GitHub GraphQL API v4的Go库.
* [go-chronos](https://github.com/axelspringer/go-chronos) -Go库，用于与 [Chronos](https://mesos.github.io/chronos/) 工作计划
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) -HackerNews API的Tiny Go客户端.
* [go-here](https://github.com/abdullahselek/go-here) -围绕基于HERE位置的API的客户端库.
* [go-imgur](https://github.com/koffeinsource/go-imgur) -访问客户端库 [imgur](https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) -访问客户端库 [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-marathon](https://github.com/gambol99/go-marathon) -用于与Mesosphere的Marathon PAAS交互的库.
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) -访问客户端库以访问 [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-postman-collection](https://github.com/rbretecher/go-postman-collection) - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) （与失眠兼容）.
* [go-sophos](https://github.com/esurdam/go-sophos) -转到客户端库 [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) 零依赖
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) -转到SPTrans Olho Vivo API的客户端库.
* [go-telegraph](https://gitlab.com/toby3d/telegraph) -电报发布平台API客户端.
* [go-trending](https://github.com/和ygrunwald/go-trending) -去图书馆访问 [trending repositories](https://github.com/trending) 和 [developers](https://github.com/trending/developers) 在Github.
* [go-twitch](https://github.com/knspriggs/go-twitch) -Go客户端，用于与Twitch v3 API进行交互.
* [go-twitter](https://github.com/dghubble/go-twitter) -使用Twitter v1.1 API的客户端库.
* [go-unsplash](https://github.com/hbagdi/go-unsplash) -转到客户端库 [Unsplash.com](https://unsplash.com) API.
* [go-xkcd](https://github.com/nishanths/go-xkcd) -转到xkcd API的客户端.
* [golang-tmdb](https://github.com/cyruzin/golang-tmdb) -电影数据库API v3的Golang包装器.
* [golyrics](https://github.com/mamal72/golyrics) -Golyrics是一个Go库，用于从Wikia网站获取音乐歌词数据.
* [gomalshare](https://github.com/MonaxGT/gomalshare) -Go库MalShare API [malshare.com](http://www.malshare.com/)
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) -转到MusicBrainz WS2客户端库.
* [google](https://github.com/google/google-api-go-client) -自动生成的Google Go API.
* [google-analytics](https://github.com/chonthu/go-google-analytics) -简单的包装器，可轻松进行Google Analytics（分析）报告.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) -Google Cloud API Go客户端库.
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) -访问客户端库 [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [google-play-scraper](https://github.com/n0madic/google-play-scraper) -从Google Play商店获取数据.
* [gopaapi5](https://github.com/utekaravinash/gopaapi5) -访问客户端库 [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
* [gosip](https://github.com/koltyakov/gosip) -转到客户端库SharePoint API.
* [gostorm](https://github.com/jsgilmore/gostorm) -GoStorm是一个Go库，它实现在Go中编写与Storm外壳进行通信的Storm喷口和螺栓所需的通信协议.
* [hipchat](https://github.com/andybons/hipchat) -该项目为Hipchat API实现了golang客户端库.
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) -通过XMPP与HipChat进行通信的golang程序包.
* [igdb](https://github.com/Henry-Sarabia/igdb) -前往客户端 [Internet Game Database API](https://api.igdb.com/).
* [lastpass-go](https://github.com/ansd/lastpass-go) -转到客户端库 [LastPass](https://www.lastpass.com/) API.
* [libgoffi](https://github.com/clevabit/libgoffi) -本机库适配器工具箱 [libffi](http://sourceware.org/libffi/) 积分
* [Medium](https://github.com/Medium/medium-sdk-go) -转到用于Medium的OAuth2 API的SDK.
* [megos](https://github.com/andygrunwald/megos) -用于访问 [Apache Mesos](http://mesos.apache.org/) 簇.
* [minio-go](https://github.com/minio/minio-go) -用于Amazon S3兼容云存储的Minio Go库.
* [mixpanel](https://github.com/dukex/mixpanel) -Mixpanel是一个用于跟踪事件并从go应用程序向Mixpanel发送Mixpanel配置文件更新的库.
* [patreon-go](https://github.com/mxpv/patreon-go) -用于Patreon API的库.
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) -PayPal付款API的包装.
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) -Playlyfe Rest API Go SDK.
* [pushover](https://github.com/gregdel/pushover) -去包装Pushover API.
* [rrdaclient](https://github.com/Omie/rrdaclient)  -转到库以访问statdns.com API，后者又是RRDA API.  通过HTTP的DNS查询.
* [shopify](https://github.com/rapito/go-shopify) -转到库向Shopify API发出CRUD请求.
* [simples3](https://github.com/rhnvrm/simples3) -使用REST和Go语言编写的V4签名，使AWS S3库简单而轻松.
* [slack](https://github.com/nlopes/slack) -Go中的Slack API.
* [smite](https://github.com/sergiotapia/smitego) -打包以包装对Smite游戏API的访问.
* [spotify](https://github.com/rapito/go-spotify) -转到库以访问Spotify WEB API.
* [steam](https://github.com/sostronk/go-steam) -去图书馆与Steam游戏服务器进行交互.
* [stripe](https://github.com/stripe/stripe-go) -使用Stripe API的客户端.
* [textbelt](https://github.com/dietsche/textbelt) -转到textbelt.com txt消息传递API的客户端.
* [translate](https://github.com/poorny/translate) -进入在线翻译包.
* [Trello](https://github.com/adlio/trello) -Trello API的包装器.
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) -为TripAdvisor API进行包装.
* [tumblr](https://github.com/mattcunningham/gumblr) -封装Tumblr v2 API.
* [twitter-scraper](https://github.com/n0madic/twitter-scraper) -删除没有身份验证和限制的Twitter Frontend API.
* [uptimerobot](https://github.com/bitfield/uptimerobot) -使用Uptime Robot v2 API的包装程序和命令行客户端.
* [vl-go](https://github.com/verifid/vl-go) -围绕VerifID身份验证层API的客户端库.
* [webhooks](https://github.com/go-playground/webhooks) -适用于GitHub和Bitbucket的Webhook接收器.
* [wit-go](https://github.com/wit-ai/wit-go) -wit.ai HTTP API的客户端.
* [ynab](https://github.com/brunomvsouza/ynab.go) -转到YNAB API的包装器.
* [zooz](https://github.com/gojuno/go-zooz) -使用Zooz API的客户端.

## Utilities

*使您的生活更轻松的通用工具和工具.*

* [apm](https://github.com/topfreegames/apm) -具有HTTP API的Golang应用程序的进程管理器.
* [backscanner](https://github.com/icza/backscanner) -类似于bufio.Scanner的扫描仪，但是它以相反的顺序读取和返回行，从给定位置开始并向后移动.
* [beyond](https://github.com/wesovilabs/beyond) -Go工具将带您进入AOP世界！
* [blank](https://github.com/Henry-Sarabia/blank) -验证或删除字符串中的空格和空格.
* [boilr](https://github.com/tmrts/boilr) -快速，快速的CLI工具，用于从样板模板创建项目.
* [chyle](https://github.com/antham/chyle) -使用git存储库的Changelog生成器具有多种配置可能性.
* [circuit](https://github.com/cep21/circuit) -断路器模式的高效且功能完整的Hystrix like Go实现.
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) -Go中的断路器.
* [clockwork](https://github.com/jonboulle/clockwork) -用于golang的简单假时钟.
* [cmd](https://github.com/SimonBaeumer/cmd) -在osx，windows和linux上执行shell命令的库.
* [command](https://github.com/txgruppi/command) -具有线程安全串行和并行调度程序的Go的命令模式.
* [compare](https://github.com/posener/compare) -启用更具可读性和更轻松的比较任务.
* [copy-pasta](https://github.com/jutkko/copy-pasta) -使用后端等S3进行存储的通用多工作站剪贴板.
* [countries](https://github.com/biter777/countries) -全面实施ISO-3166-1，ISO-4217，ITU-T E.164，Unicode CLDR和IANA ccTLD标准.
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) 容器指标的界面（例如htop）.
* [ctxutil](https://github.com/posener/ctxutil) -上下文的实用程序功能的集合.
* [dbt](https://github.com/nikogura/dbt) -一种用于从中央可信存储库运行自更新签名二进制文件的框架.
* [Death](https://github.com/vrecan/death) -通过信号管理go应用程序关闭.
* [Deepcopier](https://github.com/ulule/deepcopier) -Go的简单结构复制.
* [delve](https://github.com/derekparker/delve) -调试器.
* [dlog](https://github.com/kirillDanshin/dlog) -编译时控制的记录器，可以在不删除调试调用的情况下缩小发行版.
* [ergo](https://github.com/cristianoliveira/ergo) -简化了在不同端口上运行的多个本地服务的管理.
* [evaluator](https://github.com/nullne/evaluator)  -基于s表达式动态评估表达式.  它很容易扩展.
* [filetype](https://github.com/h2non/filetype) -小型包装，可推断检查魔术数字签名的文件类型.
* [filler](https://github.com/yaronsumel/filler) -使用“ fill”标签填充结构的小型实用程序.
* [filter](https://github.com/gookit/filter) -提供Go数据的过滤，清理和转换.
* [fzf](https://github.com/junegunn/fzf) -用Go编写的命令行模糊查找器.
* [gaper](https://github.com/maxcnunes/gaper) -当Go项目崩溃或某些观看的文件更改时，生成并重新启动它.
* [generate](https://github.com/go-playground/generate) -运行go在指定的路径或环境变量上递归生成，并且可以通过正则表达式进行过滤.
* [ghokin](https://github.com/antham/ghokin) -并行格式化程序，没有黄瓜的外部依赖关系（黄瓜，behat ...）.
* [git-time-metric](https://github.com/git-time-metric/gtm) -Git的简单，无缝，轻量级时间跟踪.
* [go-astitodo](https://github.com/asticode/go-astitodo) -在您的GO代码中解析TODO.
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) -go：generate工具，用于包装由golang插件导出的符号（仅适用于1.8）.
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) -纯Go bsdiff和bspatch库以及CLI工具.
* [go-convert](https://github.com/Eun/go-convert) -包go-convert使您可以将值转换为另一种类型.
* [go-dry](https://github.com/ungerik/go-dry) -干燥（不要重复）Go的包装.
* [go-funk](https://github.com/thoas/go-funk) -现代Go实用程序库，可提供帮助程序（映射，查找，包含，过滤器，块，反向等）.
* [go-health](https://github.com/Talento90/go-health) -运行状况软件包简化了将运行状况检查添加到服务的方式.
* [go-httpheader](https://github.com/mozillazg/go-httpheader) -Go库，用于将结构编码为Header字段.
* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) -用于处理“问题详细信息”的软件包.
* [go-rate](https://github.com/beefsack/go-rate) -定时限速器.
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) -用Go语言编写的XML Sitemaps生成器.
* [go-trigger](https://github.com/sadlil/go-trigger) -Go-lang全局事件触发程序，使用ID注册事件并从项目的任何位置触发事件.
* [goback](https://github.com/carlescere/goback) -使用简单的指数补偿程序包.
* [godaemon](https://github.com/VividCortex/godaemon) -编写守护程序的实用程序.
* [godropbox](https://github.com/dropbox/godropbox) -用于从Dropbox编写Go服务/应用程序的通用库.
* [gohper](https://github.com/cosiner/gohper) -各种工具/模块有助于开发.
* [golarm](https://github.com/msempere/golarm) -带有系统事件的火警.
* [golog](https://github.com/mlimaloureiro/golog) -简单，轻量级的CLI工具，可及时跟踪您的任务.
* [gopencils](https://github.com/bndr/gopencils) -小而简单的程序包，可轻松使用REST API.
* [goplaceholder](https://github.com/michiwend/goplaceholder) -一个小的golang库，用于生成占位符图像.
* [goreadability](https://github.com/philipjkim/goreadability) -使用Facebook Open Graph和arc90的可读性的网页摘要提取器.
* [goreleaser](https://github.com/goreleaser/goreleaser) -尽可能快速，轻松地交付Go二进制文件.
* [goreporter](https://github.com/wgliang/goreporter) -Golang工具，可进行静态分析，单元测试，代码审查并生成代码质量报告.
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) -具有几乎全部功能的SeaweedFS客户端库.
* [gostrutils](https://github.com/ik5/gostrutils) -字符串操作和转换函数的集合.
* [gotenv](https://github.com/subosito/gotenv) -从Go中的.env或任何io.Reader加载环境变量.
* [gpath](https://github.com/tenntenn/gpath) -通过Go的表达来简化访问结构字段的库.
* [gubrak](https://github.com/novalagung/gubrak)  -Golang实用程序库，带有语法糖.  就像lodash，但对于golang.
* [handy](https://github.com/miguelpragier/handy) -许多实用程序和帮助程序，例如字符串处理程序/格式化程序和验证程序.
* [hostctl](https://github.com/guumaster/hostctl) -使用简单命令管理/ etc / hosts的CLI工具.
* [htcat](https://github.com/htcat/htcat) -并行和流水线HTTP GET实用程序.
* [hub](https://github.com/github/hub) -使用其他功能包装git命令，以从终端与github进行交互.
* [hystrix-go](https://github.com/afex/hystrix-go) -实现了程序员定义的备用（又称为断路器）的Hystrix模式.
* [immortal](https://github.com/immortal/immortal) -\ * nix跨平台（与OS无关）主管.
* [intrinsic](https://github.com/mengzhuo/intrinsic) -使用x86 SIMD而不编写任何汇编代码.
* [jsend](https://github.com/clevergo/jsend) -用Go编写的JSend的实现.
* [jump](https://github.com/gsamokovarov/jump) -跳跃帮助您通过学习习惯来更快地导航.
* [koazee](https://github.com/wesovilabs/koazee) -从懒惰评估和函数式编程中汲取灵感的库，消除了使用数组的麻烦.
* [limiters](https://github.com/mennanov/limiters) -具有可配置的后端和分布式锁的Golang分布式应用程序的速率限制器.
* [lrserver](https://github.com/jaschaephraim/lrserver) -用于Go的LiveReload服务器.
* [mc](https://github.com/minio/mc) -Minio Client提供了最少的工具来与Amazon S3兼容的云存储和文件系统一起使用.
* [mergo](https://github.com/imdario/mergo)  -在Golang中合并结构和地图的助手.  对于配置默认值很有用，避免了混乱的if语句.
* [mimemagic](https://github.com/zRedShift/mimemagic) -Pure Go高性能MIME嗅探库/实用程序.
* [mimesniffer](https://github.com/aofei/mimesniffer) -Go的MIME类型嗅探器.
* [mimetype](https://github.com/gabriel-vasile/mimetype) -用于基于幻数的MIME类型检测的软件包.
* [minify](https://github.com/tdewolff/minify) -HTML，CSS，JS，XML，JSON和SVG文件格式的快速消除器.
* [minquery](https://github.com/icza/minquery) -支持有效分页的MongoDB / mgo.v2查询（光标继续列出我们停下来的文档）.
* [mmake](https://github.com/tj/mmake) -现代品牌.
* [moldova](https://github.com/StabbyCutyou/moldova) -用于基于输入模板生成随机数据的实用程序.
* [mole](https://github.com/davrodpin/mole) -CLI应用程序可轻松创建ssh隧道.
* [mssqlx](https://github.com/linxGnu/mssqlx)  -数据库客户端库，任何主从服务器的代理，主主机结构.  轻巧且自动平衡.
* [multitick](https://github.com/VividCortex/multitick) -多路复用器，用于对齐的行情.
* [myhttp](https://github.com/inancgumus/myhttp) -简单的API，可通过超时支持发出HTTP GET请求.
* [netbug](https://github.com/e-dard/netbug) -轻松远程分析您的服务.
* [nfdump](https://github.com/chrispassas/nfdump) -读取nfdump netflow文件.
* [nostromo](https://github.com/pokanop/nostromo) -用于构建功能强大的别名的CLI.
* [okrun](https://github.com/xta/okrun) -去运行错误压路机.
* [olaf](https://github.com/btnguyen2k/olaf) -Go中实现了Twitter Snowflake.
* [onecache](https://github.com/adelowo/onecache) -缓存库，支持多个后端存储（Redis，Memcached，文件系统等）.
* [panicparse](https://github.com/maruel/panicparse) -将类似的goroutine分组，并为堆栈转储着色.
* [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) -模式匹配libray.
* [peco](https://github.com/peco/peco) -简化的交互式过滤工具.
* [pgo](https://github.com/arthurkushman/pgo) -PHP社区的便捷功能.
* [pm](https://github.com/VividCortex/pm) -具有HTTP API的进程（即goroutine）管理器.
* [ptr](https://github.com/gotidy/ptr) -提供用于简化从基本类型的常量创建指针的功能的软件包.
* [r](https://github.com/is5/r) -Go的类似Python的range（）体验.
* [rclient](https://github.com/zpatrick/rclient) -用于REST API的可读，灵活，易于使用的客户端.
* [realize](https://github.com/tockins/realize)  -使用文件监视程序构建系统并实时重新加载.  使用自定义路径运行，构建和监视文件更改.
* [repeat](https://github.com/ssgreg/repeat) -实施不同的退避策略，对重试操作和心跳很有用.
* [request](https://github.com/mozillazg/request) -进行人类HTTP请求.
* [rerate](https://github.com/abo/rerate) -Go的基于Redis的速率计数器和速率限制器.
* [rerun](https://github.com/ivpusic/rerun) -当源更改时，重新编译并重新运行go应用.
* [rest-go](https://github.com/edermanoel94/rest-go) -提供了许多有用的方法来使用rest api的软件包.
* [retry](https://github.com/kamilsk/retry) -最先进的功能机制，可以重复执行操作直到成功.
* [retry](https://github.com/percolate/retry) -一个简单但高度可配置的Go重试包.
* [retry](https://github.com/thedevsaddam/retry) -Go的简单易用的重试机制包.
* [retry](https://github.com/shafreeck/retry) -一个非常简单的库，确保您可以完成工作.
* [retry-go](https://github.com/rafaeljesus/retry-go) -重试让golang简单易行.
* [robustly](https://github.com/VividCortex/robustly) -弹性运行功能，捕获并重新启动紧急情况.
* [scan](https://github.com/blockloop/scan) -直接扫描golang`sql.Rows`到结构，切片或基本类型.
* [serve](https://github.com/syntaqx/serve) -您需要的任何位置的静态http服务器.
* [shutdown](https://github.com/ztrue/shutdown) -用于OS.Signal处理的应用程序关闭挂钩.
* [silk](https://github.com/chrispassas/silk) -读取丝网流文件.
* [slice](https://github.com/psampaz/slice) -用于常见Go Slice操作的类型安全功能.
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) -基本类型之间的切片转换.
* [slicer](https://github.com/leaanthony/slicer) -使切片操作更加轻松.
* [sorty](https://github.com/jfcg/sorty) -快速并发/并行排序.
* [spinner](https://github.com/briandowns/spinner) -封装可轻松为终端旋转器提供选项.
* [sqlx](https://github.com/jmoiron/sqlx) -在出色的内置数据库/ sql软件包的基础上提供了一组扩展.
* [Storm](https://github.com/asdine/storm) -用于BoltDB的简单而强大的工具包.
* [structs](https://github.com/PumpkinSeed/structs) -实现简单的功能来操纵结构.
* [Task](https://github.com/go-task/task) -简单的“制作”替代.
* [tome](https://github.com/cyruzin/tome) -Tome旨在对简单的RESTful API进行分页.
* [toolbox](https://github.com/viant/toolbox)  -切片，映射，多图，结构，函数，数据转换实用程序.  服务路由器，宏评估程序，令牌生成器.
* [ugo](https://github.com/alxrm/ugo) -ugo是带有Go简洁语法的切片工具箱.
* [UNIS](https://github.com/esemplastic/unis) -Go中字符串实用程序的Common Architecture™.
* [usql](https://github.com/knq/usql) -usql是SQL数据库的通用命令行界面.
* [util](https://github.com/shomali11/util)  -收集有用的实用程序功能.  （字符串，并发，操作等）.
* [wuzz](https://github.com/asciimoo/wuzz) -用于HTTP检查的交互式cli工具.
* [xferspdy](https://github.com/monmohan/xferspdy) -Xferspdy在golang中提供了二进制diff和补丁库.

## UUID

*Libraries for working with UUIDs.*

* [goid](https://github.com/jakehl/goid) -生成并解析符合RFC4122的V4 UUID.
* [nanoid](https://github.com/aidarkhanov/nanoid) -微型高效的Go唯一字符串ID生成器.
* [sno](https://github.com/muyo/sno) -具有嵌入式元数据的紧凑，可排序和快速的唯一ID.
* [ulid](https://github.com/oklog/ulid) -实施ULID（通用唯一词典分类索引）.
* [uniq](https://gitlab.com/skilstak/code/go/uniq) -使用命令无需麻烦，安全，快速的唯一标识符.
* [uuid](https://github.com/agext/uuid) -使用快速或具有加密质量的随机节点标识符生成，编码和解码UUID v1.
* [uuid](https://github.com/gofrs/uuid)  -通用唯一标识符（UUID）的实现.  支持创建和解析UUID.  积极维护satori uuid的叉子.
* [uuid](https://github.com/google/uuid) -基于RFC 4122和DCE 1.1的UUID的Go软件包：身份验证和安全服务.
* [wuid](https://github.com/edwingeng/wuid) -极其快速的唯一数生成器，比UUID快10-135倍.

## Validation

*用于验证的库.*

* [checkdigit](https://github.com/osamingo/checkdigit) -提供校验位算法（Luhn，Verhoeff，Damm）和计算器（ISBN，EAN，JAN，UPC等）.
* [gody](https://github.com/guiferpa/gody) -：balloon：Go的轻量级结构验证器.
* [govalid](https://github.com/twharmon/govalid) -快速，基于标签的结构验证.
* [govalidator](https://github.com/asaskevich/govalidator) -用于字符串，数字，切片和结构的验证器和消毒器.
* [govalidator](https://github.com/thedevsaddam/govalidator)  -使用简单的规则验证Golang请求数据.  受到Laravel请求验证的极大启发.
* [jio](https://github.com/faceair/jio) -jio是类似于json模式验证器 [joi](https://github.com/hapijs/joi).
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) -支持使用在常规代码结构中指定的可配置和可扩展验证规则（而不是struct标签）验证各种数据类型（结构，字符串，映射，切片等）.
* [terraform-validator](https://github.com/thazelart/terraform-validator) -Terraform的规范和约定验证器.
* [validate](https://github.com/gookit/validate)  -进行数据验证和过滤的软件包.  支持验证Map，Struct，Request（Form，JSON，url.Values，Uploaded Files）数据和更多功能.
* [validate](https://github.com/gobuffalo/validate) -该软件包提供了用于编写Go应用程序验证的框架.
* [validator](https://github.com/go-playground/validator) -进行结构和野外验证，包括交叉场，交叉结构，地图，切片和阵列潜水.

## Version Control

*用于版本控制的库.*

* [gh](https://github.com/rjeczalik/gh) -用于GitHub Webhooks的可编写脚本的服务器和net / http中间件.
* [git2go](https://github.com/libgit2/git2go) -转到libgit2的绑定.
* [go-git](https://github.com/src-d/go-git) -在纯Go中高度可扩展的Git实现.
* [go-vcs](https://github.com/sourcegraph/go-vcs) -在Go中操作和检查VCS存储库.
* [hercules](https://github.com/src-d/hercules) -从Git储存库历史中获得高级见解.
* [hgo](https://github.com/beyang/hgo) -Hgo是Go软件包的集合，提供对本地Mercurial存储库的读取访问.

## Video

*用于处理视频的库.*

* [gmf](https://github.com/3d0c/gmf) -为\ *库的FFmpeg进行绑定.
* [go-astisub](https://github.com/asticode/go-astisub) -在GO中操作字幕（.srt，.stl，.ttml，.webvtt，.ssa / .ass，图文电视，.smi等）.
* [go-astits](https://github.com/asticode/go-astits) -在GO中本地解析和解复用MPEG传输流（.ts）.
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) -Apple m3u8播放列表的解析器和生成器库.
* [go-mpd](https://github.com/unki2aut/go-mpd) -MPEG-DASH清单文件的解析器和生成器库.
* [goav](https://github.com/giorgisio/goav) -FFmpeg的全面Go绑定.
* [gst](https://github.com/ziutek/gst) -为GStreamer进行绑定.
* [libgosubs](https://github.com/wargarblgarbl/libgosubs)  -支持字幕格式.  支持.srt，.ttml和.ass.
* [libvlc-go](https://github.com/adrg/libvlc-go) -为libvlc 2.X / 3.X / 4.X（由VLC媒体播放器使用）进行绑定.
* [m3u8](https://github.com/grafov/m3u8) -Apple HLS的M3U8播放列表的解析器和生成器库.
* [v4l](https://github.com/korandiz/v4l) -用Go编写的Linux视频捕获库.

## Web Frameworks

*全栈Web框架*

* [aah](https://aahframework.org) -用于Go的可扩展，高性能，快速开发的Web框架.
* [Aero](https://github.com/aerogo/aero) -用于Go的高性能Web框架，在Lighthouse中得分最高.
* [Air](https://github.com/aofei/air) -Go的理想完善的Web框架.
* [appy](https://github.com/appist/appy) -一个自以为是的高效Web框架，有助于轻松扩展业务.
* [Banjo](https://github.com/nsheremet/banjo) -非常简单，快速的Go Web框架.
* [Beego](https://github.com/astaxie/beego) -beego是用于Go编程语言的开源高性能Web框架.
* [Buffalo](http://gobuffalo.io) -提高Rails的生产力！
* [Echo](https://github.com/labstack/echo) -高性能，简约的Go Web框架.
* [Fiber](https://github.com/gofiber/fiber) -基于Expresshttp的Express.js启发式Web框架.
* [Fireball](https://github.com/zpatrick/fireball) -更具“自然”感觉的Web框架.
* [Flamingo](https://github.com/i-love-flamingo/flamingo)  -可插拔Web项目的框架.  包括模块概念并提供DI，Configareas，i18n，模板引擎，graphql，可观察性，安全性，事件，路由和反向路由等功能.
* [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) -使用干净的体系结构（如DDD以及端口和适配器）提供电子商务功能，可用于构建灵活的电子商务应用程序.
* [Gin](https://github.com/gin-gonic/gin)  -Gin是用Go语言编写的Web框架！  它具有类似于martini的API，性能更高，速度最高可提高40倍.  如果您需要性能和良好的生产率.
* [Ginrpc](https://github.com/xxjwxc/ginrpc) -Gin参数自动绑定工具，gin rpc工具.
* [Gizmo](https://github.com/NYTimes/gizmo) -纽约时报使用的微服务工具包.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) -设置RESTful JSON API的快速简便方法.
* [go-rest](https://github.com/ungerik/go-rest) -Go的小巧的REST框架.
* [Goa](https://github.com/goadesign/goa) -Goa提供了用于在Go中开发远程API和微服务的整体方法.
* [goa](https://github.com/goa-go/goa) -goa就像golang的koajs一样，它是一个基于中间件的灵活，轻便，高性能和可扩展的Web框架.
* [Golax](https://github.com/fulldump/golax) -非Sinatra快速HTTP框架，支持Google自定义方法，深度拦截器，递归等.
* [Golf](https://github.com/dinever/golf)  -Golf是Go的快速，简单和轻量级的微型Web框架.  它具有强大的功能，除了Go Standard Library外没有其他依赖项.
* [Gondola](https://github.com/rainycape/gondola) -用于更快编写网站的Web框架.
* [gongular](https://github.com/mustafaakin/gongular) -具有输入映射/验证和（DI）依赖注入的Fast Go Web框架.
* [goweb](https://github.com/twharmon/goweb) -具有路由，websocket，日志记录，中间件，静态文件服务器（可选gzip）和自动TLS的Web框架.
* [Goyave](https://github.com/System-Glitch/goyave) -功能齐全的Web框架，旨在提供干净的代码和快速的开发，并具有强大的内置功能.
* [hiboot](https://github.com/hidevopsio/hiboot) -hiboot是具有自动配置和依赖项注入支持的高性能Web应用程序框架.
* [Macaron](https://github.com/go-macaron/macaron) -Macaron是Go中高效且模块化的Web设计框架.
* [mango](https://github.com/paulbellamy/mango) -Mango是受Rack和PEP333启发的Go的模块化Web应用程序框架.
* [Microservice](https://github.com/claygod/microservice) -用Golang编写的用于创建微服务的框架.
* [neo](https://github.com/ivpusic/neo) -Neo是使用极简单的API的最小且快速的Go Web框架.
* [patron](https://github.com/beatlabs/patron) -Patron是遵循最佳云实践的微服务框架，重点关注生产力.
* [Resoursea](https://github.com/resoursea/api) -REST框架，用于快速编写基于资源的服务.
* [REST Layer](http://rest-layer.io) -用于在数据库之上构建REST / GraphQL API的框架，主要通过代码进行配置.
* [Revel](https://github.com/revel/revel) -Go语言的高效Web框架.
* [rex](https://github.com/goanywhere/rex) -Rex是一个基于大猩猩/ mux进行模块化开发的库，与`net / http&#39;完全兼容.
* [rux](https://github.com/gookit/rux) -用于构建golang HTTP应用程序的简单快速的Web框架.
* [tango](https://github.com/lunny/tango) -Go的微型和可插入Web框架.
* [tigertonic](https://github.com/rcrowley/go-tigertonic) -受Dropwizard启发的用于构建JSON Web服务的框架.
* [uAdmin](https://github.com/uadmin/uadmin) -受Django启发，功能全面的Golang Web框架.
* [utron](https://github.com/gernest/utron) -用于Go（Golang）的轻量级MVC框架.
* [vox](https://github.com/aisk/vox) -受Koa大力启发的人类golang网络框架.
* [WebGo](https://github.com/bnkamalesh/webgo)  -建立网络应用程序的微框架；  与处理程序链接，中间件和上下文注入.  使用符合标准库的HTTP处理程序（即http.HandlerFunc）.
* [YARF](https://github.com/yarf-framework/yarf) -快速的微框架，旨在以快速，简单的方式构建REST API和Web服务.

### Middlewares

#### Actual middlewares

* [client-timing](https://github.com/posener/client-timing) -Server-Timing标头的HTTP客户端.
* [CORS](https://github.com/rs/cors) -轻松将CORS功能添加到您的API.
* [formjson](https://github.com/rs/formjson) -以标准形式POST透明地处理JSON输入.
* [go-server-timing](https://github.com/mitchellh/go-server-timing) -添加/解析服务器计时标题.
* [Limiter](https://github.com/ulule/limiter) -Go的简单简单速率限制中间件.
* [ln-paywall](https://github.com/philippgille/ln-paywall) -可以通过Lightning Network（Bitcoin）根据请求在中间件上通过API货币化.
* [Tollbooth](https://github.com/didip/tollbooth) -速率限制HTTP请求处理程序.
* [XFF](https://github.com/sebest/xff) -处理“ X-Forwarded-For”标题和朋友.

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) -Go的无痛中间件链接.
* [catena](https://github.com/codemodus/catena) -http.Handler包装器类别（与“链”相同的API）.
* [chain](https://github.com/codemodus/chain) 处理程序包装器链与范围内的数据（基于网络/上下文的“中间件”）.
* [go-wrap](https://github.com/go-on/wrap) -用于net / http的小型中间件软件包.
* [gores](https://github.com/alioygur/gores)  -处理HTML，JSON，XML等响应的Go包.  对于RESTful API很有用.
* [interpose](https://github.com/carbocation/interpose) -用于golang的极简net / http中间件.
* [muxchain](https://github.com/stephens2424/muxchain) -用于net / http的轻量级中间件.
* [negroni](https://github.com/urfave/negroni) -Golang的惯用HTTP中间件.
* [render](https://github.com/unrolled/render) -Go包，可轻松呈现JSON，XML和HTML模板响应.
* [renderer](https://github.com/thedevsaddam/renderer) -Go的简单，轻量和更快的响应（JSON，JSONP，XML，YAML，HTML，文件）渲染包.
* [rye](https://github.com/InVisionApp/rye) -支持JWT，CORS，Statsd和Go 1.7上下文的Tiny Go中间件库（带有罐装中间件）.
* [stats](https://github.com/thoas/stats) -可以存储有关您的Web应用程序的各种信息的中间件.

### Routers

* [alien](https://github.com/gernest/alien) -来自太空的轻量级快速http路由器.
* [bellt](https://github.com/GuilhermeCaruso/bellt) -一个简单的Go HTTP路由器.
* [Bone](https://github.com/go-zoo/bone) -闪电快速HTTP多路复用器.
* [Bxog](https://github.com/claygod/Bxog)  -用于Go的简单快速的HTTP路由器.  它适用于难度，长度和嵌套不同的路线.  而且他知道如何根据接收到的参数创建URL.
* [chi](https://github.com/go-chi/chi) -基于net / context的小型，快速且富有表现力的HTTP路由器.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter)  -从“ httprouter”派生的高性能路由器.  第一个适用于`fasthttp`的路由器.
* [FastRouter](https://github.com/razonyang/fastrouter) -用Go语言编写的快速，灵活的HTTP路由器.
* [gocraft/web](https://github.com/gocraft/web) -Go中的Mux和中间件软件包.
* [Goji](https://github.com/goji/goji) -Goji是一种简约灵活的HTTP请求多路复用器，支持`net / context`.
* [goroute](https://github.com/goroute/route) -简单但功能强大的HTTP请求多路复用器.
* [GoRouter](https://github.com/vardius/gorouter) -GoRouter是一种服务器/ API微型框架，HTTP请求路由器，多路复用器和多路复用器，为请求路由器提供支持“ net / context”的中间件.
* [gowww/router](https://github.com/gowww/router) -快速的HTTP路由器与net / http.Handler接口完全兼容.
* [httprouter](https://github.com/julienschmidt/httprouter)  -高性能路由器.  使用它和标准的http处理程序可以形成一个非常高性能的Web框架.
* [httptreemux](https://github.com/dimfeld/httptreemux)  -用于Go的高速，灵活的基于树的HTTP路由器.  来自httprouter的启发.
* [lars](https://github.com/go-playground/lars) -是用于Go的轻量级，快速和可扩展的零分配HTTP路由器，用于创建可自定义的框架.
* [mux](https://github.com/gorilla/mux) -强大的Golang URL路由器和调度程序.
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing)  -非常快速的Go（golang）HTTP路由器，支持正则表达式路由匹配.  附带对构建RESTful API的全面支持.
* [pure](https://github.com/go-playground/pure) -是一种轻量级HTTP路由器，坚持使用std“ net / http”实现.
* [Siesta](https://github.com/VividCortex/siesta) -编写中间件和处理程序的可组合框架.
* [vestigo](https://github.com/husobee/vestigo) -用于Go Web应用程序的高性能，独立，HTTP兼容的URL路由器.
* [violetear](https://github.com/nbari/violetear) -转到HTTP路由器.
* [xmux](https://github.com/rs/xmux) -基于`httprouter`和`net / context`支持的高性能复用器.
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) -用于Go的简单快速的HTTP路由器.

## WebAssembly

* [dom](https://github.com/dennwc/dom) -DOM库.
* [go-canvas](https://github.com/markfarnan/go-canvas) -使用HTML5 Canvas的库，所有代码都包含在go代码中.
* [tinygo](https://github.com/tinygo-org/tinygo)  -小地方编译器.  微控制器，WebAssembly和命令行工具.  基于LLVM.
* [vert](https://github.com/norunners/vert) -Go和JS值之间的互操作.
* [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) -在浏览器中运行Go WASM测试.
* [webapi](https://github.com/gowebapi/webapi) -从WebIDL生成的DOM和HTML的绑定.

## Windows

* [d3d9](https://github.com/gonutz/d3d9) -去Direct3D9的绑定.
* [go-ole](https://github.com/go-ole/go-ole) -用于golang的Win32 OLE实现.
* [gosddl](https://github.com/MonaxGT/gosddl)  -从SDDL字符串转换为用户友好的JSON.  SDDL由四部分组成：所有者，主要组，DACL，SACL.

## XML

*用于处理XML的库和工具.

* [XML-Comp](https://github.com/xml-comp/xml-comp) -简单的命令行XML比较器，可生成文件夹，文件和标签的差异.
* [xml2map](https://github.com/sbabiv/xml2map) -XML到MAP转换器的Golang编写.
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) -基于libxml2的xmlwriter模块的过程XML生成API.
* [xpath](https://github.com/antchfx/xpath) -Go的XPath软件包.
* [xquery](https://github.com/antchfx/xquery) -XQuery使您可以使用XPath表达式从HTML / XML文档中提取数据.
* [zek](https://github.com/miku/zek) -从XML生成Go结构.

## Tools

*使用软件和插件.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) -检查Go项目的最新更改，以了解向后不兼容的更改.
* [dupl](https://github.com/mibk/dupl) -代码克隆检测工具.
* [errcheck](https://github.com/kisielk/errcheck) -Errcheck是用于检查Go程序中未经检查的错误的程序.
* [gcvis](https://github.com/davecheney/gcvis) -实时可视化Go程序GC跟踪数据.
* [go-checkstyle](https://github.com/qiniu/checkstyle)  -checkstyle是样式检查工具，例如java checkstyle.  此工具的灵感来自java checkstyle golint.  该样式涉及“ Go Code评论注释”中的某些要点.
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) -创建go-cleanarch是为了验证Clean Architecture规则，例如Dependency Rule和Go项目中程序包之间的交互.
* [go-critic](https://github.com/go-critic/go-critic) -源代码linter，它带来当前在其他linter中未实现的检查.
* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) -一种简单的方法来查找Go项目的过时依赖项.
* [go-outdated](https://github.com/firstrow/go-outdated) -显示过期软件包的控制台应用程序.
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) -基于Web的Golang AST可视化工具.
* [GoCover.io](http://gocover.io/) -GoCover.io提供任何golang软件包即服务的代码覆盖率.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) -自动修复（添加，删除）Go导入的工具.
* [GolangCI](https://golangci.com/)  -GolangCI是针对GitHub拉取请求的自动化Golang代码检查服务.  服务是开源的，对于开源项目是免费的.
* [golines](https://github.com/segmentio/golines) -自动在Go代码中缩短长行的格式化程序.
* [GoLint](https://github.com/golang/lint) -Golint是Go源代码的皮特.
* [Golint online](http://go-lint.appspot.com/) -使用golint包在GitHub，Bitbucket和Google Project Hosting上在线获取Go源文件.
* [GoPlantUML](https://github.com/jfeliu007/goplantuml) -生成文本plantump类图的库和CLI，该类图包含有关结构和接口以及它们之间的关系的信息.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) -添加零值返回语句以匹配func返回类型.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) -gosimple是Go源代码的linter，专门研究简化代码.
* [gostatus](https://github.com/shurcooL/gostatus) -命令行工具，显示包含Go软件包的存储库的状态.
* [lint](https://github.com/surullabs/lint) -将短毛绒作为围棋测试的一部分.
* [php-parser](https://github.com/z7zmey/php-parser) -用Go编写的PHP解析器.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) -tarp在Go源代码中查找没有直接单元测试的函数和方法.
* [tickgit](https://github.com/augmentable-dev/tickgit) -CLI和go软件包，用于显示代码注释TODO（以任何语言显示）并应用“ git blame”来标识作者.
* [unconvert](https://github.com/mdempsky/unconvert) -从Go源代码中删除不必要的类型转换.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) -未使用的检查在代码中查找未使用的常量，变量，函数和类型.
* [validate](https://github.com/mccoyst/validate) -使用标签自动验证结构字段.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) -用于JetBrains IDE的Go插件.
* [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
* [go-mode](https://github.com/dominikh/go-mode.el) -GNU / Emacs的进入模式.
* [go-plus](https://github.com/joefitzgerald/go-plus) -Go（Golang）原子软件包，增加了自动完成，格式设置，语法检查，整理和审核.
* [gocode](https://github.com/nsf/gocode) -Go编程语言的自动补全守护程序.
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) -此扩展在VS Code中添加了对Go语言的基准分析支持.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) -用于文本编辑器SublimeText 3的Golang插件集合，提供代码完成和其他类似IDE的功能.
* [gounit-vim](https://github.com/hexdigest/gounit-vim) -Vim插件，用于基于函数或方法的签名生成Go测试.
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) -对Theia IDE的语言支持.
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) -Vim插件可突出显示保存时的语法错误.
* [vim-go](https://github.com/fatih/vim-go) -Go Vim开发插件.
* [vscode-go](https://github.com/Microsoft/vscode-go) -Visual Studio Code（VS Code）扩展，提供对Go语言的支持.
* [Watch](https://github.com/eaburns/Watch) -在文件更改时以极致优势运行命令.

## Go Generate Tools

* [generic](https://github.com/usk81/generic) -Go的灵活数据类型.
* [genny](https://github.com/cheekybits/genny) -优雅的仿制药.
* [gocontracts](https://github.com/Parquery/gocontracts) -通过使代码与文档同步来实现按合同设计.
* [gonerics](http://github.com/bouk/gonerics) -Go中的惯用泛型.
* [gotests](https://github.com/cweill/gotests) -从您的源代码生成Go测试.
* [gounit](https://github.com/hexdigest/gounit) -使用您自己的模板生成Go测试.
* [hasgo](https://github.com/DylanMeeus/hasgo) -为您的切片生成Haskell启发的函数.
* [re2dfa](https://github.com/opennota/re2dfa) -将正则表达式转换成有限状态机并输出Go源代码.
* [TOML-to-Go](https://xuri.me/toml-to-go) -在浏览器中立即将TOML转换为Go类型.
* [xgen](https://github.com/xuri/xgen) -XSD（XML架构定义）解析器和Go / C / Java / Rust / TypeScript代码生成器.

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) -在`go`命令周围的包装器，用于着色`go build`输出.
* [depth](https://github.com/KyleBanks/depth) -通过分析导入可视化任何程序包的依赖关系树.
* [gb](https://getgb.io/) -易于使用的Go编程语言基于项目的构建工具.
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - 一个 [Yeoman](http://yeoman.io) 生成器来启动新的Go项目.
* [gilbert](https://go-gilbert.github.io) -为Go项目构建系统和任务运行器.
* [go-callvis](https://github.com/TrueFurby/go-callvis) -使用点格式可视化Go程序的调用图.
* [go-james](https://github.com/pieterclaerhout/go-james) -Go项目框架创建者，无需手动设置即可构建和测试项目.
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) -去和去的Bash完成.
* [go-swagger](https://github.com/go-swagger/go-swagger)  -Swagger 2.0实现.  Swagger是RESTful API的简单但功能强大的表示形式.
* [godbg](https://github.com/tylerwince/godbg) -实现Rusts`dbg！`宏，以便在开发过程中快速轻松地进行调试.
* [gomodrun](https://github.com/dustinblackman/gomodrun/) - Go tool that executes and caches binaries included in go.mod files.
* [gothanks](https://github.com/psampaz/gothanks) -GoThanks自动为您的go.mod github依赖项加注星标，以这种方式向其维护者发送一些爱意.
* [igo](https://github.com/rocketlaunchr/igo) -可以进行翻译的igo（Go语言的新语言功能！）
* [OctoLinker](https://github.com/OctoLinker/browser-extension) -使用GitHub的OctoLinker浏览器扩展有效地浏览go文件.
* [richgo](https://github.com/kyoh86/richgo) -丰富带有文本装饰的“ go test”输出.
* [rts](https://github.com/galeone/rts)  -RTS：对结构的响应.  从服务器响应生成Go结构.

## Software Packages

*用Go编写的软件.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) -恰恰是Debian仓库管理工具.
* [aurora](https://github.com/xuri/aurora) -跨平台的基于Web的Beanstalkd队列服务器控制台.
* [awsenv](https://github.com/soniah/awsenv) -小型二进制文件，用于为配置文件加载Amazon（AWS）环境变量.
* [Blast](https://github.com/dave/blast) -用于API负载测试和批处理作业的简单工具.
* [bombardier](https://github.com/codesenberg/bombardier) -快速的跨平台HTTP基准测试工具.
* [bosun](https://github.com/bosun-monitor/bosun) -时间序列警报框架.
* [DepCharge](https://github.com/centerorbit/depcharge) -帮助协调跨大型项目中许多依赖项的命令执行.
* [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) -一个go库和一个可执行文件，它使用各种输入通道生成有效的Dockerfile.
* [dogo](https://github.com/liudng/dogo) -监视源文件中的更改并自动编译并运行（重新启动）.
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) -使用二进制文件，泊坞窗或Drone CI触发下游Jenkins作业.
* [drone-scp](https://github.com/appleboy/drone-scp) -使用二进制文件，docker或Drone CI通过SSH复制文件和工件.
* [Dropship](https://github.com/chrismckenzie/dropship) -通过CDN部署代码的工具.
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) -Golang软件包，可通过SSH和SCP通过“ ProxyCommand”下载轻松实现远程执行.
* [fac](https://github.com/mkchoi212/fac) -修复git合并冲突的命令行用户界面.
* [gaia](https://github.com/gaia-pipeline/gaia) -以任何编程语言构建强大的管道.
* [Gitea](https://github.com/go-gitea/gitea) -Gogs的叉子，完全由社区驱动.
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) -将所有GitHub存储库，问题，里程碑和标签迁移到Gitea实例.
* [go-furnace](https://github.com/go-furnace/go-furnace)  -用Go编写的托管解决方案.  在AWS，GCP或DigitalOcean上轻松部署应用程序.
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) -使Go应用程序能够自我更新.
* [gobrew](https://github.com/cryptojuice/gobrew) -gobrew可让您轻松在go的多个版本之间切换.
* [godbg](https://github.com/sirnewton01/godbg) -基于Web的gdb前端应用程序.
* [Gogs](https://gogs.io/) -使用Go编程语言的自托管Git服务.
* [gonative](https://github.com/inconshreveable/gonative) -创建Go的版本的工具，该版本可以交叉编译到所有平台，同时仍使用启用了Cgo的stdlib软件包版本.
* [govvv](https://github.com/ahmetalpbalkan/govvv) -“ go build”包装器，可轻松将版本信息添加到Go二进制文件中.
* [gox](https://github.com/mitchellh/gox) -死法简单，没有多余的装饰可以交叉编译工具.
* [goxc](https://github.com/laher/goxc) -为Go构建工具，重点是交叉编译和打包.
* [grapes](https://github.com/yaronsumel/grapes) -轻量级工具，旨在通过ssh轻松分发命令.
* [GVM](https://github.com/moovweb/gvm) -GVM提供了管理Go版本的界面.
* [Hey](https://github.com/rakyll/hey) -嘿，这是个很小的程序，它将一些负载发送到Web应用程序.
* [jcli](https://github.com/jenkins-zh/jenkins-cli) -Jenkins CLI使您可以轻松管理Jenkins.
* [kala](https://github.com/ajvb/kala) -简单，现代，高效的工作计划程序.
* [kcli](https://github.com/cswank/kcli) -检查kafka主题/分区/消息的命令行工具.
* [kubernetes](https://github.com/kubernetes/kubernetes) -来自Google的Container Cluster Manager.
* [lstags](https://github.com/ivanilves/lstags) -跨不同注册表同步Docker映像的工具和API.
* [lwc](https://github.com/timdp/lwc) -UNIX wc命令的实时更新版本.
* [manssh](https://github.com/xwjdsh/manssh) -manssh是用于轻松管理ssh别名配置的命令行工具.
* [Moby](https://github.com/moby/moby) -容器生态系统的协作项目，以组装基于容器的系统.
* [Mora](https://github.com/emicklei/mora) -用于访问MongoDB文档和元数据的REST服务器.
* [ostent](https://github.com/ostrost/ostent) -收集并显示系统指标，并可选地中继到Graphite和/或InfluxDB.
* [Packer](https://github.com/mitchellh/packer) -Packer是一个工具，可从一个源配置为多个平台创建相同的机器映像.
* [Pewpew](https://github.com/bengadbois/pewpew) -灵活的HTTP命令行压力测试仪.
* [Pomerium](https://github.com/pomerium/pomerium) -Pomerium是一个身份识别访问代理.
* [Rodent](https://github.com/alouche/rodent) -啮齿动物可帮助您管理Go版本，项目和跟踪依赖关系.
* [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) -具有GET，PUT和DELETE方法和身份验证（OpenID Connect和基本身份验证）的S3代理.
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) -优化的小型实用程序/库，可用于将大型对象高速传输到Amazon S3和从Amazon S3传输出来.
* [s5cmd](https://github.com/peak/s5cmd) -快速的S3和本地文件系统执行工具.
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) -从命令行管理BareMetal服务器（与Docker一样容易）.
* [script](https://github.com/bitfield/script) -轻松在Go中为DevOps和系统管理任务编写类似shell的脚本.
* [sg](https://github.com/ChristopherRabotin/sg) -对一组HTTP端点（例如ab）进行基准测试，并可能根据每次响应之间的先前响应，在每次调用之间使用响应代码和数据来满足特定的服务器压力.
* [skm](https://github.com/TimothyYe/skm) -SKM是一个简单而强大的SSH密钥管理器，它可以帮助您轻松管理多个SSH密钥！
* [StatusOK](https://github.com/sanathp/statusok) -监视您的网站和REST API.当服务器关闭或响应时间超出预期时，通过Slack，电子邮件获得通知.
* [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) -Terraform provider插件，它基于包含公开API定义的OpenAPI文档（以前称为swagger文件）在运行时动态配置自身.
* [traefik](https://github.com/containous/traefik) -反向代理和负载均衡器，支持多个后端.
* [uTask](https://github.com/ovh/utask) -自动化引擎，用于建模和执行yaml中声明的业务流程.
* [Vegeta](https://github.com/tsenart/vegeta)  -HTTP负载测试工具和库.  超过9000！
* [webhook](https://github.com/adnanh/webhook) -允许用户创建在服务器上执行命令的HTTP端点（挂钩）的工具.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) -Cli工具，可在Windows计算机上远程执行命令.

### Other Software

* [borg](https://github.com/crufter/borg) -基于终端的bash片段搜索引擎.
* [boxed](https://github.com/tejo/boxed) -基于Dropbox的博客引擎.
* [Cherry](https://github.com/rafael-santiago/cherry) -Go中的微型网聊服务器.
* [Circuit](https://github.com/gocircuit/circuit) -Circuit是可编程的平台即服务（PaaS）和/或基础架构即服务（IaaS），用于管理，发现，同步和编排包含云应用程序的服务和主机.
* [Comcast](https://github.com/tylertreat/Comcast) -模拟不良的网络连接.
* [confd](https://github.com/kelseyhightower/confd) -使用来自etcd或consul的模板和数据来管理本地应用程序配置文件.
* [croc](https://github.com/schollz/croc) -轻松安全地将文件或文件夹从一台计算机发送到另一台计算机.
* [Docker](http://www.docker.com/) -为开发人员和系统管理员提供分布式应用程序的开放平台.
* [Documize](https://github.com/documize/community) -集成了SaaS工具数据的现代Wiki软件.
* [dp](https://github.com/scryinfo/dp) -通过SDK与区块链进行数据交换，开发人员可以轻松访问DAPP开发.
* [drive](https://github.com/odeke-em/drive) -命令行的Google云端硬盘客户端.
* [Duplicacy](https://github.com/gilbertchen/duplicacy) -基于无锁重复数据删除思想的跨平台网络和云备份工具.
* [gfile](https://github.com/Antonito/gfile) -通过WebRTC在没有任何第三方的情况下在两台计算机之间安全地传输文件.
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) -在您的GOPATH中显示Go软件包更新的应用.
* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) -视频流洪流客户端.
* [GoBoy](https://github.com/Humpheh/goboy) -用Go编写的Nintendo Game Boy Color模拟器.
* [gocc](https://github.com/goccmack/gocc) -Gocc是用Go编写的Go编译器套件.
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) -Go Doc网站的Chrome扩展程序，在功能列表中以工具提示的形式显示功能说明.
* [GoLand](https://jetbrains.com/go) -功能齐全的跨平台Go IDE.
* [Gor](https://github.com/buger/gor) -Http流量复制工具，用于实时重放从生产到阶段/开发环境的流量.
* [hugo](http://gohugo.io/) -快速和现代的静态网站引擎.
* [ide](https://github.com/thestrukture/ide)  -浏览器可访问的IDE.  专为Go而设计.
* [ipe](https://github.com/dimiro1/ipe) -与GO编写的Pusher客户端库兼容的开源Pusher服务器实现.
* [joincap](https://github.com/assafmo/joincap) -用于将多个pcap文件合并在一起的命令行实用程序.
* [Juju](https://jujucharms.com/) -与云无关的服务部署和编排-支持EC2，Azure，Openstack，MAAS等.
* [Leaps](https://github.com/jeffail/leaps) -使用操作转换对编程服务进行配对.
* [lgo](https://github.com/yunabe/lgo)  -使用Jupyter进行交互式Go编程.  它支持代码完成，代码检查和100％Go兼容性.
* [limetext](http://limetext.org/) -Lime Text是一款功能强大且优雅的文本编辑器，主要是在Go中开发的，旨在成为Sublime Text的免费开源软件继任者.
* [LiteIDE](https://github.com/visualfc/liteide) -LiteIDE是一个简单的，开源的，跨平台的Go IDE.
* [mockingjay](https://github.com/quii/mockingjay-server)  -从一个配置文件中伪造HTTP服务器和消费者驱动的合同.  您还可以随机使服务器行为不当，以帮助进行更实际的性能测试.
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* [naclpipe](https://github.com/unix4fun/naclpipe) -用Go语言编写的基于NaCL EC25519的简单加密管道工具.
* [nes](https://github.com/fogleman/nes) -用Go编写的Nintendo Entertainment System（NES）模拟器.
* [orange-cat](https://github.com/noraesae/orange-cat) -用Go编写的Markdown预览器.
* [Orbit](https://github.com/gulien/orbit) -用于运行命令并从模板生成文件的简单工具.
* [peg](https://github.com/pointlander/peg) -Peg，解析表达式语法，是Packrat解析器生成器的实现.
* [restic](https://github.com/restic/restic) -对备份程序进行重复数据删除.
* [scc](https://github.com/boyter/scc) -Sloc Cloc and Code，一个非常快速的准确代码计数器，具有复杂度计算和COCOMO估计.
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) -具有O（1）磁盘查找的快速，简单和可扩展的分布式文件系统.
* [shell2http](https://github.com/msoap/shell2http) -通过http服务器执行shell命令（用于原型制作或远程控制）.
* [snap](https://github.com/intelsdi-x/snap) -强大的遥测框架.
* [Snitch](https://github.com/lucasgomide/snitch) -当有人通过Tsuru部署任何应用程序时，通知您的团队和许多工具的简单方法.
* [Stack Up](https://github.com/pressly/sup) -Stack Up，一个非常简单的部署工具-仅限于Unix-将其视为服务器网络的“ make”.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [term-quiz](https://github.com/crazcalm/term-quiz) -为您的终端进行测验.
* [toxiproxy](https://github.com/shopify/toxiproxy) -代理以模拟网络和系统条件以进行自动化测试.
* [tsuru](https://tsuru.io/) -可扩展的开源平台即服务软件.
* [vFlow](https://github.com/VerizonDigital/vflow) -高性能，可扩展且可靠的IPFIX，sFlow和Netflow收集器.
* [wellington](https://github.com/wellington/wellington) -Sass项目管理工具，通过Sprite函数（如Compass）扩展了语言.

## Resources

*在哪里发现新的Go库.

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) -比较不同Go版本之间性能的框架.
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app)  -强大的HTTP基准测试工具与Аb，Wrk，Siege工具混合使用.  为基准和比较结果收集统计数据和各种参数.
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks)  -很少有其他Go微基准测试.  将某些语言功能与替代方法进行比较.
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) -进行HTTP请求路由器基准测试和比较.
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) -转到Web框架基准测试.
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) -Go序列化方法的基准.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) -Go语言常用基本操作的基准.
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) -收集流行的Go数据库/ SQL实用程序的基准.
* [gospeed](https://github.com/feyeleanor/GoSpeed) -使用微基准来计算语言构造的速度.
* [kvbench](https://github.com/jimrobinson/kvbench) -键/值数据库基准.
* [skynet](https://github.com/atemerev/skynet) -天网1M线程微基准测试.
* [speedtest-resize](https://github.com/fawick/speedtest-resize) -比较Go语言的各种图像调整大小算法.

## Conferences

* [Capital Go](http://www.capitalgolang.com) -美国华盛顿特区.
* [dotGo](http://www.dotgo.eu) -法国巴黎.
* [GoCon](http://gocon.connpass.com/) -日本东京.
* [GoDays](https://www.godays.io/) - 柏林，德国.
* [GoLab](http://golab.io/) -意大利佛罗伦萨.
* [GolangUK](http://golanguk.com/) -英国伦敦.
* [GopherChina](http://gopherchina.org) - 上海，中国.
* [GopherCon](http://www.gophercon.com/) -美国丹佛.
* [GopherCon Australia](https://gophercon.com.au/) - 悉尼，澳大利亚.
* [GopherCon Brazil](https://gopherconbr.org) -弗洛里亚诺波利斯（BR）
* [GopherCon Europe](https://gophercon.is/) - 柏林，德国.
* [GopherCon India](https://www.gophercon.in/) -印度浦那.
* [GopherCon Israel](https://www.gophercon.org.il/) -以色列特拉维夫.
* [GopherCon Russia](https://www.gophercon-russia.ru) -俄罗斯莫斯科.
* [GopherCon Singapore](https://gophercon.sg) -新加坡丰树商业城.
* [GopherCon Vietnam](https://gophercon.vn/) -越南胡志明市.
* [GothamGo](http://gothamgo.com/) -美国纽约.
* [GoWayFest](https://goway.io/) -白俄罗斯明斯克.

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) -着重于Go语法/语义和各种细节的书.
* [Go Bootcamp](http://golangbootcamp.com)
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) -波斯语
* [GoBooks](https://github.com/dariubs/GoBooks) -精选的Go图书清单.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) -玛丽亚·莱塔（Maria Letta）的Gopher图形包，包括插图和矢量和光栅中的情感人物.
* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) -Gopher矢量数据[.ai，.svg].
* [gopher-logos](https://github.com/GolangUA/gopher-logos) -可爱的地鼠徽标.
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector](https://github.com/golang-samples/gopher-vector)
* [gophericons](https://github.com/shalakhin/gophericons)
* [gopherize.me](https://github.com/matryer/gopherize.me) -善待自己.
* [gophers](https://github.com/ashleymcnamara/gophers) -Ashley McNamara创作的Gopher艺术品.
* [gophers](https://github.com/egonelbre/gophers) -免费的地鼠.
* [gophers](https://github.com/rogeralsing/gophers) -随机地鼠图形.
* [gophers](https://github.com/sillecelik/go-gopher) -Gopher amigurumi玩具图案.

## Meetups

* [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
* [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Canberra Gophers](https://www.meetup.com/Canberra-Gophers/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBandung](https://www.meetup.com/GoBandung/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Estonia](https://www.meetup.com/Golang-Estonia/)
* [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Казань](https://www.meetup.com/GolangKazan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*在此处添加您所在城市/国家/地区的组（发送** PR **）*

## Social Media
### Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

### Reddit
 * [r/golang](https://www.reddit.com/r/golang/)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) -您的Go Go工具箱.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job)  -精选的很棒的远程工作列表.  他们中的许多人正在寻找Go黑客.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) -其他令人赞叹的列表.
* [CodinGame](https://www.codingame.com/) -通过使用小游戏作为实际示例解决交互式任务来学习围棋.
* [Go Blog](http://blog.golang.org) -官方的Go博客.
* [Go Challenge](http://golang-challenge.org/) -通过解决问题并获得围棋专家的反馈来学习围棋.
* [Go Community on Hashnode](https://hashnode.com/n/go) -Hashnode上的Gophers社区.
* [Go Forum](https://forum.golangbridge.org) -论坛讨论Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) -5分钟的截屏视频专注于完成一件事情.
* [Go Projects](https://github.com/golang/go/wiki/Projects) -Go社区Wiki上的项目列表.
* [Go Report Card](https://goreportcard.com) -Go包裹的报告卡.
* [go.dev](https://go.dev/) -Go开发人员的中心.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp)  -需要帮助的Go项目集合.  在Go中开始您的开源方式的好地方.
* [godoc.org](https://godoc.org/) -开源Go软件包的文档.
* [Golang Developer Jobs](https://golangjob.xyz) -独家担任Golang相关角色的开发人员职位.
* [Golang Flow](https://golangflow.io) -发布更新，新闻，软件包等.
* [Golang News](https://golangnews.com) -有关Go编程的链接和新闻.
* [golang-graphics](https://github.com/mholt/golang-graphics) -收集Go图片，图形和艺术品.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) -转到邮件列表.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) -加入我们新的Gophers松弛社区（[Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [Gophercises](https://gophercises.com/) -萌芽地鼠的免费编码练习.
* [gowalker.org](https://gowalker.org) -转到Project API文档.
* [json2go](https://m-zajac.github.io/json2go) -高级JSON到Go结构转换-在线工具.
* [justforfunc](https://www.youtube.com/c/justforfunc) -由Francesc Campoy主持的专门介绍Go编程语言技巧的YouTube频道 [@francesc](https://twitter.com/francesc).
* [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
* [r/Golang](https://www.reddit.com/r/golang) -有关Go的新闻.
* [studygolang](https://studygolang.com) -中国的studygolang社区.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) -查找新的Go库的好地方.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) -新Golang开发人员的陷阱，陷阱和常见错误.
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) -建立Golang电子商务网站（包含示范）.
* [A Tour of Go](http://tour.golang.org/) -围棋互动之旅.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) -Golang电子书简介，介绍如何使用Golang构建网络应用.
* [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) -我们将在功能强大的Gorilla Mux的帮助下编写一个API.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) -熟悉Gin并了解它如何帮助您减少样板代码并建立请求处理管道.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) -如何缓存慢速数据库查询.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) -如何取消MySQL查询.
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) -有关使用Go进行以太坊开发的电子书.
* [Games With Go](http://gameswithgo.org/) -视频系列教学编程和游戏开发.
* [Go By Example](https://gobyexample.com/) -使用带注释的示例程序动手介绍Go.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) -Go的参考卡.
* [Go database/sql tutorial](http://go-database-sql.org/) -数据库/ sql简介.
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) -在您的移动设备上交互式地编辑和播放Go片段.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [go-patterns](https://github.com/tmrts/go-patterns) -Go设计模式，配方和惯用语的精选清单.
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) -Golang与Node.js进行比较的示例.
* [Golangbot](https://golangbot.com/learn-golang-series/) -开始使用Go进行编程的教程.
* [GolangCode](https://golangcode.com/) -收集代码段和教程，以帮助解决日常问题.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) -从golang编程社区提交和投票的最佳在线golang教程中学习Go.
* [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) -了解如何使用Docker进行Go开发以及如何构建生产Docker映像.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) -Godog入门-一种由行为驱动的开发框架，用于构建和测试Go应用程序.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) -通过测试驱动的开发学习Go.
* [Learning Golang - From zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/) -初学者使用golang入门.
* [package main](https://www.youtube.com/packagemain) -有关Go中编程的YouTube频道.
* [Programming with Google Go](https://www.coursera.org/specializations/google-golang) -Coursera专业化知识，从头开始学习Go.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Working with Go](https://github.com/mkaz/working-with-go) -面向经验丰富的程序员的介绍.
* [Your basic Go](http://yourbasic.org/golang) -大量的教程和操作方法.
