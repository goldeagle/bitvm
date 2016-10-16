# bitvm
Bitvm is an pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, HHVM, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!

## Passwords
The account:password of the virtual machine (and mysqld) is root:toor.

## Base System (2016.10 upd 20161016)
* debian 8.6.0 (netinstall)
* linux-image 4.7.5-1 (apt)
* zsh 5.2 (apt)

## VCS
* git 2.9.3 (apt)
* subversion 1.9.4 (apt)

## Toolits
* rcconf 3.2 (apt)
* sysv-rc-conf 0.99 (apt)
* htop 2.0.2 (apt)
* iotop 0.6 (apt)
* iftop 1.0 (apt)
* unzip 6.20 (apt)
* curl 7.47.0 (apt)
* vim 8.0.0022 (apt)
* nmap 7.12 (apt)
* siege 3.0.8 (apt)
* dstat 0.7.2 (apt)
* byobu 5.87 (apt)
* tmux 2.2 (apt)
* multitail 6.4.2 (apt)
* mtr 0.86 (apt)
* socat 1.7.3.1 (apt)
* iptraf 3.0.0 (apt)
* ranger 1.7.1 (apt)

## Services
* nginx 1.10.1 (apt)
* mysql 5.6.30-1 (apt)
* mongodb 2.6.12-3 (apt)
* postgre 9.6.0 (apt)
* sqlite3 3.14.2-1 (apt)
* redis 3.2.4-2 (apt)
* varnish 5.0.0-2 (apt)
* memcached 1.4.31-1 (apt)
* beanstalkd 1.10-3 (apt)
* proftpd 1.3.5a (apt)

## Language Compiler & SDK
* gcc 6.1.1 (apt)
* nodejs 6.8.1 (apt)
* php 7.0.11-1 (apt)
* php 5.6.26-1 (apt)
* rust 1.12.0 (apt)
* go 1.7.1 (apt)

## Node Toolits & Modules
* npm 3.9.5 (manual)
* grunt 1.2.0 (npm)
* gulp 3.9.1 (npm)
* bower 1.7.9 (npm)
* coffee-script 1.10.0 (npm)

## PHP Toolits & Modules
* composer 1.2.1 (manual)
* top-think/think 5.0.1 (composer)
* laravel/installer 1.3.3 (composer)
* laravel/lumen-installer 1.0.2 (composer)

## Setting
* Debian 163 Mirror with SID tag
* Composer with Chinese Mirror
* /etc/locale.gen: add zh_CN* en_US*
* dpkg-reconfigure locales: C.UTF-8
* Add SystemTap Support with PHP