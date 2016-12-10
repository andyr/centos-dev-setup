TODO
====
 - Configure kickstart file (point to 6.4 amd64)
 - Instances to setup:
    - Dev (no x), ssh-agent, keychain (extra repo), 
    - Dev (x)
    - Server (no dev tools)

 - After kickstart, need to configure (using steps in github)
 - enable dhcp, ssh-agent, keygen, copy httpd files, restart apache, start mysql
 - enter default data into db (db dump or migration)
 - test website to check response
 - setup dns



Extra Packages
===============
tmux
mercurial
ssh-agent
ssh-keygen (meta package for all these)
git
vim
vim-scripts
mysql-server
mysql
apache
whereis
php
mysql-server
mysql
apache

* dev only
nodejs (wget this file and build it locally; should install npm as well)
jasmine
python
virtualenvwrapper

