
<h3 align="center"><samp> Hi, I'Namia-A👋 </samp></h4> 
<h1 align="center">Fully automatic online compilation💻</h1>
<p align="center"><img align="center"  width="182" src="https://komarev.com/ghpvc/?username=DeveloperMDCM&color=green&label=DeveloperMDCM%20profile%20views"/></p> 
<p align="center"><a href=#><img src="contributions.svg"></a></p> 
<div align="center">

### 基于Actions-OpenWrt自动化在线编译脚本
- 默认IP地址：`192.168.5.1`
- 账户：`root`   密码：`空`

#### 鸣谢及源码来源：🎉🎉🎉
[![immortalwrt](https://img.shields.io/badge/immortalwrt-OpenWrt-orange.svg?style=flat&logo=appveyor)](https://github.com/immortalwrt/immortalwrt) 
[![Lean](https://img.shields.io/badge/Lean-OpenWrt-blueviolet.svg?style=flat&logo=appveyor)](https://github.com/coolsnowwolf/lede) 
[![Lienol](https://img.shields.io/badge/Lienol-OpenWrt-blueviolet.svg?style=flat&logo=appveyor)](https://github.com/Lienol/openwrt/tree/employ) 
[![openwrt](https://img.shields.io/badge/Official-OpenWrt-red.svg?style=flat&logo=appveyor)](https://github.com/openwrt/openwrt/tree/master)
[![Xwrt](https://img.shields.io/badge/Xwrt-OpenWrt-orange.svg?style=flat&logo=appveyor)](https://github.com/x-wrt/x-wrt) 
[![281677160](https://img.shields.io/badge/Actions-OpenWrt-orange.svg?style=flat&logo=appveyor)](https://github.com/281677160/bendi) 

#### 💕💕 点击下表中 [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?style=flat&logo=hack-the-box)](https://github.com/Namia-A/OpenWrt-X/releases) 即可跳转到该设备固件下载页面💕💕
| 平台+设备名称 | 固件编译状态 | 配置文件 | 固件下载 |
| :-------------: | :-------------: | :-------------: | :-------------: |
| [![](https://img.shields.io/badge/openwrt-X86_64-32C955.svg?logo=openwrt)](https://github.com/Namia-Q/OpenWrt-X/blob/main/.github/workflows/Lede.yml) | [![](https://github.com/Namia-A/OpenWrt-X/actions/workflows/Lede.yml/badge.svg)](https://github.com/Namia-A/OpenWrt-X/actions/workflows/Lede.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/Namia-A/OpenWrt-X/blob/main/build/Lede/seed/x86_64) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/Namia-A/OpenWrt-X/releases/tag/Update-x86) |
| [![](https://img.shields.io/badge/openwrt-PhotonicatWrt-32C955.svg?logo=openwrt)](https://github.com/Namia-Q/OpenWrt-X/blob/main/.github/workflows/Lede.yml) | [![](https://github.com/Namia-A/OpenWrt-X/actions/workflows/Lede.yml/badge.svg)](https://github.com/Namia-A/OpenWrt-X/actions/workflows/Lede.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/Namia-A/OpenWrt-X/blob/main/build/Lede/seed/photonicatWrt) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/Namia-A/OpenWrt-X/releases/tag/Update-rockchip) |

### 💕💕文化有限正在学习中💕💕
- ================================================================
- [`必看项！！！💕`](https://github.com/Namia-A/OpenWrt-X/blob/main/backups/%E5%B7%B2%E7%BC%96%E8%AF%91%E8%AF%B4%E6%98%8E/txt)
- 
  禁止6.1-6.6内核安装luci-app-netspeedtest!!!!!!!会报错，原因是分支问题，我没有处理，X86_64固件本人尽量用最新master或者23.05分支，用6.1和6.6的内核来结合编译编译出来的都可以使用自行U盘或者PE安装。，主分支就是默认提示的，但是不包括23.05或者22.21.19.18.或者其他......会出现6.6的内核,但是会出现在编译插件安装过程中会莫名缺失你的seed文件里面所标记的设备配置文件，原因是其中个别插件带的依赖和你编译得插件或者其他插件有冲突他会消失。
- Rockchip固件系列，请到Rockchip- [`OpenWrt-X — Rockchip！！！💕`](https://github.com/Namia-Q/OpenWrt-X-RK) 💕!主要对应Rockchip固件编译
- 
             总插件N个，我装插件安装的数量基于x86有【54个】未安装【N个】Rockchip尽力高大全
             特例-不是很推荐xwrt主分支此分支同步的是官方主分支你可以尝试其他xwrt分支！


- 首先需要打开 Openwrt 主页,点击系统-TTYD 命令窗,或者使用```putty```或者```openwrt```后台luci插件在线更新 
- 输入`openwrt`即可进入固件升级菜单                            
- 输入`tools`即可打开工具箱
- 输入`qinglong`即可全自动安装青龙 
- ================================================================

- ================================================================
- 自行云编译固件姿势
- 你会看到不是需要ssh，点打开，最后点击运行程序就可以编译了
- 在运行过程中会出现ssh链接网址点击它就会打开另外一个网址
- 开始 ctrl+c 
- 进ssh选择插件
- [`插件对照表！！！💕`](https://raw.githubusercontent.com/Namia-A/OpenWrt-X/main/backups/%E6%8F%92%E4%BB%B6%E5%AF%B9%E7%85%A7%E8%A1%A8/txt)
``` bash
cd openwrt && make menuconfig
```
- 结束ctrl+d
- REPO_TOKEN密匙制作教程：https://git.io/jm.md
- 云编译需要 [在此](https://github.com/settings/tokens) 创建个```token```,勾选：```repo```, ```workflow```，保存所得的key
- 然后在此仓库```Settings```->```Secrets```中添加个名字为```REPO_TOKEN```的Secret,填入token获得的key

- TG通知```Settings```->```Secrets```中添加个名字为```TELEGRAM_BOT_TOKEN```和```TELEGRAM_CHAT_ID```
- ================================================================
- 
## 自动更新固件用的不朽固件作为示列图片
- ![img.png](backups/实例/img.png)
- ![1.png](backups/实例/1img.png)
- ![2.png](backups/实例/2img.png)
- ![img2.png](backups/实例/3img.png)
- ![img3.png](backups/实例/4img.png)
- ![img2.png](backups/实例/5img.png)

### Friendly sociability
- [![Telegram](https://img.shields.io/badge/-Telegram-D114855?style=flat&logo=Telegraml&logoColor=white)](https://t.me/+LPeqwOcUjk40ZjRl) [![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=GitHub&logoColor=white)](https://github.com/Namia-A) [![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=flat&logo=Gmail&logoColor=white)](mailto:kmy258855@gmail.com)
