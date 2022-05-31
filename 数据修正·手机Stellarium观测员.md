# 数据修正·手机Stellarium观测员

手机Stellarium里的深空天体数据错误很多，以及精度很差。

另外系统很low，只绑定了ngcic天体，像M45这种强行绑定了一个错误的NGC编号。这样就也不能显示煤袋星云以及各种没有NGC编号的Cr天体等等了。

我就自己整了一个新的版本。

  

download：

小体积版本：
[观测员lite](https://gitee.com/apollo2036/public/raw/master/stellarium%E8%A7%82%E6%B5%8B%E5%91%98%E4%B8%93%E7%94%A8lite.apk)

mag13.5等：blank

  

 **数据来源：** 目前最正确的NGCIC数据

http://www.klima-luft.de/steinicke/ngcic/ngcic_e.htm

经过本人整理之后生成了新的NGCIC目录数据，涵盖了M+C+Mel+Cr+NGC+IC+各类小众疏散星团+碳星+星协。

![](https://pic1.zhimg.com/v2-257e57579650b0a67be8ede9156f517d_720w.png?source=d16d100b)![](https://pic2.zhimg.com/v2-917ee54cdf1d90c11ed4fe58d08ba504_720w.png?source=d16d100b)

相对以前的版本，修复了所有DSO的时角+赤纬+星等+尺寸+类型，新增了2574个NGC/IC，关联了Mel/Cr（可直接搜索），去除了重复编号的DSO。

我还新增了192个没有NGCIC编号的小众疏散星团， 64个碳星，N个星协。既然只能靠NGCIC索引的，那只能使用IC剩余的空白编号来对应。使用的编号范围
IC9000 - ... 。

  

对碳星的说明：

例如R2-1B是指推荐2寸口径观测，越大星等越暗，在2寸观测目录中小编号排第1，B是评级，说明如下。

![](https://pica.zhimg.com/v2-c9e8d0c20a150dd047b6cf139953c191_720w.png?source=d16d100b)

  

示例如下（来自刀锋兄整理的极红星星表）：

  

![](https://pica.zhimg.com/v2-6a2e67aaebfed3de08596ff2763965e2_720w.png?source=d16d100b)

  

极红星编号如下：

    
    
    极红星编号 恒星编号
    R2-1B	hip27989
    R2-2B	hip107259
    R2-3B	hip25945
    R3-1A	hip52009
    R3-2B	hip62223
    R3-3	hip117245
    R3-4S	hip31579
    R3-5S	hip51821
    R3-6B	hip90913
    R3-7	hip21479
    R3-8	hip14930
    R3-9S	hip6759
    R3-10	hip74582
    R3-11A	hip95154
    R3-12	hip105334
    R3-13A	hip52577
    R5-1S	hip23680
    R5-2A	hip107129
    R5-3A	hip30564
    R5-4	hip33189
    R5-5A	hip63152
    R5-6	hip105678
    R5-7A	hip84332
    R5-8	hip67261
    R5-9S	HD108105
    R5-10S	hip48327
    R5-11	hip43811
    R5-12	hip110478
    R5-13	hip86728
    R5-14C	hip49950
    R5-15B	hip110504
    R5-16S	hip53085
    R6-1A	hip64778
    R6-2B	hip34413
    R6-3A	hip94940
    R6-4A	hip104719
    R6-5A	hip27181
    R6-6A	hip108603
    R6-7A	hip99
    R6-8A	hip48662
    R6-9S	hip96255
    R6-10A	hip99990
    R6-11S	hip67419
    R8-1S	hip93666
    R8-2S	hip92442
    R8-3A	hip96836
    R8-4S	hip90883
    R8-5SS	hip23203
    R8-6	hip26958
    R8-7A	hip26032
    R8-8A	hip85617
    R8-9A	hip91774
    R10-1A	hip98190
    R10-2C	hip62126
    R10-3A	hd161849
    R10-4S	hd160205
    R10-5	hip100219
    R10-6B	hd39909
    R12-1A	hip95777
    R12-2S	sao207911
    R12-3A	hd164264
    R12-4C	hip102202
    R12-5A	hip99310
    R12-6B	hip31349

源码：

[csdn](https://blog.csdn.net/wsl985/article/details/105492099)

发布于 2020-04-13 16:58:58 编辑于 2020-04-13 16:59:44

