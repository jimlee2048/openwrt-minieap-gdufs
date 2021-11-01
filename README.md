minieap-openwrt-gdufs
=====

基于 [@ysc3839](https://github.com/ysc3839)/**[openwrt-minieap](https://github.com/ysc3839/openwrt-minieap)** 修改

编译方法请参考下方原仓库 README 

建议配合安装 [@ysc3839](https://github.com/ysc3839)/**[luci-proto-minieap](https://github.com/ysc3839/luci-proto-minieap)** ，以便在 Web 管理页面中配置参数。

有问题欢迎提出 Issues。

**仅作为学习EAP， EAPOL协议使用，请勿用于其他用途，造成后果自负。**

以下是原仓库 README 内容：

---
minieap for OpenWrt
=====

## Build

First download [OpenWrt SDK](https://downloads.openwrt.org/) for your device.

```sh
cd /path/to/your/sdk
git clone https://github.com/jimlee2002/openwrt-minieap.git package/minieap
make menuconfig # choose `minieap` in section `Network`
make package/minieap/compile V=s
```
