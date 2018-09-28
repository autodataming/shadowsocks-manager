Shadowsocks-Manager
===================

Shadowsocks with multi user and traffic control.Base on MEAN (Mongo Express Angularjs Nodejs).

Notice
------
The author just maintain [version 2](https://github.com/shadowsocks/shadowsocks-manager) .
But I will maintain the version 1.

Dependencies
------------

    Nodejs  4.4
    Mongodb 3.2

Install
-------

    git clone -b version1 https://github.com/shadowsocks/shadowsocks-manager.git
    npm install -g bower
    cd shadowsocks-manager
    npm install
    bower install

Usage
-----

    cd shadowsocks-manager
    mv config.js.sample config.js

在config.js文件中配置管理员账号，邮箱账号等
    node server

Demo
----

http://gyteng.com:6003/

Screenshot
----------

<img src="https://github.com/shadowsocks/shadowsocks-manager/blob/version1/wiki/img/Screenshot0.png" width="240">
<img src="https://github.com/shadowsocks/shadowsocks-manager/blob/version1/wiki/img/Screenshot1.png" width="240">
<img src="https://github.com/shadowsocks/shadowsocks-manager/blob/version1/wiki/img/Screenshot2.png" width="240">
<img src="https://github.com/shadowsocks/shadowsocks-manager/blob/version1/wiki/img/Screenshot3.png" width="240">
