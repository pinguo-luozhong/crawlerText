node爬虫
=
1、建站
-
服务端：nodejs + expressjs + sqlite

参考文档	

[expressjs文档](http://www.expressjs.com.cn/4x/api.html)

[Express JS入门搭建网站](http://www.chinaz.com/web/2015/0512/405473.shtml)

[nodejs+sqlite使用](http://blog.modulus.io/nodejs-and-sqlite)

[使用nodejs sqlite3查询数据](https://www.phodal.com/blog/node-sqlite3-javascript-with-sqlite3-db-file/)

2、展示（开发跨平台桌面应用）
=
前端：node-webkit

实现

	html+node-webkit开发桌面应用
	
	展示目标论坛list
	
	记录各个论坛状态，并标注显示
	
	点击链接可载入当前页

参考文档

[node-webkit框架学习](http://blog.csdn.net/glt3953/article/details/12783801)

[node-webkit工程搭建](http://blog.csdn.net/glt3953/article/details/12510923)

[玄魂的博客（node-webkit学习）](http://www.cnblogs.com/xuanhun/tag/node-webkit/)

[github源文档](https://github.com/nwjs/nw.js)

3、识别 记录，存储
-
浏览器：node-webkit

具体实现：

	载入目标页面
	
	鼠标mouseover mouseout事件跟踪并改变样式
	
	当选中目标时，记录目标dom节点和数据，并按一定规则发送到服务端记录
4、制作爬虫
-
参考文档

[nodejs制作爬虫](http://www.aspku.com/kaifa/javascript/45405.html)

步骤

	创建项目

	superagent获取源数据

	cheerio解析
	
	CSS selector来筛选目标数据对比

	eventproxy并发抓取
	

5、启动服务
=
以上功能准备就绪
	
		定时运行爬虫遍历列表数据进行对比
		
		根据返回的结果展示最新列表信息，做出标注
		