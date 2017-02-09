# bitvm
Bitvm is an pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, HHVM, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!

## Passwords
The account:password of the virtual machine (and mysqld) is root:toor.

## Base System (2017.2 upd 20170209)
* debian 8.7.0 (netinstall)
* linux-image 4.9.6-3 (apt)
* zsh 5.3.1 (apt)

## VCS
* git 2.11.0 (apt)
* subversion 1.9.5 (apt)

## Toolits
* rcconf 3.2 (apt)
* sysv-rc-conf 0.99-7 (apt)
* htop 2.0.2-1 (apt)
* iotop 0.6-2 (apt)
* iftop 1.0~pre4-4 (apt)
* unzip 6.0-21 (apt)
* curl 7.52.1-2 (apt)
* vim 8.0.0197-1 (apt)
* nmap 7.40-1 (apt)
* siege 4.0.2-1 (apt)
* dstat 0.7.3-1 (apt)
* byobu 5.112-1 (apt)
* tmux 2.3-4 (apt)
* multitail 6.4.2-1 (apt)
* mtr 0.87-1 (apt)
* socat 1.7.3.1-2 (apt)
* iptraf-ng 1.1.4-4 (apt)
* ranger 1.8.1-0.1 (apt)

## Services
* nginx 1.10.2-4 (apt)
* mysql 5.7.17-1 (apt)
* mongodb 3.2.11-2 (apt)
* postgre 9.6+179 (apt)
* sqlite3 3.16.2-2 (apt)
* redis 3.2.7-1 (apt)
* varnish 5.0.0-6 (apt)
* memcached 1.4.33-1 (apt)
* beanstalkd 1.10-4 (apt)
* vsftpd 3.0.3-8+b1 (apt)

## Language Compiler & SDK
* gcc 6.3.0-6 (apt)
* nodejs 6.9.5 (bin)
* php 7.0.15-1 (apt)
* php 5.6.26-1 (apt)
* rust 1.14.0 (apt)
* go 1.7.4 (apt)

## Node Toolits & Modules
* npm 3.10.8 (manual)
* bower 1.8.0 (npm)
* coffee-script 1.11.0 (npm)

## PHP Toolits & Modules
* composer 1.2.2 (apt)

## Setting
* Debian 163 Mirror with SID tag
* Composer with Chinese Mirror
* /etc/locale.gen: add zh_CN* en_US*
* dpkg-reconfigure locales: C.UTF-8
* Add SystemTap Support with PHP