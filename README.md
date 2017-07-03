# 智慧运维工作站软件(OM-Site)

## OM-Site软件定义 ##

```
基于工作站组态软件(OM-SiteLab)描绘的组态画面，呈现于项目现场工作站电脑中，并提供用户操作设备、查看运行状态、接受实时报警和交互的一套软件解决方案。
```

该软件运行于 **windows平台(win7/win10 32位/64位兼容)** 下，一般发布版本为绿色版本，可直接解压运行。

需 **与OM-SiteLab配合使用** ，控制服务器端软件需配套使用 CoreEngine/ LogicEngine两个控制引擎软件。


## 概要设计点 ##

主要考虑点：

1. 是否沿用老的设计？否。因为老的设计以桌面版为主，与当前HTML5的各类软件效果差距很大，经过论证本次设计以web为核心。

2. 后台数据库：MySQL，开发经验已有，不需要更换，建议仍保留MySQL方案

3. 组态文件：SQLLite文件，开发经验已有，不需要更换，建议仍保留本方案

4. 兼容性问题，云端软件往往要求支持：IE 10，本设计所使用框架暂时不考虑IE浏览器需求，OM-site的限制chrome测试为主。


## 概要设计产品目标参考图 ## 
![](/assets/设计.png)