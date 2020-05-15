# Lean-luci-app-ssr-plus
来自大雕的SSR+ 大雕删库了，只能在这做个备份
适用于openwrt/lede
使用方法：
1、cd openwrt/package
2、git clone https://github.com/maxlicheng/luci-app-ssr-plus.git
3、回到openwrt目录
4、./scripts/feeds update -a && ./scripts/feeds install -a
5、make menuconfig
   LuCI ---> Applications ---> <*>luci-app-ssr+
   【save】
