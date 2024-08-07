<div class="github-widget" data-repo="DataDaoDe/awesome-foss-apps"></div>
## Awesome FOSS apps [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome production grade free and open source software organized by category.

This list is for developers who are looking for non-trivial quality applications they can analyze and learn from.

*Inspired by Sindre Sorhus's [awesome](https://github.com/sindresorhus/awesome).*

## TOC



## Web Apps (frontend only)
----

### [Codesandbox](https://github.com/CompuIves/codesandbox-client)

* react, nginx, phoenix
* GNU General Public License

> Codesandbox is an online IDE for web developers to quickly prototype and implement frontend applications using modern javascript frameworks like Vue, Preact, React etc Or even vanilla javascript.  

### [CircleCI](https://github.com/circleci/frontend)

* clojurescript, om, react
* Eclipse Public License

> CircleCI provides a continuous integration and deployment platform. The frontend is an impressive example of a large application built with the immutable data structures of clojurescript. The frontend integrates with pusher, intercom, d3, and google analytics and has a great example of navigation routing and communication via real-time events, websockets, and backend API servers. Its test suite is not that extensive but does provide a good example of how to test clojurescript/om apps using karma.

### [Precursor App](https://github.com/PrecursorApp/precursor)

* clojurescript, om, react
* Eclipse Public License

> Precursor is a highly interactive prototyping webapp. Its frontend is built from the ground up with clojurescript. The project has a simple enough routing and event passing system such that newer clojurescript developers could easily understand how routing in clojurescript applications can work. It is also full of many examples of how to build a component based frontend architecture that is part of an interactive graphics application i.e. where many components manipulate the HTML5 canvas or work with HTML5 APIs. 

### [The Guardian](https://github.com/guardian/frontend)

* play2, scala, node
* Apache 2.0 License

> The guardian is a news site with subscriptions, sign in, search, an admin interface and a series of middleman scala apps that handle communication between the static frontends and backend APIs. Its very fast and has a comprehensive test suite plus great examples of how to optimize large traditional websites for speed.

### Web Apps (fullstack)
----

### [Ghost](https://github.com/TryGhost/Ghost)

* node, express, ember
* MIT License

> Ghost provides a simple publishing platform for bloggers. The code contains an emberjs client and node server backend that handle authorization, role management, tagging, blog posting, data persistence, and most things you'd expect from a quality blogging platform. The only thing that Ghost doesn't handle is i18n. It also contains a comprehensive test suite with both integration and unit tests that hit the whole ember/node stack.

### [Gitlab](https://github.com/gitlabhq/gitlabhq)

* ruby, rails, coffescript, redis, sidekiq,
* MIT License

> Gitlab is a code collaboration tool. It is used by more than 100,000 organizations. It has just about everything you could imagine in a webapp, user management, user roles, OAuth, i18n, many modules designed for integrating with third-parties, deep git integration, and an extensive asynchronous task system using Sidekiq. It has an exemplary test suite using cucumber and rspec.

### [Discourse](https://github.com/discourse/discourse)

* ruby, rails, ember
* GPLv2 License

> Discourse is a discussion platform or a modern take on the web forum. It has a very modular system built on top of rails and contains great examples of how to build an interactive frontend in ember within a rails application. It has an admin interface, signup/sign-in with Oauth for Google, Facebook, Twitter, Yahoo, and Github. It has extensive i18n, real time notifications, a plugin ecosystem, is SEO optimized, and is designed for tablet and mobile devices.

### [Reddit](https://github.com/reddit)

* python, pylons, node, react, rabbitmq, postgresql
* Common Public Attribution License Version 1.0

> Reddit is a news platform for what's new and popular on the web. It is built in python and integrates with a lot of third party services: rabbitmq, memcached, cassandra, solr, and postgresql to name a few. The code provides a good example of a large pylons project and shines when it comes to the code that integrates with many other services.

### [Taiga](https://github.com/taigaio)

* python3, django, coffeescript, angular
* GNU Affero License

> Taiga is a project management tool. It is an incredible example of a modular architecture. Its interface is clean, very well-designed, responsive, and fast, and the modern backend code written in python3 is a great example of a well written django app. It also has an extensive test suite with both integration and unit tests using pytest.


### [Travis CI](https://github.com/travis-ci)

* ruby, rails, sinatra, rabbitmq, ember
* MIT License

> Travis CI is a continutous integration and deployment system. What's great about Travis is its modular architecture, every component of this large distributed system is split up by its main function. From worker management, rails backend, emberjs frontend to yaml configuration parser, each is split up into there own repositories.

### [Filestash](https://github.com/mickael-kerjean/filestash)

* golang, react
* AGPLv3 License

> Filestash is a web based file manager that supports a range of protocols and platforms: FTP, SFTP, S3, Minio, Git, WebDAV, Backblaze, Dropbox, Google Drive, LDAP, CalDAV, CardDAV.

### [Dnote](https://github.com/dnote/dnote)

* golang, react, typescript
* GPLv3 License, AGPLv3 License

> Dnote is a free and open source command line note-taking software that supports a scalable data synchronization among an unlimited number of devices and a mobile-first web interface that can also be installed as a Progressive Web App on mobile devices.

### [Healthchecks](https://github.com/healthchecks/healthchecks)

* python, django, postgresql
* BSD License

> Healthchecks is a cron job monitoring service. It listens for HTTP requests and email messages ("pings") from your cron jobs and scheduled tasks ("checks"). When a ping does not arrive on time, Healthchecks sends out alerts.

## Desktop Apps
----

### [Blender](http://www.blender.org/download/)

* c, c++, python
* GPLv2 License

> Blender is 3D Graphic Software that can visually compete with Maya and 3DS Max. The end product is an amazing example of a cross-platform 3D Tooling piece of software. It is a very mature project having been in development since 1994. It has an embedded python scripting engine, a game logic engine and is loaded with implementations of 3d manipulation, rendering, and compositing algorithms.


### [Atom](https://github.com/atom/atom)

* coffeescript, electron, node
* MIT License

> Atom is a hackable text editor. Its built on top of electron and is a good example of integrating libchromium, nodejs, and web technologies into a cross-platform runnable binary. It also contains an exemplary test suite for electron apps.

### [Daytona](https://github.com/daytonaio/daytona)

* go
* Apache 2.0 License

> Daytona is a radically simple open source development environment manager. It automates the entire process of setting up development environments; provisioning the instance, interpreting and applying the configuration, setting up prebuilds, establishing a secure VPN connection, securely connecting your local or a Web IDE, and assigning a fully qualified domain name to the development environment for easy sharing and collaboration.

### Mobile Apps
----

*still searching*

### Games
----

### [0ad](https://github.com/0ad/0ad)

* c++, python
* GPLv2 License

> 0 A.D is a cross-platform real-time strategy game of ancient warfare. Every aspect of the game's implementation is modern and impressive - from the AI to the graphics. It also has an embedded SpiderMonkey scripting engine, which is a great example for adding js scriptability to an existing cpp project.

### [Hedgewars](https://github.com/hedgewars/hw)

* c, c++, pascal, haskell
* GPLv2 License

> Hedgewars is a 2D turn-based strategy game like worms but with hedgehogs. Its graphics, animation, and gameplay can compete with worms on every level. The game server is an impressive real-world example of Haskell and the frontend provides a clean interface between QT and the backend game.

### [Wesnoth](https://github.com/wesnoth/wesnoth)

* c, c++, lua
* GPLv2 License

> The Battle for Wesnoth is a turn-based tactical strategy game with a high fantasy theme. It features single player and online multiplayer combat. Its GUI and gameplay graphics are impressive as well as its multi-platform support (it even builds on NaCL). It has clean, well-coded examples of pretty much everything a game developer would want to know, from a an embedded lua scripting engine, to a dialog and GUI system, to a c++ test suite and cross-platform builds.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, John Faucett has waived all copyright and related or neighboring rights to this work.
