node爬虫
=
1、建站
-
服务端：nodejs + expressjs + sqlite

前端：reactjs

参考文档	

[expressjs文档](http://www.expressjs.com.cn/4x/api.html)

[Express JS入门搭建网站](http://www.chinaz.com/web/2015/0512/405473.shtml)

[nodejs+sqlite使用](http://blog.modulus.io/nodejs-and-sqlite)

[使用nodejs sqlite3查询数据](https://www.phodal.com/blog/node-sqlite3-javascript-with-sqlite3-db-file/)

2、识别 记录，存储
-
浏览器：chrome

小工具：chrome插件（页面手势跟踪）

参考文档

[chrome插件制作](http://www.cnblogs.com/guogangj/p/3235703.html)

[谷歌开发者官方文档](https://developer.chrome.com/extensions/getstarted.html)*（需要翻墙）*

具体实现：

	使用chrome加载目标网页
	在目标网页上点击小工具，小工具会跟踪鼠标轨迹（鼠标hover事件可以实现）
	当选中目标时，记录目标dom节点和数据，并按一定规则发送到服务端记录
开爬
-
