openwrt-minieap-gdufs
=====

**⚠已知问题：在某些区域无法通过认证，详见[issue#1](https://github.com/jimlee2002/minieap-gdufs/issues/1)**

基于 [@ysc3839](https://github.com/ysc3839)/**[openwrt-minieap](https://github.com/ysc3839/openwrt-minieap)** 修改

关于使用方法，请参考[MiniEAP 在 OpenWRT 上的使用](https://github.com/jimlee2002/openwrt-minieap-gdufs/blob/master/docs/how-to-configure-minieap-in-openwrt.md)

关于 GDUFS 校园网的更多详细信息，请参见 [Surf in GDUFS](https://github.com/jimlee2002/openwrt-minieap-gdufs/blob/master/docs/surf-in-gdufs.md)

欢迎 Issues / Pull Request。

**仅作为学习EAP， EAPOL协议使用，请勿用于其他用途，造成后果自负。**

以下修改自原仓库 README 内容：

---
minieap for OpenWrt
=====

## Build

First download [OpenWrt SDK](https://downloads.openwrt.org/) for your device.

```sh
cd /path/to/your/sdk
git clone https://github.com/jimlee2002/openwrt-minieap-gdufs.git package/minieap
make menuconfig # choose `minieap` in section `Network`
make package/minieap/compile V=s
```
