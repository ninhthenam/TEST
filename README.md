![GitHub Repo stars](https://img.shields.io/github/stars/ninhthenam/TEST?color=Blue&label=Stars&style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/ninhthenam/TEST?color=Blue&label=Fork&style=for-the-badge)
![GitHub](https://img.shields.io/github/license/ninhthenam/TEST?color=Blue&style=for-the-badge)


第二部分
======================

Actions-OpenWrt — 多设备固件自动云编译 [![](https://img.shields.io/badge/-云编译固件-green.svg)](#云编译固件-)
======================

-- 支持的设备平台以及固件下载地址 [![](https://img.shields.io/badge/-设备及固件列表下载-lightgrey.svg)](#设备及固件列表下载-)
-------------

|    序号   |     平台+设备名称     |   编译状态+下载链接 |  
| :-----------------: | :-------------: |:-----------------: | 
| 1 |   [![](https://img.shields.io/badge/OpenWrt-x86%E5%A4%9A%E6%8B%A8%E6%9E%81%E7%AE%80%E7%89%88-lightgrey.svg)](https://github.com/MrH723/Actions-OpenWrt/actions?query=workflow%3A%22x86%E5%A4%9A%E6%8B%A8%E6%9E%81%E7%AE%80+OpenWrt%22)    | [![x86full OpenWrt](https://github.com/MrH723/Actions-OpenWrt/actions/workflows/x86full.yml/badge.svg)](https://github.com/MrH723/Actions-OpenWrt/actions/workflows/x86full.yml) |
| 2 |   [![](https://img.shields.io/badge/OpenWrt-x86%E6%97%81%E8%B7%AF%E7%94%B1%E6%9E%81%E7%AE%80%E7%89%88-yellowgreen.svg)](https://github.com/MrH723/Actions-OpenWrt/actions?query=workflow%3A%22x86%E6%97%81%E8%B7%AF%E7%94%B1%E6%9E%81%E7%AE%80+OpenWrt%22)    | [![x86simple OpenWrt](https://github.com/MrH723/Actions-OpenWrt/actions/workflows/x86simple.yml/badge.svg)](https://github.com/MrH723/Actions-OpenWrt/actions/workflows/x86simple.yml) |
| 3 |   [![](https://img.shields.io/badge/OpenWrt-%E5%B0%8F%E5%A8%B1%20C5-lightgrey.svg)](https://github.com/MrH723/Actions-OpenWrt/actions?query=workflow%3A%22Build+XiaoYu+XY-C5+OpenWrt%22)    | [![Build XiaoYu XY-C5 OpenWrt](https://github.com/MrH723/Actions-OpenWrt/workflows/Build%20XiaoYu%20XY-C5%20OpenWrt/badge.svg)](https://github.com/MrH723/Actions-OpenWrt/actions?query=workflow%3A%22Build+XiaoYu+XY-C5+OpenWrt%22) |
| 4 |   [![](https://img.shields.io/badge/OpenWrt-%E6%A0%91%E8%8E%93%E6%B4%BE%203B%2F3B%2B-yellowgreen.svg)](https://github.com/MrH723/Actions-OpenWrt/actions?query=workflow%3A%22Build+RaspBerryPi3+OpenWrt%22)    | [![Build RaspBerryPi3 OpenWrt](https://github.com/MrH723/Actions-OpenWrt/workflows/Build%20RaspBerryPi3%20OpenWrt/badge.svg)](https://github.com/MrH723/Actions-OpenWrt/actions?query=workflow%3A%22Build+RaspBerryPi3+OpenWrt%22) |

-- 最近更新 [![](https://img.shields.io/badge/-最近更新-lightgrey.svg)](#最近更新-)
-------------
- 更新 P3TERX 大大的编译源码[![](https://img.shields.io/badge/P3TERX-源码-orange.svg)](https://github.com/P3TERX/Actions-OpenWrt)，解决编译提示 set-env 即将被禁用
- 添加新设备 Netgear WNDR 3800 固件的编译
- 添加新设备 Linksys WRT1900 固件的编译
- 添加新设备 友华 WR1200JS 固件的编译
- 添加新设备 NANO-PI R4S 固件的编译
- 添加新设备 小米 AX3600 固件的编译
- 
赞助 [![](https://img.shields.io/badge/-赞助项目-green.svg)](#赞助项目-)
======================
- 您要是觉得好用不错的话，不妨考虑赞助一下本项目。

<img src="https://github.com/MrH723/Actions-OpenWrt/blob/main/img/alipay.jpg?raw=true" width="160" height="180" />

我用过的机场 [![](https://img.shields.io/badge/-机场推荐-green.svg)](#机场推荐-)
======================
- iplc.vip, 最好的机场，没有之一，全IPLC节点，全1倍率，无倍率套路，用不完的剩余流量还可以折现，价格稍高，但绝对物超所值！

[iplc.vip]  [![](https://img.shields.io/badge/全IPLC节点机场-iplc.vip-brightgreen.svg)](https://portal.iplc-j.pw/aff.php?aff=1228)

<details>
<summary>IPLC.vip 节点测速</summary>
<img src="https://github.com/MrH723/Actions-OpenWrt/blob/main/img/speed.png?raw=true" width="890" hight="1080">
   
   *测试结果来自bigdongdong [![](https://img.shields.io/badge/bigdongdong-Github-orange.svg)](https://github.com/bigdongdongCLUB)
</details>


- 心阶，入门级别机场，也是我第一个使用的机场，性价比高，有时会挂。

[心阶]  [![](https://img.shields.io/badge/心阶-xinjiecloud-brightgreen.svg)](https://www.xinjiecloud.vip/auth/register?code=e9yu)

- 西部世界，不少的trojan节点，但是速度一般。有时会挂。想要使用trojan协议的朋友可以酌情斟酌购买

[西部世界]  [![](https://img.shields.io/badge/西部世界-westworldss-brightgreen.svg)](https://xbnet.site/i/iv201020/KKPgMHE)

鸣谢 [![](https://img.shields.io/badge/-鸣谢-green.svg)](#鸣谢-)
======================
 
[P3TERX 的 Action 源码] [![](https://img.shields.io/badge/P3TERX-源码-orange.svg)](https://github.com/P3TERX/Actions-OpenWrt)

[Lean 的 OpenWrt 源码] [![](https://img.shields.io/badge/Lean-源码-orange.svg)](https://github.com/coolsnowwolf/lede)

特别鸣谢
======================
[Lienol] [![](https://img.shields.io/badge/Lienol-%E6%BA%90%E7%A0%81-orange.svg)](https://github.com/Lienol)

[Kenzok8] [![](https://img.shields.io/badge/Kenzok8-%E6%BA%90%E7%A0%81-orange.svg)](https://github.com/kenzok8)


免责声明 [![](https://img.shields.io/badge/-免责声明-green.svg)](#免责声明-)
======================
***- 由于本人小白，有可能使用到了大神的代码，没有放进鸣谢名单里的，请联系添加，再次感谢各位大神的贡献***

***- 请务必遵从‘不涉及政治，不涉及宗教，不涉及黄赌毒’的三不原则***


