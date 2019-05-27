<div class="github-widget" data-repo="avelino/awesome-go"></div>
## Awesome Go

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)]（https://www.patreon.com/avelinosource）对Awesome Go的财务支持

 精选的Go框架，库和软件的精选列表.  灵感来自 [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

请快速了解一下 [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md)  第一.  谢谢大家 [contributors](https://github.com/avelino/awesome-go/graphs/contributors) ;  你摇滚！

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*






## Audio and Music

*用于操纵音频的库.*

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) -  EasyMidi是一个简单可靠的库，用于处理标准midi文件（SMF）.
* [flac](https://github.com/eaburns/flac) - 简洁的原生Go FLAC解码器，可将FLAC文件解码为字节片.
* [flac](https://github.com/mewkiz/flac) -  Native Go FLAC编码器/解码器，支持FLAC流.
* [gaad](https://github.com/Comcast/gaad) -  Native Go AAC比特流解析器.
* [go-sox](https://github.com/krig/go-sox) - 用于go的libsox绑定.
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - 用于go的libmediainfo绑定.
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - 用于go的libsamplerate绑定.
* [id3v2](https://github.com/bogem/id3v2) -  Go的快速稳定的ID3解析和编写库.
* [malgo](https://github.com/gen2brain/malgo) - 迷你音频库.
* [minimp3](https://github.com/tosone/minimp3) - 轻量级MP3解码器库.
* [mix](https://github.com/go-mix/mix) - 用于音乐应用程序的基于序列的Go-native音频混音器.
* [mp3](https://github.com/tcolgate/mp3) -  Native Go MP3解码器.
* [music-theory](https://github.com/go-music-theory/music-theory) -  Go中的音乐理论模型.
* [Oto](https://github.com/hajimehoshi/oto) - 在多个平台上播放声音的低级库.
* [PortAudio](https://github.com/gordonklaus/portaudio) - 转到PortAudio音频I / O库的绑定.
* [portmidi](https://github.com/rakyll/portmidi) - 为PortMidi绑定绑定.
* [taglib](https://github.com/wtolson/go-taglib) - 为taglib绑定绑定.
* [vorbis](https://github.com/mccoyst/vorbis) - “Native”Go Vorbis解码器（使用CGO，但没有依赖关系）.
* [waveform](https://github.com/mdlayher/waveform) -  Go包能够从音频流生成波形图像.

## Authentication and OAuth

*用于实施认证计划的图书馆.*

* [authboss](https://github.com/volatiletech/authboss)   - 用于Web的模块化身份验证系统.  它试图删除尽可能多的样板和“硬件”，以便每次在Go中启动新的Web项目时，您都可以插入，配置和开始构建应用程序，而无需每次都构建一个身份验证系统.
* [branca](https://github.com/hako/branca) -  Golang实施布兰卡令牌.
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - 提供cookies.txt文件格式的解析器.
* [go-jose](https://github.com/square/go-jose) - 相当完整地实施JOSE工作组的JSON Web令牌，JSON Web签名和JSON Web加密规范.
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang.
* [gologin](https://github.com/dghubble/gologin) - 用于使用OAuth1和OAuth2身份验证提供程序登录的可链接处理程序.
* [gorbac](https://github.com/mikespook/gorbac) - 在Golang中提供基于角色的轻量级访问控制（RBAC）实现.
* [goth](https://github.com/markbates/goth)   - 提供使用OAuth和OAuth2的简单，干净和惯用的方法.  开箱即用处理多个提供商.
* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware.
* [jwt](https://github.com/robbert229/jwt) - 清洁且易于使用的JSON Web令牌（JWT）实现.
* [jwt](https://github.com/pascaldekloe/jwt) - 轻量级JSON Web令牌（JWT）库.
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - 用于Golang http服务器的JWT中间件，具有许多配置选项.
* [jwt-go](https://github.com/dgrijalva/jwt-go) -  Golang实现JSON网络令牌（JWT）的.
* [loginsrv](https://github.com/tarent/loginsrv) - 具有可插拔后端的JWT登录微服务，如OAuth2（Github），htpasswd，osiam.
* [oauth2](https://github.com/golang/oauth2)   -  goauth2的继承者.  JWT，Google API，计算引擎和App Engine支持附带的通用OAuth 2.0软件包.
* [osin](https://github.com/openshift/osin) -  Golang了OAuth2服务器库.
* [paseto](https://github.com/o1egl/paseto) -  Golang实现平台不可知安全性令牌（PASETO）.
* [permissions2](https://github.com/xyproto/permissions2)   - 用于跟踪用户，登录状态和权限的库.  使用安全cookie和bcrypt.
* [rbac](https://github.com/zpatrick/rbac) -  Go应用程序的简约RBAC包.
* [securecookie](https://github.com/chmike/securecookie) - 高效的安全cookie编码/解码.
* [session](https://github.com/icza/session) - 进行Web服务器的会话管理（包括对Google App Engine的支持 -  GAE）.
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - 使用SessionGate Redis模块进行会话管理.
* [sessions](https://github.com/adam-hanna/sessions) - 用于go http服务器的简单，高性能，高度可定制的会话服务.
* [signedvalue](https://github.com/sashka/signedvalue) - 与...兼容的带符号和带时间戳的字符串 [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`，`decode_signed_value`，因此`set_secure_cookie`和`get_secure_cookie`.

## Bot Building

*用于建造和使用机器人的图书馆.*

* [go-chat-bot](https://github.com/go-chat-bot/bot) - 用Go编写的IRC，Slack和Telegram机器人.
* [go-sarah](https://github.com/oklahomer/go-sarah) - 为期望的聊天服务构建机器人的框架，包括LINE，Slack，Gitter等.
* [go-tgbot](https://github.com/olebedev/go-tgbot) -  Pure Golang Telegram Bot API包装器，由swagger文件，基于会话的路由器和中间件生成.
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - 用于加密货币交换的基于控制台的交易机器人的golang实现.
* [govkbot](https://github.com/nikepan/govkbot) - 简单的去 [VK](https://vk.com) 机器人库.
* [hanu](https://github.com/sbstjn/hanu) - 编写Slack机器人的框架.
* [Kelp](https://github.com/stellar/kelp) - 官方交易和市场制造机器人 [Stellar](https://www.stellar.org/)  DEX.  开箱即用，用Golang编写，兼容集中交换和自定义交易策略.
* [margelet](https://github.com/zhulik/margelet) - 构建电报机器人的框架.
* [micha](https://github.com/onrik/micha) -  Go Library for Telegram bot api.
* [slacker](https://github.com/shomali11/slacker) - 易于使用的框架来创建Slack机器人.
* [tbot](https://github.com/yanzay/tbot) - 具有类似于net / http的API的Telegram bot服务器.
* [telebot](https://github.com/tucnak/telebot) - 用Go编写的Telegram bot框架.
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - 简单而干净的Telegram bot客户端.
* [Tenyks](https://github.com/kyleterry/tenyks) - 使用Redis和JSON进行消息传递的面向服务的IRC bot.

## Command Line

### Standard CLI

*用于构建标准或基本命令行应用程序的库.*

* [argparse](https://github.com/akamensky/argparse) - 受Python的argparse模块启发的命令行参数解析器.
* [argv](https://github.com/cosiner/argv) - 使用bash语法将库分割为命令行字符串作为参数数组.
* [cli](https://github.com/mkideal/cli) - 基于golang结构标记的功能丰富且易于使用的命令行包.
* [cli](https://github.com/teris-io/cli) - 用于在Go中构建命令行界面的简单而完整的API.
* [cli-init](https://github.com/tcnksm/gcli) - 开始构建Golang命令行应用程序的简便方法.
* [climax](http://github.com/tucnak/climax) - 以Go命令的精神，用“人脸”替代CLI.
* [cobra](https://github.com/spf13/cobra) - 现代Go CLI交互的指挥官.
* [commandeer](https://github.com/jaffee/commandeer) - 开发友好的CLI应用程序：根据结构字段和标记设置标志，默认值和用法.
* [complete](https://github.com/posener/complete) - 在Go + Go命令bash完成中写入bash完成.
* [docopt.go](https://github.com/docopt/docopt.go) - 命令行参数解析器，会让你微笑.
* [env](https://github.com/codingconcepts/env) - 结构的基于标记的环境配置.
* [flag](https://github.com/cosiner/flag) -  Go支持子命令的简单但功能强大的命令行选项解析库.
* [flaggy](https://github.com/integrii/flaggy) - 一个强大的惯用标志包，具有出色的子命令支持.
* [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
* [go-arg](https://github.com/alexflint/go-arg) -  Go中基于struct的参数解析.
* [go-commander](https://github.com/yitsushi/go-commander) - 使用库来简化CLI工作流程.
* [go-flags](https://github.com/jessevdk/go-flags) -  go命令行选项解析器.
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) -  Go选项解析器的灵感来自于Perl的GetOpt :: Long的灵活性.
* [gocmd](https://github.com/devfacet/gocmd) -  Go库用于构建命令行应用程序.
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - 具有自动配置和依赖注入的cli应用程序框架.
* [job](https://github.com/liujianping/job) -  JOB，让你的短期指挥作为一项长期工作.
* [kingpin](https://github.com/alecthomas/kingpin) - 支持子命令的命令行和标志解析器.
* [liner](https://github.com/peterh/liner) - 为命令行界面使用类似readline的库.
* [mitchellh/cli](https://github.com/mitchellh/cli) -  Go库用于实现命令行界面.
* [mow.cli](https://github.com/jawher/mow.cli) - 使用复杂的标志和参数解析和验证来构建用于构建CLI应用程序的库.
* [pflag](https://github.com/spf13/pflag) - 直接替换Go的标志包，实现POSIX / GNU样式 - 标志.
* [readline](https://github.com/chzyer/readline) - 纯粹的golang实现，在MIT许可下提供GNU-Readline中的大多数功能.
* [sand](https://github.com/Zaba505/sand) - 用于创建解释器的简单API等等.
* [sflags](https://github.com/octago/sflags) - 用于flag，urfave / cli，pflag，cobra，kingpin和其他库的基于struct的标志生成器.
* [strumt](https://github.com/antham/strumt) - 库创建提示链.
* [ukautz/clif](https://github.com/ukautz/clif) - 小命令行界面框架.
* [urfave/cli](https://github.com/urfave/cli) - 用于在Go（以前的codegangsta / cli）中构建命令行应用程序的简单，快速和有趣的包.
* [wlog](https://github.com/dixonwille/wlog) - 简单的日志记录界面，支持跨平台的颜色和并发性.
* [wmenu](https://github.com/dixonwille/wmenu) - 易于使用的cli应用程序菜单结构，提示用户做出选择.

### Advanced Console UIs

*用于构建控制台应用程序和控制台用户界面的库.*

* [asciigraph](https://github.com/guptarohit/asciigraph) - 在没有其他依赖关系的命令行应用程序中使用包来制作轻量级ASCII线图..
* [aurora](https://github.com/logrusorgru/aurora) - 支持fmt.Printf / Sprintf的ANSI终端颜色.
* [cfmt](https://github.com/mingrammer/cfmt) - 受bootstrap颜色类启发的上下文fmt.
* [chalk](https://github.com/ttacon/chalk) - 用于美化终端/控制台输出的直观包装.
* [color](https://github.com/fatih/color) - 用于彩色终端输出的多功能包装.
* [colourize](https://github.com/TreyBastian/colourize) - 在终端中使用ANSI颜色文本库.
* [ctc](https://github.com/wzshiming/ctc) - 非侵入式跨平台终端颜色库不需要修改Print方法.
* [go-ataman](https://github.com/workanator/go-ataman) -  Go库，用于在终端中呈现ANSI彩色文本模板.
* [go-colorable](https://github.com/mattn/go-colorable) -  Windows的着名作家.
* [go-colortext](https://github.com/daviddengcn/go-colortext) - 转到终端的彩色输出库.
* [go-isatty](https://github.com/mattn/go-isatty) -  isatty为golang.
* [go-prompt](https://github.com/c-bata/go-prompt) - 用于构建强大的交互式提示的库，受到启发 [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
* [gocui](https://github.com/jroimartin/gocui) -  Minimalist Go库旨在创建控制台用户界面.
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - 样式终端文本.
* [gookit/color](https://github.com/gookit/color) - 终端颜色渲染工具库，支持16种颜色，256种颜色，RGB颜色渲染输出，兼容Windows.
* [mpb](https://github.com/vbauerster/mpb) - 终端应用程序的多进度条.
* [progressbar](https://github.com/schollz/progressbar) - 适用于每个操作系统的基本线程安全进度条.
* [simpletable](https://github.com/alexeyco/simpletable) - 带Go的终端中的简单表格.
* [tabby](https://github.com/cheynewallace/tabby) - 一个用于超级简单Golang表的小型库.
* [tabular](https://github.com/InVisionApp/tabular) - 从命令行实用程序打印ASCII表，而无需将大量数据传递给API.
* [termbox-go](https://github.com/nsf/termbox-go) -  Termbox是一个用于创建跨平台基于文本的界面的库.
* [termdash](https://github.com/mum4k/termdash) - 基于** termbox-go **的终端仪表板，并受到启发 [termui](https://github.com/gizak/termui).
* [termtables](https://github.com/apcera/termtables) - 去Ruby库的端口 [terminal-tables](https://github.com/tj/terminal-table) 用于简单的ASCII表生成以及提供markdown和HTML输出.
* [termui](https://github.com/gizak/termui) - 基于** termbox-go **的终端仪表板，并受到启发 [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* [uilive](https://github.com/gosuri/uilive) - 用于实时更新终端输出的库.
* [uiprogress](https://github.com/gosuri/uiprogress) - 灵活的库，用于在终端应用程序中渲染进度条.
* [uitable](https://github.com/gosuri/uitable) - 使用表格数据提高终端应用程序可读性的库.

## Configuration

*用于配置解析的库.*

* [config](https://github.com/JeremyLoy/config)   - 云原生应用程序配置.  将ENV绑定到只有两行的结构.
* [config](https://github.com/olebedev/config) - 带有环境变量和标志解析的JSON或YAML配置包装器.
* [configure](https://github.com/paked/configure) - 通过多个源提供配置，包括JSON，标志和环境变量.
* [confita](https://github.com/heetch/confita) - 从多个后端级联加载到结构中的配置.
* [conflate](https://github.com/the4thamigo-uk/conflate) - 库/工具，用于合并来自任意URL的多个JSON / YAML / TOML文件，针对JSON模式进行验证，以及应用模式中定义的默认值.
* [env](https://github.com/caarlos0/env) - 将环境变量解析为Go结构（使用默认值）.
* [envcfg](https://github.com/tomazk/envcfg) - 将编组环境变量解组为Go结构.
* [envconf](https://github.com/ian-kent/envconf) - 从环境配置.
* [envconfig](https://github.com/vrischmann/envconfig) - 从环境变量中读取配置.
* [envh](https://github.com/antham/envh) - 帮助管理环境变量.
* [gcfg](https://github.com/go-gcfg/gcfg)   - 将INI样式的配置文件读入Go结构;  支持用户定义的类型和子部分.
* [go-up](https://github.com/ufoscout/go-up) - 一个简单的配置库，具有递归占位符分辨率，没有魔法.
* [goConfig](https://github.com/crgimenes/goConfig) - 解析结构作为输入，并使用命令行，环境变量和配置文件中的参数填充此结构的字段.
* [godotenv](https://github.com/joho/godotenv) - 去Ruby的dotenv库的端口（从`.env`加载环境变量）.
* [gofigure](https://github.com/ian-kent/gofigure) - 轻松完成应用程序配置.
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf)   - 模块化JSON配置.  保持配置结构及其配置的代码，并将解析委托给子模块，而不会牺牲完整的配置序列化.
* [gookit/config](https://github.com/gookit/config)   - 应用程序配置管理（加载，获取，设置）.  支持JSON，YAML，TOML，INI，HCL.  多文件加载，数据覆盖合并.
* [hjson](https://github.com/hjson/hjson-go)   -  Human JSON，一种用于人类的配置文件格式.  轻松的语法，更少的错误，更多的评论.
* [ingo](https://github.com/schachmat/ingo) - 标志持久存在于类似ini的配置文件中.
* [ini](https://github.com/go-ini/ini) - 去包读取和写入INI文件.
* [joshbetz/config](https://github.com/joshbetz/config) -  Go的小型配置库，用于解析环境变量，JSON文件以及在SIGHUP上自动重新加载.
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) -  Go库，用于管理环境变量的配置数据.
* [mini](https://github.com/sasbury/mini) -  Golang包解析这种风格的配置文件.
* [sprbox](https://github.com/oblq/sprbox) - 构建环境感知的工具箱工厂和不可知的配置解析器（YAML，TOML，JSON和环境变量）.
* [store](https://github.com/tucnak/store) -  Go的轻量级配置管理器.
* [viper](https://github.com/spf13/viper) - 用f牙进行配置.
* [xdg](https://github.com/OpenPeeDeeP/xdg) - 遵循的跨平台包 [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## Continuous Integration

*帮助持续集成的工具.*

* [drone](https://github.com/drone/drone) -  Drone是一个基于Docker的持续集成平台，用Go编写.
* [duci](https://github.com/duck8823/duci) - 简单的ci服务器不需要特定于域的语言.
* [gomason](https://github.com/nikogura/gomason) - 从干净的工作区测试，构建，签名和发布您的二进制文件.
* [goveralls](https://github.com/mattn/goveralls) - 集成Coveralls.io连续代码覆盖跟踪系统.
* [overalls](https://github.com/go-playground/overalls) - 多包装去项目封面文件，用于像goveralls这样的工具.
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - 递归覆盖测试工具.

## CSS Preprocessors

*用于预处理CSS文件的库.*

* [gcss](https://github.com/yosssi/gcss) -  Pure Go CSS预处理器.
* [go-libsass](https://github.com/wellington/go-libsass) - 将包装器转到100％Sass兼容的libsass项目.

## Data Structures

* Go中的通用数据结构和算法.*
* [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
* [binpacker](https://github.com/zhuangsirui/binpacker) - 二进制打包程序和解包程序可帮助用户构建自定义二进制流.
* [bit](https://github.com/yourbasic/bit) -  Golang设置数据结构，具有奖励比特功能.
* [bitset](https://github.com/willf/bitset) -  Go包实现bitsets.
* [bloom](https://github.com/zhenjl/bloom) -  Go中实现的Bloom过滤器.
* [bloom](https://github.com/yourbasic/bloom) -  Golang布隆过滤器实现.
* [boomfilters](https://github.com/tylertreat/BoomFilters) - 用于处理连续，无界流的概率数据结构.
* [concurrent-writer](https://github.com/free/concurrent-writer) - 高度并发替换`bufio.Writer`.
* [conjungo](https://github.com/InVisionApp/conjungo) - 一个小巧，强大且灵活的合并库.
* [count-min-log](https://github.com/seiflotfy/count-min-log) -  Go实现Count-Min-Log草图：使用近似计数器近似计数（如Count-Min草图，但使用较少的内存）.
* [crunch](https://github.com/superwhiskers/crunch) -  Go包实现缓冲区，可以轻松处理各种数据类型.
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - 布谷鸟过滤器：Go中实现的计数布隆过滤器的一个很好的替代品.
* [deque](https://github.com/edwingeng/deque) - 高度优化的双端队列.
* [deque](https://github.com/gammazero/deque) - 快速环缓冲双端队列（双端队列）.
* [dict](https://github.com/srfrog/dict) -  Go的类似Python的词典（dict）.
* [encoding](https://github.com/zhenjl/encoding) -  Go的整数压缩库.
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - 实现自适应基数树.
* [go-datastructures](https://github.com/Workiva/go-datastructures) - 收集有用，高性能和线程安全的数据结构.
* [go-ef](https://github.com/amallia/go-ef) -  Elias-Fano编码的Go实现.
* [go-geoindex](https://github.com/hailocab/go-geoindex) - 内存中的地理索引.
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache)   - 快速内存中的密钥：值存储/缓存库.  指针缓存.
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - 具有有效点位置和邻域发现的区域四叉树.
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - 并发FIFO队列.
* [gods](https://github.com/emirpasic/gods)   - 转到数据结构.  容器，集合，列表，堆栈，地图，BidiMaps，树，HashSet等.
* [golang-set](https://github.com/deckarep/golang-set) -  Go的线程安全和非线程安全高性能集.
* [goset](https://github.com/zoumo/goset) -  Go的一个有用的Set集合实现.
* [goskiplist](https://github.com/ryszard/goskiplist) -  Go中的跳过列表实现.
* [gota](https://github.com/kniren/gota) - 为Go实现数据帧，系列和数据争用方法.
* [hide](https://github.com/emvi/hide) - 具有到/来自散列的编组的ID类型，以防止向客户端发送ID.
* [hilbert](https://github.com/google/hilbert) -  Go包用于在空间填充曲线上映射值，例如Hilbert和Peano曲线.
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - 具有稀疏，LogLog-Beta偏差校正和TailCut空间缩减的HyperLogLog实现.
* [levenshtein](https://github.com/agext/levenshtein) -  Levenshtein距离和相似性指标，具有可自定义的编辑成本和类似Winkler的共同前缀奖金.
* [levenshtein](https://github.com/agnivade/levenshtein) - 在Go中计算levenshtein距离的实现.
* [mafsa](https://github.com/smartystreets/mafsa) - 使用最小完美散列的MA-FSA实现.
* [mspm](https://github.com/BlackRabbitt/mspm) - 用于信息检索的多字符串模式匹配算法.
* [null](https://github.com/emvi/null) - 可以对JSON进行编组/解组的Nullable Go类型.
* [parsefields](https://github.com/MonaxGT/parsefields) - 用于解析类似JSON的日志以收集唯一字段和事件的工具.
* [pipeline](https://github.com/hyfather/pipeline) - 具有扇入和扇出的管道的实现.
* [ring](https://github.com/TheTannerRyan/ring) - 实现高性能，线程安全的布隆过滤器.
* [roaring](https://github.com/RoaringBitmap/roaring) -  Go包实现压缩位集.
* [set](https://github.com/StudioSol/set) - 使用LinkedHashMap在Go中简单设置数据结构.
* [skiplist](https://github.com/MauriceGit/skiplist) - 非常快的Go Skiplist实施.
* [skiplist](https://github.com/gansidui/skiplist) -  Go中的Skiplist实现.
* [timedmap](https://github.com/zekroTJA/timedmap) - 使用过期键值对映射.
* [treap](https://github.com/perdata/treap) - 使用树堆的持久，快速排序的地图.
* [trie](https://github.com/derekparker/trie) - 在Go中实现Trie.
* [ttlcache](https://github.com/diegobernardes/ttlcache) - 内存LRU字符串接口{}映射，其中golang过期.
* [typ](https://github.com/gurukami/typ) - 空类型，安全基元类型转换和复杂结构的取值.
* [willf/bloom](https://github.com/willf/bloom) -  Go包实现Bloom过滤器.

## Database

* Go中实施的数据库*

* [badger](https://github.com/dgraph-io/badger) -  Go中的快速键值存储.
* [bcache](https://github.com/iwanbk/bcache) - 最终一致的分布式内存缓存Go库.
* [BigCache](https://github.com/allegro/bigcache) - 千兆字节数据的高效键/值缓存.
* [bolt](https://github.com/boltdb/bolt) -  Go的低级键/值数据库.
* [buntdb](https://github.com/tidwall/buntdb) -  Go的快速，可嵌入，内存中键/值数据库，具有自定义索引和空间支持.
* [cache](https://github.com/akyoto/cache) - 内存中密钥：具有到期时间的值存储，0依赖性，&lt;100 LoC，100％覆盖率.
* [cache2go](https://github.com/muesli/cache2go) - 内存中密钥：值缓存，支持基于超时的自动失效.
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - 具有群集支持和单个项目到期的BigCache.
* [cockroach](https://github.com/cockroachdb/cockroach) - 可扩展，地理复制，事务数据存储.
* [couchcache](https://github.com/codingsince1985/couchcache) - 由Couchbase服务器支持的RESTful缓存微服务.
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) -  CovenantSQL是区块链上的SQL数据库.
* [dgraph](https://github.com/dgraph-io/dgraph) - 可扩展，分布式，低延迟，高吞吐量图数据库.
* [diskv](https://github.com/peterbourgon/diskv) - 本土磁盘支持的键值存储.
* [eliasdb](https://github.com/krotik/eliasdb) - 具有REST API，短语搜索和类似SQL的查询语言的无依赖关系的事务图数据库.
* [fastcache](https://github.com/VictoriaMetrics/fastcache)   - 针对大量条目的快速线程安全内存缓存.  最大限度地减少GC开销.
* [GCache](https://github.com/bluele/gcache) - 缓存库，支持可过期的Cache，LFU，LRU和ARC.
* [go-cache](https://github.com/pmylund/go-cache) - 内存中密钥：Go的值存储/缓存（类似于Memcached）库，适用于单机应用程序.
* [goleveldb](https://github.com/syndtr/goleveldb) - 实施 [LevelDB](https://github.com/google/leveldb) Go中的键/值数据库.
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) -  Gorocksdb是一个包装 [RocksDB](https://rocksdb.org) 写在Go.
* [groupcache](https://github.com/golang/groupcache) -  Groupcache是​​一个缓存和缓存填充库，在许多情况下用作memcached的替代品.
* [influxdb](https://github.com/influxdb/influxdb) - 用于指标，事件和实时分析的可扩展数据存储.
* [ledisdb](https://github.com/siddontang/ledisdb) -  Ledisdb是一款基于LevelDB的高性能NoSQL，如Redis.
* [levigo](https://github.com/jmhodges/levigo) -  Levigo是LevelDB的Go包装器.
* [moss](https://github.com/couchbase/moss) -  Moss是一个简单的LSM键值存储引擎，用100％Go编写.
* [nutsdb](https://github.com/xujiajun/nutsdb)   -  Nutsdb是一个用纯Go编写的简单，快速，可嵌入，持久的键/值存储.  它支持完全可序列化的事务和许多数据结构，如列表，集合，排序集.
* [piladb](https://github.com/fern4lvarez/piladb) - 基于堆栈数据结构的轻量级RESTful数据库引擎.
* [prometheus](https://github.com/prometheus/prometheus) - 监控系统和时间序列数据库.
* [pudge](https://github.com/recoilme/pudge) - 使用Go标准库编写的快速简单的键/值存储.
* [rqlite](https://github.com/rqlite/rqlite) - 基于SQLite构建的轻量级分布式关系数据库.
* [Scribble](https://github.com/nanobox-io/golang-scribble) - 微小的平面文件JSON商店.
* [slowpoke](https://github.com/recoilme/slowpoke) - 具有持久性的键值存储.
* [tempdb](https://github.com/rafaeljesus/tempdb) - 临时物品的钥匙价值商店.
* [tidb](https://github.com/pingcap/tidb)   -  TiDB是一个分布式SQL数据库.  灵感来自Google F1的设计.
* [tiedot](https://github.com/HouzuoGuo/tiedot) - 由Golang提供支持的NoSQL数据库.
* [Vasto](https://github.com/chrislusf/vasto)   - 分布式高性能键值存储.  在磁盘上.  最终一致.  哈.  能够在没有服务中断的情况下成长或缩小.

*数据库模式迁移.*

* [avro](https://github.com/khezen/avro)   - 发现SQL模式并将其转换为AVRO模式.  将SQL记录查询为AVRO字节.
* [darwin](https://github.com/GuiaBolso/darwin) -  Go的数据库模式演化库.
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - 用于Golang优秀的内置数据库/ sql库的Django风格装置.
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) -  Go包用go-pg / pg帮助编写迁移.
* [gondolier](https://github.com/emvi/gondolier) - 使用struct decorators的数据库迁移库.
* [goose](https://github.com/steinbacher/goose)   - 数据库迁移工具.  您可以通过创建增量SQL或Go脚本来管理数据库的演变.
* [gormigrate](https://github.com/go-gormigrate/gormigrate) -  Gorm ORM的数据库模式迁移帮助程序.
* [migrate](https://github.com/golang-migrate/migrate)   - 数据库迁移.  CLI和Golang库.
* [pravasan](https://github.com/pravasan/pravasan) - 简单迁移工具 - 目前用于MySQL，但计划很快支持Postgres，SQLite，MongoDB等.
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) -  MySQL，PostgreSQL和SQLite的数据库迁移，创建，ORM等.
* [sql-migrate](https://github.com/rubenv/sql-migrate)   - 数据库迁移工具.  允许使用go-bindata将迁移嵌入到应用程序中.

*数据库工具.*

* [chproxy](https://github.com/Vertamedia/chproxy) -  ClickHouse数据库的HTTP代理.
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - 收集小型insterts并向ClickHouse服务器发送大量请求.
* [datagen](https://github.com/codingconcepts/datagen) - 快速数据生成器，支持多表并支持多行DML.
* [dbbench](https://github.com/sj14/dbbench) - 数据库基准测试工具，支持多个数据库和脚本.
* [go-mysql](https://github.com/siddontang/go-mysql) - 使用工具集来处理MySQL协议和复制.
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - 自动将MySQL数据同步到Elasticsearch.
* [kingshard](https://github.com/flike/kingshard) -  kingshard是由Golang提供支持的MySQL的高性能代理.
* [myreplication](https://github.com/2tvenom/myreplication)   -  MySql二进制日志复制监听器.  支持基于语句和行的复制.
* [octillery](https://github.com/knocknote/octillery) - 用于分片数据库的包（支持每个ORM或原始SQL）.
* [orchestrator](https://github.com/github/orchestrator) -  MySQL复制拓扑管理器和可视化工具.
* [pgweb](https://github.com/sosedoff/pgweb) - 基于Web的PostgreSQL数据库浏览器.
* [prep](https://github.com/hexdigest/prep) - 使用准备好的SQL语句而不更改代码.
* [pREST](https://github.com/nuveo/prest) - 从任何PostgreSQL数据库提供RESTful API.
* [rwdb](https://github.com/andizzle/rwdb) -  rwdb为多个数据库服务器设置提供只读副本功能.
* [vitess](https://github.com/youtube/vitess) -  vitess提供服务器和工具，有助于扩展大型Web服务的MySQL数据库.

* SQL查询构建器，用于构建和使用SQL的库.*

* [Dotsql](https://github.com/gchaincl/dotsql) -  Go库可以帮助您将sql文件保存在一个位置并轻松使用它们.
* [gendry](https://github.com/didi/gendry) - 非侵入式SQL构建器和强大的数据绑定器.
* [godbal](https://github.com/xujiajun/godbal)   - 数据库抽象层（dbal）for go.  支持SQL构建器并轻松获得结果.
* [goqu](https://github.com/doug-martin/goqu) - 惯用SQL构建器和查询库.
* [igor](https://github.com/galeone/igor) -  PostgreSQL的抽象层，支持高级功能并使用类似gorm的语法.
* [ormlite](https://github.com/pupizoid/ormlite) - 轻量级包，包含一些类似ORM的功能和sqlite数据库的帮助程序.
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - 强大的数据检索方法以及与数据库无关的查询构建功能.
* [scaneo](https://github.com/variadico/scaneo) - 生成Go代码以将数据库行转换为任意结构.
* [sqrl](https://github.com/elgris/sqrl) -  SQL查询构建器，具有改进性能的Squirrel分支.
* [Squalus](https://gitlab.com/qosenergy/squalus) -  Go SQL包上的薄层，可以更轻松地执行查询.
* [Squirrel](https://github.com/Masterminds/squirrel) -  Go库，帮助您构建SQL查询.
* [xo](https://github.com/knq/xo) - 基于现有模式定义或支持PostgreSQL，MySQL，SQLite，Oracle和Microsoft SQL Server的自定义查询，为数据库生成惯用的Go代码.

## Database Drivers

*用于连接和操作数据库的库.*

*关系数据库
    * [avatica](https://github.com/apache/calcite-avatica-go) - 用于数据库/ sql的Apache Avatica / Phoenix SQL驱动程序.
    * [bgc](https://github.com/viant/bgc) - 用于BigQuery的数据存储连接.
    * [firebirdsql](https://github.com/nakagami/firebirdsql) -  Go的Firebird RDBMS SQL驱动程序.
    * [go-adodb](https://github.com/mattn/go-adodb) - 用于go的Microsoft ActiveX Object DataBase驱动程序，它使用database / sql.
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) -  Go的Microsoft MSSQL驱动程序.
    * [go-oci8](https://github.com/mattn/go-oci8) - 使用database / sql的Oracle驱动程序.
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) -  Go的MySQL驱动程序.
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - 用于使用数据库/ sql的SQL的SQLite3驱动程序.
    * [gofreetds](https://github.com/minus5/gofreetds)   -  Microsoft MSSQL驱动程序.  去封装 [FreeTDS](http://www.freetds.org).
    * [goracle](https://github.com/go-goracle/goracle) - 使用ODPI-C驱动程序的Go的Oracle驱动程序.
    * [pgx](https://github.com/jackc/pgx) -  PostgreSQL驱动程序支持数据库/ sql暴露的功能.
    * [pq](https://github.com/lib/pq) - 用于数据库/ sql的Pure Go Postgres驱动程序.

* NoSQL数据库
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) -  Go语言的Aerospike客户端.
    * [arangolite](https://github.com/solher/arangolite) - 为ArangoDB轻型golang驱动程序.
    * [asc](https://github.com/viant/asc) - 用于Aerospike的数据存储连接.
    * [dynago](https://github.com/underarmour/dynago) -  Dynago是DynamoDB最少的意外客户端原则.
    * [forestdb](https://github.com/couchbase/goforestdb) - 转到ForestDB的绑定.
    * [go-couchbase](https://github.com/couchbase/go-couchbase) -  Go中的Couchbase客户端.
    * [go-couchdb](https://github.com/fjl/go-couchdb) -  Go的另一个CouchDB HTTP API包装器.
    * [go-pilosa](https://github.com/pilosa/go-pilosa) - 去Pilosa的客户端库.
    * [go-rejson](https://github.com/nitishm/go-rejson)   - 使用Redigo golang客户端的redlanglabs的ReJSON模块的Golang客户端.  在redis中轻松存储和操作结构作为JSON对象.
    * [gocb](https://github.com/couchbase/gocb) - 官方Couchbase Go SDK.
    * [gocql](http://gocql.github.io) - 转到Apache Cassandra的语言驱动程序.
    * [godscache](https://github.com/defcronyke/godscache) -  Google Cloud Platform Go数据存储区程序包的包装程序，使用memcached添加缓存.
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - 用于Go编程语言的memcache客户端库.
    * [gorethink](https://github.com/dancannon/gorethink) - 转到RethinkDB的语言驱动程序.
    * [goriak](https://github.com/zegl/goriak) - 去Riak KV的语言驱动程序.
    * [mgo](https://github.com/globalsign/mgo) - 用于Go语言的MongoDB驱动程序，它根据标准Go习语在非常简单的API下实现丰富且经过良好测试的功能选择.
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) -  Go语言的官方MongoDB驱动程序.
    * [neo4j](https://github.com/cihangir/neo4j) - 休息Neo4j的API绑定Golang.
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) -  Neo4j的REST客户端在golang.
    * [neoism](https://github.com/jmcvetta/neoism) - 为Golang Neo4j的客户端.
    * [redigo](https://github.com/gomodule/redigo) -  Redigo是Redis数据库的Go客户端.
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang.
    * [redis](https://github.com/bsm/redeo) -  Redis协议兼容的TCP服务器/服务.
    * [xredis](https://github.com/shomali11/xredis) -  Typeisfe，可自定义，干净且易于使用的Redis客户端.

*搜索和分析数据库.
    * [bleve](https://github.com/blevesearch/bleve) - 用于go的现代文本索引库.
    * [elastic](https://github.com/olivere/elastic) -  Go的Elasticsearch客户端.
    * [elasticsql](https://github.com/cch123/elasticsql) - 在Go中将sql转换为elasticsearch dsl.
    * [elastigo](https://github.com/mattbaird/elastigo) -  Elasticsearch客户端库.
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) -  Go的官方Elasticsearch客户端.
    * [goes](https://github.com/OwnLocal/goes) - 与Elasticsearch交互的库.
    * [riot](https://github.com/go-ego/riot) -  Go开源，分布式，简单高效的搜索引擎.
    * [skizze](https://github.com/seiflotfy/skizze) - 概率数据结构服务和存储.

*多个后端.
    * [cachego](https://github.com/fabiorphp/cachego) - 用于多个驱动程序的Golang Cache组件.
    * [cayley](https://github.com/google/cayley) - 支持多个后端的图形数据库.
    * [dsc](https://github.com/viant/dsc) -  SQL，NoSQL，结构化文件的数据存储连接.
    * [gokv](https://github.com/philippgille/gokv) -  Go的简单键值存储抽象和实现（Redis，Consul，etcd，bbolt，BadgerDB，LevelDB，Memcached，DynamoDB，S3，PostgreSQL，MongoDB，CockroachDB等等）.

## Date and Time

*处理日期和时间的图书馆.*

* [carbon](https://github.com/uniplaces/carbon) - 使用许多util方法的简单时间扩展，从PHP Carbon库移植.
* [date](https://github.com/rickb777/date) - 增加使用日期，日期范围，时间跨度，时段和时间的时间.
* [dateparse](https://github.com/araddon/dateparse) - 在不事先知道格式的情况下解析日期.
* [durafmt](https://github.com/hako/durafmt) -  Go的持续时间格式库.
* [feiertage](https://github.com/wlbr/feiertage)   - 计算德国公共假日的功能集，包括  德国各州的专业化（Bundesländer）.  像复活节，五旬节，感恩节......
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - 在Go（golang）实施波斯语（Solar Hijri）日历.
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - 计算给定位置的日出和日落时间.
* [goweek](https://github.com/grsmv/goweek) - 用于在golang中使用周实体的库.
* [iso8601](https://github.com/relvacode/iso8601) - 无需正则表达式即可高效地解析ISO8601日期时间.
* [kair](https://github.com/GuilhermeCaruso/kair) - 日期和时间 -  Golang格式库.
* [now](https://github.com/jinzhu/now) - 现在是golang的时间工具包.
* [NullTime](https://github.com/kirillDanshin/nulltime) -  Nullable`time.Time`.
* [strftime](https://github.com/awoodbeck/strftime) - 兼容C99的strftime格式化程序.
* [timespan](https://github.com/SaidinWoT/timespan) - 用于与时间间隔交互，定义为开始时间和持续时间.
* [timeutil](https://github.com/leekchan/timeutil) -  golang的时间包中有用的扩展（Timedelta，Strftime，...）.
* [tuesday](https://github.com/osteele/tuesday) - 兼容Ruby的Strftime功能.

## Distributed Systems

*有助于构建分布式系统的软件包.*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - 用于添加对Go中的Celery工作者，任务和事件的交互和监视的支持的库.
* [consistent](https://github.com/buraksezer/consistent) - 有界负载的一致散列.
* [dht](https://github.com/anacrolix/dht) -  BitTorrent Kademlia DHT实施.
* [digota](https://github.com/digota/digota) -  grpc电子商务微服务.
* [dot](https://github.com/dotchain/dot/) - 使用操作转换/ OT的分布式同步.
* [doublejump](https://github.com/edwingeng/doublejump) - 改进了谷歌的跳跃一致哈希.
* [drmaa](https://github.com/dgruber/drmaa) - 基于DRMAA标准的集群调度程序的作业提交库.
* [dynamolock](https://cirello.io/dynamolock) -  DynamoDB支持的分布式锁定实现.
* [dynatomic](https://github.com/tylfin/dynatomic) - 使用DynamoDB作为原子计数器的库.
* [emitter-io](https://github.com/emitter-io/emitter) - 使用MQTT，Websockets和爱构建的高性能，分布式，安全和低延迟的发布 - 订阅平台.
* [flowgraph](https://github.com/vectaport/flowgraph) - 基于流程的编程包.
* [gleam](https://github.com/chrislusf/gleam) - 使用纯Go和Luajit编写的快速且可扩展的分布式map / reduce系统，将Go的高并发性与Luajit的高性能相结合，可以独立运行或分布式运行.
* [glow](https://github.com/chrislusf/glow) - 易于使用的可扩展分布式大数据处理，Map-Reduce，DAG执行，全部采用纯Go.
* [go-health](https://github.com/InVisionApp/go-health) - 用于在服务中启用异步依赖项运行状况检查的库.
* [go-jump](https://github.com/dgryski/go-jump) -  Google的“Jump”Consistent Hash功能端口.
* [go-kit](https://github.com/go-kit/kit) - 微服务工具包，支持服务发现，负载平衡，可插拔传输，请求跟踪等.
* [gorpc](https://github.com/valyala/gorpc) - 简单，快速和可扩展的RPC库，适用于高负载.
* [grpc-go](https://github.com/grpc/grpc-go)   -  gRPC的Go语言实现.  基于HTTP / 2的RPC.
* [hprose](https://github.com/hprose/hprose-golang) - 非常新的RPC库，现在支持25种以上的语言.
* [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
* [jsonrpc](https://github.com/osamingo/jsonrpc) -  jsonrpc包有助于实现JSON-RPC 2.0.
* [jsonrpc](https://github.com/ybbus/jsonrpc) -  JSON-RPC 2.0 HTTP客户端实现.
* [KrakenD](https://github.com/devopsfaith/krakend) - 具有中间件的超高性能API网关框架.
* [micro](https://github.com/micro/micro) - 可插拔微服务工具包和分布式系统平台.
* [NATS](https://github.com/nats-io/gnatsd) - 用于微服务，物联网和云原生系统的轻量级高性能消息传递系统.
* [outboxer](https://github.com/italolelis/outboxer) -  Outboxer是一个实现发件箱模式的go库.
* [pglock](https://cirello.io/pglock) -  PostgreSQL支持的分布式锁定实现.
* [raft](https://github.com/hashicorp/raft) -  HashiCorp的Golang实施Raft共识协议.
* [raft](https://github.com/coreos/etcd/tree/master/raft) - 由CoreOS实施Raft共识协议.
* [redis-lock](https://github.com/bsm/redis-lock) - 使用Redis简化分布式锁定实现.
* [resgate](https://resgate.io/) - 用于构建REST，实时和RPC API的实时API网关，其中所有客户端都可以无缝同步.
* [ringpop-go](https://github.com/uber/ringpop-go) -  Go应用程序的可扩展，容错的应用程序层分片.
* [rpcx](https://github.com/smallnest/rpcx) - 分布式可插拔RPC服务框架，如阿里巴巴Dubbo.
* [sleuth](https://github.com/ursiform/sleuth) - 用于无主p2p自动发现和HTTP服务之间的RPC的库（使用 [ZeroMQ](https://github.com/zeromq/libzmq)).
* [tendermint](https://github.com/tendermint/tendermint) - 使用Tendermint共识和区块链协议将用任何编程语言编写的状态机转换为拜占庭容错复制状态机的高性能中间件.
* [torrent](https://github.com/anacrolix/torrent) -  BitTorrent客户端包.

## Email

*实现电子邮件创建和发送的库和工具.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - 用Go编写的SMTP服务器.
* [douceur](https://github.com/aymerick/douceur) -  HTML电子邮件的CSS内联.
* [email](https://github.com/jordan-wright/email) -  Go强大而灵活的电子邮件库.
* [go-dkim](https://github.com/toorop/go-dkim) -  DKIM库，用于签署和验证电子邮件.
* [go-imap](https://github.com/emersion/go-imap) - 客户端和服务器的IMAP库.
* [go-message](https://github.com/emersion/go-message) - 用于Internet邮件格式和邮件消息的流式库.
* [go-premailer](https://github.com/vanng822/go-premailer) -  Go中HTML邮件的内联样式.
* [Gomail](https://github.com/go-gomail/gomail/) -  Gomail是一个非常简单而强大的发送电子邮件的包.
* [Hectane](https://github.com/hectane/hectane) - 提供HTTP API的轻量级SMTP客户端.
* [hermes](https://github.com/matcornic/hermes) -  Golang包，可生成干净，响应迅速的HTML电子邮件.
* [MailHog](https://github.com/mailhog/MailHog) - 使用Web和API接口进行电子邮件和SMTP测试.
* [SendGrid](https://github.com/sendgrid/sendgrid-go) -  SendGrid的Go库用于发送电子邮件.
* [smtp](https://github.com/mailhog/smtp) -  SMTP服务器协议状态机.

## Embeddable Scripting Languages

*在您的go代码中嵌入其他语言.*

* [agora](https://github.com/PuerkitoBio/agora) -  Go中的动态类型，可嵌入编程语言.
* [anko](https://github.com/mattn/anko) - 用Go编写的可编写脚本的解释器.
* [binder](https://github.com/alexeyco/binder) - 转到Lua绑定库，基于 [gopher-lua](https://github.com/yuin/gopher-lua).
* [expr](https://github.com/antonmedv/expr) - 可以评估表达式的引擎.
* [gentee](https://github.com/gentee/gentee) - 可嵌入脚本编程语言.
* [gisp](https://github.com/jcla1/gisp) -  Go中的简单LISP.
* [go-duktape](https://github.com/olebedev/go-duktape) - 针对Go的Duktape JavaScript引擎绑定.
* [go-lua](https://github.com/Shopify/go-lua) -  Lua 5.2 VM的端口到纯Go.
* [go-php](https://github.com/deuill/go-php) -  Go的PHP绑定.
* [go-python](https://github.com/sbinet/go-python) - 天真地绑定到CPython C-API.
* [golua](https://github.com/aarzilli/golua) -  Goa绑定Lua C API.
* [gopher-lua](https://github.com/yuin/gopher-lua) - 用Go编写的Lua 5.1 VM和编译器.
* [gval](https://github.com/PaesslerAG/gval) - 用Go编写的高度可定制的表达式语言.
* [ngaro](https://github.com/db47h/ngaro) - 可嵌入的Ngaro VM实现，支持Retro中的脚本.
* [otto](https://github.com/robertkrimen/otto) - 用Go编写的JavaScript解释器.
* [purl](https://github.com/ian-kent/purl) -  Go中嵌入的Perl 5.18.2.
* [tengo](https://github.com/d5/tengo) - 用于Go的Bytecode编译脚本语言.

## Error Handling

*处理错误的图书馆.*

* [errlog](https://github.com/snwfdhmp/errlog)   -  Hackable包，用于确定错误的负责任源代码（以及其他一些快速调试功能）.  可插入任何记录器就地.
* [errors](https://github.com/pkg/errors) - 提供简单错误处理原语的包.
* [errorx](https://github.com/joomcode/errorx) - 功能丰富的错误包，包含堆栈跟踪，错误组合等.
* [go-multierror](https://github.com/hashicorp/go-multierror) -  Go（golang）包，用于将错误列表表示为单个错误.
* [tracerr](https://github.com/ztrue/tracerr) - 堆栈跟踪和源片段的Golang错误.
* [werr](https://github.com/txgruppi/werr) -  Error Wrapper为Go中的错误类型创建一个包装器，它捕获调用它的文件，行和堆栈.

## Files

*用于处理文件和文件系统的库.*

* [afero](https://github.com/spf13/afero) -  Go的FileSystem抽象系统.
* [checksum](https://github.com/codingsince1985/checksum) - 为大文件计算消息摘要，如MD5和SHA256.
* [flop](https://github.com/homedepot/flop) - 文件操作库，旨在镜像功能奇偶校验 [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - 使用标记加载csv文件.
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - 复制人类文件.
* [go-gtfs](https://github.com/artonge/go-gtfs) - 在go中加载gtfs文件.
* [notify](https://github.com/rjeczalik/notify) - 具有简单API的文件系统事件通知库，类似于os / signal.
* [opc](https://github.com/qmuntal/opc) - 为Go加载开放式打包协议（OPC）文件.
* [pdfcpu](https://github.com/hhrutter/pdfcpu) -  PDF处理器.
* [skywalker](https://github.com/dixonwille/skywalker) - 允许一个人轻松地同时通过文件系统的包.
* [stl](https://gitlab.com/russoj88/stl)   - 用于读写STL（立体光刻）文件的模块.  并发算法用于阅读.
* [tarfs](https://github.com/posener/tarfs) - 实施 [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) 用于获取文件.
* [vfs](https://github.com/C2FO/vfs) - 用于跨越多种文件系统类型（如os，S3和GCS）的Go的可插入，可扩展和固定的文件系统功能集.

## Financial

*会计和财务方案.*

* [accounting](https://github.com/leekchan/accounting) -  golang的货币和货币格式.
* [currency](https://github.com/bnkamalesh/currency) - 高性能和准确的货币计算包.
* [decimal](https://github.com/shopspring/decimal) - 任意精度的定点十进制数.
* [go-finance](https://github.com/FlashBoys/go-finance) -  Go的综合金融市场数据.
* [go-finance](https://github.com/alpeb/go-finance) - 金钱函数库，用于货币时间价值（年金），现金流量，利率转换，债券和折旧计算.
* [go-money](https://github.com/rhymond/go-money) - 实施福勒的金钱模式.
* [ofxgo](https://github.com/aclindsa/ofxgo) - 查询OFX服务器和/或解析响应（使用示例命令行客户端）.
* [orderbook](https://github.com/i25959341/orderbook) -  Golang中限价订单簿的匹配引擎.
* [techan](https://github.com/sdcoffey/techan) - 具有先进市场分析和交易策略的技术分析库.
* [transaction](https://github.com/claygod/transaction) - 嵌入式帐户事务数据库，以多线程模式运行.
* [vat](https://github.com/dannyvankooten/vat) - 增值税号验证和欧盟增值税率.

## Forms

*用于处理表格的图书馆.*

* [bind](https://github.com/robfig/bind) - 将表单数据绑定到任何Go值.
* [binding](https://github.com/mholt/binding) - 将表单和JSON数据从net / http请求绑定到struct.
* [conform](https://github.com/leebenson/conform)   - 控制用户输入.  基于struct标签修剪，清理和清理数据.
* [form](https://github.com/go-playground/form)   - 将url.Values解码为Go值，将Encodes Go值转换为url.Values.  双阵列和全地图支持.
* [formam](https://github.com/monoculum/formam) - 将表单的值解码为结构.
* [forms](https://github.com/albrow/forms) - 框架无关的库，用于解析和验证支持多部分表单和文件的表单/ JSON数据.
* [gorilla/csrf](https://github.com/gorilla/csrf) - 针对Go Web应用程序和服务的CSRF保护.
* [nosurf](https://github.com/justinas/nosurf) -  Go的CSRF保护中间件.

## Functional

*支持Go中的函数式编程的包.*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - 单子，函数式编程功能的Golang.
* [fuego](https://github.com/seborama/fuego) -  Go中的功能实验.
* [go-underscore](https://github.com/tobyhede/go-underscore) - 有用的Go功能集合实用程序的有用集合.

## Game Development

*令人敬畏的游戏开发库.*

* [Azul3D](https://github.com/azul3d/engine) - 用Go编写的3D游戏引擎.
* [Ebiten](https://github.com/hajimehoshi/ebiten) -  Go中死的简单2D游戏库.
* [engo](https://github.com/EngoEngine/engo)   -  Engo是一个用Go编写的开源2D游戏引擎.  它遵循实体 - 组件 - 系统范例.
* [g3n](https://github.com/g3n/engine) - 去3D游戏引擎.
* [GarageEngine](https://github.com/vova616/GarageEngine) - 使用Go编写的2d游戏引擎在OpenGL上工作.
* [glop](https://github.com/runningwild/glop) -  Glop（Power Library Of Power）是一个相当简单的跨平台游戏库.
* [go-astar](https://github.com/beefsack/go-astar) - 实现A \ *路径查找算法.
* [go-collada](https://github.com/GlenKelley/go-collada) - 使用Collada文件格式的包.
* [go-sdl2](https://github.com/veandco/go-sdl2) - 去绑定 [Simple DirectMedia Layer](https://www.libsdl.org/).
* [go3d](https://github.com/ungerik/go3d) -  Go的面向性能的2D / 3D数学包.
* [gonet](https://github.com/xtaci/gonet) - 用主题实现的游戏服务器骨架.
* [goworld](https://github.com/xiaonanln/goworld) - 可扩展的游戏服务器引擎，具有空间实体框架和热交换功能.
* [Leaf](https://github.com/name5566/leaf) - 轻量级游戏服务器框架.
* [nano](https://github.com/lonng/nano) - 轻量级，设施，高性能的golang游戏服务器框架.
* [Oak](https://github.com/oakmound/oak) -  Pure Go游戏引擎.
* [Pitaya](https://github.com/topfreegames/pitaya) - 可扩展的游戏服务器框架，通过C SDK为iOS，Android，Unity和其他人提供集群支持和客户端库.
* [Pixel](https://github.com/faiface/pixel) -  Go手工制作的2D游戏库.
* [raylib-go](https://github.com/gen2brain/raylib-go) - 去绑定 [raylib](http://www.raylib.com/)，一个简单易用的库，用于学习视频游戏编程.
* [termloop](https://github.com/JoelOtter/termloop) - 基于终端的Go游戏引擎，构建于Termbox之上.

## Generation and Generics

*通过代码生成增强语言功能的工具，例如泛型.*

* [efaceconv](https://github.com/t0pep0/efaceconv) - 代码生成工具，用于从接口{}到不可分配的不可变类型的高性能转换.
* [gen](https://github.com/clipperhouse/gen) - 用于“泛型”功能的代码生成工具.
* [generis](https://github.com/senselogic/GENERIS) - 代码生成工具，提供泛型，自由格式宏，条件编译和HTML模板.
* [go-enum](https://github.com/abice/go-enum) - 代码注释的枚举代码生成.
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) -  Go的类似.NET LINQ的查询方法.
* [goderive](https://github.com/awalterschulze/goderive) - 从输入类型派生函数.
* [gotype](https://github.com/wzshiming/gotype) -  Golang源代码解析，像反映使用包.
* [GoWrap](https://github.com/hexdigest/gowrap) - 使用简单模板为Go接口生成装饰器.
* [interfaces](https://github.com/rjeczalik/interfaces) - 用于生成接口定义的命令行工具.
* [jennifer](https://github.com/dave/jennifer) - 生成没有模板的任意Go代码.
* [pkgreflect](https://github.com/ungerik/pkgreflect) - 使用包预测反射的预处理器.

## Geographic

*地理工具和服务器*

* [geocache](https://github.com/melihmucuk/geocache) - 适用于基于地理定位的应用程序的内存缓存.
* [geoserver](https://github.com/hishamkaram/geoserver) -  geoserver是一个Go包，用于通过GeoServer REST API操作GeoServer实例.
* [gismanager](https://github.com/hishamkaram/gismanager) - 将您的GIS数据（矢量数据）发布到PostGIS和Geoserver.
* [osm](https://github.com/paulmach/osm) - 用于阅读，编写和使用OpenStreetMap数据和API的库.
* [pbf](https://github.com/maguro/pbf) -  OpenStreetMap的PBF golang编码器/解码器.
* [S2 geometry](https://github.com/golang/geo) -  Go中的S2几何库.
* [Tile38](https://github.com/tidwall/tile38) - 具有空间索引和实时地理围栏的地理定位DB.

## Go Compilers

*编译工具转到其他语言.*

* [c4go](https://github.com/Konstantin8105/c4go) -  Go代码的Transpile C代码.
* [f4go](https://github.com/Konstantin8105/f4go) - 将Goile FORTRAN 77代码转换为Go代码.
* [gopherjs](https://github.com/gopherjs/gopherjs) - 转到JavaScript的编译器.
* [llgo](https://github.com/go-llvm/llgo) -  Go的基于LLVM的编译器.
* [tardisgo](https://github.com/tardisgo/tardisgo) -  Golang到Haxe转到CPP / CSharp / Java / JavaScript转换器.

## Goroutines

*管理和使用Goroutines的工具.*

* [ants](https://github.com/panjf2000/ants) - 高性能够程池golang.
* [artifex](https://github.com/borderstech/artifex) - 使用基于工作线的调度的Golang简单内存作业队列.
* [async](https://github.com/studiosol/async) - 异步执行函数的安全方法，在发生恐慌时恢复它们.
* [breaker](https://github.com/kamilsk/breaker) - 灵活的机制，使您的代码易碎.
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - 为的CyclicBarrier golang.
* [go-floc](https://github.com/workanator/go-floc) - 轻松协调goroutines.
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - 控制goroutines执行顺序.
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - 使用这个轻量级库和简单的API管理goroutine池.
* [go-trylock](https://github.com/subchen/go-trylock) - 针对Golang的读写锁定的TryLock支持.
* [gollback](https://github.com/vardius/gollback) - 异步简单函数实用程序，用于管理闭包和回调的执行.
* [GoSlaves](https://github.com/themester/GoSlaves) - 简单和异步Goroutine池库.
* [goworker](https://github.com/benmanns/goworker) -  goworker是一名Go-based背景工作者.
* [gpool](https://github.com/Sherifabdlnaby/gpool) - 管理可调整大小的上下文感知goroutine池以绑定并发.
* [grpool](https://github.com/ivpusic/grpool) - 轻量级Goroutine游泳池.
* [oversight](https://cirello.io/oversight) -  Oversight是Erlang监督树的完整实现.
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - 并行运行功能.
* [pool](https://github.com/go-playground/pool) - 有限的消费者goroutine或无限goroutine池，更容易goroutine处理和取消.
* [queue](https://github.com/AnikHasibul/queue)   - 为您提供类似队列组可访问性的`sync.WaitGroup`.  帮助您限制和限制goroutines，等待所有goroutines的结束等等.
* [semaphore](https://github.com/kamilsk/semaphore) - 基于通道和上下文的锁定/解锁操作超时的信号量模式实现.
* [semaphore](https://github.com/marusama/semaphore) - 基于CAS的快速可调整大小的信号量实现（比基于通道的信号量实现更快）.
* [stl](https://github.com/ssgreg/stl) - 基于软件事务内存（STM）并发控制机制的软件事务锁.
* [threadpool](https://github.com/shettyh/threadpool) -  Golang线程池的实现.
* [tunny](https://github.com/Jeffail/tunny) - 够程池golang.
* [worker-pool](https://github.com/vardius/worker-pool) -  goworker是一个Go简单的异步工作池.
* [workerpool](https://github.com/gammazero/workerpool) -  Goroutine池限制任务执行的并发性，而不是排队的任务数.

## GUI

*用于构建GUI应用程序的库.*

*Toolkits*

* [app](https://github.com/murlokswarm/app)   - 使用GO，HTML和CSS创建应用程序的包.  支持：MacOS，Windows正在进行中.
* [fyne](https://github.com/fyne-io/fyne)   - 为Go设计的跨平台原生GUI，使用EFL渲染.  支持：Linux，macOS，Windows.
* [go-astilectron](https://github.com/asticode/go-astilectron) - 使用GO和HTML / JS / CSS构建跨平台GUI应用程序（由Electron提供支持）.
* [go-gtk](http://mattn.github.io/go-gtk/) - 为GTK绑定绑定.
* [go-sciter](https://github.com/sciter-sdk/go-sciter)   - 针对Sciter的绑定：用于现代桌面UI开发的可嵌入HTML / CSS /脚本引擎.  跨平台.
* [gotk3](https://github.com/gotk3/gotk3) - 为GTK3绑定绑定.
* [gowd](https://github.com/dtylman/gowd)   - 使用GO，HTML，CSS和NW.js进行快速简单的桌面UI开发.  跨平台.
* [qt](https://github.com/therecipe/qt) -  Go的Qt绑定（支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi）.
* [ui](https://github.com/andlabs/ui)   -  Go的平台原生GUI库.  跨平台.
* [Wails](https://wails.app) - 使用内置操作系统HTML呈现器的带有HTML UI的Mac，Windows，Linux桌面应用程序.
* [walk](https://github.com/lxn/walk) -  Go的Windows应用程序库工具包.
* [webview](https://github.com/zserge/webview) - 具有简单双向JavaScript绑定的跨平台webview窗口（Windows / macOS / Linux）.

*Interaction*

* [go-appindicator](https://github.com/dawidd6/go-appindicator) - 为libappindicator3 C库绑定绑定.
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) -  Go的OSX桌面通知库.
* [robotgo](https://github.com/go-vgo/robotgo)   -  Go Native跨平台GUI系统自动化.  控制鼠标，键盘等.
* [systray](https://github.com/getlantern/systray) - 跨平台Go库，在通知区域中放置图标和菜单.
* [trayhost](https://github.com/shurcooL/trayhost) - 跨平台Go库，在主机操作系统的任务栏中放置一个图标.


## Hardware

*与硬件交互的库，工具和教程.*

See [go-hardware](https://github.com/rakyll/go-hardware) 全面的清单.

## Images

*用于处理图像的库.*

* [bild](https://github.com/anthonynsimon/bild) - 纯Go中图像处理算法的集合.
* [bimg](https://github.com/h2non/bimg) - 小型软件包，可使用libvips快速高效地进行图像处理.
* [cameron](https://github.com/aofei/cameron) -  Go的头像生成器.
* [geopattern](https://github.com/pravj/geopattern) - 从字符串创建美丽的生成图像模式.
* [gg](https://github.com/fogleman/gg) - 纯Go中的2D渲染.
* [gift](https://github.com/disintegration/gift) - 图像处理过滤器包.
* [go-cairo](https://github.com/ungerik/go-cairo) - 转到cairo图形库的绑定.
* [go-gd](https://github.com/bolknote/go-gd) - 转到GD库的绑定.
* [go-nude](https://github.com/koyachi/go-nude) - 使用Go检测裸露.
* [go-opencv](https://github.com/lazywei/go-opencv) - 转到OpenCV的绑定.
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - 从Python到Go的webcolors库的端口.
* [gocv](https://github.com/hybridgroup/gocv) - 使用OpenCV 3.3+获取计算机视觉包.
* [goimagehash](https://github.com/corona10/goimagehash) -  Go Perceptual图像哈希包.
* [govatar](https://github.com/o1egl/govatar) - 用于生成有趣头像的库和CMD工具.
* [image2ascii](https://github.com/qeesung/image2ascii) - 将图像转换为ASCII.
* [imagick](https://github.com/gographics/imagick) - 绑定到ImageMagick的MagickWand C API.
* [imaginary](https://github.com/h2non/imaginary) - 用于图像大小调整的快速简单的HTTP微服务.
* [imaging](https://github.com/disintegration/imaging) -  Simple Go图像处理包.
* [img](https://github.com/hawx/img) - 选择图像处理工具.
* [ln](https://github.com/fogleman/ln) -  Go中的3D线条艺术渲染.
* [mergi](https://github.com/noelyahan/mergi) - 用于图像处理的Tool＆Go库（合并，裁剪，调整大小，水印，动画）.
* [mort](https://github.com/aldor007/mort) - 用Go编写的存储和图像处理服务器.
* [mpo](https://github.com/donatj/mpo) - 用于MPO 3D照片的解码器和转换工具.
* [picfit](https://github.com/thoas/picfit) - 用Go编写的图像大小调整服务器.
* [pt](https://github.com/fogleman/pt) - 用Go编写的路径跟踪引擎.
* [resize](https://github.com/nfnt/resize) - 使用常见插值方法调整Go的图像大小.
* [rez](https://github.com/bamiaux/rez) - 纯Go和SIMD中的图像大小调整.
* [smartcrop](https://github.com/muesli/smartcrop) - 为任意图像和裁剪尺寸找到好作物.
* [steganography](https://github.com/auyer/steganography) - 用于LSB隐写术的Pure Go Library.
* [stegify](https://github.com/DimitarPetrov/stegify) - 用于LSB隐写术的工具，能够隐藏图像中的任何文件.
* [svgo](https://github.com/ajstarks/svgo) - 转到SVG生成的语言库.
* [tga](https://github.com/ftrvxmtrx/tga) - 包tga是TARGA图像格式解码器/编码器.

## IoT (Internet of Things)

*用于物联网编程设备的库.*

* [connectordb](https://github.com/connectordb/connectordb) - 量化自我和物联网的开源平台.
* [devices](https://github.com/goiot/devices) - 物联网设备库套件，x / exp / io实验.
* [eywa](https://github.com/xcodersun/eywa) -  Project Eywa本质上是一个跟踪连接设备的连接管理器.
* [flogo](https://github.com/tibcosoftware/flogo) -  Project Flogo是物联网边缘应用和集成的开源框架.
* [gatt](https://github.com/paypal/gatt) -  Gatt是用于构建蓝牙低功耗外设的Go软件包.
* [gobot](https://github.com/hybridgroup/gobot/) -  Gobot是机器人，物理计算和物联网的框架.
* [huego](https://github.com/amimof/huego) - 适用于Go的广泛的Philips Hue客户端库.
* [iot](https://github.com/vaelen/iot/) - 物联网是实施Google IoT核心设备的简单框架.
* [mainflux](https://github.com/Mainflux/mainflux) - 工业物联网消息和设备管理服务器.
* [periph](https://periph.io/) - 与低级电路板设备连接的外围设备I / O.
* [sensorbee](https://github.com/sensorbee/sensorbee) - 物联网的轻量级流处理引擎.

## Job Scheduler

*用于安排工作的图书馆.*

* [clockwerk](http://github.com/onatm/clockwerk) - 使用简单流畅的语法来打包以安排定期作业.
* [clockwork](https://github.com/whiteShtef/clockwork) -  Go中简单直观的作业调度库.
* [go-cron](https://github.com/rk/go-cron)   - 用于go的简单Cron库，可以在不同的时间间隔执行闭包或功能，从特定日期和时间的每秒一次到每年一次.  主要用于Web应用程序和长时间运行的守护进程.
* [gron](https://github.com/roylee0704/gron) - 使用简单的Go API定义基于时间的任务，Gron的调度程序将相应地运行它们.
* [JobRunner](https://github.com/bamzi/jobrunner) - 智能且功能强大的cron作业调度程序，内置作业排队和实时监控功能.
* [jobs](https://github.com/albrow/jobs) - 持久而灵活的后台工作库.
* [leprechaun](https://github.com/kilgaloon/leprechaun) - 支持webhooks，crons和经典调度的作业调度程序.
* [scheduler](https://github.com/carlescere/scheduler) -  Cronjobs调度变得简单.

## JSON

*使用JSON的库.*

* [ajson](https://github.com/spyzhov/ajson) - 支持JSONPath的golang的抽象JSON.
* [gjo](https://github.com/skanehira/gjo) - 用于创建JSON对象的小实用程序.
* [GJSON](https://github.com/tidwall/gjson) - 使用一行代码获取JSON值.
* [go-respond](https://github.com/nicklaw5/go-respond) -  Go包用于处理常见的HTTP JSON响应.
* [gojq](https://github.com/elgs/gojq) - 在Golang JSON查询.
* [gojson](https://github.com/ChimeraCoder/gojson) - 从示例JSON自动生成Go（golang）结构定义.
* [JayDiff](https://github.com/yazgazan/jaydiff) - 用Go编写的JSON diff实用程序.
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - 将JSON转换为Go结构.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - 根据JSON API错误参考来绑定绑定.
* [jsonf](https://github.com/miolini/jsonf) - 用于突出显示格式的控制台工具和用于获取JSON的结构查询.
* [jsongo](https://github.com/ricardolonga/jsongo) -  Fluent API，可以更轻松地创建Json对象.
* [jsonhal](https://github.com/RichardKnop/jsonhal) -  Simple Go包使自定义结构编组为HAL兼容的JSON响应.
* [kazaam](https://github.com/Qntfy/kazaam) - 用于任意转换JSON文档的API.
* [mp](https://github.com/sanbornm/mp)   - 简单的cli电子邮件解析器.  它目前需要stdin并输出JSON.

## Logging

*用于生成和处理日志文件的库.*

* [distillog](https://github.com/amoghe/distillog) - 蒸馏水平测井（将其视为stdlib + log水平）.
* [glg](https://github.com/kpango/glg) -  glg是Go的简单快速级别的日志库.
* [glo](https://github.com/lajosbencz/glo) - 具有相同严重性级别的PHP Monolog灵感日志记录工具.
* [glog](https://github.com/golang/glog) -  Go的执行日志.
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - 简单的编写器，根据当前日期和时间自动旋转日志文件，如cronolog.
* [go-log](https://github.com/subchen/go-log) - 简单且可配置的Go in Go，包含级别，格式化程序和编写器.
* [go-log](https://github.com/siddontang/go-log) -  Log lib支持级别和多个处理程序.
* [go-log](https://github.com/ian-kent/go-log) -  Go中的Log4j实现.
* [go-logger](https://github.com/apsdehal/go-logger) -  Go程序的简单记录器，带有级别处理程序.
* [gologger](https://github.com/sadlil/gologger) - 简单易用的log lib for go，登录Colored Console，Simple Console，File或Elasticsearch.
* [gomol](https://github.com/aphistic/gomol) - 具有可扩展日志记录输出的Go的多输出结构化日志记录.
* [gone/log](https://github.com/One-com/gone/tree/master/log) - 快速，可扩展，功能齐全，std-lib源兼容的日志库.
* [journald](https://github.com/ssgreg/journald) - 实现systemd Journal的本机API以进行日志记录.
* [log](https://github.com/aerogo/log) -  O（1）日志记录系统，允许您将一个日志连接到多个写入程序（例如stdout，文件和TCP连接）.
* [log](https://github.com/apex/log) -  Go的结构化日志包.
* [log](https://github.com/go-playground/log) -  Go的简单，可配置和可扩展的结构化日志记录.
* [log](https://github.com/teris-io/log) -  Go的结构化日志界面干净地将日志记录外观与其实现分开.
* [log-voyage](https://github.com/firstrow/logvoyage) - 用golang编写的全功能日志saas.
* [log15](https://github.com/inconshreveable/log15) - 简单，强大的Go日志记录.
* [logdump](https://github.com/ewwwwwqm/logdump) - 用于多级日志记录的包.
* [logex](https://github.com/chzyer/logex) -  Golang日志库，支持跟踪和级别，由标准日志库包装.
* [logger](https://github.com/azer/logger) -  Go的简约日志记录库.
* [logmatic](https://github.com/borderstech/logmatic) -  Golang的彩色记录器，具有动态日志级别配置.
* [logo](https://github.com/mbndr/logo) -  Golang记录器到不同的可配置编写器.
* [logrus](https://github.com/Sirupsen/logrus) -  Go的结构化记录器.
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) 插件将错误发​​送给 [Loggly](https://www.loggly.com/).
* [logutils](https://github.com/hashicorp/logutils) - 用于在Go（Golang）中稍微更好地记录扩展标准记录器的实用程序.
* [logxi](https://github.com/mgutz/logxi) -  12因素应用程序记录器，快速，让你开心.
* [lumberjack](https://github.com/natefinch/lumberjack) - 简单的滚动记录器，实现io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) - 用于go的简单日志记录模块，具有5个级别，可选的旋转日志文件功能和stdout / stderr输出.
* [onelog](https://github.com/francoispqt/onelog)   -  Onelog是一个简单但非常有效的JSON记录器.  它是所有场景中最快的JSON记录器.  此外，它是具有最低分配的记录器之一.
* [ozzo-log](https://github.com/go-ozzo/ozzo-log)   - 支持日志严重性，分类和过滤的高性能日志记录.  可以将过滤后的日志消息发送到各种目标（例如控制台，网络，邮件）.
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) -  RollingWriter是一个自动旋转`io.Writer`实现，具有多策略以提供日志文件轮换.
* [seelog](https://github.com/cihub/seelog) - 具有灵活调度，过滤和格式化的记录功能.
* [spew](https://github.com/davecgh/go-spew) - 为Go数据结构实现深度漂亮的打印机，以帮助调试.
* [stdlog](https://github.com/alexcesaro/log)   -  Stdlog是一个面向对象的库，提供分层日志记录.  它对于cron作业非常有用.
* [tail](https://github.com/hpcloud/tail) -  Go包试图模仿BSD尾部程序的功能.
* [xlog](https://github.com/xfxdev/xlog) -  Go的插件架构和灵活的日志系统，具有级别控制，多个日志目标和自定义日志格式.
* [xlog](https://github.com/rs/xlog) - 具有灵活调度的“net / context”感知HTTP处理程序的结构化记录器.
* [zap](https://github.com/uber-go/zap) -  Go中快速，结构化，水平的日志记录.
* [zerolog](https://github.com/rs/zerolog) - 零分配JSON记录器.

## Machine Learning

*机器学习库.*

* [bayesian](https://github.com/jbrukh/bayesian) - 贝叶斯分类为Golang天真.
* [CloudForest](https://github.com/ryanbressler/CloudForest) - 用于纯Go中机器学习的快速，灵活，多线程的决策树集合.
* [eaopt](https://github.com/MaxHalford/eaopt) - 进化优化库.
* [evoli](https://github.com/khezen/evoli) - 遗传算法和粒子群优化库.
* [fonet](https://github.com/Fontinalis/fonet) - 用Go编写的深度神经网络库.
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - 实现k模式和k-prototypes聚类算法.
* [go-deep](https://github.com/patrikeh/go-deep) -  Go中一个功能丰富的神经网络库.
* [go-fann](https://github.com/white-pony/go-fann) - 快速人工神经网络（FANN）库的绑定.
* [go-galib](https://github.com/thoj/go-galib) - 用Go / golang编写的遗传算法库.
* [go-pr](https://github.com/daviddengcn/go-pr) -  Go lang中的模式识别包.
* [gobrain](https://github.com/goml/gobrain) - 用go编写的神经网络.
* [godist](https://github.com/e-dard/godist) - 各种概率分布和相关方法.
* [goga](https://github.com/tomcraven/goga) -  Go的遗传算法库.
* [GoLearn](https://github.com/sjwhitworth/golearn) -  Go的通用机器学习库.
* [golinear](https://github.com/danieldk/golinear) -  Go的liblinear绑定.
* [GoMind](https://github.com/surenderthakran/gomind) -  Go中一个简单的神经网络库.
* [goml](https://github.com/cdipaolo/goml) -  Go中的在线机器学习.
* [goRecommend](https://github.com/timkaye11/goRecommend) - 用Go编写的推荐算法库.
* [gorgonia](https://github.com/chewxy/gorgonia) - 基于图形的计算库，如Theano for Go，提供用于构建各种机器学习和神经网络算法的原语.
* [gorse](https://github.com/zhenghaoz/gorse) - 基于Go协同过滤的高性能推荐系统包.
* [goscore](https://github.com/asafschers/goscore) - 针对PMML的Go Scoring API.
* [gosseract](https://github.com/otiai10/gosseract) - 使用Tesseract C ++库，获取OCR（光学字符识别）包.
* [libsvm](https://github.com/datastream/libsvm) - 基于LIBSVM 3.14的libsvm golang版本派生工作.
* [mlgo](https://github.com/NullHypothesis/mlgo) - 该项目旨在提供Go中的简约机器学习算法.
* [neat](https://github.com/jinyeom/neat) - 即插即用，并行Go框架，用于增强拓扑（NEAT）的NeuroEvolution.
* [neural-go](https://github.com/schuyler/neural-go) - 在Go中实现的多层感知器网络，通过反向传播进行训练.
* [ocrserver](https://github.com/otiai10/ocrserver) - 一个简单的OCR API服务器，Docker和Heroku非常容易部署.
* [onnx-go](https://github.com/owulveryck/onnx-go) -  Go Interface to Open Neural Network Exchange（ONNX）.
* [probab](https://github.com/ThePaw/probab)   - 概率分布函数.  贝叶斯推断.  写在纯粹的Go.
* [regommend](https://github.com/muesli/regommend) - 推荐和协作过滤引擎.
* [shield](https://github.com/eaigner/shield) - 贝叶斯文本分类器，为Go提供灵活的标记器和存储后端.
* [tfgo](https://github.com/galeone/tfgo)   - 易于使用的Tensorflow绑定：简化了官方Tensorflow Go绑定的使用.  在Go中定义计算图，加载和执行用Python训练的模型.
* [Varis](https://github.com/Xamber/Varis) -  Golang神经网络.

## Messaging

*实现消息传递系统的库.*

* [APNs2](https://github.com/sideshow/apns2) - 用于Go的HTTP / 2 Apple推送通知提供程序 - 向iOS，tvOS，Safari和OSX应用程序发送推送通知.
* [Beaver](https://github.com/Clivern/Beaver) - 实时消息服务器，用于在Web和移动应用程序中构建可扩展的应用程序内通知，多人游戏，聊天应用程序.
* [Benthos](https://github.com/Jeffail/benthos) - 一系列协议之间的消息流桥接.
* [Bus](https://github.com/mustafaturan/bus) - 用于内部通信的极简主义消息总线实现.
* [Centrifugo](https://github.com/centrifugal/centrifugo) -  Go中的实时消息传递（Websockets或SockJS）服务器.
* [dbus](https://github.com/godbus/dbus) -  D-Bus的Native Go绑定.
* [drone-line](https://github.com/appleboy/drone-line) - 发送 [Line](https://at.line.me/en) 使用二进制，docker或Drone CI的通知.
* [emitter](https://github.com/olebedev/emitter) - 使用Go方式发布事件，包括通配符，谓词，取消可能性和许多其他好的胜利.
* [event](https://github.com/agoalofalife/event) - 模式观察者的实施.
* [EventBus](https://github.com/asaskevich/EventBus) - 具有异步兼容性的轻量级事件总线.
* [gaurun-client](https://github.com/osamingo/gaurun-client) - 用Go编写的Gaurun客户端.
* [Glue](https://github.com/desertbit/glue) - 强大的Go和Javascript套接字库（Socket.io的替代品）.
* [go-notify](https://github.com/TheCreeper/go-notify) -  freedesktop通知规范的本机实现.
* [go-nsq](https://github.com/nsqio/go-nsq) -  NSQ的官方Go包.
* [go-socket.io](https://github.com/googollee/go-socket.io) - 用于golang的socket.io库，一个实时应用程序框架.
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - 客户图书馆到Viessmann Vitotrol网络服务.
* [Gollum](https://github.com/trivago/gollum) -  n：m多路复用器，用于收集来自不同源的消息并将它们广播到一组目的地.
* [golongpoll](https://github.com/jcuga/golongpoll) -  HTTP longpoll服务器库，使web pub-sub变得简单.
* [goose](https://github.com/ian-kent/goose) -  Go中的服务器发送事件.
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) -  gopush-cluster是一个推送服务器集群.
* [gorush](https://github.com/appleboy/gorush) - 使用推送通知服务器 [APNs2](https://github.com/sideshow/apns2) 和谷歌 [GCM](https://github.com/google/go-gcm).
* [guble](https://github.com/smancke/guble) - 使用推送通知的消息服务器（Google Firebase云消息传递，Apple推送通知服务，SMS）以及websockets，REST API，具有分布式操作和消息持久性.
* [hub](https://github.com/leandro-lugaresi/hub) -  Go应用程序的消息/事件中心，使用发布/订阅模式，支持像rabbitMQ交换这样的别名.
* [jazz](https://github.com/socifi/jazz) - 一个简单的RabbitMQ抽象层，用于队列管理，发布和消息消息.
* [machinery](https://github.com/RichardKnop/machinery) - 基于分布式消息传递的异步任务队列/作业队列.
* [mangos](https://github.com/go-mangos/mangos) -  Pure实现具有传输互操作性的Nanomsg（“可扩展协议”）.
* [melody](https://github.com/olahol/melody) - 处理websocket会话的极简主义框架，包括广播和自动ping / pong处理.
* [Mercure](https://github.com/dunglas/mercure) - 使用Mercure协议（基于服务器发送事件构建）调度服务器发送的更新的服务器和库.
* [messagebus](https://github.com/vardius/message-bus) -  messagebus是一种简单的异步消息总线，非常适合在进行事件采购，CQRS，DDD时用作事件总线.
* [NATS Go Client](https://github.com/nats-io/nats) - 轻量级和高性能的发布 - 订阅和分布式排队消息系统 - 这是Go库.
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - 围绕NSQ主题和频道的微小包装.
* [oplog](https://github.com/dailymotion/oplog) -  REST API的通用oplog /复制系统.
* [pubsub](https://github.com/tuxychandru/pubsub) - 简单的pubsub包去.
* [rabbus](https://github.com/rafaeljesus/rabbus) -  amqp交换和队列上的一个小包装器.
* [rabtap](https://github.com/jandelgado/rabtap) -  RabbitMQ瑞士军刀cli app.
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) -  RapidMQ是一个轻量级且可靠的库，用于管理本地消息队列.
* [rmqconn](https://github.com/sbabiv/rmqconn)   -  RabbitMQ重新连接.  amqp.Connection和amqp.Dial上的包装器.  在强制调用Close（）方法关闭之前，允许在连接断开时重新连接.
* [sarama](https://github.com/Shopify/sarama) - 去Apache Kafka的图书馆.
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) -  Redis支持针对移动设备的服务器端通知的统一推送服务.
* [zmq4](https://github.com/pebbe/zmq4) -  Go接口到ZeroMQ版本4.也适用于 [version 3](https://github.com/pebbe/zmq3) 和 [version 2](https://github.com/pebbe/zmq2).

## Microsoft Office

### Microsoft Excel
*使用Microsoft Excel的库.*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - 用于读写Microsoft Excel™（XLSX）文件的Golang库.
* [go-excel](https://github.com/szyhf/go-excel) - 一个简单而轻便的阅读器，可以像桌子一样读取与数据库类似的Excel.
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) -  Golang绑定libxlsxwriter写XLSX（Microsoft Excel）中的文件.
* [xlsx](https://github.com/tealeg/xlsx) - 用于简化读取Go程序中最新版Microsoft Excel使用的XML格式的库.
* [xlsx](https://github.com/plandem/xlsx) - 在Go程序中快速安全地读取/更新现有Microsoft Excel文件的方法.

## Miscellaneous

### Dependency Injection
*用于依赖注入的库.*

* [alice](https://github.com/magic003/alice) -  Golang的附加依赖注入容器.
* [dig](https://github.com/uber-go/dig) -  Go的基于反射的依赖注入工具包.
* [fx](https://github.com/uber-go/fx) - 基于依赖注入的Go应用程序框架（建立在挖掘之上）.
* [wire](https://github.com/Fs02/wire) - 严格的运行依赖注入Golang.

### Project Layout

*用于构建项目的非官方模式集.*

* [go-sample](https://github.com/zitryss/go-sample) - 使用实际代码的Go应用程序项目的示例布局.
* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) -  Go生态系统中常见的历史和新兴项目布局模式集.
* [scaffold](https://github.com/catchplay/scaffold)   -  Scaffold生成入门Go项目布局.  让您专注于实施的业务逻辑.

### Strings
*用于处理字符串的库.*
* [strutil](https://github.com/ozgio/strutil) - 字符串实用程序
* [xstrings](https://github.com/huandu/xstrings) - 从其他语言移植的有用字符串函数的集合.

*这些图书馆放在这里，因为其他类别似乎都不合适.*

* [anagent](https://github.com/mudler/anagent) - 带有依赖注入的简约，可插拔的Golang evloop / timer处理程序.
* [antch](https://github.com/antchfx/antch) - 快速，强大且可扩展的Web爬行和抓取框架.
* [archiver](https://github.com/mholt/archiver) - 用于制作和提取.zip和.tar.gz档案的库和命令.
* [autoflags](https://github.com/artyom/autoflags) -  Go包自动从struct字段定义命令行标志.
* [avgRating](https://github.com/kirillDanshin/avgRating) - 根据Wilson Score Equation计算平均得分和评分.
* [banner](https://github.com/dimiro1/banner) - 在Go应用程序中添加漂亮的横幅.
* [base64Captcha](https://github.com/mojocn/base64Captcha) -  Base64captch支持数字，数字，字母，算术，音频和数字字母验证码.
* [battery](https://github.com/distatus/battery) - 跨平台，标准化的电池信息库.
* [bitio](https://github.com/icza/bitio) - 针对Go的高度优化的位级读取器和写入器.
* [browscap_go](https://github.com/digitalcrab/browscap_go) - 库GoLang [Browser Capabilities Project](http://browscap.org/).
* [captcha](https://github.com/steambap/captcha) - 包验证码为验证码生成提供了易于使用，不受任何影响的API.
* [conv](https://github.com/cstockton/go-conv) -  Package conv提供跨Go类型的快速直观转换.
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* [ffmt](https://github.com/go-ffmt/ffmt) - 为人类提供美化数据显示.
* [ghorg](https://github.com/gabrie30/ghorg) - 将所有repos从GitHub组织克隆到单个目录中.
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) -  Golang的通用对象池.
* [go-openapi](https://github.com/go-openapi) - 用于解析和利用open-api模式的软件包集合.
* [go-resiliency](https://github.com/eapache/go-resiliency) - 弹性模式为golang.
* [go-unarr](https://github.com/gen2brain/go-unarr) - 用于RAR，TAR，ZIP和7z档案的解压缩库.
* [gofakeit](https://github.com/brianvoe/gofakeit) - 用go编写的随机数据生成器.
* [gommit](https://github.com/antham/gommit) - 分析git commit消息以确保它们遵循定义的模式.
* [gopsutil](https://github.com/shirou/gopsutil) - 用于检索进程和系统利用率的跨平台库（CPU，内存，磁盘等）.
* [gosh](https://github.com/osamingo/gosh) - 提供Go统计处理程序，结构，度量方法.
* [gosms](https://github.com/haxpax/gosms) -  Go中您自己的本地SMS网关，可用于发送短信.
* [gountries](https://github.com/pariz/gountries) - 公开国家和细分数据的包.
* [health](https://github.com/dimiro1/health) - 易于使用，可扩展的健康检查库.
* [healthcheck](https://github.com/etherlabsio/healthcheck) -  RESTful服务的固定和并发健康检查HTTP处理程序.
* [hostutils](https://github.com/Wing924/hostutils) - 用于打包和解包FQDN列表的golang库.
* [indigo](https://github.com/osamingo/indigo) - 使用Sonyflake并由Base58编码的分布式唯一ID生成器.
* [lk](https://github.com/hyperboloide/lk) -  golang的简单许可库.
* [llvm](https://github.com/llir/llvm) - 用于在纯Go中与LLVM IR交互的库.
* [metrics](https://github.com/pascaldekloe/metrics) - 指标检测和普罗米修斯博览会的图书馆.
* [morse](https://github.com/alwindoss/morse) - 要转换为莫尔斯代码的库.
* [numa](https://github.com/lrita/numa)   -  NUMA是一个实用程序库，用go编写.  它帮助我们编写了一些NUMA-AWARED代码.
* [pdfgen](https://github.com/hyperboloide/pdfgen) - 用于从Json请求生成PDF的HTTP服务.
* [persian](https://github.com/mavihq/persian) - 一些波斯语语言实用程序.
* [sandid](https://github.com/aofei/sandid) - 地球上每粒沙子都有自己的ID.
* [shellwords](https://github.com/Wing924/shellwords) - 一个Golang库，用于根据UNIX Bourne shell的单词解析规则操作字符串.
* [shortid](https://github.com/teris-io/shortid) - 分布式生成超短，唯一，非顺序，URL友好ID.
* [stats](https://github.com/go-playground/stats) - 监控MemStats +系统统计数据，如内存，交换和CPU，并通过UDP发送到任何你想要的日志记录等...
* [turtle](https://github.com/hackebrot/turtle) -  Go的Emojis.
* [url-shortener](https://github.com/pantrif/url-shortener) - 具有mysql支持的现代，强大且强大的URL缩短微服务.
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - 生成样板http输入和输出处理.
* [xdg](https://github.com/rkoesters/xdg) - 在Go中实现的FreeDesktop.org（xdg）规范.
* [xkg](https://github.com/go-xkg/xkg) -  X键盘抓取器.

## Natural Language Processing

*使用人类语言的图书馆.*

* [getlang](https://github.com/rylans/getlang) - 快速自然语言检测包.
* [go-eco](https://github.com/ThePaw/go-eco)   - 相似度，相异度和距离矩阵;  多样性，公平性和不平等措施;  物种丰富度估算;  coenocline模型.
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - 包和使用本地化文本的附带工具.
* [go-mystem](https://github.com/dveselov/mystem) -  CGo绑定到Yandex.Mystem  - 俄罗斯形态分析器.
* [go-nlp](https://github.com/nuance/go-nlp) - 用于处理离散概率分布的实用程序和用于执行NLP工作的其他工具.
* [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.
* [go-stem](https://github.com/agonopol/go-stem) - 实施搬运工干扰算法.
* [go-unidecode](https://github.com/mozillazg/go-unidecode) -  Unicode文本的ASCII音译.
* [go2vec](https://github.com/danieldk/go2vec) - 用于word2vec嵌入的读者和实用程序功能.
* [gojieba](https://github.com/yanyiwu/gojieba) - 这是Go的实现 [jieba](https://github.com/fxsjy/jieba) 其中一个中文分词算法.
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - 包括搬运工2的雪球libstemmer库的绑定.
* [gotokenizer](https://github.com/xujiajun/gotokenizer)   - 基于Golang的字典和Bigram语言模型的标记化器.  （现在只支持中文细分）
* [gounidecode](https://github.com/fiam/gounidecode) -  Go的Unicode音译器（也称为unidecode）.
* [gse](https://github.com/go-ego/gse)   - 进行有效的文本分割;  支持英语，中文，日语等.
* [icu](https://github.com/goodsign/icu)   - 用于icu4c C库检测和转换功能的Cgo绑定.  保证与版本50.1的兼容性.
* [kagome](https://github.com/ikawaha/kagome) - 用纯Go编写的JP形态分析器.
* [libtextcat](https://github.com/goodsign/libtextcat)   - 用于libtextcat C库的Cgo绑定.  保证与2.2版兼容.
* [MMSEGO](https://github.com/awsong/MMSEGO) - 这是GO的实现 [MMSEG](http://technology.chtsai.org/mmseg/) 其中一个中文分词算法.
* [nlp](https://github.com/Shixzie/nlp) - 从字符串中提取值并使用nlp填充结构.
* [nlp](https://github.com/james-bowman/nlp) -  Go Natural Language Processing库支持LSA（潜在语义分析）.
* [paicehusk](https://github.com/rookii/paicehusk) -  Golang实现Paice / Husk词干算法.
* [petrovich](https://github.com/striker2000/petrovich) - 彼得罗维奇是一个图书馆，它根据语法情况调整俄语名称.
* [porter](https://github.com/a2800276/porter) - 这是一个相当简单的Port Porter C实现Porter词干算法的端口.
* [porter2](https://github.com/zhenjl/porter2) - 真正修复了波特2票.
* [prose](https://github.com/jdkato/prose) - 用于文本处理的库，支持标记化，词性标记，命名实体提取等.
* [RAKE.go](https://github.com/Obaied/RAKE.go) - 快速自动关键字提取算法（RAKE）的Go端口.
* [segment](https://github.com/blevesearch/segment) -  Go库，用于执行Unicode文本分段，如中所述 [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* [sentences](https://github.com/neurosnap/sentences) - 句子标记器：将文本转换为句子列表.
* [shamoji](https://github.com/osamingo/shamoji) -  shamoji是用Go编写的文字过滤包.
* [snowball](https://github.com/goodsign/snowball)   -  Go的Snowball stemmer port（cgo wrapper）.  提供词干提取功能 [Snowball native](http://snowball.tartarus.org/).
* [stemmer](https://github.com/dchest/stemmer)   - 用于Go编程语言的Stemmer包.  包括英语和德语词干分析器.
* [textcat](https://github.com/pebbe/textcat) -  Go包用于基于n-gram的文本分类，支持utf-8和原始文本.
* [whatlanggo](https://github.com/abadojack/whatlanggo)   -  Go的自然语言检测包.  支持84种语言和24种脚本（书写系统，如拉丁语，西里尔语等）.
* [when](https://github.com/olebedev/when) - 具有可插拔规则的自然EN和RU语言日期/时间解析器.

## Networking

*用于处理网络各层的库.*

* [arp](https://github.com/mdlayher/arp) - 包arp实现ARP协议，如RFC 826中所述.
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - 通过TCP流式传输协议缓冲数据变得简单.
* [canopus](https://github.com/zubairhamed/canopus) -  CoAP客户端/服务器实施（RFC 7252）.
* [cidranger](https://github.com/yl2chen/cidranger) - 快速IP到CIDR查找Go.
* [dhcp6](https://github.com/mdlayher/dhcp6) - 包dhcp6实现DHCPv6服务器，如RFC 3315中所述.
* [dns](https://github.com/miekg/dns) - 去图书馆使用DNS.
* [ether](https://github.com/songgao/ether) - 用于发送和接收以太网帧的跨平台Go包.
* [ethernet](https://github.com/mdlayher/ethernet) - 包以太网实现了IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标记的编组和解组.
* [fasthttp](https://github.com/valyala/fasthttp) - 包fasthttp是Go的快速HTTP实现，比net / http快10倍.
* [fortio](https://github.com/fortio/fortio)   - 加载测试库和命令行工具，高级回显服务器和Web UI.  允许指定设置的每秒查询负载和记录延迟直方图以及其他有用的统计信息并对其进行图形化.  Tcp，Http，gRPC.
* [ftp](https://github.com/jlaffaye/ftp) - 包ftp实现了一个FTP客户端，如中所述 [RFC 959](http://tools.ietf.org/html/rfc959).
* [gmqtt](https://github.com/DrmagicE/gmqtt) -  Gmqtt是一个灵活的高性能MQTT代理库，完全实现MQTT协议V3.1.1.
* [gNxI](https://github.com/google/gnxi) - 使用gNMI和gNOI协议的网络管理工具集合.
* [go-getter](https://github.com/hashicorp/go-getter) - 使用URL从各种来源下载文件或目录的库.
* [go-stun](https://github.com/ccding/go-stun) - 实施STUN客户端（RFC 3489和RFC 5389）.
* [gobgp](https://github.com/osrg/gobgp) - 使用Go编程语言实现的BGP.
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - 包golibwireshark使用libwireshark库解码pcap文件并分析解剖数据.
* [gopacket](https://github.com/google/gopacket) - 使用libpcap绑定转到库处理数据包.
* [gopcap](https://github.com/akrennmair/gopcap) - 去libpcap的包装器.
* [goshark](https://github.com/sunwxg/goshark) - 包goshark使用tshark解码IP数据包并创建数据结构来分析数据包.
* [gosnmp](https://github.com/soniah/gosnmp) - 用于执行SNMP操作的Native Go库.
* [gotcp](https://github.com/gansidui/gotcp) -  Go包快速编写tcp应用程序.
* [grab](https://github.com/cavaliercoder/grab) -  Go包管理文件下载.
* [graval](https://github.com/koofr/graval) - 实验FTP服务器框架.
* [HTTPLab](https://github.com/gchaincl/httplab) -  HTTPLabs允许您检查HTTP请求和伪造响应.
* [iplib](https://github.com/c-robinson/iplib) - 受到python启发的用于处理IP地址的库（net.IP，net.IPNet） [ipaddress](https://docs.python.org/3/library/ipaddress.html) 和红宝石 [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
* [jazigo](https://github.com/udhos/jazigo) -  Jazigo是一个用Go编写的工具，用于检索多个网络设备的配置.
* [kcp-go](https://github.com/xtaci/kcp-go) -  KCP  - 快速可靠的ARQ协议.
* [kcptun](https://github.com/xtaci/kcptun) - 基于KCP协议的极其简单和快速的udp隧道.
* [lhttp](https://github.com/fanux/lhttp) - 强大的websocket框架，更轻松地构建您的IM服务器.
* [linkio](https://github.com/ian-kent/linkio) - 读/写器接口的网络链接速度模拟.
* [llb](https://github.com/kirillDanshin/llb)   - 对于代理服务器来说，这是一个非常简单但快速的后端.  可用于快速重定向到预定义域，内存分配为零，响应速度快.
* [mdns](https://github.com/hashicorp/mdns) -  Golang中的简单mDNS（多播DNS）客户端/服务器库.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) -  Paho Go Client提供了一个MQTT客户端库，用于通过TCP，TLS或WebSockets连接到MQTT代理.
* [NFF-Go](https://github.com/intel-go/nff-go) - 为云和裸机（前YANFF）快速开发高性能网络功能的框架.
* [packet](https://github.com/aerogo/packet)   - 通过TCP和UDP发送数据包.  如果需要，它可以缓冲消息和热交换连接.
* [peerdiscovery](https://github.com/schollz/peerdiscovery) - 使用UDP多播进行跨平台本地对等体发现的Pure Go库.
* [portproxy](https://github.com/aybabtme/portproxy) - 简单的TCP代理，它为不支持它的API添加了CORS支持.
* [publicip](https://github.com/polera/publicip) - 包publicip返回面向公众的IPv4地址（互联网出口）.
* [quic-go](https://github.com/lucas-clemente/quic-go) - 纯Go中QUIC协议的实现.
* [raw](https://github.com/mdlayher/raw) -  Package raw允许在设备驱动程序级别为网络接口读取和写入数据.
* [sftp](https://github.com/pkg/sftp) - 软件包sftp实现SSH文件传输协议，如https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt中所述.
* [ssh](https://github.com/gliderlabs/ssh) - 用于构建SSH服务器的高级API（包装crypto / ssh）.
* [sslb](https://github.com/eduardonunesp/sslb) - 这是一个超级简单的负载均衡器，只是一个实现某种性能的小项目.
* [stun](https://github.com/go-rtc/stun) - 执行RFC 5389 STUN协议.
* [tcp_server](https://github.com/firstrow/tcp_server) - 更快地建立tcp服务器库.
* [tspool](https://github.com/two/tspool) -  TCP库使用工作池来提高性能并保护您的服务器.
* [utp](https://github.com/anacrolix/utp) - 去uTP微传输协议实现.
* [water](https://github.com/songgao/water) - 简单的TUN / TAP库.
* [webrtc](https://github.com/pions/webrtc) -  WebRTC API的纯Go实现.
* [winrm](https://github.com/masterzen/winrm) - 使用WinRM客户端在Windows机器上远程执行命令.
* [xtcp](https://github.com/xfxdev/xtcp) -  TCP Server Framework，具有同步全双工通信，正常关闭，自定义协议.

### HTTP Clients

*用于发出HTTP请求的库.*

* [gentleman](https://github.com/h2non/gentleman) - 功能齐全的插件驱动的HTTP客户端库.
* [goreq](https://github.com/smallnest/goreq) - 基于gorequest的增强型简化HTTP客户端.
* [grequests](https://github.com/levigross/grequests) - 着名的Requests图书馆的Go“克隆”.
* [heimdall](https://github.com/gojektech/heimdall) - 具有重试和hystrix功能的增强型http客户端.
* [pester](https://github.com/sethgrid/pester) - 使用重试，退避和并发来进行HTTP客户端调用.
* [rq](https://github.com/ddo/rq) -  golang stdlib HTTP客户端的更好的界面.
* [sling](https://github.com/dghubble/sling) -  Sling是一个用于创建和发送API请求的Go HTTP客户端库.

## OpenGL

* Go中使用OpenGL的库.*

* [gl](https://github.com/go-gl/gl) - 转到OpenGL的绑定（通过发光生成）.
* [glfw](https://github.com/go-gl/glfw) - 为GLFW 3绑定绑定.
* [goxjs/gl](https://github.com/goxjs/gl) - 进入跨平台的OpenGL绑定（OS X，Linux，Windows，浏览器，iOS，Android）.
* [goxjs/glfw](https://github.com/goxjs/glfw) - 转到跨平台的glfw库，用于创建OpenGL上下文和接收事件.
* [mathgl](https://github.com/go-gl/mathgl) -  Pure Go数学包，专门用于3D数学，灵感来自GLM.

## ORM

*实现对象关系映射或数据映射技术的库.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm)   - 强大的orm框架.  支持：pq / mysql / sqlite3.
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* [go-queryset](https://github.com/jirfag/go-queryset) - 具有代码生成的100％类型安全ORM和基于GORM的MySQL，PostgreSQL，Sqlite3，SQL Server支持.
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - 灵活且功能强大的SQL字符串构建器库以及零配置ORM.
* [go-store](https://github.com/gosuri/go-store) - 简单快速的Redis支持的Go键值存储库.
* [GORM](https://github.com/jinzhu/gorm) -  Golang梦幻般的ORM库，旨在让开发人员更加友好.
* [gorp](https://github.com/go-gorp/gorp) -  Go关系持久性，Go的ORM-ish库.
* [grimoire](https://github.com/Fs02/grimoire)   -  Grimoire是golang的数据库访问层和验证.  （支持：MySQL，PostgreSQL和SQLite3）.
* [lore](https://github.com/abrahambotros/lore) -  Go的简单轻量级伪ORM /伪结构映射环境.
* [Marlow](https://github.com/dadleyy/marlow) - 从项目结构生成ORM以进行编译时安全保证.
* [pop/soda](https://github.com/gobuffalo/pop) -  MySQL，PostgreSQL和SQLite的数据库迁移，创建，ORM等.
* [QBS](https://github.com/coocood/qbs)   - 代表按结构查询.  一个Go ORM.
* [reform](https://github.com/go-reform/reform) - 基于非空接口和代码生成，更好的ORM for Go.
* [SQLBoiler](https://github.com/volatiletech/sqlboiler)   -  ORM发电机.  生成针对您的数据库模式定制的功能强大且超快的ORM.
* [upper.io/db](https://github.com/upper/db) - 单一界面，通过使用包装成熟数据库驱动程序的适配器与不同数据源进行交互.
* [Xorm](https://github.com/go-xorm/xorm) - 简单而强大的ORM for Go.
* [Zoom](https://github.com/albrow/zoom) - 基于Redis构建的超快数据存储和查询引擎.

## Package Management

*依赖和包管理的官方工具*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more)   - 模块是源代码交换和版本控制的单元.  go命令直接支持使用模块，包括记录和解析对其他模块的依赖性.

*包装管理的官方实验工具*

* [dep](https://github.com/golang/dep) - 去依赖工具.
* [vgo](https://go.googlesource.com/vgo/) -  Versioned Go.

*用于包和依赖管理的非官方库.*

* [gigo](https://github.com/LyricalSecurity/gigo) - 用于golang的类似PIP的依赖工具，支持私有存储库和哈希.
* [glide](https://github.com/Masterminds/glide)   - 轻松管理您的golang供应商和销售包裹.  灵感来自Maven，Bundler和Pip等工具.
* [godep](https://github.com/tools/godep) -  go的依赖工具，godep通过修复它们的依赖关系来帮助重复构建包.
* [gom](https://github.com/mattn/gom) - 去经理 - 捆绑去.
* [goop](https://github.com/nitrous-io/goop) - 受Bundler启发的Go（golang）简单依赖管理器.
* [gop](https://github.com/lunny/gop) - 从GOPATH构建和管理您的Go应用程序.
* [gopm](https://github.com/gpmgo/gopm) - 去套餐经理.
* [govendor](https://github.com/kardianos/govendor)   - 去套餐经理.  使用与标准供应商文件一起使用的供应商工具.
* [gpm](https://github.com/pote/gpm) -  Go的Barebones依赖管理器.
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - 使用Git的最小依赖版本.
* [mvn-golang](https://github.com/raydac/mvn-golang) - 插件，提供在Maven项目基础架构中自动加载Golang SDK，依赖关系管理和启动构建环境的方法.
* [nut](https://github.com/jingweno/nut) - 供应商Go依赖项.
* [VenGO](https://github.com/DamnWidget/VenGO) - 创建和管理可导出的隔离虚拟环境.

## Query Language

* [gojsonq](https://github.com/thedevsaddam/gojsonq) - 一个简单的Go包来查询JSON数据.
* [graphql](https://github.com/tmc/graphql) -  graphql解析器+实用程序.
* [graphql](https://github.com/neelance/graphql-go) -  GraphQL服务器，重点是易用性.
* [graphql-go](https://github.com/graphql-go/graphql) -  Go的GraphQL实现.
* [jsonql](https://github.com/elgs/jsonql) - 在Golang JSON查询表达式库.
* [jsonslice](https://github.com/bhmj/jsonslice) - 使用高级过滤器的Jsonpath查询.
* [rql](https://github.com/a8m/rql) -  REST API的资源查询语言.

## Resource Embedding

* [esc](https://github.com/mjibson/esc) - 将文件嵌入到Go程序中，并为它们提供http.FileSystem接口.
* [fileb0x](https://github.com/UnnoTed/fileb0x) - 嵌入文件的简单工具，专注于“自定义”，易于使用.
* [go-embed](https://github.com/pyros2097/go-embed) - 生成go代码以将资源文件嵌入到库或可执行文件中.
* [go-resources](https://github.com/omeid/go-resources) - 使用Go嵌入不同的资源.
* [go.rice](https://github.com/GeertJohan/go.rice) -  go.rice是一个Go包，可以很容易地处理html，js，css，图像和模板等资源.
* [packr](https://github.com/gobuffalo/packr) - 将静态文件嵌入Go二进制文件的简单方法.
* [statics](https://github.com/go-playground/statics) - 将静态资源嵌入到单个二进制编译的go文件中+使用http.FileSystem +符号链接.
* [statik](https://github.com/rakyll/statik) - 将静态文件嵌入Go可执行文件.
* [templify](https://github.com/wlbr/templify) - 将外部模板文件嵌入到Go代码中以创建单个文件二进制文件.
* [vfsgen](https://github.com/shurcooL/vfsgen) - 生成静态实现给定虚拟文件系统的vfsdata.go文件.

## Science and Data Analysis

*用于科学计算和数据分析的图书馆.*

* [assocentity](https://github.com/ndabAP/assocentity) - 包关联返回从单词到给定实体的平均距离.
* [bradleyterry](https://github.com/seanhagen/bradleyterry) - 提供用于成对比较的Bradley-Terry模型.
* [chart](https://github.com/vdobler/chart)   -  Go的简单图表绘图库.  支持许多图形类型.
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) -  Go用于机器学习和统计的数据帧（类似于熊猫）.
* [evaler](https://github.com/soniah/evaler) - 简单浮点算术表达式求值程序.
* [ewma](https://github.com/VividCortex/ewma) - 指数加权移动平均线.
* [geom](https://github.com/skelterjohn/geom) -  golang的2D几何体.
* [go-dsp](https://github.com/mjibson/go-dsp) -  Go的数字信号处理.
* [go-fn](https://github.com/ematvey/go-fn) - 用Go语言编写的数学函数，不包括在数学pkg中.
* [go-gt](https://github.com/ThePaw/go-gt) - 用“Go”语言编写的图论算法.
* [gocomplex](https://github.com/varver/gocomplex) -  Go编程语言的复数库.
* [goent](https://github.com/kzahedi/goent) - 实施熵措施.
* [gohistogram](https://github.com/VividCortex/gohistogram) - 数据流的近似直方图.
* [gonum](https://github.com/gonum/gonum)   -  Gonum是Go编程语言的一组数字库.  它包含用于矩阵，统计，优化等的库.
* [gonum/plot](https://github.com/gonum/plot) -  gonum / plot提供了一个用于在Go中构建和绘制图的API.
* [goraph](https://github.com/gyuho/goraph) -  Pure Go图论库（数据结构，算法可视化）.
* [gosl](https://github.com/cpmech/gosl) - 使用线性代数，FFT，几何，NURBS，数值方法，概率，优化，微分方程等科学库.
* [GoStats](https://github.com/OGFris/GoStats) -  GoStats是一个用于数学统计的开源GoLang库，主要用于机器学习领域，它涵盖了大多数统计测量功能.
* [graph](https://github.com/yourbasic/graph) - 基本图算法库.
* [ode](https://github.com/ChristopherRabotin/ode) - 普通微分方程（ODE）求解器，支持扩展状态和基于通道的迭代停止条件.
* [orb](https://github.com/paulmach/orb) - 具有剪切的2D几何类型，GeoJSON和Mapbox Vector Tile支持.
* [pagerank](https://github.com/alixaxel/pagerank) -  Go中实现的加权PageRank算法.
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - 微小的线性插值库.
* [PiHex](https://github.com/claygod/PiHex) - 为十六进制数Pi实现“Bailey-Borwein-Plouffe”算法.
* [rootfinding](https://github.com/khezen/rootfinding) - 用于查找二次函数根的根查找算法库.
* [sparse](https://github.com/james-bowman/sparse) -  Go支持线性代数的稀疏矩阵格式，支持科学和机器学习应用，与gonum矩阵库兼容.
* [stats](https://github.com/montanaflynn/stats) -  Golang标准库中缺少常用功能的统计包.
* [streamtools](https://github.com/nytlabs/streamtools) - 用于处理数据流的通用图形工具.
* [TextRank](https://github.com/DavidBelicza/TextRank) -  Golang中的TextRank实现，具有可扩展功能（摘要，加权，短语提取）和多线程（goroutine）支持.
* [triangolatte](https://github.com/tchayen/triangolatte)   -  2D三角测量库.  允许将线条和多边形（均基于点）转换为GPU的语言.

## Security

*用于帮助您提高应用程序安全性的库.*

* [acmetool](https://github.com/hlandau/acme) - 具有自动续订功能的ACME（Let&#39;s Encrypt）客户端工具.
* [acra](https://github.com/cossacklabs/acra) - 网络加密代理，用于保护基于数据库的应用程序免受数据泄漏：强选择性加密，SQL注入防护，入侵检测系统.
* [argon2pw](https://github.com/raja/argon2pw) - 具有恒定时间密码比较的Argon2密码哈希生成.
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - 自动配置让我们加密证书并启动TLS服务器.
* [BadActor](https://github.com/jaredfolkins/badactor) - 以fail2ban的精神构建的内存，应用程序驱动的jailer.
* [Cameradar](https://github.com/Ullaakut/cameradar) - 远程破解来自监控摄像机的RTSP流的工具和库.
* [go-yara](https://github.com/hillu/go-yara) - 去绑定 [YARA](https://github.com/plusvic/yara)，“用于恶意软件研究人员（以及其他所有人）的模式匹配瑞士刀”.
* [goArgonPass](https://github.com/dwin/goArgonPass) -  Argon2密码哈希和验证，旨在与现有的Python和PHP实现兼容.
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - 一个可能是偏执的包，用于安全散列和加密密码.
* [Interpol](https://bitbucket.org/vahidi/interpol) - 用于模糊测试和渗透测试的基于规则的数据生成器.
* [jwc](https://github.com/khezen/jwc) -  JSON Web Cryptography库.
* [lego](https://github.com/xenolf/lego) -  Pure Go ACME客户端库和CLI工具（用于Let的加密）.
* [memguard](https://github.com/awnumar/memguard) - 用于处理内存中敏感值的纯Go库.
* [nacl](https://github.com/kevinburke/nacl) - 去实施NaCL的API集.
* [passlib](https://github.com/hlandau/passlib) -  Futureproof密码哈希库.
* [secure](https://github.com/unrolled/secure) -  Go的HTTP中间件，有助于快速获得安全性.
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) -  Scrypt软件包，内置简单明了的API和自动成本校准功能.
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - 使用ssh密钥加密/解密.
* [sslmgr](https://github.com/adrianosela/sslmgr) - 使用acme / autocert周围的高级包装器轻松实现SSL证书.

## Serialization

*用于二进制序列化的库和工具.*

* [asn1](https://github.com/PromonLogicalis/asn1) - 用于golang的Asn.1 BER和DER编码库.
* [bambam](https://github.com/glycerine/bambam) - 来自Cap&#39;n Proto架构的发生器.
* [bel](https://github.com/32leaves/bel)   - 从Go结构/接口生成TypeScript接口.  对JSON RPC很有用.
* [binstruct](https://github.com/ghostiam/binstruct) -  Golang二进制解码器，用于将数据映射到结构中.
* [colfer](https://github.com/pascaldekloe/colfer) -  Colfer二进制格式的代码生成.
* [csvutil](https://github.com/jszwec/csvutil) - 针对原生Go结构的高性能，惯用CSV记录编码和解码.
* [fwencoder](https://github.com/o1egl/fwencoder) -  Go的固定宽度文件解析器（编码和解码库）.
* [go-capnproto](https://github.com/glycerine/go-capnproto) -  Cap&#39;n Proto库和解析器.
* [go-codec](https://github.com/ugorji/go) - 用于msgpack，cbor和json的高性能，功能丰富，惯用的编码，解码和rpc库，以及基于运行时的OR代码生成支持.
* [gogoprotobuf](https://github.com/gogo/protobuf) - 使用小工具的Go协议缓冲区.
* [goprotobuf](https://github.com/golang/protobuf) - 以库和协议编译器插件的形式支持Google的协议缓冲区.
* [jsoniter](https://github.com/json-iterator/go) - 高性能100％兼容直接替代“encoding / json”.
* [mapstructure](https://github.com/mitchellh/mapstructure) - 使用库将通用映射值解码为本机Go结构.
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) -  GoLang库，用于处理PHP会话格式和PHP Serialize / Unserialize函数.
* [structomap](https://github.com/tuvistavie/structomap) - 库可以轻松动态地从静态结构生成地图.

## Server Applications

* [algernon](https://github.com/xyproto/algernon) - 内置支持Lua，Markdown，GCSS和Amber的HTTP / 2 Web服务器.
* [Caddy](https://github.com/mholt/caddy) -  Caddy是一种易于配置和使用的替代HTTP / 2 Web服务器.
* [consul](https://www.consul.io/) -  Consul是一种服务发现，监控和配置工具.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers.
* [discovery](https://github.com/Bilibili/discovery) - 用于弹性中间层负载平衡和故障转移的注册表.
* [etcd](https://github.com/coreos/etcd) - 用于共享配置和服务发现的高可用密钥值存储.
* [Fider](https://github.com/getfider/fider) -  Fider是一个收集和整理客户反馈的开放平台.
* [Flagr](https://github.com/checkr/flagr) -  Flagr是一个开源功能标记和A / B测试服务.
* [flipt](https://github.com/markphelps/flipt) - 用Go和Vue.js编写的自包含功能标志解决方案
* [jackal](https://github.com/ortuman/jackal) - 用Go编写的XMPP服务器.
* [minio](https://github.com/minio/minio) -  Minio是一个分布式对象存储服务器.
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) -  Nginx日志解析器和导出器到Prometheus.
* [nsq](http://nsq.io/) - 实时分布式消息传递平台.
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) - 将数据库事件从PostgreSQL流式传输到Kafka.
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) - 继电器负载平衡黎曼事件和/或将它们转换为碳.
* [RoadRunner](https://github.com/spiral/roadrunner) - 高性能PHP应用程序服务器，负载平衡器和进程管理器.
* [yakvs](https://git.sci4me.com/sci4me/yakvs) - 小型，联网，内存中的键值存储.

## Template Engines

*用于模板和lexing的库和工具.*

* [ace](https://github.com/yosssi/ace)   -  Ace是Go的HTML模板引擎，灵感来自Slim和Jade.  Ace是对Gold的改进.
* [amber](https://github.com/eknkc/amber) -  Amber是Go编程语言的优雅模板引擎.它源自HAML和Jade.
* [damsel](https://github.com/dskinner/damsel) - 标记语言，通过css选择器提供html概述，可通过pkg html / template等扩展.
* [ego](https://github.com/benbjohnson/ego)   - 轻量级模板语言，可让您在Go中编写模板.  模板被翻译成Go并编译.
* [extemplate](https://github.com/dannyvankooten/extemplate) - 围绕html /模板的微小包装，以允许轻松的基于文件的模板继承.
* [fasttemplate](https://github.com/valyala/fasttemplate)   - 简单快速的模板引擎.  替换模板占位符的速度比快10倍 [text/template](http://golang.org/pkg/text/template/).
* [gofpdf](https://github.com/jung-kurt/gofpdf) -  PDF文档生成器，支持文本，绘图和图像.
* [goview](https://github.com/foolin/goview) -  Goview是一个轻量级，极简主义和惯用的模板库，基于golang html / template构建Go Web应用程序.
* [hero](https://github.com/shiyanhui/hero) -  Hero是一款方便，快速且功能强大的模板引擎.
* [jet](https://github.com/CloudyKit/jet) -  Jet模板引擎.
* [kasia.go](https://github.com/ziutek/kasia.go) - 用于HTML和其他文本文档的模板系统 - 实现.
* [liquid](https://github.com/osteele/liquid) - 实施Shopify Liquid模板.
* [mustache](https://github.com/hoisie/mustache) - 去实现Mustache模板语言.
* [pongo2](https://github.com/flosch/pongo2) -  Go的Django式模板引擎.
* [quicktemplate](https://github.com/valyala/quicktemplate)   - 快速，功能强大且易于使用的模板引擎.  将模板转换为Go代码，然后编译它.
* [raymond](https://github.com/aymerick/raymond) -  Go中完整的把手实施.
* [Razor](https://github.com/sipin/gorazor) -  Razor视图的Golang引擎.
* [Soy](https://github.com/robfig/soy) - 关闭Go的关闭模板（又名大豆模板） [official spec](https://developers.google.com/closure/templates/).
* [velvet](https://github.com/gobuffalo/velvet) -  Go中完整的把手实施.

## Testing

*用于测试代码库和生成测试数据的库.*

*测试框架
    * [assert](https://github.com/go-playground/assert) - 基本断言库与侧面本机测试一起使用，带有用于自定义断言的构建块.
    * [badio](https://github.com/cavaliercoder/badio) -  Go的`testing / iotest`包的扩展.
    * [baloo](https://github.com/h2non/baloo) - 轻松实现富有表现力和多功能的端到端HTTP API测试.
    * [biff](https://github.com/fulldump/biff) - 分叉测试框架，兼容BDD.
    * [bro](https://github.com/marioidival/bro) - 在目录中监视文件并为它们运行测试.
    * [charlatan](https://github.com/percolate/charlatan) - 为测试生成虚假接口实现的工具.
    * [commander](https://github.com/SimonBaeumer/commander) - 用于在Windows，Linux和osx上测试cli应用程序的工具.
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - 清理数据库以进行测试，灵感来自Ruby中的`database_cleaner`.
    * [dsunit](https://github.com/viant/dsunit) -  SQL，NoSQL，结构化文件的数据存储测试.
    * [endly](https://github.com/viant/endly) - 声明式端到端功能测试.
    * [frisby](https://github.com/verdverm/frisby) -  REST API测试框架.
    * [ginkgo](http://onsi.github.io/ginkgo/) -  Go的BDD测试框架.
    * [go-carpet](https://github.com/msoap/go-carpet) - 用于查看终端中测试覆盖范围的工具.
    * [go-cmp](https://github.com/google/go-cmp) - 用于比较测试中的Go值的包.
    * [go-mutesting](https://github.com/zimmski/go-mutesting) -  Go源代码的变异测试.
    * [go-testdeep](https://github.com/maxatome/go-testdeep) - 非常灵活的golang深度比较，扩展了go测试包.
    * [go-vcr](https://github.com/dnaeon/go-vcr) - 记录并重放您的HTTP交互，以进行快速，确定和准确的测试.
    * [goblin](https://github.com/franela/goblin) - 摩卡喜欢Go的测试框架.
    * [gocheck](http://labix.org/gocheck) - 更高级的测试框架替代gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - 具有Web UI和实时重新加载的BDD风格框架.
    * [gocrest](https://github.com/corbym/gocrest) - 用于Go断言的可组合的hamcrest-like匹配器.
    * [godog](https://github.com/DATA-DOG/godog) - 像Go的BDD框架一样的Cucumber或Behat.
    * [gofight](https://github.com/appleboy/gofight) - 对于路由器Golang架构处理器API测试.
    * [gogiven](https://github.com/corbym/gogiven) -  Go的YATSPEC类BDD测试框架.
    * [gomatch](https://github.com/jfilipczyk/gomatch) - 创建用于针对模式测试JSON的库.
    * [gomega](http://onsi.github.io/gomega/) -  Rspec像matcher / assertion库.
    * [GoSpec](https://github.com/orfjackal/gospec) -  Go编程语言的BDD风格测试框架.
    * [gospecify](https://github.com/stesla/gospecify)   - 这提供了用于测试Go代码的BDD语法.  任何使用过像rspec这样的库的人都应该很熟悉.
    * [gosuite](https://github.com/pavlo/gosuite) - 通过利用Go1.7的Subtests为轻量级测试套件提供设置/拆卸设施以“测试”.
    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) - 一组包，用于扩充go测试包并支持常见模式.
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - 声明性Matcher对象的流畅框架，当应用于输入值时，会生成自描述结果.
    * [httpexpect](https://github.com/gavv/httpexpect) - 简明，声明且易于使用的端到端HTTP和REST API测试.
    * [jsonassert](https://github.com/kinbiko/jsonassert) - 用于验证您的JSON有效负载是否已正确序列化的包.
    * [restit](https://github.com/yookoala/restit) -  Go micro framework帮助编写RESTful API集成测试.
    * [testcase](https://github.com/adamluzsi/testcase) - 行为驱动开发的惯用测试框架.
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) -  Rails的帮手，就像测试数据库应用程序的测试夹具一样.
    * [Testify](https://github.com/stretchr/testify) - 对标准测试包的神圣扩展.
    * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - 将markdown代码段转换为可测试的代码.
    * [testsql](https://github.com/zhulongcheng/testsql) - 在测试之前从SQL文件生成测试数据，并在完成后清除它.
    * [Tt](https://github.com/vcaesar/tt) - 简单而多彩的测试工具.
    * [wstest](https://github.com/posener/wstest) - 用于对websocket http.Handler进行单元测试的Websocket客户端.

*模拟
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - 用于生成自包含模拟对象的工具.
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - 用于测试数据库交互的模拟SQL驱动程序.
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - 基于单个事务的数据库驱动程序主要用于测试目
    * [gock](https://github.com/h2non/gock) - 多功能的HTTP模拟变得简单.
    * [gomock](https://github.com/golang/mock) -  Go编程语言的模拟框架.
    * [govcr](https://github.com/seborama/govcr) -  Golang的HTTP模拟：记录和重放用于离线测试的HTTP交互.
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - 用于记录和模拟具有可扩展中间件和易于使用的CLI的REST / SOAP API的HTTP（S）代理.
    * [httpmock](https://github.com/jarcoal/httpmock) - 轻松模拟来自外部资源的HTTP响应.
    * [minimock](https://github.com/gojuno/minimock) - 用于Go接口的模拟生成器.
    * [mockhttp](https://github.com/tv42/mockhttp) -  Go http.ResponseWriter的模拟对象.

*模糊测试和增量调试/减少/缩小.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - 随机测试系统.
    * [gofuzz](https://github.com/google/gofuzz) - 用于使用随机值填充go对象的库.
    * [Tavor](https://github.com/zimmski/tavor) - 通用模糊测试和增量调试框架.

* Selenium和浏览器控制工具.
    * [cdp](https://github.com/mafredri/cdp) -  Chrome调试协议的类型安全绑定，可与浏览器或实现它的其他调试目标一起使用.
    * [chromedp](https://github.com/knq/chromedp) - 一种驱动/测试Chrome，Safari，Edge，Android Webviews以及支持Chrome调试协议的其他浏览器的方法.
    * [ggr](https://github.com/aerokube/ggr) - 一个轻量级服务器，用于将Selenium Wedriver请求路由和代理到多个Selenium集线器.
    * [selenoid](https://github.com/aerokube/selenoid) - 在容器内启动浏览器的备用Selenium中心服务器.

*注射失败
    * [failpoint](https://github.com/pingcap/failpoint) - 执行 [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) 对于Golang.

## Text Processing

*用于解析和操作文本的库.*

*特定格式
    * [align](https://github.com/Guitarbum722/align) - 对齐文本的通用应用程序.
    * [allot](https://github.com/sbstjn/allot) -  CLI工具和机器人的占位符和通配符文本解析.
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - 将bbCode转换为HTML，允许您添加对自定义bbCode标记的支持.
    * [blackfriday](https://github.com/russross/blackfriday) -  Go中的Markdown处理器.
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) -  HTML Sanitizer.
    * [codetree](https://github.com/aerogo/codetree) - 解析缩进代码（python，pixy，scarlet等）并返回树结构.
    * [colly](https://github.com/asciimoo/colly) - 地鼠快速优雅的刮痧框架.
    * [commonregex](https://github.com/mingrammer/commonregex) -  Go的常用正则表达式的集合.
    * [dataflowkit](https://github.com/slotix/dataflowkit) -  Web scraping Framework将网站转换为结构化数据.
    * [did](https://github.com/ockam-network/did) -  DID（分散标识符）Go中的Parser和Stringer.
    * [doi](https://github.com/hscells/doi) -  Go中的文档对象标识符（doi）解析器.
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) -  Go的Editorconfig文件解析器和操纵器.
    * [enca](https://github.com/endeveit/enca) - 最小的cgo绑定 [libenca](http://cihar.com/software/enca/).
    * [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa.
    * [genex](https://github.com/alixaxel/genex) - 计算并将正则表达式扩展为所有匹配的字符串.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) -  GitHub Flavored Markdown渲染器（使用blackfriday），带有围栏代码块突出显示，可点击的标题锚链接.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - 固定宽度的文本格式（带反射的编码器/解码器）.
    * [go-humanize](https://github.com/dustin/go-humanize) - 将时间，数字和内存大小格式化为人类可读格式.
    * [go-nmea](https://github.com/adrianmo/go-nmea) - 用于Go语言的NMEA解析器库.
    * [go-runewidth](https://github.com/mattn/go-runewidth) - 获取字符或字符串固定宽度的函数.
    * [go-slugify](https://github.com/mozillazg/go-slugify) - 使用多种语言支持制作漂亮的slug.
    * [go-toml](https://github.com/pelletier/go-toml) - 使用查询支持和方便的cli工具转到TOML格式的库.
    * [go-vcard](https://github.com/emersion/go-vcard) - 解析并格式化vCard.
    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) -  Go的零宽度字符检测和删除.
    * [gofeed](https://github.com/mmcdole/gofeed) - 在Go中解析RSS和Atom提要.
    * [gographviz](https://github.com/awalterschulze/gographviz) - 解析Graphviz DOT语言.
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - 将字节格式化为字符串.
    * [gonameparts](https://github.com/polera/gonameparts) - 将人名解析为个别名称部分.
    * [goq](https://github.com/andrewstuart/goq) - 使用带有jQuery语法的struct标签声明解组HTML（使用GoQuery）.
    * [GoQuery](https://github.com/PuerkitoBio/goquery) -  GoQuery为Go语言带来了类似于jQuery的语法和一组特性.
    * [goregen](https://github.com/zach-klippenstein/goregen) - 用于从正则表达式生成随机字符串的库.
    * [gotext](https://github.com/leonelquinteros/gotext) -  Go的GNU gettext实用程序.
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - 用于确定unicode文本的自然语言的函数.
    * [htmlquery](https://github.com/antchfx/htmlquery) -  HTML的XPath查询包，允许您通过XPath表达式提取数据或从HTML文档中进行评估.
    * [inject](https://github.com/facebookgo/inject) - 包注入提供基于反射的注射器.
    * [ltsv](https://github.com/Wing924/ltsv) - 高性能 [LTSV (Labeled Tab Separeted Value)](http://ltsv.org/) Go的读者.
    * [mxj](https://github.com/clbanning/mxj)   - 将XML编码/解码为JSON或map [string] interface {};  使用点符号路径和通配符提取值.  替换x2j和j2x包.
    * [sdp](https://github.com/gortc/sdp) -  SDP：会话描述协议 [[RFC 4566](https://tools.ietf.org/html/rfc4566)].
    * [sh](https://github.com/mvdan/sh) -  Shell解析器和格式化程序.
    * [slug](https://github.com/gosimple/slug) - 具有多种语言支持的URL友好的slugify.
    * [Slugify](https://github.com/avelino/slugify) -  Go slugify应用程序处理字符串.
    * [syndfeed](https://github.com/zhengchun/syndfeed) -  Atom 1.0和RSS 2.0的联合供稿.
    * [toml](https://github.com/BurntSushi/toml) -  TOML配置格式（带反射的编码器/解码器）.
* 效用
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - 针对Go的基于消毒的脏化过滤器.
    * [gotabulate](https://github.com/bndr/gotabulate) - 使用Go轻松漂亮地打印表格数据.
    * [kace](https://github.com/codemodus/kace) - 涉及常见初始主义的常见案例转换.
    * [parseargs-go](https://github.com/nproc/parseargs-go) - 理解引号和反斜杠的字符串参数解析器.
    * [parth](https://github.com/codemodus/parth) -  URL路径分段解析.
    * [radix](https://github.com/yourbasic/radix) - 快速字符串排序算法.
    * [TySug](https://github.com/Dynom/TySug) - 关于键盘布局的替代建议.
    * [xj2go](https://github.com/stackerzzq/xj2go) - 将xml或json转换为struct.
    * [xurls](https://github.com/mvdan/xurls) - 从文本中提取网址.

## Third-party APIs

*用于访问第三方API的库.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - 去客户端库 [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda](https://github.com/ChimeraCoder/anaconda) - 转到Twitter 1.1 API的客户端库.
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) -  Go编程语言的官方AWS开发工具包.
* [brewerydb](https://github.com/naegelejd/brewerydb) -  Go库用于访问BreweryDB API.
* [cachet](https://github.com/andygrunwald/cachet) - 去客户端库 [Cachet (open source status page system)](https://cachethq.io/).
* [circleci](https://github.com/jszwedko/go-circleci) - 转到客户端库以与CircleCI的API进行交互.
* [clarifai](https://github.com/samuelcouch/clarifai) - 使用客户端库与Clarifai API进行交互.
* [codeship-go](https://github.com/codeship/codeship-go) - 使用客户端库与Codeship的API v2进行交互.
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - 转到客户端库以与Coinpaprika的API进行交互.
* [discordgo](https://github.com/bwmarrin/discordgo) - 转到Discord Chat API的绑定.
* [ethrpc](https://github.com/onrik/ethrpc) - 转到以太坊JSON RPC API的绑定.
* [facebook](https://github.com/huandu/facebook) -  Go Library支持Facebook Graph API.
* [fcm](https://github.com/maddevsio/fcm) -  Go Library for Firebase Cloud Messaging.
* [gads](https://github.com/emiddleton/gads) -  Google Adwords非官方API.
* [gami](https://github.com/bit4bit/gami) - 转到Asterisk Manager Interface的库.
* [gcm](https://github.com/Aorioli/gcm) - 使用Google Cloud Messaging库.
* [geo-golang](https://github.com/codingsince1985/geo-golang) - 去图书馆访问 [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/)，和 [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) 地理编码/反向地理编码API.
* [github](https://github.com/google/go-github) -  Go库用于访问GitHub REST API v3.
* [githubql](https://github.com/shurcooL/githubql) -  Go库访问GitHub GraphQL API v4.
* [go-chronos](https://github.com/axelspringer/go-chronos) - 去图书馆与互动 [Chronos](https://mesos.github.io/chronos/) Job Scheduler
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) -  HackerNews API的Tiny Go客户端.
* [go-imgur](https://github.com/koffeinsource/go-imgur) - 去客户端库 [imgur](https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) - 去客户端库 [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-marathon](https://github.com/gambol99/go-marathon) - 去图书馆与Mesosphere的Marathon PAAS互动.
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - 去客户端库访问 [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-sophos](https://github.com/esurdam/go-sophos) - 去客户端库 [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) 没有依赖关系.
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - 转到SPTrans Live API的客户端库.
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - 电报发布平台API客户端.
* [go-trending](https://github.com/和ygrunwald/go-trending) - 去图书馆进行访问 [trending repositories](https://github.com/trending) 和 [developers](https://github.com/trending/developers) 在Github.
* [go-twitch](https://github.com/knspriggs/go-twitch) - 去客户端与Twitch v3 API进行交互.
* [go-twitter](https://github.com/dghubble/go-twitter) - 转到Twitter v1.1 API的客户端库.
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - 去客户端库 [Unsplash.com](https://unsplash.com) API.
* [go-xkcd](https://github.com/nishanths/go-xkcd) - 转到xkcd API的客户端.
* [golyrics](https://github.com/mamal72/golyrics) -  Golyrics是一个Go库，用于从Wikia网站获取音乐歌词数据.
* [gomalshare](https://github.com/MonaxGT/gomalshare) - 去图书馆MalShare API [malshare.com](http://www.malshare.com/)
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - 去MusicBrainz WS2客户端库.
* [google](https://github.com/google/google-api-go-client) - 为Go自动生成的Google API.
* [google-analytics](https://github.com/chonthu/go-google-analytics) - 简单的包装，便于谷歌分析报告.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) -  Google Cloud API Go Client Library.
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - 去客户端库 [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [gostorm](https://github.com/jsgilmore/gostorm) -  GoStorm是一个Go库，它实现了编写Storm spouts和Go中的Bolts与Storm shell通信所需的通信协议.
* [hipchat](https://github.com/andybons/hipchat) - 该项目为Hipchat API实现了一个golang客户端库.
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - 通过XMPP与HipChat通信的golang包.
* [igdb](https://github.com/Henry-Sarabia/igdb) - 去客户端 [Internet Game Database API](https://api.igdb.com/).
* [Medium](https://github.com/Medium/medium-sdk-go) - 适用于Medium的OAuth2 API的Golang SDK.
* [megos](https://github.com/andygrunwald/megos) - 用于访问的客户端库 [Apache Mesos](http://mesos.apache.org/) cluster.
* [minio-go](https://github.com/minio/minio-go) - 适用于Amazon S3兼容云存储的Minio Go Library.
* [mixpanel](https://github.com/dukex/mixpanel) -  Mixpanel是一个库，用于跟踪事件并从您的应用程序向Mixpanel发送Mixpanel配置文件更新.
* [patreon-go](https://github.com/mxpv/patreon-go) - 去Patreon API的库.
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) -  PayPal支付API的包装.
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) -  Playlyfe Rest API Go SDK.
* [pushover](https://github.com/gregdel/pushover) - 转到Pushover API的包装器.
* [rrdaclient](https://github.com/Omie/rrdaclient)   -  Go Library访问statdns.com API，后者又是RRDA API.  HTTP上的DNS查询.
* [shopify](https://github.com/rapito/go-shopify) -  Go Library向Shopify API发出CRUD请求.
* [simples3](https://github.com/rhnvrm/simples3) - 简单没有多余装饰AWS S3库使用REST和V4签名用Go编写.
* [slack](https://github.com/nlopes/slack) -  Go中的Slack API.
* [smite](https://github.com/sergiotapia/smitego) -  Go包以包含对Smite游戏API的访问权限.
* [spotify](https://github.com/rapito/go-spotify) -  Go Library访问Spotify WEB API.
* [steam](https://github.com/sostronk/go-steam) -  Go Library与Steam游戏服务器进行交互.
* [stripe](https://github.com/stripe/stripe-go) - 转到Stripe API的客户端.
* [textbelt](https://github.com/dietsche/textbelt) - 转到textbelt.com txt消息传递API的客户端.
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - 简单的golang包与之沟通 [themoviedb.org](https://themoviedb.org).
* [translate](https://github.com/poorny/translate) - 去在线翻译包.
* [Trello](https://github.com/adlio/trello) - 转到Trello API的包装器.
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - 转到TripAdvisor API的包装器.
* [tumblr](https://github.com/mattcunningham/gumblr) - 转到Tumblr v2 API的包装器.
* [uptimerobot](https://github.com/bitfield/uptimerobot) - 转到Uptime Robot v2 API的包装器和命令行客户端.
* [webhooks](https://github.com/go-playground/webhooks) -  GhHub和Bitbucket的Webhook接收器.
* [wit-go](https://github.com/wit-ai/wit-go) - 转到wit.ai HTTP API的客户端.
* [ynab](https://github.com/brunomvsouza/ynab.go) - 转到YNAB API的包装器.
* [zooz](https://github.com/gojuno/go-zooz) - 转到Zooz API的客户端.

## Utilities

*通用工具和工具，让您的生活更轻松.*

* [abutil](https://github.com/bahlo/abutil) - 经常使用的Golang助手的收集.
* [apm](https://github.com/topfreegames/apm) - 使用HTTP API的Golang应用程序的进程管理器.
* [backscanner](https://github.com/icza/backscanner) - 类似于bufio.Scanner的扫描程序，但它以相反的顺序读取和返回行，从给定位置开始向后移动.
* [blank](https://github.com/Henry-Sarabia/blank) - 验证或删除字符串中的空格和空格.
* [boilr](https://github.com/tmrts/boilr) - 用于从样板模板创建项目的超快CLI工具.
* [chyle](https://github.com/antham/chyle) - 使用具有多种配置可能性的git存储库的Changelog生成器.
* [circuit](https://github.com/cep21/circuit) - 高效且功能齐全的Hystrix，如断路器模式的Go实现.
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - 围棋中的断路器.
* [clockwork](https://github.com/jonboulle/clockwork) -  golang的简单假时钟.
* [command](https://github.com/txgruppi/command) -  Go的命令模式，带有线程安全的串行和并行调度程序.
* [copy-pasta](https://github.com/jutkko/copy-pasta) - 通用多工作站剪贴板，使用S3作为存储后端.
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) 容器指标的界面（例如htop）.
* [ctxutil](https://github.com/posener/ctxutil) - 用于上下文的实用程序函数的集合.
* [Death](https://github.com/vrecan/death) - 使用信号管理应用程序关闭.
* [Deepcopier](https://github.com/ulule/deepcopier) -  Go的简单结构复制.
* [delve](https://github.com/derekparker/delve) - 去调试器.
* [dlog](https://github.com/kirillDanshin/dlog) - 编译时控制的记录器，使您的版本更小，而无需删除调试调用.
* [ergo](https://github.com/cristianoliveira/ergo) - 简化了在不同端口上运行的多个本地服务的管理.
* [evaluator](https://github.com/nullne/evaluator)   - 基于s表达式动态评估表达式.  它简单易用.
* [fastlz](https://github.com/digitalcrab/fastlz) - 包裹 [FastLz](http://fastlz.org/) （GoLang的免费，开源，便携式实时压缩库）.
* [filetype](https://github.com/h2non/filetype) - 小包以推断检查魔数签名的文件类型.
* [filler](https://github.com/yaronsumel/filler) - 使用“填充”标记填充结构的小实用程序.
* [filter](https://github.com/gookit/filter) - 提供Go数据的过滤，清理和转换.
* [fzf](https://github.com/junegunn/fzf) - 用Go编写的命令行模糊查找器.
* [gaper](https://github.com/maxcnunes/gaper) - 在崩溃或某些观看文件更改时构建并重新启动Go项目.
* [generate](https://github.com/go-playground/generate) - 运行在指定的路径或环境变量上递归生成，并可以通过正则表达式进行过滤.
* [ghokin](https://github.com/antham/ghokin) - 平行格式化器，没有外部依赖性为小黄瓜（黄瓜，behat ......）.
* [git-time-metric](https://github.com/git-time-metric/gtm) -  Git的简单，无缝，轻量级时间跟踪.
* [go-astitodo](https://github.com/asticode/go-astitodo) - 在GO代码中解析TODO.
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) -  go：生成用于包装golang插件导出的符号的工具（仅限1.8）.
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) -  Pure Go bsdiff和bspatch库和CLI工具.
* [go-dry](https://github.com/ungerik/go-dry) - 干的（不要重复自己）Go包.
* [go-funk](https://github.com/thoas/go-funk) -  Modern Go实用程序库，提供帮助程序（map，find，contains，filter，chunk，reverse，...）.
* [go-health](https://github.com/Talento90/go-health) - 运行状况包简化了向服务添加运行状况检查的方式.
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - 使用库将结构编码到Header字段中.
* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) -  Go包用于处理问题详细信息.
* [go-rate](https://github.com/beefsack/go-rate) -  Go的定时速率限制器.
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - 用Go编写的XML Sitemap生成器.
* [go-torch](https://github.com/uber/go-torch) -  Go程序的随机火焰图分析器.
* [go-trigger](https://github.com/sadlil/go-trigger) -  Go-lang全局事件触发器，使用id注册事件并从项目的任何位置触发事件.
* [goback](https://github.com/carlescere/goback) - 转到简单的指数退避包.
* [godaemon](https://github.com/VividCortex/godaemon) - 用于编写守护进程的实用程序.
* [godropbox](https://github.com/dropbox/godropbox) - 用于从Dropbox编写Go服务/应用程序的通用库.
* [gohper](https://github.com/cosiner/gohper) - 各种工具/模块有助于开发.
* [golarm](https://github.com/msempere/golarm) - 带系统事件的火警.
* [golog](https://github.com/mlimaloureiro/golog) - 简单轻便的CLI工具，可以跟踪您的任务.
* [gopencils](https://github.com/bndr/gopencils) - 小而简单的包，可轻松使用REST API.
* [goplaceholder](https://github.com/michiwend/goplaceholder) - 一个小的golang lib来生成占位符图像.
* [goreadability](https://github.com/philipjkim/goreadability) - 使用Facebook Open Graph和arc90可读性的网页摘要提取器.
* [goreleaser](https://github.com/goreleaser/goreleaser) - 尽可能快速，轻松地发送Go二进制文件.
* [goreporter](https://github.com/wgliang/goreporter) -  Golang工具，可进行静态分析，单元测试，代码审查和生成代码质量报告.
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - 具有几乎全部功能的SeaweedFS客户端库.
* [gostrutils](https://github.com/ik5/gostrutils) - 字符串操作和转换函数的集合.
* [gotenv](https://github.com/subosito/gotenv) - 从Go中的`.env`或任何`io.Reader`加载环境变量.
* [gpath](https://github.com/tenntenn/gpath) - 使用Go的反射表达式简化访问结构字段的库.
* [gubrak](https://github.com/novalagung/gubrak)   - 具有语法糖的Golang实用程序库.  这就像lodash，但对于golang来说.
* [handy](https://github.com/miguelpragier/handy) - 许多实用程序和帮助程序，如字符串处理程序/格式化程序和验证程序.
* [htcat](https://github.com/htcat/htcat) - 并行和流水线HTTP GET实用程序.
* [hub](https://github.com/github/hub) - 使用附加功能包装git命令，以便从终端与github进行交互.
* [hystrix-go](https://github.com/afex/hystrix-go) - 实现程序员定义的回退（即断路器）的Hystrix模式.
* [immortal](https://github.com/immortal/immortal) -  \ * nix跨平台（OS无关）主管.
* [intrinsic](https://github.com/mengzhuo/intrinsic) - 使用x86 SIMD而无需编写任何汇编代码.
* [jump](https://github.com/gsamokovarov/jump) - 通过学习您的习惯，跳跃可以帮助您更快地导航
* [koazee](https://github.com/wesovilabs/koazee) - 图书馆受到Lazy评估和函数式编程的启发，无需使用数组.
* [lrserver](https://github.com/jaschaephraim/lrserver) -  Go的LiveReload服务器.
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [mergo](https://github.com/imdario/mergo)   - 帮助合并Golang中的结构和地图.  用于配置默认值，避免凌乱的if语句.
* [mimemagic](https://github.com/zRedShift/mimemagic) -  Pure Go超高性能MIME嗅探库/实用程序.
* [mimesniffer](https://github.com/aofei/mimesniffer) -  Go的MIME类型嗅探器.
* [mimetype](https://github.com/gabriel-vasile/mimetype) - 基于幻数的MIME类型检测包.
* [minify](https://github.com/tdewolff/minify) -  HTML，CSS，JS，XML，JSON和SVG文件格式的快速缩小器.
* [minquery](https://github.com/icza/minquery) - 支持高效分页的MongoDB / mgo.v2查询（游标继续列出我们中断的文档）.
* [mmake](https://github.com/tj/mmake) - 现代制作.
* [moldova](https://github.com/StabbyCutyou/moldova) - 用于基于输入模板生成随机数据的实用程序.
* [mole](https://github.com/davrodpin/mole) -  cli app轻松创建ssh隧道.
* [mssqlx](https://github.com/linxGnu/mssqlx)   - 数据库客户端库，任何主从属的代理，主主结构.  轻量化和自动平衡.
* [multitick](https://github.com/VividCortex/multitick) - 用于对齐的代码的多路复用器.
* [myhttp](https://github.com/inancgumus/myhttp) - 使用超时支持发出HTTP GET请求的简单API.
* [netbug](https://github.com/e-dard/netbug) - 轻松远程分析您的服务.
* [okrun](https://github.com/xta/okrun) - 去运行错误压路机.
* [olaf](https://github.com/btnguyen2k/olaf) - 在Go中实施Twitter Snowflake.
* [onecache](https://github.com/adelowo/onecache) - 支持多个后端存储的缓存库（Redis，Memcached，文件系统等）.
* [panicparse](https://github.com/maruel/panicparse) - 组合类似的goroutine并着色堆栈转储.
* [peco](https://github.com/peco/peco) - 简单的交互式过滤工具.
* [pgo](https://github.com/arthurkushman/pgo) -  PHP社区的便捷功能.
* [pm](https://github.com/VividCortex/pm) - 使用HTTP API处理（即goroutine）管理器.
* [profile](https://github.com/pkg/profile) -  Go的简单性能分析支持包.
* [rclient](https://github.com/zpatrick/rclient) -  REST API的可读，灵活，易用的客户端.
* [realize](https://github.com/tockins/realize)   - 使用文件监视器和实时重新加载构建系统.  使用自定义路径运行，构建和监视文件更改.
* [repeat](https://github.com/ssgreg/repeat) - 实施不同的退避策略，可用于重试操作和心跳.
* [request](https://github.com/mozillazg/request) - 针对Humans™的HTTP请求.
* [rerate](https://github.com/abo/rerate) -  Go的基于Redis的速率计数器和速率限制器.
* [rerun](https://github.com/ivpusic/rerun) - 在源更改时重新编译并重新运行应用程序.
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [retry](https://github.com/kamilsk/retry) - 最先进的功能机制，重复执行操作直到成功.
* [retry](https://github.com/percolate/retry) -  Go的简单但高度可配置的重试包.
* [retry](https://github.com/thedevsaddam/retry) -  Go简单易用的重试机制包.
* [retry](https://github.com/shafreeck/retry) - 一个非常简单的库，以确保您的工作完成.
* [retry-go](https://github.com/rafaeljesus/retry-go) - 重试简单易用golang.
* [robustly](https://github.com/VividCortex/robustly) - 弹性运行，捕捉并重启恐慌.
* [scan](https://github.com/blockloop/scan) - 将golang`sql.Rows`直接扫描到结构，切片或原始类型.
* [serve](https://github.com/syntaqx/serve) - 您需要的任何地方的静态http服务器.
* [silk](https://github.com/chrispassas/silk) - 阅读丝绸netflow文件.
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - 基元类型之间的切片转换.
* [slicer](https://github.com/leaanthony/slicer) - 使切片更容易使用.
* [spinner](https://github.com/briandowns/spinner) -  Go包以轻松为终端微调器提供选项.
* [sqlx](https://github.com/jmoiron/sqlx) - 在优秀的内置数据库/ sql包之上提供一组扩展.
* [sslice](https://github.com/yaa110/sslice) - 创建始终排序的切片.
* [Storm](https://github.com/asdine/storm) -  BoltDB简单而强大的工具包.
* [structs](https://github.com/PumpkinSeed/structs) - 实现简单的函数来操作结构.
* [Task](https://github.com/go-task/task) - 简单的“制造”替代方案.
* [toolbox](https://github.com/viant/toolbox)   - 切片，地图，多图，结构，功能，数据转换实用程序.  服务路由器，宏评估器，标记器.
* [ugo](https://github.com/alxrm/ugo) -  ugo是切片工具箱，简洁的Go语法.
* [UNIS](https://github.com/esemplastic/unis) -  Go中针对字符串实用程序的Common Architecture™.
* [usql](https://github.com/knq/usql) -  usql是SQL数据库的通用命令行界面.
* [util](https://github.com/shomali11/util)   - 有用的实用功能的集合.  （字符串，并发，操作，......）.
* [wuzz](https://github.com/asciimoo/wuzz) - 用于HTTP检查的交互式cli工具.
* [xferspdy](https://github.com/monmohan/xferspdy) -  Xferspdy在golang中提供二进制diff和补丁库.

## UUID

*与UUID合作的图书馆.*

* [goid](https://github.com/jakehl/goid) - 生成并解析符合RFC4122的V4 UUID.
* [ulid](https://github.com/oklog/ulid) - 实施ULID（通用唯一词典可排序标识符）.
* [uuid](https://github.com/agext/uuid) - 使用快速或加密质量的随机节点标识符生成，编码和解码UUID v1.
* [uuid](https://github.com/gofrs/uuid)   - 通用唯一标识符（UUID）的实现.  支持UUID的创建和解析.  积极维护satori uuid的分叉.
* [wuid](https://github.com/edwingeng/wuid) - 极快的唯一编号生成器，比UUID快10-135倍.

## Validation

*用于验证的库.*

* [checkdigit](https://github.com/osamingo/checkdigit) - 提供校验位算法（Luhn，Verhoeff，Damm）和计算器（ISBN，EAN，JAN，UPC等）.
* [govalidator](https://github.com/asaskevich/govalidator) - 字符串，数字，切片和结构的验证器和消毒剂.
* [govalidator](https://github.com/thedevsaddam/govalidator)   - 使用简单的规则验证Golang请求数据.  受到Laravel的请求验证的启发.
* [jio](https://github.com/faceair/jio) -  jio是一个类似的json模式验证器 [joi](https://github.com/hapijs/joi).
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - 支持使用通常的代码构造中指定的可配置和可扩展的验证规则来验证各种数据类型（结构，字符串，映射，切片等），而不是结构标记.
* [validate](https://github.com/gookit/validate)   -  Go包用于数据验证和过滤.  支持验证Map，Struct，Request（Form，JSON，url.Values，Uploaded Files）数据和更多功能.
* [validate](https://github.com/gobuffalo/validate) - 此包提供了为Go应用程序编写验证的框架.
* [validator](https://github.com/go-playground/validator) - 进行结构和场验证，包括交叉场，交叉结构，地图，切片和阵列潜水.

## Version Control

*用于版本控制的库.*

* [gh](https://github.com/rjeczalik/gh) -  GitHub Webhooks的可编写脚本的服务器和net / http中间件.
* [git2go](https://github.com/libgit2/git2go) - 为libgit2绑定绑定.
* [go-git](https://github.com/src-d/go-git) - 纯Go中高度可扩展的Git实现.
* [go-vcs](https://github.com/sourcegraph/go-vcs) - 在Go中操作和检查VCS存储库.
* [hercules](https://github.com/src-d/hercules) - 从Git存储库历史中获得高级见解.
* [hgo](https://github.com/beyang/hgo) -  Hgo是Go包的集合，提供对本地Mercurial存储库的读访问权.

## Video

*用于操纵视频的图书馆.*

* [gmf](https://github.com/3d0c/gmf) - 为FFmpeg库绑定绑定.
* [go-astisub](https://github.com/asticode/go-astisub) - 操纵GO中的字幕（.srt，.stl，.ttml，.webvtt，.ssa / .ass，teletext，.smi等）.
* [go-astits](https://github.com/asticode/go-astits) - 在GO中本地解析和解复用MPEG传输流（.ts）.
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) -  Apple m3u8播放列表的分析器和生成器库.
* [goav](https://github.com/giorgisio/goav) -  FFmpeg的综合Go绑定.
* [gst](https://github.com/ziutek/gst) - 为GStreamer绑定绑定.
* [libgosubs](https://github.com/wargarblgarbl/libgosubs)   -  go的字幕格式支持.  支持.srt，.ttml和.ass.
* [libvlc-go](https://github.com/adrg/libvlc-go) - 为libvlc 2.X / 3.X / 4.X绑定绑定（由VLC媒体播放器使用）.
* [v4l](https://github.com/korandiz/v4l) - 用Go编写的Linux视频捕获库.

## Web Frameworks

*完整的堆栈Web框架.*

* [aah](https://aahframework.org) -  Go的可扩展，高性能，快速开发的Web框架.
* [Aero](https://github.com/aerogo/aero) -  Go的高性能Web框架，在Lighthouse中达到最高分.
* [Air](https://github.com/aofei/air) -  Go的理想精炼Web框架.
* [Banjo](https://github.com/nsheremet/banjo) -  Go的非常简单和快速的Web框架.
* [Beego](https://github.com/astaxie/beego) -  beego是Go编程语言的开源，高性能Web框架.
* [Buffalo](http://gobuffalo.io) - 带来Rails的生产力！
* [Echo](https://github.com/labstack/echo) - 高性能，极简主义的Go Web框架.
* [Fireball](https://github.com/zpatrick/fireball) - 更“自然”的感觉Web框架.
* [Gem](https://github.com/go-gem/gem) - 简单快速的Web框架，对REST API友好.
* [Gin](https://github.com/gin-gonic/gin)   -  Gin是一个用Go编写的Web框架！  它具有类似马提尼的API，具有更好的性能，速度提高了40倍.  如果您需要性能和良好的生产力.
* [Gizmo](https://github.com/NYTimes/gizmo) - 纽约时报使用的微服务工具包.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - 快速简便地设置RESTful JSON API.
* [go-rest](https://github.com/ungerik/go-rest) -  Go的小而邪恶的REST框架.
* [Goa](https://github.com/goadesign/goa) -  Goa提供了一种在Go中开发远程API和微服务的整体方法.
* [Golax](https://github.com/fulldump/golax) - 非Sinatra快速HTTP框架，支持Google自定义方法，深度拦截器，递归等.
* [Golf](https://github.com/dinever/golf)   - 高尔夫是Go的快速，简单和轻量级的微型Web框架.  它具有强大的功能，除了Go标准库之外没有其他依赖项.
* [Gondola](https://github.com/rainycape/gondola) - 用于更快地编写更快网站的Web框架.
* [gongular](https://github.com/mustafaakin/gongular) - 具有输入映射/验证和（DI）依赖注入的Fast Go Web框架.
* [hiboot](https://github.com/hidevopsio/hiboot) -  hiboot是一个高性能的Web应用程序框架，具有自动配置和依赖注入支持.
* [Macaron](https://github.com/go-macaron/macaron) -  Mac中是一个高效的模块化设计Web框架.
* [mango](https://github.com/paulbellamy/mango) -  Mango是Go的模块化Web应用程序框架，受Rack和PEP333的启发.
* [Microservice](https://github.com/claygod/microservice) - 用Golang编写的用于创建微服务的框架.
* [neo](https://github.com/ivpusic/neo) -  Neo是极简单且快速的Go Web Framework，具有极其简单的API.
* [nio](https://github.com/go-nio/nio) - 现代，简约且高效的Go HTTP框架.
* [Resoursea](https://github.com/resoursea/api) - 用于快速编写基于资源的服务的REST框架.
* [REST Layer](http://rest-layer.io) - 在数据库之上构建REST / GraphQL API的框架，主要是代码配置.
* [Revel](https://github.com/revel/revel) -  Go语言的高效Web框架.
* [rex](https://github.com/goanywhere/rex) -  Rex是一个基于gorilla / mux的模块化开发库，与`net / http`完全兼容.
* [sawsij](https://github.com/jaybill/sawsij) - 轻量级的开源Web框架，用于构建高性能，数据驱动的Web应用程序.
* [tango](https://github.com/lunny/tango) -  Go的微型和可插拔Web框架.
* [tigertonic](https://github.com/rcrowley/go-tigertonic) -  Go框架，用于构建受Dropwizard启发的JSON Web服务.
* [traffic](https://github.com/pilu/traffic) --Sinatra为Go启发了regexp / pattern mux和web框架.
* [uAdmin](https://github.com/uadmin/uadmin) -  Golang的全功能Web框架，灵感来自Django.
* [utron](https://github.com/gernest/utron) -  Go（Golang）的轻量级MVC框架.
* [vox](https://github.com/aisk/vox) - 人类的golang网络框架，受到Koa的启发.
* [WebGo](https://github.com/bnkamalesh/webgo)   - 构建Web应用程序的微框架;  处理程序链接，中间件和上下文注入.  使用标准库兼容的HTTP处理程序（即http.HandlerFunc）.
* [YARF](https://github.com/yarf-framework/yarf) - 快速微框架，旨在以快速简单的方式构建REST API和Web服务.
* [Zerver](https://github.com/cosiner/zerver) -  Zerver是一个富有表现力，模块化，功能完善的RESTful框架.

### Middlewares

#### Actual middlewares

* [client-timing](https://github.com/posener/client-timing) -  Server-Timing标头的HTTP客户端.
* [CORS](https://github.com/rs/cors) - 轻松为您的API添加CORS功能.
* [formjson](https://github.com/rs/formjson) - 透明地将JSON输入作为标准表单POST处理.
* [go-server-timing](https://github.com/mitchellh/go-server-timing) - 添加/解析Server-Timing标头.
* [Limiter](https://github.com/ulule/limiter) -  Go的死简单速率限制中间件.
* [ln-paywall](https://github.com/philippgille/ln-paywall) - 使用Lightning Network（比特币）通过中间件在每个请求的基础上货币化API.
* [Tollbooth](https://github.com/didip/tollbooth) - 速率限制HTTP请求处理程序.
* [XFF](https://github.com/sebest/xff) - 处理`X-Forwarded-For`标题和朋友.

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) -  Go的无痛中间件链接.
* [catena](https://github.com/codemodus/catena) -  http.Handler包装器连接（与“链”相同的API）.
* [chain](https://github.com/codemodus/chain) - 处理程序包装器与范围数据链接（基于网络/上下文的“中间件”）.
* [go-wrap](https://github.com/go-on/wrap) - 用于net / http的小型中间件包.
* [gores](https://github.com/alioygur/gores)   -  Go包处理HTML，JSON，XML等响应.  对RESTful API很有用.
* [interpose](https://github.com/carbocation/interpose) -  golang的极简主义网络/ http中间件.
* [muxchain](https://github.com/stephens2424/muxchain) - 用于网络/ http的轻量级中间件.
* [negroni](https://github.com/urfave/negroni) -  Golang的惯用HTTP中间件.
* [render](https://github.com/unrolled/render) -  Go包，可轻松呈现JSON，XML和HTML模板响应.
* [renderer](https://github.com/thedevsaddam/renderer) -  Go的简单，轻量级和更快的响应（JSON，JSONP，XML，YAML，HTML，File）渲染包.
* [rye](https://github.com/InVisionApp/rye) - 支持JWT，CORS，Statsd和Go 1.7上下文的Tiny Go中间件库（带有固定中间件）.
* [stats](https://github.com/thoas/stats) - 转到存储有关Web应用程序的各种信息的中间件.

### Routers

* [alien](https://github.com/gernest/alien) - 来自外太空的轻量级和快速的http路由器.
* [bellt](https://github.com/GuilhermeCaruso/bellt) - 一个简单的Go HTTP路由器.
* [Bone](https://github.com/go-zoo/bone) -  Lightning Fast HTTP Multiplexer.
* [Bxog](https://github.com/claygod/Bxog)   -  Go的简单快速HTTP路由器.  它适用于不同难度，长度和嵌套的路线.  他知道如何根据收到的参数创建一个URL.
* [chi](https://github.com/go-chi/chi) - 基于网络/上下文构建的小型，快速且富有表现力的HTTP路由器.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter)   - 来自`httprouter`的高性能路由器.  第一个路由器适合`fasthttp`.
* [FastRouter](https://github.com/razonyang/fastrouter) - 用Go编写的快速，灵活的HTTP路由器.
* [gocraft/web](https://github.com/gocraft/web) -  Go中的Mux和中间件包.
* [Goji](https://github.com/goji/goji) -  Goji是一个简约灵活的HTTP请求多路复用器，支持`net / context`.
* [GoRouter](https://github.com/vardius/gorouter) -  GoRouter是一个服务器/ API微型框架，HTTP请求路由器，多路复用器，多路复用器，为请求路由器提供支持`net / context`的中间件.
* [gowww/router](https://github.com/gowww/router) -  Lightning fast HTTP路由器与net / http.Handler接口完全兼容.
* [httprouter](https://github.com/julienschmidt/httprouter)   - 高性能路由器.  使用此标准http处理程序构成一个非常高性能的Web框架.
* [httptreemux](https://github.com/dimfeld/httptreemux)   -  Go的高速，灵活的基于树的HTTP路由器.  来自httprouter的灵感.
* [lars](https://github.com/go-playground/lars) - 用于Go的轻量级，快速且可扩展的零分配HTTP路由器用于创建可自定义的框架.
* [mux](https://github.com/gorilla/mux) - 强大的URL路由器和golang调度程序.
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing)   - 极速的Go（golang）HTTP路由器，支持正则表达式路由匹配.  全面支持构建RESTful API.
* [pure](https://github.com/go-playground/pure) - 是一个轻量级HTTP路由器，坚持std“net / http”实现.
* [Siesta](https://github.com/VividCortex/siesta) - 用于编写中间件和处理程序的可组合框架.
* [vestigo](https://github.com/husobee/vestigo) - 用于go web应用程序的高性能，独立，HTTP兼容的URL路由器.
* [violetear](https://github.com/nbari/violetear) - 去HTTP路由器.
* [xmux](https://github.com/rs/xmux) - 基于`httprouter`并支持`net / context`的高性能复用器.
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) -  Go的简单快速HTTP路由器.

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - 为Direct3D9绑定绑定.
* [go-ole](https://github.com/go-ole/go-ole) -  Win32的OLE实施golang.
* [gosddl](https://github.com/MonaxGT/gosddl)   - 从SDDL-string转换为用户友好的JSON.  SDDL由四部分组成：所有者，主要组，DACL，SACL.

## XML

*用于操作XML的库和工具.*

* [XML-Comp](https://github.com/xml-comp/xml-comp) - 简单的命令行XML比较器，生成文件夹，文件和标签的差异.
* [xml2map](https://github.com/sbabiv/xml2map) - 写入Golang的XML到MAP转换器.
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - 基于libxml2的xmlwriter模块的程序XML生成API.
* [xpath](https://github.com/antchfx/xpath) -  Go的XPath包.
* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.
* [zek](https://github.com/miku/zek) - 从XML生成Go结构.

## Tools

*去软件和插件.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - 检查Go项目的最新更改，以了解向后不兼容的更改.
* [dupl](https://github.com/mibk/dupl) - 用于代码克隆检测的工具.
* [errcheck](https://github.com/kisielk/errcheck) -  Errcheck是一个用于检查Go程序中未经检查的错误的程序.
* [gcvis](https://github.com/davecheney/gcvis) - 实时可视化Go程序GC跟踪数据.
* [go-checkstyle](https://github.com/qiniu/checkstyle)   -  checkstyle是一种样式检查工具，如java checkstyle.  这个工具的灵感来自java checkstyle，golint.  这种风格涉及Go Code Review Comments中的一些要点.
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - 创建go-cleanarch以验证Clean Architecture规则，例如Dependency Rule以及Go项目中包之间的交互.
* [go-critic](https://github.com/go-critic/go-critic) - 源代码linter，带来当前未在其他linters中实现的检查.
* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - 查找Go项目过时依赖关系的简便方法.
* [go-outdated](https://github.com/firstrow/go-outdated) - 显示过期软件包的控制台应用程序.
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - 基于Web的Golang AST可视化.
* [GoCover.io](http://gocover.io/) -  GoCover.io提供任何golang包作为服务的代码覆盖率.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - 自动修复（添加，删除）Go导入的工具.
* [GolangCI](https://golangci.com/)   -  GolangCI是一个针对GitHub拉取请求的自动Golang代码审查服务.  服务是开源的，开源项目是免费的.
* [GoLint](https://github.com/golang/lint) -  Golint是Go源代码的linter.
* [Golint online](http://go-lint.appspot.com/) - 在线提示使用golint包在GitHub，Bitbucket和Google Project Hosting上获取源文件.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - 添加零值返回语句以匹配func返回类型.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) -  gosimple是Go源代码的一个linter，专门用于简化代码.
* [gostatus](https://github.com/shurcooL/gostatus) - 命令行工具，显示包含Go包的存储库的状态.
* [lint](https://github.com/surullabs/lint) - 作为go测试的一部分运行linters.
* [php-parser](https://github.com/z7zmey/php-parser) - 用Go编写的PHP解析器.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) -  tarp在Go源代码中找不到直接单元测试的函数和方法.
* [unconvert](https://github.com/mdempsky/unconvert) - 从Go源中删除不必要的类型转换.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - 未使用的检查转到未使用的常量，变量，函数和类型的代码.
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - 去JetBrains IDE的插件.
* [go-language-server](https://github.com/theia-ide/go-language-server) - 将VSCode转换为支持语言服务器协议的语言服务器的包装器.
* [go-mode](https://github.com/dominikh/go-mode.el) -  GNU / Emacs的Go模式.
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [gocode](https://github.com/nsf/gocode) -  Go编程语言的自动完成守护程序.
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - 此扩展将Go语言的基准分析支持添加到VS Code.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - 用于文本编辑器SublimeText 3的Golang插件集合，提供代码完成和其他类似IDE的功能.
* [gounit-vim](https://github.com/hexdigest/gounit-vim) - 用于根据函数或方法的签名生成Go测试的Vim插件.
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - 为Theia IDE提供语言支持.
* [velour](https://github.com/velour/velour) -  acme编辑器的IRC客户端.
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) -  Vim插件，用于突出显示保存时的语法错误.
* [vim-go](https://github.com/fatih/vim-go) - 去Vim的开发插件.
* [vscode-go](https://github.com/Microsoft/vscode-go) -  Visual Studio Code（VS Code）的扩展，它提供对Go语言的支持.
* [Watch](https://github.com/eaburns/Watch) - 在文件更改的acme win中运行命令.

## Go Generate Tools

* [generic](https://github.com/usk81/generic) -  Go的灵活数据类型.
* [genny](https://github.com/cheekybits/genny) -  Go优雅的仿制药.
* [gocontracts](https://github.com/Parquery/gocontracts) - 通过将代码与文档同步，将合同设计带给Go.
* [gonerics](http://github.com/bouk/gonerics) -  Go中的惯用仿制药.
* [gotests](https://github.com/cweill/gotests) - 从源代码生成Go测试.
* [gounit](https://github.com/hexdigest/gounit) - 使用您自己的模板生成Go测试.
* [re2dfa](https://github.com/opennota/re2dfa) - 将正则表达式转换为有限状态机并输出Go源代码.
* [TOML-to-Go](https://xuri.me/toml-to-go) - 立即将TOML转换为浏览器中的Go类型.

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) - 围绕`go`命令的换行器，用于彩色化`go build`输出.
* [depth](https://github.com/KyleBanks/depth) - 通过分析导入来可视化任何包的依赖关系树.
* [gb](https://getgb.io/) -  Go编程语言易于使用的基于项目的构建工具.
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - 一个 [Yeoman](http://yeoman.io) 生成器以启动新的Go项目.
* [go-callvis](https://github.com/TrueFurby/go-callvis) - 使用点格式可视化Go程序的调用图.
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - 去和wgo的Bash完成.
* [go-swagger](https://github.com/go-swagger/go-swagger)   - 为Sw的Swagger 2.0实现.  Swagger是RESTful API的简单而强大的代表.
* [godbg](https://github.com/tylerwince/godbg) - 实现Rusts`dbg！`宏，以便在开发过程中快速轻松地进行调试.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - 使用适用于GitHub的OctoLinker浏览器扩展，有效地浏览go文件.
* [richgo](https://github.com/kyoh86/richgo) - 用文本装饰丰富`go test`输出.
* [rts](https://github.com/galeone/rts)   -  RTS：对结构的响应.  从服务器响应生成Go结构.

## Software Packages

*用Go编写的软件.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - 恰好是Debian存储库管理工具.
* [aurora](https://github.com/xuri/aurora) - 跨平台的基于Web的Beanstalkd队列服务器控制台.
* [awsenv](https://github.com/soniah/awsenv) - 用于加载配置文件的Amazon（AWS）环境变量的小二进制文件.
* [Blast](https://github.com/dave/blast) - 用于API负载测试和批处理作业的简单工具.
* [bombardier](https://github.com/codesenberg/bombardier) - 快速的跨平台HTTP基准测试工具.
* [bosun](https://github.com/bosun-monitor/bosun) - 时间序列警报框架.
* [DepCharge](https://github.com/centerorbit/depcharge) - 帮助协调跨大型项目中的许多依赖项执行命令.
* [dogo](https://github.com/liudng/dogo) - 监视源文件中的更改并自动编译和运行（重新启动）.
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - 使用二进制，docker或Drone CI触发下游Jenkins作业.
* [drone-scp](https://github.com/appleboy/drone-scp) - 使用二进制，docker或Drone CI通过SSH复制文件和工件.
* [Dropship](https://github.com/chrismckenzie/dropship) - 通过cdn部署代码的工具.
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) -  Golang软件包，通过SSH和SCP下载，通过`ProxyCommand`轻松实现远程执行.
* [fac](https://github.com/mkchoi212/fac) - 用于修复git合并冲突的命令行用户界面.
* [gaia](https://github.com/gaia-pipeline/gaia) - 使用任何编程语言构建强大的管道.
* [Gitea](https://github.com/go-gitea/gitea) -  Gogs的叉子，完全由社区驱动.
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - 将所有GitHub存储库，问题，里程碑和标签迁移到Gitea实例.
* [go-furnace](https://github.com/go-furnace/go-furnace)   - 用Go编写的托管解决方案.  在AWS，GCP或DigitalOcean上轻松部署您的应用程序.
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - 使您的Go应用程序能够自我更新.
* [gobrew](https://github.com/cryptojuice/gobrew) -  gobrew让您轻松切换多个版本的go.
* [godbg](https://github.com/sirnewton01/godbg) - 基于Web的gdb前端应用程序.
* [Gogs](https://gogs.io/) -  Go编程语言中的自托管Git服务.
* [gonative](https://github.com/inconshreveable/gonative) - 创建Go构建的工具，可以交叉编译到所有平台，同时仍然使用支持Cgo的stdlib软件包版本.
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build”包装器，可以轻松地将版本信息添加到Go二进制文件中.
* [gox](https://github.com/mitchellh/gox) - 死简单，没有多余的装饰去交叉编译工具.
* [goxc](https://github.com/laher/goxc) - 为Go构建工具，重点是交叉编译和打包.
* [grapes](https://github.com/yaronsumel/grapes) - 轻量级工具，旨在轻松地通过ssh分发命令.
* [GVM](https://github.com/moovweb/gvm) -  GVM提供管理Go版本的界面.
* [Hey](https://github.com/rakyll/hey) - 嘿是一个很小的程序，可以向Web应用程序发送一些负载.
* [kala](https://github.com/ajvb/kala) - 简单，现代，高效的工作调度程序.
* [kcli](https://github.com/cswank/kcli) - 用于检查kafka主题/分区/消息的命令行工具.
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [lstags](https://github.com/ivanilves/lstags) - 跨不同注册表同步Docker镜像的工具和API.
* [lwc](https://github.com/timdp/lwc) -  UNIX wc命令的实时更新版本.
* [manssh](https://github.com/xwjdsh/manssh) -  manssh是一个命令行工具，可以轻松管理ssh别名配置.
* [Moby](https://github.com/moby/moby) - 集装箱生态系统的协作项目，以组装基于容器的系统.
* [Mora](https://github.com/emicklei/mora) - 用于访问MongoDB文档和元数据的REST服务器.
* [ostent](https://github.com/ostrost/ostent) - 收集并显示系统指标，并可选择中继到Graphite和/或InfluxDB.
* [Packer](https://github.com/mitchellh/packer) -  Packer是一种从单一来源配置为多个平台创建相同机器映像的工具.
* [Pewpew](https://github.com/bengadbois/pewpew) - 灵活的HTTP命令行压力测试仪.
* [Pomerium](https://github.com/pomerium/pomerium) -  Pomerium是一种身份识别访问代理.
* [Rodent](https://github.com/alouche/rodent) -  Rodent帮助您管理Go版本，项目和跟踪依赖项.
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - 小型实用程序/库，针对大型对象进出Amazon S3的高速传输进行了优化.
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - 从命令行管理BareMetal服务器（就像使用Docker一样容易）.
* [script](https://github.com/bitfield/script) - 在Go for DevOps和系统管理任务中轻松编写类似shell的脚本.
* [sg](https://github.com/ChristopherRabotin/sg) - 对一组HTTP端点（如ab）进行基准测试，可以根据其先前的响应，在每次调用之间使用响应代码和数据，以应对特定的服务器压力.
* [skm](https://github.com/TimothyYe/skm) -  SKM是一个简单而强大的SSH密钥管理器，它可以帮助您轻松管理多个SSH密钥！
* [StatusOK](https://github.com/sanathp/statusok) - 监控您的网站和REST API.当您的服务器关闭或响应时间超过预期时，通过Slack，电子邮件通知.
* [traefik](https://github.com/containous/traefik) - 反向代理和负载均衡器，支持多个后端.
* [Vegeta](https://github.com/tsenart/vegeta)   -  HTTP负载测试工具和库.  超过9000！
* [webhook](https://github.com/adnanh/webhook) - 允许用户创建在服务器上执行命令的HTTP端点（挂钩）的工具.
* [Wide](https://wide.b3log.org/login) - 使用Golang的基于Web的团队IDE.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - 用于在Windows机器上远程执行命令的Cli工具.

### Other Software
* [borg](https://github.com/crufter/borg) - 基于终端的bash片段搜索引擎.
* [boxed](https://github.com/tejo/boxed) - 基于Dropbox的博客引擎.
* [Cherry](https://github.com/rafael-santiago/cherry) -  Go中的微型网络聊天服务器.
* [Circuit](https://github.com/gocircuit/circuit) - 电路是可编程平台即服务（PaaS）和/或基础设施即服务（IaaS），用于包括云应用的服务和主机的管理，发现，同步和协调.
* [Comcast](https://github.com/tylertreat/Comcast) - 模拟糟糕的网络连接.
* [confd](https://github.com/kelseyhightower/confd) - 使用来自etcd或consul的模板和数据管理本地应用程序配置文件.
* [DDNS](https://github.com/skibish/ddns) - 使用数字海洋网络DNS作为后端的个人DDNS客户端.
* [Docker](http://www.docker.com/) - 面向开发人员和系统管理员的分布式应用程序的开放平台.
* [Documize](https://github.com/documize/community) - 现代wiki软件，集成了SaaS工具的数据.
* [drive](https://github.com/odeke-em/drive) - 命令行的Google云端硬盘客户端.
* [Duplicacy](https://github.com/gilbertchen/duplicacy) - 基于无锁重复数据删除理念的跨平台网络和云备份工具.
* [gfile](https://github.com/Antonito/gfile) - 通过WebRTC在两台计算机之间安全地传输文件，无需任何第三方.
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - 显示GOPATH中Go包的更新的应用程序.
* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - 视频流洪流客户端.
* [GoBoy](https://github.com/Humpheh/goboy) - 用Go编写的Nintendo Game Boy Color模拟器.
* [gocc](https://github.com/goccmack/gocc) -  Gocc是Go编写的Go编译器套件.
* [GoDNS](https://github.com/timothyye/godns) - 动态DNS客户端工具，支持用Go编写的DNSPod和HE.net.
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) -  Go Doc网站的Chrome扩展程序，在功能列表中将功能描述显示为工具提示.
* [GoLand](https://jetbrains.com/go) - 全功能的跨平台Go IDE.
* [Gor](https://github.com/buger/gor) -  Http流量复制工具，用于实时重放从生产到阶段/开发环境的流量.
* [hugo](http://gohugo.io/) - 快速和现代的静态网站引擎.
* [ide](https://github.com/thestrukture/ide)   - 浏览器可访问的IDE.  专为Go with Go设计.
* [ipe](https://github.com/dimiro1/ipe) - 与GO编写的Pusher客户端库兼容的开源Pusher服务器实现.
* [joincap](https://github.com/assafmo/joincap) - 用于将多个pcap文件合并在一起的命令行实用程序.
* [Juju](https://jujucharms.com/) - 与云无关的服务部署和编排 - 支持EC2，Azure，Openstack，MAAS等.
* [Leaps](https://github.com/jeffail/leaps) - 使用Operational Transforms对编程服务.
* [lgo](https://github.com/yunabe/lgo)   - 使用Jupyter进行Interactive Go编程.  它支持代码完成，代码检查和100％Go兼容性.
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) -  LiteIDE是一个简单的开源跨平台Go IDE.
* [mockingjay](https://github.com/quii/mockingjay-server)   - 从一个配置文件伪造HTTP服务器和消费者驱动的合同.  您还可以使服务器随机出现异常，以帮助进行更实际的性能测试.
* [myLG](https://github.com/mehrdadrad/mylg) - 用Go编写的命令行网络诊断工具.
* [naclpipe](https://github.com/unix4fun/naclpipe) - 用Go编写的简单的基于NaCL EC25519的加密管道工具.
* [nes](https://github.com/fogleman/nes) - 用Go编写的任天堂娱乐系统（NES）模拟器.
* [orange-cat](https://github.com/noraesae/orange-cat) - 用Go编写的Markdown预览器.
* [Orbit](https://github.com/gulien/orbit) - 用于运行命令和从模板生成文件的简单工具.
* [peg](https://github.com/pointlander/peg) -  Peg，Parsing Expression Grammar，是Packrat解析器生成器的实现.
* [Pipe](https://github.com/b3log/pipe) - 一个小而美丽的博客平台.
* [restic](https://github.com/restic/restic) - 重复删除备份程序.
* [rkt](https://github.com/coreos/rkt) - 与init系统集成的App Container运行时，与Docker等其他容器格式兼容，并支持KVM等替代执行引擎.
* [scc](https://github.com/boyter/scc) -  Sloc Cloc和Code，一个非常快速准确的代码计数器，具有复杂度计算和COCOMO估计.
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - 具有O（1）磁盘搜索功能的快速，简单和可扩展的分布式文件系统.
* [shell2http](https://github.com/msoap/shell2http) - 通过http服务器执行shell命令（用于原型设计或远程控制）.
* [snap](https://github.com/intelsdi-x/snap) - 强大的遥测框架.
* [Snitch](https://github.com/lucasgomide/snitch) - 当有人通过Tsuru部署任何应用程序时，通知您的团队和许多工具的简单方法.
* [Stack Up](https://github.com/pressly/sup) -  Stack Up，一个超级简单的部署工具 - 只需Unix--就像服务器网络的&#39;make&#39;一样.
* [syncthing](https://syncthing.net/) - 开放，分散的文件同步工具和协议.
* [term-quiz](https://github.com/crazcalm/term-quiz) - 您的终端的测验.
* [toxiproxy](https://github.com/shopify/toxiproxy) - 代理模拟自动测试的网络和系统条件.
* [tsuru](https://tsuru.io/) - 可扩展和开源平台即服务软件.
* [vFlow](https://github.com/VerizonDigital/vflow) - 高性能，可扩展且可靠的IPFIX，sFlow和Netflow收集器.
* [wellington](https://github.com/wellington/wellington) -  Sass项目管理工具，使用精灵功能扩展语言（如Compass）.

## Resources

*在哪里发现新的Go库.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - 比较不同Go版本之间性能的框架.
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app)   - 强大的HTTP基准工具与Аb，Wrk，Siege工具混合使用.  收集基准和比较结果的统计数据和各种参数.
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks)   - 很少杂项Go微基准测试.  将一些语言特征与替代方法进行比较
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - 转到HTTP请求路由器基准和比较.
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - 去Web框架基准.
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) -  Go序列化方法的基准.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) -  Go语言常见基本操作的基准.
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks)   - 微型基准测试的微小集合.  目的是将一些语言特征与其他语言特征进行比较.
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - 收集流行的Go数据库/ SQL实用程序的基准.
* [gospeed](https://github.com/feyeleanor/GoSpeed) - 使用微基准来计算语言结构的速度.
* [kvbench](https://github.com/jimrobinson/kvbench) - 键/值数据库基准.
* [skynet](https://github.com/atemerev/skynet) -  Skynet 1M线程microbenchmark.
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - 比较Go语言的各种图像调整大小算法.

## Conferences

* [Capital Go](http://www.capitalgolang.com) - 华盛顿特区，美国.
* [dotGo](http://www.dotgo.eu) - 法国巴黎.
* [GoCon](http://gocon.connpass.com/) - 日本东京
* [GoDays](https://www.godays.io/) - 柏林，德国.
* [GoLab](http://golab.io/) - 意大利佛罗伦萨.
* [GolangUK](http://golanguk.com/) - 英国伦敦.
* [GopherChina](http://gopherchina.org) - 上海，中国.
* [GopherCon](http://www.gophercon.com/) - 美国丹佛.
* [GopherCon Brazil](https://gopherconbr.org) - 弗洛里亚诺波利斯，BR.
* [GopherCon Europe](https://gophercon.is/) - 冰岛雷克雅未克.
* [GopherCon India](https://www.gophercon.in/) -  Put，印度.
* [GopherCon Israel](https://www.gophercon.org.il/) - 以色列特拉维夫
* [GopherCon Russia](https://www.gophercon-russia.ru) - 俄罗斯莫斯科.
* [GopherCon Singapore](https://gophercon.sg) - 新加坡丰树商业城.
* [GopherCon Vietnam](https://gophercon.vn/) - 越南胡志明市.
* [GothamGo](http://gothamgo.com/) - 美国纽约市.
* [GoWayFest](https://goway.io/) - 白俄罗斯明斯克.

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - 一本专注于Go语法/语义和各种细节的书.
* [Go Bootcamp](http://golangbootcamp.com)
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - 波斯语
* [GoBooks](https://github.com/dariubs/GoBooks) - 精选的Go书籍清单.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) -  Maria Letta的Gopher图形包，矢量和光栅中的插图和情感角色.
* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - 去gopher矢量数据[.ai，.svg].
* [gopher-logos](https://github.com/GolangUA/gopher-logos) - 可爱的gopher标志.
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector](https://github.com/golang-samples/gopher-vector)
* [gophericons](https://github.com/shalakhin/gophericons)
* [gopherize.me](https://github.com/matryer/gopherize.me) - 自己动手吧.
* [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara.
* [gophers](https://github.com/egonelbre/gophers) - 免费的地鼠.
* [gophers](https://github.com/rogeralsing/gophers) - 随机gopher图形.
* [gophers](https://github.com/sillecelik/go-gopher) -  Gopher amigurumi玩具图案.

## Meetups

* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
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
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
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
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*在这里添加您所在城市/国家的组（发送** PR **）*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - 你的Go-to Go工具箱.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job)   - 精选的远程作业列表.  他们中的很多人都在寻找黑客.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - 其他惊人的名单列表.
* [CodinGame](https://www.codingame.com/) - 通过使用小游戏作为实例解决交互式任务来学习Go.
* [Go Blog](http://blog.golang.org) -  Go官方博客.
* [Go Challenge](http://golang-challenge.org/) - 通过解决问题并获得Go专家的反馈来学习Go.
* [Go Community on Hashnode](https://hashnode.com/n/go) -  Hashnode的Gophers社区.
* [Go Forum](https://forum.golangbridge.org) - 讨论围棋的论坛.
* [Go In 5 Minutes](https://www.goin5minutes.com/) -  5分钟的截屏视频专注于完成一件事.
* [Go Projects](https://github.com/golang/go/wiki/Projects) -  Go社区维基上的项目列表.
* [Go Report Card](https://goreportcard.com) -  Go套餐的成绩单.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp)   - 收集需要帮助的Go项目.  在Go开始你的开源方式的好地方.
* [godoc.org](https://godoc.org/) - 开源Go包的文档.
* [Golang Flow](https://golangflow.io) - 发布更新，新闻，包等.
* [Golang News](https://golangnews.com) - 关于Go编程的链接和新闻.
* [golang-graphics](https://github.com/mholt/golang-graphics) -  Go图像，图形和艺术的集合.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - 去邮件列表.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - 加入我们新的松弛社区（地鼠）（[Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [Gophercises](https://gophercises.com/) - 为萌芽的地鼠提供免费的编码练习.
* [gowalker.org](https://gowalker.org) -  Go Project API文档.
* [justforfunc](https://www.youtube.com/c/justforfunc) - 由Francesc Campoy主持的Youtube频道，致力于Go编程语言提示和技巧 [@francesc](https://twitter.com/francesc).
* [r/Golang](https://www.reddit.com/r/golang) - 有关Go的新闻.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - 寻找新Go库的好地方.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - 新Golang Devs的陷阱，陷阱和常见错误.
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - 建立电子商务的Golang网站（包括演示）.
* [A Tour of Go](http://tour.golang.org/) -  Go的互动之旅.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) -  Golang电子书介绍如何使用golang构建Web应用程序.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - 熟悉Gin并了解它如何帮助您减少样板代码并构建请求处理管道.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - 如何缓存慢速数据库查询.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - 如何取消MySQL查询.
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - 关于以太坊开发的一本小电子书.
* [Games With Go](http://gameswithgo.org/) - 视频系列教学编程和游戏开发.
* [Go By Example](https://gobyexample.com/) - 使用带注释的示例程序直接介绍Go.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) -  Go的参考卡.
* [Go database/sql tutorial](http://go-database-sql.org/) - 数据库/ sql简介.
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - 在移动设备上以交互方式编辑和播放Go片段.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - 与用于学习的Node.js相比的Golang示例.
* [Golangbot](https://golangbot.com/learn-golang-series/) - 开始使用Go进行编程的教程.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - 学习Golang编程社区提交和投票的最佳在线golang教程.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - 开始使用Godog  - 一个行为驱动的开发框架，用于构建和测试Go应用程序.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - 通过测试驱动开发学习Go.
* [package main](https://www.youtube.com/packagemain) - 关于Go in Programming的YouTube频道.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Working with Go](https://github.com/mkaz/working-with-go) - 介绍有经验的程序员.
* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's.
