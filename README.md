# 兆能ZN-M2 openwrt usb 无wifi 协同5g随身wifi f50 实现网络高可用
自用款固件 为配合f50实现网络高可用 改造 想用passwall 推荐内存512M以上 内核版本 4.4.60

根据需求，在原作者的基础上增加了usb支持(未测试，若用于网络共享存储，谨慎使用；仅为了支持usb网络共享，f50测试识别，默认为eth4，MWAN 配置权重实现高可用)

感谢大佬 sdf8057 的贡献 https://github.com/sdf8057/ipq6000

感谢原作者相关贡献 原作者地址 https://github.com/openwrt-fork/zn-m2-openwrt-build/releases

控制台地址`192.168.11.1` 默认密码`password`，可在 scripts/zn-m2/diy-part3.sh 进行修改

uboot刷机用`openwrt-ipq60xx-generic-zn_m2-squashfs-nand-factory.ubi`

openwrt系统升级用`openwrt-ipq60xx-generic-zn_m2-squashfs-nand-factory.ubi`

高可用简单配置参考：https://www.right.com.cn/forum/thread-4058779-1-1.html
