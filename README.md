# openwrt

[***P3TERX***大佬写的中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## 说明
- 基于***flippy大***的固件打包脚本，适配的机型有：***微加云***、***贝壳云***、***我家云***、***N1***、***S905x3（包括常见的hk1、h96、x96等盒子）***、***章鱼星球***、***s922x（目前支持GT-King、GT-King Pro两款盒子）*** 等！
- releases中的直刷固件分为[***精简版***](https://github.com/hibuddies/openwrt/releases/tag/Z-ARMv8-mini) 和[***高大全版***](https://github.com/hibuddies/openwrt/releases/tag/Z-ARMv8-gdq)，精简版主要适合科学上网为主要需求的用户，高大全版用的是f大的配置文件，+o版是flowoffload加速,+版是sfe加速！
- Docker固件：`docker pull hibuddies/openwrt-aarch64:latest`，精简版：`docker pull hibuddies/openwrt-aarch64-mini:latest`
- 固件默认IP：`192.168.1.1` 默认密码：`password`
- 刷机和升级方法请参考f大这两个帖子：[➦旧帖](https://www.right.com.cn/forum/thread-981406-1-1.html) 和 [➦新帖](https://www.right.com.cn/forum/thread-4055451-1-1.html)
- 精简版固件包含的插件预览：

  ![image](https://github.com/hibuddies/openwrt/blob/main/image/%E7%B2%BE%E7%AE%80%E7%89%88%E5%9B%BA%E4%BB%B6.jpg)

## 声明
- 刷此固件风险自行承担！我只是出于个人爱好学习编译创建的这个项目，固件编译用的上游源码和f大用的都是相同的，编译的配置文件和打包源码都是f大的，我除了加了些主题外没有做任何的修改。所以不要一遇到问题就抱怨我的固件这不行那不行，f大的就没事！因为我的固件是日更f大更新不会这么频繁，这期间上游做了改动导致有些bug谁也说不准，所以再次提醒，刷此固件请三思，本人不承担任何后果和技术支持！

## 感谢

- [flippy大](https://github.com/unifreq/)
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [c-hive/gha-remove-artifacts](https://github.com/c-hive/gha-remove-artifacts)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
