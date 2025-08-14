重要的事情说三遍，商用请购买正版！！商用请购买正版！！商用请购买正版！！
本源码只适用于学习，禁止商用！！禁止商用！！禁止商用！！

首先需要安装php扩展。根据网站要使用的php版本，下载扩展文件（php7.2），上传到php安装目录 /lib/php/extensions/no-debug-non-zts-xxxx（xxxx 为一串数字）文件夹里面。

修改php配置文件（php.ini），加入以下内容，然后重启php进程。

extension=idcsmart.so


