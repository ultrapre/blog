# 修正Stellarium的NGC/IC目录

修正完的数据使用方法：

1.将下面的catalog.dat放到C:\Program
Files\Stellarium\nebulae\default。Stellarium的版本一定要是对应下面的版本号。

_[0.20.2](https://github.com/ultrapre/Stellarium_DSO_catalog/raw/master/0.20.2/catalog.dat)_

_[0.20.1](https://github.com/ultrapre/Stellarium_DSO_catalog/raw/master/0.20.1/catalog.dat)_

2.打开Stellarium即可。

  

* * *

  

## 利用Dr. Wolfgang Steinicke的数据对Stellarium的NGCIC目录数据进行修正

1.拿到数据

catalog 文本源
_<https://github.com/Stellarium/stellarium/blob/master/nebulae/default/catalog.txt>_

Dr. Wolfgang Steinicke的数据

 _<http://www.klima-luft.de/steinicke/index_e.htm>_

2..处理Bug

①重复ID：例如NGC3626=NGC3632，则剔除其中一个。在识别ID表里也如此剔除重复ID。

②不可识别类型：对EN+OCL这种需要变换成C+N，GxyP则是PoG。

③NI的数据项只能是int。这样有很多带扩展符的目标无法识别。

3.处理思路：

①修正绑定错误。NGC是先前目录，被PGC的ID进行绑定。而PGC、ESO等的数据是机器数据无需修正，因此只要绑定到对的ID上即可。Steinicke的数据里没有绑定Mel、Cr目录，需要自己找。最终完成一个识别ID表。

②遍历完已有列表发现还有没有绑定的目标，构造新行。

③Stellarium只保留一对NI重复位。对于两个重复IC重定向到NGC，则需要保留一个IC。

④修正RA、Dec、Vmag等等。

⑤写入未使用数据列默认格式，例如99、0。

⑥注意Excel的自动格式bug，特别是ESO编号。选用文本格式即可。

发布于 2020-08-29 00:57:53

