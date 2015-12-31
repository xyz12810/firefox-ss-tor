Firefox+Lantern+Tor
-------------------
* 项目状态：匿名翻墙工具，Firefox_43.0.2集成Tor 0.2.7.6，前置Lantern_2.0.10最新源码编译，12月31日更新。
   - 点击Firefox-Tor.vbs启动。
* 说明：前置lantern和前置ss，分别是两种匿名方案，一般只需要下载一种即可使用。前置ss请打开Shadowsocks文件夹，配置自己的ss账号；前置lantern不用任何配置，点击Firefox-Tor.vbs即用。

下载
-----
* firefox43集成tor，前置lantern  [**本地下载**](https://github.com/yeahwu/firefox-tor/archive/master.zip)   &&&&&&&& [**Dropbox下载**](https://www.dropbox.com/s/w2rcccu4uodj67y/Firefox43-Tor.7z?dl=0﻿)

* firefox42集成tor，前置ss [**Dropbox下载**](https://www.dropbox.com/s/cqp1auw3h4am0dy/ss-tor.zip?dl=0)

* Tor检测，点击下面网址查看有没有成功匿名。https://check.torproject.org/?lang=zh_CN

问题
------
* 链路链接不上问题：
   - 1:请删除原有lantern的yaml文件，让其自动生成。
   - 2:请不要在浏览器上安装或设置代理插件，PAC。
   - 3:确认文件是否下载完整，大小65mb左右。
* 文件解压错误问题：
   - 请用[7-zip](https://sparanoid.com/lab/7z/)解压

特色
----
* 一键启动lantern和tor，启动检测进程，保持各项单进程，不会重复进程。
* tor隐身启动，可以去进程管理器查看进程，lantern最小化启动。五秒连上，速度取决于前置。
* 优化tor链路缺省，保证链路速度。
* 优化浏览器各项安全设置，保证tor的匿名性。

技术原理
------
* 由于GFW的原因，tor在国内基本不能直连，必须前置lantern或者ss等才能连上。前置SS的作用仅仅是起个链路建立里的通信用。当链路建立后，所有数据走链路。因为缺省每30秒重建链路，所以，SS使用每30秒一次。匿名和安全性不受影响。

系统支持
------
*  windows xp/7/8/10
 
联系
------
* [Goolge+](https://plus.google.com/communities/101215702940766881013)
* [Twitter](https://twitter.com/yeahwu404)

感谢
------
非常感谢gary12的居多建议和技术支持！
* Gary12
* Shadowsocks
* Tor
* Lantern
* PortableApps

附图
------
firefox状态页
![Tor_status](https://raw.githubusercontent.com/yeahwu/wu/master/tor.JPG)
![firefox_status](https://github.com/yeahwu/wu/blob/master/firefox8.JPG?raw=true)

