# Stellarium 深空特别版1.0（安卓）

apk地址 ：

<https://gitee.com/apollo2036/Stellarium-adv/releases/Pro_V1.0>

  

* * *

## Stellarium Pro（深空天体观测特别版） 新增功能

by喻园

1.修正深空类型等，从7种类型增加到19种类型。

2.自定义深空目录路径。

ngc2000.dat、ngc2000names.dat均可以自己设计放在/sdcard/stellarium/中。

3.修正了NGC/IC的所有数据。

4.增加了bmag、b-v mag、详细类型（比如I2r）、德雷尔描述（详细描述一个天体）

5.增加了1000+明亮的非M/NGC/IC深空，可以支持6位数数量级别的深空数量

6.支持按照梅西耶、NGC、Caldwell显示或不显示目标

7.支持按照星系、疏散星团等深空类型显示或不显示目标

8.支持观测清单，观测记录；可以按照设置显示或不显示已观测或者观测清单中的目标。

  

  

配置说明：

  

在用户存储空间下可以自己修改配置。每次生效必须要关闭应用并且重新开启。

配置文件路径如：“stellarium/config.ini” (全路径/sdcard/stellarium/config.ini)

  

下面可以把等号后的值进行修改，比如真（true）、假（false）和数值等。

  

 **（1）目录筛选**

支持按照梅西耶、NGC、Caldwell显示或不显示目标，优先级：Messier,Caldwell>NGC,IC>Other, 如设置
Messier_show=true但NGC_show=false时同时拥有梅西耶和NGC编号的M8为显示。

  

格式：

 _[nebula_catalog]_

 _Caldwell_show = true_

 _IC_show = true_

 _Messier_show = true_

 _NGC_show = true_

 _Other_show = true_

  

 **（2）数值筛选**

  

在和config.ini同级目录下（/sdcard/stellarium/）新建utf-8格式的Observations.txt（观测记录：已经观测的目标，下次不想看了）和Observing.txt（观测计划：还在观测计划中，下次还想看），要注意名字大小写要相同。

  

里面的文字如下，可以写支持的各种星表名，中间不要留空格，换行隔开。

  

![](https://pic3.zhimg.com/v2-797d968090f9c2a027e7db9ad7851357_720w.jpg?source=d16d100b)

  

  

checked_show=2：仅不显示没有在 **观测计划** 中但是在 **观测记录** 中的目标

checked_show=1：不显示在观测记录中的目标

checked_show=0：全部显示

  

比如Observations.txt包含C86和C91，而Observing.txt包含C91，最终星图里显示C91而不显示C86。

  

limit_mag_show是指显示的最暗星等，星等暗于这个数值的深空天体不显示，默认是99即最大。flag_nomag_show为是否显示没有星等的深空。

  

limit_surfbr_show和flag_nosurfbr_show同理，限制面亮度显示最暗值。

  

limit_size_show和flag_nosize_show同理，限制深空天体尺寸显示。

  

 _[nebula_range]_

 _checked_show = 2_

 _flag_nomag_show = true_

 _flag_nosize_show = true_

 _flag_nosurfbr_show = true_

 _limit_mag_show = 99_

 _limit_size_show = 0_

 _limit_surfbr_show = 99_

  

 **（3）类型筛选**

  

说明如下：

【星系Gxy， 星系团Gxy_Cluster， 星云Nb， 超新星遗迹SNR， 行星状星云PN， 疏散星团OCL， 球状星团GCL，
其他星系的一部分结GxyP， 暗星云DarkNebula， 带星云的星团Cluster_nebula, 星协Ass, 恒星云StarCloud,
恒星Stars, 碳星CarbonStar, 流量积分云IFN， 双星DoubleStar， 变星VariableStar， 不存在NotFound，
重复Dup】

  

 _[nebula_type]_

 _Ass_show = true_

 _CarbonStar_show = true_

 _Cluster_nebula_show = true_

 _DarkNebula_show = true_

 _DoubleStar_show = true_

 _Dup_show = false_

 _GCL_show = true_

 _GxyP_show = true_

 _Gxy_Cluster_show = true_

 _Gxy_show = true_

 _IFN_show = true_

 _Nb_show = true_

 _NotFound_show = false_

 _OCL_show = true_

 _PN_show = true_

 _SNR_show = true_

 _StarCloud_show = true_

 _Stars_show = true_

 _VariableStar_show = true_

发布于 2020-06-11 12:06:32

