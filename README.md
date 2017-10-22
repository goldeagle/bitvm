# bitvm
Bitvm is an pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, HHVM, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!

## Passwords
The account:password of the virtual machine (and mysqld) is root:toor.

## Base System (2017.8 upd 20170825)
* debian 9.2.1 (netinstall)
* linux-image 4.13.4-2 (apt)
* zsh 5.4.1 (apt)

## VCS
* git 2.15rc1 (apt)
* subversion 1.9.7 (apt)

## Toolits
* rcconf 3.2 (apt)
* sysv-rc-conf 0.99-7 (apt)
* htop 2.0.2-1 (apt)
* iotop 0.6-2 (apt)
* iftop 1.0~pre4-4 (apt)
* unzip 6.0-21 (apt)
* curl 7.55.0-1 (apt)
* vim 8.0.1141-b1 (apt)
* nmap 7.60-1 (apt)
* siege 4.0.2-1 (apt)
* dstat 0.7.3-1 (apt)
* byobu 5.112-1 (apt)
* tmux 2.5-3 (apt)
* multitail 6.4.2-3 (apt)
* mtr 0.87-1 (apt)
* socat 1.7.3.1-2 (apt)
* iptraf-ng 1.1.4-6 (apt)
* ranger 1.8.1-0.1 (apt)

## Services
* nginx 1.13.6-2 (apt)
* mysql 5.7.18-1 (apt)
* mongodb 3.2.17-1 (apt)
* postgre 9.6+184 (apt)
* sqlite3 3.19.3 (apt)
* redis 4.0.2 (apt)
* varnish 5.0.0-7.1 (apt)
* memcached 1.4.33-1 (apt)
* beanstalkd 1.10-4 (apt)
* vsftpd 3.0.3-9 (apt)

## Language Compiler & SDK
* gcc 7.2.0-1 (apt)
* nodejs 8.7.0 (manual)
* php 7.0.22-3 (apt)
* rust 1.21.0 (manual)

## Node Toolits & Modules
* npm 5.14.2 (manual)
* bower 1.8.0 (npm)

## PHP Toolits & Modules
* composer 1.5.2 (manual)

## Setting
* Debian 163 Mirror with SID tag
* Composer with Chinese Mirror
* /etc/locale.gen: add zh_CN* en_US*
* dpkg-reconfigure locales: C.UTF-8
* Add SystemTap Support with PHP
