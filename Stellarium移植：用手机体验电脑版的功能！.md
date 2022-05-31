# Stellarium移植：用手机体验电脑版的功能！

2021，感谢各位一直以来的交流与支持！

## Stellarium

Qt 5.15的发布可以说是天降神兵，自带的CMake对Qt
安卓的构建支持很完美。再经过0.18.0发布以来野生大神对Stellarium做了安卓的代码匹配以及本人的辛勤修bug，移植版已经能很好的工作了。

![](https://pic3.zhimg.com/v2-d8df59e20af6ec61ba8fde3be059dedc_720w.png?source=d16d100b)

相比于电脑版，还增加了Stellarium mobile带有的传感器功能。

下载页面：[Release Stellarium Android
LTS](https://github.com/silas1037/stellarium/releases/tag/v0.20.4)

文件链接： [Stellarium
apk](https://github.com/silas1037/stellarium/releases/download/v0.20.4/android-
build-debug.apk)

如果你不会下载，把apk链接贴到 [这里](https://d.serctl.com/) 下载

反馈：评论区或者[issues](https://github.com/silas1037/stellarium/issues)

  

## 说明与考古

1.为什么使用CMake？ 我也试过使用独立编写的QMake构建，但是插件产生了很多bug。而CMake是原生的。另外，QT公司已经准备放弃qmake了。

  

2.本文也会发布到这里：[Stellarium手机移植版(电脑版移植到安卓手机，更新到0.20.4) - 书刊软件多媒体 -
牧夫天文论坛（中国最早的天文论坛，致力于天文和望远镜的科普交流平台） - Powered by
Discuz!](http://bbs.imufu.cn/forum.php?mod=viewthread&tid=799922&page=1&extra=#pid4970895)

  

3.Stellarium官方项目为什么不支持Android？

曾经风靡于各大应用商店的Stellarium mobile是基于PC 0.12制作的，不过由于项目的转手以及创始人的一些私人目的，PC和手机版就分道扬镳了。

下面是一些历史——

> 付费的Stellarium Mobile安卓和iOS端是由Noctua Software开发的，这家公司是由Fabien
> Chereau创建的，他和他的兄弟曾经是Stellarium的主要开发者之一(对这个家伙打着GNU旗号，别的作者略为et
> al表示愤慨)。正如天吧苯哥和其他塞班手机用户经历的那样，这个程序原本为诺基亚手机设计。官方在这个维基中讨论的是打算中的官方移植版，尽可能有较少的出入和较高的还原度。

开源是一门生意。虽然俩创始人多多少少和开源有过瓜葛，不过还是很感谢其给开源做的贡献。

项目分开了，Stellarium官方网站也就早早删除了安卓构建指南的网页，并且不欢迎在论坛讨论noctuasoft的产品 Stellarium
mobile的问题。

现在俩创始人主导Stellarium web项目和Stellarium mobile
plus项目。不过代码是独立于Stellarium的，而且stellarium+是不开源的。

而Stellarium官方项目则由一个俄罗斯人和一个维也纳人一起维护了，而且还都是用业余时间维护（下班弄弄）。现在Stellarium是以PC端为目标的。只有两个围护者而且缺乏精力缺乏测试人手下，不可能新增一个Android版。

  

4.支持iOS吗？

不支持。手机基本都是安卓和iOS俩大阵营。虽然我也有两部iOS设备，但是iOS的生态还是太封闭垄断了，我构建完Stellarium mobile for
iOS后就没考虑PC版移植了。而且代码适配也有很大问题。

发布于 2021-01-01 23:32:54 编辑于 2021-01-02 00:20:19

