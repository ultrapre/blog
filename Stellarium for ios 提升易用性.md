# Stellarium for ios 提升易用性

ios下载Stellarium可以到AppCake搞定（<https://www.iphonecake.com/app/>）

爱思助手导出ipa，然后自己可以修改资源以提升易用性。

步骤：

后缀增加.zip，然后winrar打开，要增加/替换什么资源就拖进去即可。

然后后缀去掉.zip，变回.ipa。

爱思助手->IPA签名

![](https://pic3.zhimg.com/v2-3467b0b5fd46b9ebc0ed7761be8880b9_720w.png?source=d16d100b)

然后

我的设备-导入安装即可。

  

## 主要增加/替换的资源：

1.增加恒星星等：

默认最高只有9等，对于我们搞观测的怎么够用呢？

defaultStarsConfig.json里面找到更高星等的cat文件，从其他来源复制进去。推荐最高到13.5等。

  

2.深空图片增加

默认只有163张图片。

嘉兴排排完善后有545张图片。

  

3.关闭人眼动态调节

default_config.ini里 use_luminance_adaptation = false

（这个需要同时修改info.plist 里面的版本号：1.29.11）

  

4.增加深空天体数量

修改ngc2000.dat和ngc2000names.dat，具体可以翻翻我之前的博文。

  

5.增加可观测彗星

ssystem_minor.ini里面添加F8、U6等等彗星数据。

  

...

发布于 2020-06-17 12:49:08 编辑于 2020-07-05 16:15:55

