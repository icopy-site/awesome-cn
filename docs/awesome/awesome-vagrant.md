<div class="github-widget" data-repo="iJackUA/awesome-vagrant"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Vagrant
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/iJackUA/awesome-vagrant?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![Build Status](https://api.travis-ci.org/iJackUA/awesome-vagrant.svg?branch=master)](https://travis-ci.org/iJackUA/awesome-vagrant)

精选的Vagrant资源，插件，教程和其他好东西的精选列表.


## Official resources

* [Vagrant site](https://www.vagrantup.com/) -安装说明，官方手册和文档.
* [GitHub repo](https://github.com/hashicorp/vagrant) -源代码，问题讨论和协作.


## Boxes

*在哪里可以找到OS盒？*

* [Vagrantbox.es](http://www.vagrantbox.es/) -所有可用盒子的最大列表，由社区通过GitHub拉取请求维护.
* [Vagrant Cloud](https://app.vagrantup.com/boxes/search) -配置共享，盒子分发和发现（也是私人协作和共享的高级功能）.
* [Cloud Images Ubuntu.com](https://cloud-images.ubuntu.com/vagrant/) -“干净的”官方Ubuntu云映像.
* [Baseboxes from Opscode](https://github.com/chef/bento#current-baseboxes) -CentOS，Fedora，Debian，FreeBSD，Ubuntu.
* [Puppet Labs Vagrant Boxes](http://puppet-vagrant-boxes.puppetlabs.com/) -这些盒子被提供给各种Puppet项目使用.
* [Cloudsmith](https://cloudsmith.io) -全面管理的软件包管理SaaS，支持Vagrant存储库（以及许多其他存储库）.

## Provisioning

* [All available build in provisioning providers](https://www.vagrantup.com/docs/provisioning/index.html) -官方文件
* [Vaprobash](http://fideloper.github.io/Vaprobash/index.html) -Vagrant Provisioning Bash脚本.


## Notable plugins

*您可以通过以下命令安装这些模块`vagrant plugin install MODULE-NAME` *

* [List of available Vagrant plugins from GitHub wiki](https://github.com/hashicorp/vagrant/wiki/Available-Vagrant-Plugins).
* [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) -自动更新VirtualBox来宾添加（根据VB版本）.
* [vagrant-hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater) -在主机系统上的/ etc / hosts文件中添加一个条目.
* [vagrant-cachier](http://fgrehm.viewdocs.io/vagrant-cachier/) -在相似的VM实例之间共享一个通用程序包（apt-get，npm等）缓存.
* [vagrant-host-shell](https://github.com/phinze/vagrant-host-shell) -一个无用的供应商，可在VM启动时在主机上运行命令.
* [vagrant-ansible-local](https://github.com/jaugustin/vagrant-ansible-local)  允许直接从来宾VM为VM配置Ansible剧本.
* [sahara](https://github.com/jedi4ever/sahara) -轻松管理虚拟机状态（在尝试软件堆栈时提交/回退）.
* [vagrant-registration](https://github.com/projectatomic/adb-vagrant-registration) -向Vagrant来宾添加“注册”和“取消注册”功能，以便在具有订阅模型（如Red Hat Enterprise Linux）的系统上进行更新.
* [vagrant-service-manager](https://github.com/projectatomic/vagrant-service-manager) -使您可以更轻松地访问由 [Atomic Developer Bundle (ADB)](https://github.com/projectatomic/adb-atomic-developer-bundle).
* [vagrant-scp](https://github.com/invernizzi/vagrant-scp) -通过SCP将文件复制到Vagrant VM.

## Helpers / Tools

* [Packer](https://www.packer.io/)  -用于从单一源配置为多个平台创建相同机器映像的工具.  具有多提供商可移植性的快速基础架构部署.
* [T.A.D.S. boilerplate](https://github.com/Thomvaill/tads-boilerplate) -使用Vagrant在本地复制生产环境的样板文件，用于创建，开发和部署Docker Swarm环境.
* [Veewee](https://github.com/jedi4ever/veewee) -用于轻松（并反复）构建自定义Vagrant基本框，KVM和虚拟机映像的工具.
* [Vagrant plugin for ZSH shell](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#vagrant) -自动完成命令，任务名称，框名称和内置文档.
* [CLI Vagrant Manager](https://github.com/MunGell/vgm) -简单的命令行工具来管理多个无用的盒子

## Desktop tools

* [Vagrant Manager](http://vagrantmanager.com/) 对于OSX.

## Web services

*使用自动配置脚本生成Vagrantfile.*

* [Phansible](http://phansible.com/) -提供易于使用的界面，可帮助您为基于PHP的项目生成Ansible Playbook.
* [PuPHPet](https://puphpet.com/) -一个简单的GUI，用于为<s>PHP</s> Web开发设置虚拟机.
* [Protobox](http://getprotobox.com/) -PuPHPet模拟，但使用具有YAML配置格式的自己的安装程序来控制虚拟机上安装的所有内容.
* [Rove](http://rove.io/) -一项服务，可让您预先生成典型的Vagrant版本.

## Proxy services

*要代理您的本地Web服务器并使其可以通过Internet公开使用.

* [Vagrant share](https://www.vagrantup.com/docs/share/) -允许您与世界上任何人共享您的Vagrant环境.
* [nip.io](http://nip.io) -提供通配符DNS的魔术域名
任何IP地址.
* [ngrok](https://ngrok.com/) -创建安全隧道的工具，用于将NAT或防火墙后面的本地服务器公开到Internet.
* [serveo](https://serveo.net/) -将本地服务器暴露给Internet，而无需安装任何客户端！
* [proxylocal.com](http://proxylocal.com) -代理您的本地网络服务器，并使其可以通过Internet公开使用.
* [localtunnel.me](https://localtunnel.github.io/www/) -为您分配一个唯一的公共可访问网址，该网址会将所有请求代理到本地运行的网络服务器.
* [portmap.io](https://portmap.io/) -基于OpenVPN的免费端口转发解决方案.

## Tutorials

* [Getting Started With Vagrant](http://www.thisprogrammingthing.com/2013/getting-started-with-vagrant/) 通过这个编程的东西.
* [Getting started with Vagrant - automated dev servers deploy and provisioning.](http://stdout.in/en/post/getting_started_with_vagrant_automated_dev_servers_deploy_and_provisioning)
* [Working with Advanced Vagrant features in PhpStorm.](http://confluence.jetbrains.com/display/PhpStorm/Working+with+Advanced+Vagrant+features+in+PhpStorm)
* [Sharing Your Virtual Machine on the Web with Vagrant Share](https://scotch.io/tutorials/sharing-your-virtual-machine-on-the-web-with-vagrant-share).
* [Programming Community Curated Resources for Learning Vagrant](https://hackr.io/tutorials/learn-vagrant)

## Books

* [Vagrant: Up and Running](https://www.amazon.com/Vagrant-Running-Virtualized-Development-Environments/dp/1449335837) 由桥本（Mitchell Hashimoto）设计.
* [Vagrant CookBook](https://leanpub.com/vagrantcookbook) 埃里卡·海蒂（Erika Heidi）撰写.
* [Pro Vagrant](https://www.amazon.com/Pro-Vagrant-Wlodzimierz-Gajda/dp/1484200748/) 给Wlodzimierz Gajda.
* [Creating Development Environments with Vagrant](http://shop.oreilly.com/product/9781849519182.do) / [2nd Edition](http://shop.oreilly.com/product/9781784397029.do) 迈克尔·孔雀（Michael Peacock）
* [Vagrant Virtual Development Environment Cookbook](http://shop.oreilly.com/product/9781784393748.do) 乍得汤普森（Chad Thompson）

## Popular readymade environments

* [Vagrantpress](https://github.com/vagrantpress/vagrantpress) -用于创建和修改WordPress网站的开发环境.
* [Varying Vagrant Vagrants](https://github.com/Varying-Vagrant-Vagrants/VVV) -专注于WordPress开发的开源Vagrant配置.
* [Joomla-Vagrant](https://github.com/joomlatools/joomlatools-vagrant).
* [VDD](https://www.drupal.org/project/vdd) -无家可归的Drupal开发.
* [Drupal VM](https://www.drupalvm.com/) -使用Vagrant + Ansible构建的用于本地Drupal开发的VM
* [Try Yii2](https://github.com/iJackUA/try-yii2) -尝试使用带有Vagrant VM的Yii2 + Ansible置备=完整的现成虚拟服务器游乐场.
* [Laravel4-Vagrant](https://github.com/bryannielsen/Laravel4-Vagrant) -在带有PHP 5.5的Ubuntu 12.04 Vagrant虚拟机中运行Laravel 4.
* [OpenStack on Ansible with Vagrant](https://github.com/openstack-ansible/openstack-ansible).
* [Laravel Homestead](https://laravel.com/docs/master/homestead) -用于Laravel开发的官方Vagrant Box，基于Ubuntu 16.04 LTS，PHP 7，Nginx和多个数据库平台.
* [Scotch Box](https://scotch.io/bar-talk/announcing-scotch-box-2-0-our-dead-simple-vagrant-lamp-stack-improved) -简单的无业游民箱 [LAMP](https://en.m.wikipedia.org/wiki/LAMP_%28software_bundle%29) 堆栈，以及基于Ubuntu 14.04 LTS的一些有用的其他功能.


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Ievgen Kuzminov](http://stdout.in/) 放弃了此作品的所有版权以及相关或邻近的权利.
