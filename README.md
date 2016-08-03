# bitvm
Bitvm is an pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, HHVM, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!

## Passwords
The account:password of the virtual machine (and mysqld) is root:toor.

## Base System (2016.5 upd 20160714)
* debian 8.4.0 (netinstall)
* linux-image 4.6.4-1 (apt)
* zsh 5.2 (apt)

## VCS
* git 2.8.1 (apt)
* subversion 1.9.4 (apt)

## Toolits
* rcconf 3.1 (apt)
* sysv-rc-conf 0.99 (apt)
* htop 2.0.1 (apt)
* iotop 0.6 (apt)
* iftop 1.0 (apt)
* unzip 6.20 (apt)
* curl 7.47.0 (apt)
* vim 7.4.1829 (apt)
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
* mysql 5.6.30 (apt)
* mongodb 2.4.14 (apt)
* postgre 9.5+175 (apt)
* sqlite3 3.13.0 (apt)
* redis 3.2.1-3 (apt)
* varnish 4.1.3 (apt)
* memcached 1.4.25 (apt)
* beanstalkd 1.10 (apt)
* proftpd 1.3.5 (apt)

## Language Compiler & SDK
* gcc 5.4.0-6 (apt)
* nodejs 6.3.1 (manual)
* php 7.0.9-1 (apt)
* php 5.6.23-1 (apt)
* rust 1.10.0 (apt)
* go 1.6.3 (apt)

## Node Toolits & Modules
* npm 3.9.5 (manual)
* grunt 1.2.0 (npm)
* gulp 3.9.1 (npm)
* bower 1.7.9 (npm)
* coffee-script 1.10.0 (npm)

## PHP Toolits & Modules
* composer 1.1.3 (apt)
* hhvm 3.12.1 (apt)
* top-think/think 5.0RC4 (composer)
* laravel/installer 1.3.3 (composer)
* laravel/lumen-installer 1.0.2 (composer)

## Setting
* Debian 163 Mirror with SID tag
* Composer with Chinese Mirror
* /etc/locale.gen: add zh_CN* en_US*
* dpkg-reconfigure locales: C.UTF-8
* Add SystemTap Support with PHP