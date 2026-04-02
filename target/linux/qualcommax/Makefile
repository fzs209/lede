include $(TOPDIR)/rules.mk

ARCH:=aarch64
BOARD:=qualcommax
BOARDNAME:=Qualcomm Atheros 802.11ax WiSoC-s
FEATURES:=squashfs ramdisk fpu nand rtc emmc
KERNELNAME:=Image dtbs
CPU_TYPE:=cortex-a53
SUBTARGETS:=ipq50xx ipq60xx ipq807x

KERNEL_PATCHVER:=6.12
KERNEL_TESTING_PATCHVER:=6.6

include $(INCLUDE_DIR)/target.mk
DEFAULT_PACKAGES += \
	kmod-leds-gpio kmod-gpio-button-hotplug \
	kmod-qca-nss-dp kmod-qca-nss-drv kmod-qca-ssdk \
	kmod-qca-nss-ecm kmod-qca-nss-drv-bridge-mgr \
	kmod-qca-nss-drv-vlan kmod-qca-nss-drv-pppoe \
	uboot-envtools \
	e2fsprogs f2fsck mkf2fs losetup automount autocore-arm \
	kmod-qca-nss-dp kmod-nss-ifb \
	kmod-qca-nss-drv kmod-qca-nss-ecm \
	kmod-qca-nss-drv-bridge-mgr \
	kmod-qca-nss-drv-eogremgr \
	kmod-qca-nss-drv-gre \
	kmod-qca-nss-drv-igs \
	kmod-qca-nss-drv-l2tpv2 \
	kmod-qca-nss-drv-lag-mgr \
	kmod-qca-nss-drv-map-t \
	kmod-qca-nss-drv-match \
	kmod-qca-nss-drv-mirror \
	kmod-qca-nss-drv-netlink \
	kmod-qca-nss-drv-pppoe \
	kmod-qca-nss-drv-pptp \
	kmod-qca-nss-drv-qdisc \
	kmod-qca-nss-drv-tun6rd \
	kmod-qca-nss-drv-tunipip6 \
	kmod-qca-nss-drv-vlan-mgr \
	kmod-qca-nss-drv-vxlanmgr

$(eval $(call BuildTarget))
