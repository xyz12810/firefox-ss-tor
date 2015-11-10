Firefox+Lantern+Tor
-------------------
* 项目状态：Firefox41.0.2集成Tor,前置Lantern。
   - 点击Firefox-Tor.vbs启动。
* 请不要更新浏览器，因为为了匿名，浏览器经过特殊设置，更新后会被重置。

准备工作
-------------
*  前置lantern不用任何配置，点击Firefox-Tor.vbs即用。

*  前置ss请打开Shadowsocks-2.5.8文件夹，配置自己的ss账号。确保本地监听端口为：127.0.0.1:1080

下载
-----
* [**前置lantern下载**](https://github.com/yeahwu/firefox-tor/archive/master.zip)
  
* [**前置shadowsocks下载**](https://github.com/yeahwu/firefox-tor/archive/Firefox41.0.2%E9%9B%86%E6%88%90Tor,%E5%89%8D%E7%BD%AEShadowsocks.zip)

* 前置lantern，Sync同步密匙：  BLELSDQV6NJXJLW57O7CXK2RJKKHXG6I7

* Tor检测，点击下面网址查看有没有成功匿名。https://check.torproject.org/?lang=zh_CN

特色
----
* 一键启动lantern和tor，启动检测进程，保持各项单进程，不会重复进程。
* tor隐身启动，可以去进程管理器查看进程。lantern最小化启动。
* tor五秒连上，速度取决于前置。

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

