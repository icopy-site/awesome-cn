<div class="github-widget" data-repo="iJackUA/awesome-vagrant"></div>
## Awesome Vagrant
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/iJackUA/awesome-vagrant?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![Build Status](https://api.travis-ci.org/iJackUA/awesome-vagrant.svg?branch=master)](https://travis-ci.org/iJackUA/awesome-vagrant)

精选的 Vagrant 资源、插件、教程和其他好东西的精选列表.


## Official resources

* [Vagrant site](https://www.vagrantup.com/) - 安装说明、官方手册和文档.
* [GitHub repo](https://github.com/hashicorp/vagrant) - 源代码、问题讨论和协作.


## Boxes

*在哪里可以找到操作系统盒？*

* [Vagrantbox.es](http://www.vagrantbox.es/) - 所有可用框的最大列表，由社区通过 GitHub 拉取请求维护.
* [Vagrant Cloud](https://app.vagrantup.com/boxes/search) - 配置共享、盒子分发和发现（也是私人协作和共享的高级功能）.
* [Cloud Images Ubuntu.com](https://cloud-images.ubuntu.com/vagrant/) - “干净”的官方 Ubuntu 云镜像.
* [Baseboxes from Opscode](https://github.com/chef/bento#current-baseboxes) - CentOS、Fedora、Debian、FreeBSD、Ubuntu.
* [Puppet Labs Vagrant Boxes](http://puppet-vagrant-boxes.puppetlabs.com/) - 这些盒子供各种 Puppet 项目使用.
* [Cloudsmith](https://cloudsmith.io) - 一个完全托管的包管理 SaaS，支持 Vagrant 存储库（以及许多其他存储库）.

## Provisioning

* [All available build in provisioning providers](https://www.vagrantup.com/docs/provisioning) - 官方文档.
* [Vaprobash](http://fideloper.github.io/Vaprobash/index.html) - Vagrant Provisioning Bash 脚本.


## Notable plugins

*你可以通过这个命令`vagrant plugin install MODULE-NAME`安装这些模块*

* [List of available Vagrant plugins from GitHub wiki](https://github.com/hashicorp/vagrant/wiki/Available-Vagrant-Plugins).
* [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) - 自动更新 VirtualBox 来宾添加（根据 VB 版本）.
* [vagrant-hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater) - 在主机系统上的 /etc/hosts 文件中添加一个条目.
* [vagrant-cachier](http://fgrehm.viewdocs.io/vagrant-cachier/) - 在相似的 VM 实例之间共享一个公共包（apt-get、npm 等）缓存.
* [vagrant-host-shell](https://github.com/phinze/vagrant-host-shell) - 在 VM 启动时在主机上运行命令的 vagrant provisioner.
* [vagrant-ansible-local](https://github.com/jaugustin/vagrant-ansible-local)  允许直接从来宾 VM 为您的 VM 配置 ansible playbook.
* [sahara](https://github.com/jedi4ever/sahara) - 轻松管理 VM 状态（在试验软件堆栈时提交/回滚）.
* [vagrant-registration](https://github.com/projectatomic/adb-vagrant-registration) - 为 Vagrant 来宾添加“注册”和“取消注册”功能，以便在具有订阅模型（如 Red Hat Enterprise Linux）的系统上进行更新.
* [vagrant-service-manager](https://github.com/projectatomic/vagrant-service-manager) - 可以更轻松地访问由 [Atomic Developer Bundle (ADB)](https://github.com/projectatomic/adb-atomic-developer-bundle).
* [vagrant-scp](https://github.com/invernizzi/vagrant-scp) - 通过 SCP 将文件复制到 Vagrant VM.

## Helpers / Tools

* [Packer](https://www.packer.io/)  - 用于从单一源配置为多个平台创建相同机器映像的工具. 用于具有多供应商可移植性的快速基础设施部署.
* [T.A.D.S. boilerplate](https://github.com/Thomvaill/tads-boilerplate) - 创建、开发和部署 Docker Swarm 环境的样板，使用 Vagrant 在本地复制生产环境.
* [Veewee](https://github.com/jedi4ever/veewee) - 一种用于轻松（并重复）构建自定义 Vagrant 基础框、KVM 和虚拟机映像的工具.
* [Vagrant plugin for ZSH shell](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#vagrant) - 自动完成命令、任务名称、框名称和内置文档.
* [CLI Vagrant Manager](https://github.com/MunGell/vgm) - 管理多个 vagrant boxes 的简单命令行工具

## Desktop tools

* [Vagrant Manager](http://vagrantmanager.com/) 对于 OS X.

## Web services

*使用自动配置脚本生成 Vagrantfile.*

* [Phansible](http://phansible.com/) - 提供易于使用的界面，帮助您为基于 PHP 的项目生成 Ansible Playbook.
* [PuPHPet](https://puphpet.com/) - 为<s>PHP</s> Web 开发设置虚拟机的简单 GUI.
* [Protobox](http://getprotobox.com/) - PuPHPet 模拟，但使用自己的安装程序和 YAML 配置格式来控制安装在虚拟机上的所有内容.
* [Rove](http://rove.io/) - 允许您预生成典型 Vagrant 构建的服务.

## Proxy services

*代理您的本地网络服务器并使其在互联网上公开可用.*

* [Vagrant share](https://www.vagrantup.com/docs/share/) - 允许您与世界上任何人分享您的 Vagrant 环境.
* [nip.io](http://nip.io) - 提供通配符DNS的神奇域名
对于任何 IP 地址.
* [ngrok](https://ngrok.com/) - 用于创建安全隧道以将 NAT 或防火墙后面的本地服务器暴露给 Internet 的工具.
* [serveo](https://serveo.net/) - 将本地服务器暴露在互联网上，无需安装任何客户端！
* [proxylocal.com](http://proxylocal.com) - 代理您的本地网络服务器并使其在互联网上公开可用.
* [localtunnel.me](https://localtunnel.github.io/www/) - 为您分配一个唯一的可公开访问的 url，该 url 将代理所有请求到您本地运行的网络服务器.
* [portmap.io](https://portmap.io/) - 基于 OpenVPN 的免费端口转发解决方案.

## Tutorials

* [Getting Started With Vagrant](http://www.thisprogrammingthing.com/2013/getting-started-with-vagrant/) 通过这个编程的东西.
* [Getting started with Vagrant - automated dev servers deploy and provisioning.](http://stdout.in/en/post/getting_started_with_vagrant_automated_dev_servers_deploy_and_provisioning)
* [Working with Advanced Vagrant features in PhpStorm.](http://confluence.jetbrains.com/display/PhpStorm/Working+with+Advanced+Vagrant+features+in+PhpStorm)
* [Sharing Your Virtual Machine on the Web with Vagrant Share](https://scotch.io/tutorials/sharing-your-virtual-machine-on-the-web-with-vagrant-share).
* [Programming Community Curated Resources for Learning Vagrant](https://hackr.io/tutorials/learn-vagrant)
* [Vagrant Online Courses at Classpert](https://classpert.com/vagrant) Vagrant 在线课程列表（免费和付费）

## Books

* [Vagrant: Up and Running](https://www.amazon.com/Vagrant-Running-Virtualized-Development-Environments/dp/1449335837) 米切尔桥本.
* [Vagrant CookBook](https://leanpub.com/vagrantcookbook) 埃里卡·海蒂 (Erika Heidi) 着.
* [Pro Vagrant](https://www.amazon.com/Pro-Vagrant-Wlodzimierz-Gajda/dp/1484200748/) Wlodzimierz Gajda 着.
* [Creating Development Environments with Vagrant](http://shop.oreilly.com/product/9781849519182.do) / [2nd Edition](http://shop.oreilly.com/product/9781784397029.do) 通过迈克尔孔雀
* [Vagrant Virtual Development Environment Cookbook](http://shop.oreilly.com/product/9781784393748.do) 通过乍得汤普森

## Popular readymade environments

* [Vagrantpress](https://github.com/vagrantpress/vagrantpress) - 用于创建和修改 WordPress 站点的开发环境.
* [Varying Vagrant Vagrants](https://github.com/Varying-Vagrant-Vagrants/VVV) - 专注于 WordPress 开发的开源 Vagrant 配置.
* [Joomla-Vagrant](https://github.com/joomlatools/joomlatools-vagrant).
* [VDD](https://www.drupal.org/project/vdd) - Vagrant Drupal 开发.
* [Drupal VM](https://www.drupalvm.com/) - 用于本地 Drupal 开发的 VM，使用 Vagrant + Ansible 构建
* [Try Yii2](https://github.com/iJackUA/try-yii2) - 尝试 Yii2 与 Vagrant VM + Ansible provisioning = 完整的现成虚拟服务器游乐场.
* [Laravel4-Vagrant](https://github.com/bryannielsen/Laravel4-Vagrant) - 在带有 PHP 5.5 的 Ubuntu 12.04 Vagrant 虚拟机中运行 Laravel 4.
* [OpenStack on Ansible with Vagrant](https://github.com/openstack-ansible/openstack-ansible).
* [Laravel Homestead](https://laravel.com/docs/master/homestead) - 用于 Laravel 开发的官方 Vagrant Box，基于 Ubuntu 16.04 LTS、PHP 7、Nginx 和多个数据库平台.
* [Scotch Box](https://scotch.io/bar-talk/announcing-scotch-box-2-0-our-dead-simple-vagrant-lamp-stack-improved) - 简单的 Vagrant Box [LAMP](https://en.m.wikipedia.org/wiki/LAMP_%28software_bundle%29) 堆栈，加上一些有用的额外功能，基于 Ubuntu 14.04 LTS.


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Ievgen Kuzminov](http://stdout.in/) 已放弃该作品的所有版权和相关或邻接权.
