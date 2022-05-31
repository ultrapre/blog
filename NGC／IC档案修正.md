# NGC/IC档案修正

修复完的Stellarium深空天体数据：

[link](https://gitee.com/apollo2036/public/raw/master/Stellarium%E4%BF%AE%E5%A4%8D%E7%89%88DSO%E6%95%B0%E6%8D%AE%5BSilas%5D.rar)

解压到Stellarium安装目录下 nebulae\default中即可（注意要重命名原文件以备份）。

* * *

  

手头上有一本NGCIC档案大全，有SIMBAD数据库，还有一份Historic表格

NGCIC天体的问题是这样：一旦关联上了PGC这些表格，就一定会有确定的类型。

这是因为NGCIC大多数是肉眼望远镜搜索和照相发现的。除了方位指示可能出现错误之外，肉眼对暗弱天体的探测能力可能会受到干扰，从而导致大量的后来使用卫星无法验证的不存在的天体。另外，照相板也会出现缺陷，导致不存在天体的产生。在NGCIC天体表时代，像Dunlop那样的大量虚假填表最后获得爵位的情况已经少了很多了。NGCIC天体里面大量的恒星物体的存在也是一大缺陷。

  

对于那些争议不休或者主流数据库都无法完全修正的情况，可以参考比对出没有引用的天体

Stellarium引用的是SIMBAD数据库

在这里我把LMC、SMC里面的天体类型冲突忽略了，因为像GC和OC这样明显的区分在银河系里面是可以做到的，然而在LMC这样的年轻星系里面出现了大量很难验证的星团类型。

  

其中Stellarium没有类型显示的：1234个（400个NGC，剩余为IC）

其中，282个SIMBAD里面有类型。（我称为C类）

剩余952个里面在SIMBAD中不存在。

为了方便，我会分为B类（Historic表格显示为恒星、彗星或者不存在）和A类（剩余）

经过手动修正，查阅文档和historic清单里面差别非常大的天体（警告）

download:

[xlsx](https://gitee.com/apollo2036/public/raw/master/0.3%E5%89%A9%E4%BD%99%E6%89%80%E6%9C%89%E7%B1%BB%E5%9E%8B%E5%86%B2%E7%AA%81%E5%A4%A9%E4%BD%93.xlsx)

在表格里面handle_type是最终修正的类型，也就是最终得出的正确结果，而第三列TYPE是historic里面的类型。

* * *

  

  

NGCIC handle_type TYPE FALSE

NGC421 NonEx Gx FALSE W

NGC1671 NonEx Gx FALSE W

NGC3176 NonEx Gx FALSE W

NGC3386 Gx FALSE W

NGC3472 NonEx Gx FALSE W

NGC4042 Gx FALSE W

IC337 NonEx Gx FALSE W

IC408 NonEx Gx FALSE W

IC554 NonEx Gx FALSE W

IC1493 * Gx FALSE W

IC2948 Nb FALSE W

IC3601 NonEx Gx FALSE W

IC3657 Gx * FALSE W

IC4339 * Gx FALSE W

* * *

  

3386：椭圆星系（确证）PGC 32284

4042：紧凑星系 （类型C）

I1493：螺旋

I2948：发射星云 ESO 94-SC5

I3657：恒星 *

I4339：螺旋 PGC 49366

发布于 2020-03-09 18:45:22 编辑于 2021-10-29 16:42:39

