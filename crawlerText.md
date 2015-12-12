node爬虫
=
1、建站
-
服务端：nodejs + expressjs + sqlite

前端：reactjs

参考文档	

[http://www.expressjs.com.cn/4x/api.html](http://www.expressjs.com.cn/4x/api.html)

[http://www.chinaz.com/web/2015/0512/405473.shtml]()

[http://blog.modulus.io/nodejs-and-sqlite]()

2、识别 记录，存储
-
浏览器：chrome

小工具：chrome插件（页面手势跟踪）

参考文档

[http://www.cnblogs.com/guogangj/p/3235703.html](chrome插件制作)

[https://developer.chrome.com/extensions/getstarted.html]()*（需要翻墙）*

具体实现：

	使用chrome加载目标网页
	在目标网页上点击小工具，小工具会跟踪鼠标轨迹（鼠标hover事件可以实现）
	当选中目标时，记录目标dom节点和数据，并按一定规则发送到服务端记录

3、域名分析 字段对比 找出不同
-
