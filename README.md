ipq6000系列固件分享:  

固件下载请去telegram频道，https://t.me/ipq6000_romshare

0819更新日志：  
1.ssr-plus更新到最新版。  
2.添加了自动重启app，定时重启能提高使用体验，  
3.去掉了turboacc中的bbr加速状态，kernel 4.4不支持bbr加速。  

0824更新日志：  
1.解锁网易云音乐使用go版本，节约内存，  
2.修复turboacc开启dns缓存再关闭之后dns解析不正常的问题，  
3.加入nsscrypto模块，或许对于某些软件的加解密过程有些作用。  

0920更新日志：  
1.插件更新。  
2.最大连接数增加到65535。  

0923更新日志：  
1.同步上游最新更新。  
2.cpu超频到1.8ghz。  

1003更新日志：  
1.优化超频选项，根据跑分结果选定三档频率，1.0-1.4ghz。  
2.优化nss失效状态下的网络性能。  

1014更新日志：  
1.源码还原部分默认设置。  
2.和目ax18固件精简版和完全版双版本更新。  
3.重构云编译脚本仓库，提升可读性。  
4.添加nss状态显示。  

1016更新日志：  
1.更优雅的解决的端口回环设置失效的问题。  
2.简化云编译.config文件，方便二次修改。

1020更新日志：  
1.梳理dnsmasq相关代码，修复bug。  
2.默认关闭“过滤ipv6 dns解析”。  
3.openssl升级到q版本。  

1111更新日志：  
1.cpu频率开放更多挡位，0.8~1.8g。  
2.云编译添加红米ax6支持。

12.01更新日志：  
1.云编译添加了360t7设备支持。  
2.云编译添加了红米ax6000设备支持。  

12.25更新日志  
1.支持opkg在线安装软件。  
2.删除部分不必要改动。  
3.luci package仓库更新。  
