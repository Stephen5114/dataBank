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
![](https://p.ananas.chaoxing.com/star3/origin/e1657e0e01caf9a5bbaff327b304375e.png) <br/>
2）	安装wampserver，具体的安装教程在网上都可以找到。在安装wamp过程中，需要选择一个默认浏览器和默认编辑器（如sublime或其它）。安装完wampserver，本地环境就算搭完了。打开wampserver，带右下角的图标变绿说明wamp启动成功，如下图所示。<br/>
![](https://p.ananas.chaoxing.com/star3/origin/a82be81b93730414bd676bb4f2d98600.png)<br/>
3）在浏览器中输入http://localhost/phpmyadmin/,选择phpMyAdmin 后，浏览器中弹出phpMyAdmin 登录界面，用户名为root，密码为空，点击执行即可进入主页，如下图所示，后面将在此进行数据库设计。<br/>
![](https://p.ananas.chaoxing.com/star3/origin/ff2280a07b614db91dd58a89813a7cf4.png)<br/>
4）	完成一个课程小程序，具有以下需求：<br/>

* 可以微信授权，获取个人信息

* 可以进行注册

* 注册成功登录后，可以进入我的页面，查看个人信息

* 可以修改个人信息

* 可以加入该课程进入学习

* 可以在课程中进行做题<br/>
5）	 最终，小程序完成，如下图所示：<br/>
![](https://img-blog.csdnimg.cn/20200517142941530.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQ0NzA0MjAw,size_16,color_FFFFFF,t_70#pic_center)<br/>

项目总结
------
## 1. 项目过程遇到的问题和解决的办法
* 1) 在配置Wam时，Wam为橙色，发现是端口占用的问题，经过百度，我test了3306和80端口，找到了占用80端口的sql server和3306的另一个mysql，这些程序被我禁止后，wam变成绿色，能够正常运行。 <br/>
* 2) 在做微信授权的时候，button按钮没有显示出来，后来发现是没有清除缓存操作。</br>
