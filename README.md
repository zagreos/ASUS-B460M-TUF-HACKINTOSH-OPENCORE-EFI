# ASUS-B460M-TUF-HACKINTOSH-OPENCORE-EFI

![OpenCore-version](https://img.shields.io/badge/OpenCore-0.6.4-brightgreen)

## 硬件参数

|     CPU      |                        intel i5 10400                        |
| :----------: | :----------------------------------------------------------: |
|   **内存**   |  **酷兽（CUSO）DDR4 16G 2666频率台式机内存条 16G 2666 * 2**  |
|   **硬盘**   | **铠侠（Kioxia）500GB SSD固态硬盘 NVMe M.2接口 EXCERIA NVMe RC10系列** |
|   **显卡**   |                  **Intel UHD Graphics 630**                  |
|   **电源**   |    **海韵 (SEASONIC)FOCUS GX550 550W电源 80PLUS金牌全模**    |
|   **主板**   |       **华硕（ASUS）TUF GAMING B460M-PLUS重炮手主板**        |
| **显示器1**  |           **AOC 27英寸玄英质感黑 微框 IPS技术屏**            |
| **显示器2**  | **戴尔（DELL） P2419H 23.8英寸IPS显示屏幕办公液晶电脑显示器** |
| **无线网卡** |    **BCM943602CS(双频 1750M + 蓝牙 4.0）PCI-E 无线网卡**     |

## 系统参数

**机型**：iMac19,1 

**OpenCore** 0.6.4

**系统**：MAC OS Catalina 10.15.7

![system](https://github-image-1301846849.cos.ap-guangzhou.myqcloud.com/EFI/image/system.png)

## 可正常工作

- [x] 声卡（板载）/ 网卡（板载）
- [x] 显卡（核显）/ 硬解 4K（HEVC + H.264）
- [x] WiFi（PCI-E 设备） / 蓝牙（PEI-E 载 USB 设备）
- [x] 隔空投送 / 接力 / 随航
- [x] FaceTime / iMessage
- [x] Apple Music / Apple TV Plus

![sidcar](https://github-image-1301846849.cos.ap-guangzhou.myqcloud.com/EFI/image/sidcar.png)

![hevc](https://github-image-1301846849.cos.ap-guangzhou.myqcloud.com/EFI/image/hevc.png)

![wifi && bluetooth](https://github-image-1301846849.cos.ap-guangzhou.myqcloud.com/EFI/image/wifi.png)

![wifi && bluetooth](https://github-image-1301846849.cos.ap-guangzhou.myqcloud.com/EFI/image/wifi2.png)

## 不正常工作

- [ ] HDMI口（可正常显示，可热拔插，但是休眠或者开机的时候无法正常使用，需要带DP口的设备）
- [ ] 原生电源管理(如果外接了HDMI无法正常休眠，还是建议使用DP口的设备)
- [ ] BIOS（开机卡F1，好像是华硕主板的通病，可以通过屏蔽主板CMOS解决，具体请看[RTC综述](https://blog.xjn819.com/post/rtc-issues-related-to-oc.html)）

## 感谢

@[daliansky](https://github.com/daliansky)

@[Xjn's Blog](https://blog.xjn819.com/)

@[独行秀才](https://shuiyunxc.gitee.io/)

@[OpenCore-Desktop-Guide](https://dortania.github.io/OpenCore-Desktop-Guide/)