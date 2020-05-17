# dataBank
微信小程序-答题练习
====


项目记录
------
## 1、项目概述
本项目致力于开发一个节约成本，体积小的程序，从而为公众提供方便学习，练习答题的服务。我们的“答题小助手”会为公众提供更具体、精细、海量的数据，进而提高公众对资源练习信息的可利用率，大大提升公众的学习能力和学习效率<br/>
## 2、项目设计
1）     登陆页面开发<br/>
2）     注册页面开发<br/>
3）    公告页面开发<br/>
4）	我的页面模块开发<br/>
5）	信息修改页面模块开发<br/>
6）	课程页面模块开发<br/>
7）	后台数据库开发<br/>
8）	系统的实现；<br/>
9）	系统测试。<br/>
## 3、项目实现及测试
1）	https://mp.weixin.qq.com。 申请微信小程序的账号。申请完成，登录小程序账号，进入小程序后台管理页面，左侧导航栏选择“开发”，然后单击“开发设置”可查看AppID及AppSecret，需要单独记录和保存（切记，AppSecret只能查看一次，后面查看需要重置），后面用于开发工具的登录。
![](https://p.ananas.chaoxing.com/star3/origin/e1657e0e01caf9a5bbaff327b304375e.png)
2）	进行前期数据采集，调用python中urllib库和requests库等第三方库，爬取政府数据网站中各省市人口数据和百度地图中世界地图，爬取所得的地图文件以img形式存储在本地。<br/>
3）	对数据进行清洗、加工、特征分析，根据数据利用python语言的basemap库绘制人口热力图、人口密集度、人口聚集度图。<br/>
4）	同时，利用canvas前端技术，进行地理大数据可视化分析，绘制经济爆发点预测图、人口流动图、经济辐射图等。<br/>
5）	完成数据可视化模块，将数据分析后所得图片制成web页面，便于用户查询。<br/>
