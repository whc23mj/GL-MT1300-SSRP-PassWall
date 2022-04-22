# GL-iNet GL-MT1300 路由器安装科学上网插件
感谢P3TERX的GitHub Actions项目，感谢Lienol和Lean两位大神所提供的插件

基于官方固件版本3.211安装，包含插件 passwall，ssr plus, frpc, nps, unblockneteasemusic等

    空间不够可参考openwrt扩容overlay将 Overlay 空间指向外置存储
    opkg update && opkg install block-mount luci ttyd luci-app-ttyd luci-compat luci-lib-ipkg wget htop

可以同时安装ssrp和passwall
