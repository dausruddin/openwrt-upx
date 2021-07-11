# openwrt-upx

1. Go to openwrt base folder
2. `git clone https://github.com/dausruddin/openwrt-upx tools/upx`
3. Edit `tools/Makefile` and revert [this change](https://github.com/openwrt/openwrt/commit/0685f2a66cbb4d39417f168cfb37ae6fa7dbf6cb#diff-e327741dae7d1efd73c66ab134d50ac2c56187d814c443bb55464272b8b44113). Simple add the missing line.



