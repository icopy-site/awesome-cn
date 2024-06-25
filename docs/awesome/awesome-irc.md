<div class="github-widget" data-repo="davisonio/awesome-irc"></div>
## Awesome IRC [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) resources.

A list of tools, software & other resources related to the Internet Relay Chat (IRC) protocol.

IRC (Internet Relay Chat) is an open source protocol that can be used for multi-user text based communication through channels.


<!--lint disable awesome-toc-->
<!--lint disable awesome-list-item-->
<!--lint ignore double-link-->

## Clients

*You use these to connect to IRC.*

- [Textual](https://www.codeux.com/textual/) - Very customizable, ZNC integration, iCloud sync ($4.99). ([source](https://github.com/Codeux-Software/Textual)) `macOS`
- [LimeChat](http://limechat.net/mac/) - One window for multiple servers, keyboard shortcuts, fast & stable. ([source](https://github.com/psychs/limechat)) `macOS` `iOS`
- [HexChat](https://hexchat.github.io) - Based on XChat, easy to use, spell check & multiple languages. ([source](https://github.com/hexchat/hexchat)) `Windows` `macOS` `Linux`
- [gamja](https://sr.ht/~emersion/gamja/) - A simple IRC web client. ([source](https://git.sr.ht/~emersion/gamja)) `Web`
- [Kiwi IRC](https://kiwiirc.com) - Powerful modern IRC messenger for the web. ([source](https://github.com/kiwiirc/kiwiirc), [demo](https://kiwiirc.com/nextclient/)) `Web`
- [CIRC](https://flackr.github.io/circ/) - Uses the chrome.sockets APIs to connect directly to IRC servers without needing a proxy. ([source](https://github.com/flackr/circ)) `Chrome`
- [Quassel](https://quassel-irc.org) - Distributed (clients can attach to and detach from a central core that stays permanently online. ([source](https://github.com/quassel/quassel)) `Linux` `macOS` `Windows`
- [Yaaic](https://www.yaaic.org) - Multi-server/channel support, SASL support, Smooth channel scrolling / swiping. ([source](https://github.com/pocmo/Yaaic)) `Android`
- [relay.js](https://github.com/Fauntleroy/relay.js) - Focuses on making IRC less intimidating and easier to use. `Web`
- [Circe](https://github.com/emacs-circe/circe) - For use in Emacs, sane defaults. `Emacs`
- [Smuxi](https://smuxi.im) - User-friendly, based on GNOME / GTK+. ([source](https://github.com/meebey/smuxi)) `Linux` `Windows` `macOS`
- [KvIRC](https://www.kvirc.net) - Free, portable, based on Qt GUI toolkit. ([source](https://github.com/kvirc/KVIrc)) `Linux` `macOS` `Windows`
- [Konversation](https://konversation.kde.org) - User-friendly client built on the KDE Platform. ([source](https://github.com/KDE/konversation)) `Linux`
- [sic](https://tools.suckless.org/sic/) - **S**imple **I**RC **c**lient - a terminal client in less than 250 lines of C. `Linux`
- [irssi](https://irssi.org) - Terminal client, multi-protocol friendly for module authors, GPLv2. `Linux` `macOS` `Cygwin` `BSD`
- [Revolution IRC](https://github.com/MCMrARM/revolution-irc) - Feature-full, actively maintained Android IRC client. `Android`
- [AdiIRC](https://adiirc.com) - Never has a client offered such granular settings for every aspect of the IRC experience. ([features](https://dev.adiirc.com/projects/adiirc/wiki/Features), [screenshots](https://dev.adiirc.com/projects/adiirc/wiki/Screenshots)) `Windows` `WINE`
- [IRC for Android™](https://www.countercultured.net/android/) - Android/Chrome OS client for power users, with ZNC built-ins, notification logic, reliable DCC, keybinds for hardware keyboards, etc. `Android` `ChromeOS`
- [Iridium](https://appcenter.elementary.io/com.github.avojak.iridium/) - Friendly IRC client built in Vala and GTK, designed for elementary OS. ([source](https://github.com/avojak/iridium)) `Linux`
- [Goguma](https://sr.ht/~emersion/goguma/) - An IRC client for mobile devices, from the creator of soju. `Android` `Linux`

<!--lint ignore double-link-->
*More? Clients that include bouncers are found [below](#bouncers).*

## Bouncers

*Useful for disconnecting and reconnecting without losing the chat session.*

### Hosted

- [IRCCloud](https://www.irccloud.com) - Group chat for teams, friends, and communities. stay connected, chat from anywhere, and never miss a message (+client) (£0-£3.50/month).
  - [iOS App](https://github.com/irccloud/ios) - Official. `Objective-C`
  - [Android App](https://github.com/irccloud/android) - Official. `Java`
  - [Nimbus](https://github.com/jnordberg/irccloudapp) - Standalone client. `macOS` `Objective-C`

### Self-hosted

- [Convos](https://convos.chat) - Always online web IRC client. ([source](https://github.com/convos-chat/convos)) `Perl` `JavaScript` `Web`
- [ZNC](https://wiki.znc.in/ZNC) - Most popular. many different plugins. ([source](https://github.com/znc/znc)) `C++`
- [BIP IRC Proxy](https://bip.milkypond.org) - Always online, lightweight and secure Open Source IRC proxying with backlogging. ([source](https://projects.duckcorp.org/projects/bip/repository)) `C`
- [TheLounge](https://thelounge.chat) - Responsive, self-hosted & support for multiple users. ([source](https://github.com/thelounge/thelounge), [demo](https://demo.thelounge.chat/)) `JavaScript` `Node.js` `Web`
- [WeeChat](https://weechat.org) - A fast, light and extensible chat client. ([source](https://github.com/weechat/weechat)) `Linux` `macOS` `Windows`
- [soju](https://git.sr.ht/~emersion/soju) - A user-friendly IRC bouncer. `Go`
- [sms-webhook](https://github.com/terminaldweller/sms-webhook) - A simple webhook to receive SMS messages on IRC. `Go`

## Daemons

*Used for running your own IRC server or network.*

- [ircd.js](https://github.com/alexyoung/ircd.js) - Server will allow clients to connect, join channels, change topics; basic stuff.
- [InspIRCd](https://www.inspircd.org) - Modular, stable, written from scratch. ([source](https://github.com/inspircd/inspircd))
- [miniircd](https://github.com/jrosdahl/miniircd) - Very simple and limited.
- [ngIRCd](https://ngircd.barton.de) - Portable and lightweight for small or private networks. ([source](https://github.com/ngircd/ngircd))
- [Ergo](https://github.com/ergochat/ergo) - Modern server that's portable and designed around specifications (bleeding-edge IRCv3 support).
- [RobustIRC](https://robustirc.net) - IRC server without netsplits. ([source](https://github.com/robustirc/robustirc/))

## Services

*Used to provide user accounts and bots like NickServ/ChanServ to your network.*

- [Atheme](https://atheme.github.io) - Designed for large networks with high scalability requirements. ([source](https://github.com/atheme/atheme))
- [anope](https://www.anope.org) - Designed for flexibility and ease of use. ([source](https://github.com/anope/anope))

## Bots

*IRC users which provide services for humans, e.g. integrations or information.*

- [Eggdrop](https://www.eggheads.org) - Oldest IRC bot still in active development. Feature rich, uses Tcl scripting. ([source](https://github.com/eggheads/eggdrop)) `C`
- [Sopel](https://sopel.chat) - Tonnes of ready made features, tutorial, fully documented. ([source](https://github.com/sopel-irc/sopel)) `Python`
- [Limnoria](https://github.com/ProgVal/Limnoria) - Robust, user friendly, developer friendly. `Python`
- [Twitch Plays](https://github.com/aidanrwt/twitch-plays ) - Takes input from the chat and presses the corresponding key. `Python`
- [Skybot](https://github.com/rmmh/skybot) - Main goals are simplicity and power. `Python`
- [talkbackbot](https://geekchick77.dreamwidth.org/472.html) - Responds to configured trigger phrases with quotes from notable women. ([source](https://github.com/jessamynsmith/talkbackbot)) `Python`
- [lazybot](https://github.com/Raynes/lazybot) - User-friendly and powerful. `Clojure`
- [IRC-BF](https://gitlab.com/ddevault/bf-irc-bot) - `Brainfuck`
- [geordi](https://github.com/Eelis/geordi) - Compiles and runs C++ code snippets. `C++`
- [CloudBot](https://github.com/TotallyNotRobots/CloudBot) - Simple, fast, expandable. `Python`
- [yossarian-bot](https://github.com/woodruffw/yossarian-bot) - Large default plugin set, Cinch-based. `Ruby`
- [helga](https://github.com/shaunduncan/helga) - Pluggable chat bot supporting multiple protocols. `Python`
- [EveIRC](https://github.com/Inspyre-Technologies/EveIRC) - Extendable chat/channel/server-managenent service-providing bot. Using the [Cinch Framework](https://github.com/cinchrb/cinch). `Ruby`
- [BitBot](https://github.com/bitbot-irc/bitbot) - Modular, event-driven bot featuring a REST API, individual user settings and much more. ([bitbot.dev](https://bitbot.dev)) `Python`
- [Cardinal](https://github.com/JohnMaguire/Cardinal) - Python Twisted IRC bot with a focus on ease of plugin development. `Python`
- [pyHoneybot](https://pyhoneybot.github.io/honeybot-store/) - Python Twisted IRC bot with a focus on ease of plugin development. ([source](https://github.com/pyhoneybot/honeybot)) `Python`
- [wayback](https://github.com/wabarc/wayback) - An archiving tool with an IRC interface integrated with various archiving services.
- [milla](https://github.com/terminaldweller/milla) - New generation LLM-powered bot with lua scripting support. `Go`

## Frameworks

*Helpful to write bots or integrate IRC with applications.*

- [node-irc](https://github.com/Throne3d/node-irc) `JavaScript`
- [goirc](https://github.com/fluffle/goirc) - Event-based, stateful, lacking documentation. `Go`
- [Hubot IRC Adapter](https://github.com/nandub/hubot-irc) - The IRC adapter for hubot. `JavaScript`
- [go-ircevent](https://github.com/thoj/go-ircevent) - Event-based. `Go`
- [slate-irc](https://github.com/slate/slate-irc) - Plugin system, simple api, arbitrary input stream, debug support. `JavaScript`
- [PircBotX](https://github.com/pircbotx/pircbotx) - Event based IRC Library with a straightforward API (updated fork of [PircBot](http://www.jibble.org/pircbot.php)). `Java`
- [IRC::Client](https://github.com/lizmat/IRC-Client) - `Perl6` based extendable IRC client framework.
- [irccd](https://projects.malikania.fr/irccd/index.html) - Flexible IRC bot customizable with JavaScript. `C++`.

### Bridges

*Sends messages back and forth.*

- [discord-irc](https://github.com/reactiflux/discord-irc) - Discord ↔ IRC. `JavaScript`
- [dibridge](https://github.com/OpenTTD/dibridge) - Discord ↔ IRC (with puppets) `Python`
- [slack-irc](https://github.com/ekmartin/slack-irc) - Slack ↔ IRC. `JavaScript`
- [irc-slack](https://github.com/insomniacslk/irc-slack) - Slack ↔ IRC. `Go`
- [BitlBee](https://www.bitlbee.org/main.php/news.r.html) - XMPP, Jabber, Google Talk, MSN Messenger, Yahoo! Messenger, AIM, ICQ, Twitter API, HipChat ↔ IRC. `C`
- [Biboumi](https://biboumi.louiz.org/) - IRC gateway for XMPP clients `C`
- [teleirc](https://github.com/RITlug/teleirc) - Telegram ↔ IRC. `JavaScript`
- [toxirc](https://github.com/jhert0/toxirc) - Tox ↔ IRC. `C`
- [skyweb2irc](https://github.com/ProgVal/skyweb2irc) - Skype (webclient API) ↔ IRC. `Javascript`
- [matterbridge](https://github.com/42wim/matterbridge) - IRC ↔ Mattermost ↔ Discord ↔ XMPP ↔ Gitter ↔ Slack ↔ Discord ↔ Telegram ↔ etc. `Go`
- [Heisenbridge](https://github.com/hifi/heisenbridge) - Bouncer-style Matrix IRC bridge `Python`
- [Appservice-IRC](https://github.com/matrix-org/matrix-appservice-irc) - Gateway and bridge Matrix ↔ IRC `Javascript`
- [matterircd](https://github.com/42wim/matterircd) - Matterbridge ↔ IRC, Slack ↔ IRC, Mastodon ↔ IRC. `Go`

## Channels

*IRC channels.*

### Discovery

- [netsplit.de Search](https://netsplit.de/channels/ ) - Searches 563 different networks.
- [mibbit Search](https://search.mibbit.com) - Searches networks listed [here](https://search.mibbit.com/networks).
- [KiwiIRC Search](https://kiwiirc.com/search) - Searches 318 different networks.

### Platforms

- [#ubuntu](https://wiki.ubuntu.com/IRC/ChannelList)@Libera.Chat - Official Ubuntu support channel. ([rules](https://wiki.ubuntu.com/IRC/Guidelines))

## Networks

*A collection of IRC servers is known as a network.*

- [Libera.Chat](https://libera.chat) - Network mostly focused on free and open source projects, run by former freenode staff.
- [Snoonet](https://snoonet.org) - Community of redditors and subreddits. ([rules](https://snoonet.org/rules/))
- [OFTC](https://oftc.net) - Community for free and open source software communities.
- [LibertaCasa](https://liberta.casa) - Privacy endorsing community serving as a safe and open space for the discussion of various topics.

## Articles

*Articles and blog posts about IRC.*

- [Please don't use Slack for FOSS projects](https://drewdevault.com/2015/11/01/Please-stop-using-slack.html) - Drew DeVault's Blog.
- [IRC Networks Under Systematic Attack From Governments](https://www.quakenet.org/articles/102-press-release-irc-networks-under-systematic-attack-from-governments) - QuakeNet.
- [IRC is dead, long live IRC](https://www.pingdom.com/blog/irc-is-dead-long-live-irc/) - Pingdom.
- [IRC Has Lost 60% Of Its Users Since 2003, But Life As A Robot Is Just Beginning](https://techcrunch.com/2013/01/06/irc-has-lost-60-of-its-users-since-2003-but-life-as-a-robot-is-just-beginning/) - Alex Williams (TechCrunch).

## Guides

*How-to's, documentation and books.*

- [#irchelp](https://www.irchelp.org) - A vast amount of reasonably up-to-date information.

## Protocol

*Information and resources about the IRC protocol itself.*

- [IRCv3 Working Group](https://ircv3.net) - A group of IRC software authors working to enhance, improve, maintain and standardize the IRC protocol. ([source](https://github.com/ircv3/ircv3.github.io))
- [Modern IRC Documents](https://modern.ircdocs.horse) - An attempt to write an update to the original IRC protocol. documentation ([source](https://github.com/ircdocs/modern-irc))
- [IRC Definition Files](https://defs.ircdocs.horse) - Lists of numerics, modes, ISUPPORT tokens and other protocol details. ([source](https://github.com/ircdocs/irc-defs))
- [grawity's IRC docs](https://github.com/grawity/irc-docs) - Collection of misc IRC protocol documentation.
- [Protocol Statistics](https://stats.ircdocs.horse) - Statistics around the server software in use on networks today. ([source](https://github.com/ircdocs/irc-stats))
- [IRC Parser Tests](https://github.com/ircdocs/parser-tests) - A CC0 set of test suites, to ensure IRC message parsers are consistent.
- [DareNET Archives](https://archives.darenet.org) - IRC Archives for old hard to find IRC related software.

## Miscellaneous

*Items that belong on the list but defy classification.*

- [superseriousstats](https://github.com/tommyrot/superseriousstats) - Fast and efficient program to create statistics out of various types of chat logs. `PHP` `Web`
- [img2src](https://github.com/waveplate/img2irc) - Convert images to halfblock ANSI or IRC, with a bunch of post-processing filters. `Rust`

## Use

The best ways to use this list are:

- By using <kbd>command</kbd> + <kbd>F</kbd> to search the contents

This list also uses tags to help when searching the contents:
- **Language** - `Python`, `Java`, `C++`, `Go`, `JavaScript`, `Ruby`, `C` etc.
- **Platform** - `Web`, `macOS`, `Windows`, `Linux`, `Chrome` etc.

## Credits

By [Craig Davison](https://davison.io) and contributors.
