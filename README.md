# bitvm
Bitvm is an pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, HHVM, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!

## Passwords
The account:password of the virtual machine (and mysqld) is root:toor.

## Base System (2020.2 upd 20200208)
* debian 10.2 (netinstall)
* linux-image 4.13.4-2 (apt)
* zsh 5.4.1 (apt)

## VCS
* git 2.15rc1 (apt)
* subversion 1.9.7 (apt)

## Toolits
* htop 2.2.0-2 (apt)
* iotop 0.6-24 (apt)
* iftop 1.0~pre4-6 (apt)
* unzip 6.0-25 (apt)
* curl 7.67.0-2 (apt)
* vim 8.1.2269-1 (apt)
* nmap 7.80-1 (apt)
* siege 4.0.4-1 (apt)
* dstat 0.7.4-6 (apt)
* byobu 5.130-1.1 (apt)
* tmux 3.0a-2 (apt)
* multitail 6.4.2-3+b1 (apt)
* mtr 0.93-1 (apt)
* socat 1.7.3.3-2 (apt)
* iptraf-ng 1.1.4-+b1 (apt)
* ranger 1.9.3-1 (apt)

## Services
* nginx 1.16.1-3 (apt)
* mariadb 10.3.22-1 (apt)
* postgre 12.1-2q (apt)
* sqlite3 3.31.1-1 (apt)
* redis 5.0.7-1 (apt)
* varnish 6.2.1-2 (apt)
* memcached 1.5.22-2 (apt)
* beanstalkd 1.11-1 (apt)
* vsftpd 3.0.3-12+b1 (apt)

## Language Compiler & SDK
* gcc 9.2.1-3-1 (apt)
* nodejs 13.8.0 (manual)
* php 7.4.1-1 (apt)
* rust 1.41.0 (manual)

## PHP Toolits & Modules
* composer 1.9.3 (manual)

## Setting
* Debian 163 Mirror with SID tag
* Composer with Chinese Mirror
* /etc/locale.gen: add zh_CN* en_US*
* dpkg-reconfigure locales: C.UTF-8
* Add SystemTap Support with PHP
