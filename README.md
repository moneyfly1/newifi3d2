# Auto build OpenWrt firmware for Newifi D2
固件采用GitHub Actions不定时自动云编译。  
Auto build OpenWrt firmware for Newifi D2 via GitHub Actions
路由器地址： 192.168.5.1 密码password
# 致谢大佬&Thanks

https://github.com/coolsnowwolf/lede  
https://github.com/P3TERX/Actions-OpenWrt/  
https://github.com/Lienol/openwrt-package  
https://github.com/kenzok8/openwrt-packages  
.....

# 最新版下载&Download Latest
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/leopardciaw/D2?style=for-the-badge&label=Download)](https://github.com/leopardciaw/D2/releases/latest)

# 请注意
1.集成的插件只是自己需要用到的，请多多包涵。  
2.源码来自https://github.com/coolsnowwolf/lede， 除了增减插件和主题、修改管理IP外，未做其他修改，有问题请直接到 https://github.com/coolsnowwolf/lede/issues 这里提交issue，提交issues请注意基本的礼仪和格式，翻看之前是否有大佬已提出相关issue。  
3.才疏学浅、时间有限，回答不了任何技术问题哈，只是定时或不定时更新下大雕的源码编译。  
4.若需要上传至releases，需要自行设置并修改GITHUB_TOKEN: ${{ secrets.***_TOKEN }}，当中的***_TOKEN。否则只能在Actions里查看和下载编译的固件。  
