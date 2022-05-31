# 开启Stellarium最强大的功能：数字化巡天

本文仅限电脑版Stellarium。

标准版Stellarium里面的贴图是一张一张贴上去的，放大看有比较明显的边框。

![](https://pic1.zhimg.com/v2-e63e07fb3262a81be08ea1a462618812_720w.png?source=d16d100b)

虽然很多深空天体拍的很好看，但是！天上那么多星系，那么多深空，会有一天贴的完吗？

全凭项目维护人员和广大爱好者的辛勤劳作啊，手动
[@排排](http://www.zhihu.com/people/9c42e5f9f8fb47bf127d6adcb31fa302)

  

你是否苦于电脑版Stellarium的糟糕贴图？如果是，那就请打开数字巡天化按钮！

简单来说，TOAST数字化巡天就是拍摄全天的红蓝图像并且拼成一个全天球图像。

  

![](https://pic1.zhimg.com/v2-0f4ff020f8e7c70a4aca51da9c84400a_720w.png?source=d16d100b)![](https://pic3.zhimg.com/v2-99f42ba3c969fffd7936e74874123d1d_720w.png?source=d16d100b)

  

不要苛责为什么一块一块的，因为确实是一块一块拍摄的。我们想要的是天然的深空图像！

比如伯比奇链，巡天模式就能让你看到旁边很多没有贴图的星系

![](https://pica.zhimg.com/v2-a54078747f7849a1f76581983ed0a490_720w.png?source=d16d100b)

  

![](https://pic2.zhimg.com/v2-b08baa174fadce19ea91d8209187a0c0_720w.png?source=d16d100b)

巡天模式的优点就是各种星系没有贴图的一样有显示！

缺点嘛，就主要是行星状星云这块了。还有缺乏自行现象比如巴纳德星这种自行很快的恒星。。

![](https://pic3.zhimg.com/v2-db556256f9eb1dd4c5aa9e4bc00c7b29_720w.png?source=d16d100b)

  

![](https://pic1.zhimg.com/v2-5c95521881906f11e807e1d532b49246_720w.png?source=d16d100b)

  

接下来就是最重要的问题了，很多人表示，怎么我打开巡天按钮半天都没有出现个啥？

因为服务器不在这边啊。如果是在国外正常网络都是秒连秒开的。

## 解决方法：

打开下面的网址，建议吧0-10lvl下下来，因为lvl11和lvl10差不多，lvl10已经满足大部分要求了，而且lvl11相对太大又慢，所以lvl11不用下。

    
    
    file                                               date                             size
    lvl0-6.tar.gz                                      26-Jan-2017 14:14           136748118
    lvl7.tar.gz                                        26-Jan-2017 14:24           398081115
    lvl8.tar.gz                                        26-Jan-2017 15:02          1534141524
    lvl9.tar.gz                                        26-Jan-2017 17:42          5593660242
    lvl10.tar.gz                                       27-Jan-2017 13:28         18013857194
    lvl11.tar.gz                                       30-Jan-2017 05:22         77930924596
    

<https://dss.stellarium.org/offline/>

解压到某个盘比如：

![](https://pic1.zhimg.com/v2-5b308a560cc55119fa3031371a315c41_720w.png?source=d16d100b)

  
打开"C:\Users\username\AppData\Roaming\Stellarium\config.ini"

找到[astro]项，添加以下

    
    
    toast_survey_directory =StelDSS
    toast_survey_host=H:/
    toast_survey_levels=10

重启Stellarium即可。

  

最后附一些图片吧。

![](https://pic3.zhimg.com/v2-ab21b2710158a52dc597e6d1169fedbb_720w.png?source=d16d100b)

  

![](https://pic2.zhimg.com/v2-ff8be3523d6aecb216ec75dbb6a26770_720w.png?source=d16d100b)![](https://pic3.zhimg.com/v2-a87b9d272ae1ea579a10f2af190b84a8_720w.png?source=d16d100b)![](https://pic1.zhimg.com/v2-25fee8fae9e0667b3eb99a06d12687e8_720w.png?source=d16d100b)![](https://pic1.zhimg.com/v2-9382b0f1fab06ddd0caabc9858bbbfbe_720w.png?source=d16d100b)

发布于 2020-04-28 22:23:33

