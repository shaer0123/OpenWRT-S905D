# OpenWRT-S905D

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/Aibx/OpenWRT-S905D/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/Aibx/OpenWRT-S905D.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/Aibx/OpenWRT-S905D.svg?style=flat-square&label=Forks&logo=github)

## 斐讯N1 Openwrt自动编译

> 自动编译固件可能存在各种问题，如发现请前往各自软件仓库处询问并等待更新或下载旧版进行降级操作

> 默认网关：192.168.6.1 默认密码：password

> 当前内核：5.4.188|5.10.111|5.15.38|5.17.6

[![GitHub Action (latest by date)](https://img.shields.io/github/workflow/status/Aibx/OpenWRT-S905D/Build%20OpenWRT%20for%20N1?style=for-the-badge&logo=appveyor&label=Build%20Status)](https://github.com/Aibx/OpenWRT-S905D/actions)
[![GitHub Release (latest by date)](https://img.shields.io/github/v/release/Aibx/OpenWRT-S905D?style=for-the-badge&label=Download)](https://github.com/Aibx/OpenWRT-S905D/releases/latest)
- 本项目为斐讯N1固件自动编译打包脚本仓库，每日0:30 UTC(北京时间8:30)和12:30 UTC(北京时间20:30)自动编译，预计4小时完成编译工作
- 内含精选Vssr、SSRPlus、Passwall、京东签到、Clash、Adguard、去广告、迅雷快鸟、网易UU等绝大多数常用插件，包含仓库内基本全部的主题，每日跟随仓库软件编译
- 如果最新版本不含img等文件即编译失败，请前往[Releases](https://github.com/Aibx/OpenWRT-S905D/releases)或[Actions](https://github.com/Aibx/OpenWRT-S905D/actions?query=workflow%3A%22Build+OpenWrt%22)寻找旧版
- Releases仅保留最新14份编译内容,Actions则保留30天内全部的编译内容,WeTransfer下载链接有效时长为7天，Cowtransfer已改为1天

> 如需IPK文件请前往[Actions](https://github.com/Aibx/OpenWRT-S905D/actions?query=workflow%3A%22Build+OpenWrt%22)内下载文件名含"OpenWrt_bin"的文件

## 版本选择
- 带有+的内核版本为5.10+，内核较新，含有新特性，但相对可能更加不稳定
- 带有+o的为5.4+内核，内核更为稳定，但缺少新特性

## 更新记录

- V1.0  
去除argon重复主题，保障编译成功  
- V1.1  
因netgearv2主题手机页面存在错误，退回netgearV1主题  
- V1.2  
修复上游软件包变更导致的编译错误问题,自动删除无用Action  
- V1.3  
修复上游编译环境导致的错误，去除VSSR-PLUS，改为VSSR  
- V1.4  
变更编译触发方式为软件仓库更新，修复编译流程中Workflow相关仓库丢失问题  
- V1.5  
应用过滤因上游变动导致编译失误，已临时去除(现已修复，重新加回)  
- V1.6  
Passwall全家桶回归  

## 联动仓库
- [OpenWRT-Packages](https://github.com/Aibx/OpenWRT-Packages)：国内常用OpenWRT软件包集合
- [OpenWRT-R619AC](https://github.com/Aibx/OpenWRT-R619AC)：竞斗云2.0自动编译仓库,内含IPK及最新固件

## 致谢
- [Liuran001](https://github.com/liuran001)：OpenWRT常用软件自动更新脚本作者
- [Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)：GitHub Actions云编译OpenWrt脚本
- [Flippy's OpenWrt](https://github.com/unifreq/openwrt_packit)：Flippy的OpenWRT打包源码
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)：Lean的OpenWRT源码仓库
- [Lienol's OpenWrt](https://github.com/Lienol/openwrt)：Lienol的OpenWRT源码仓库
