# Copyright 2019 X-WRT <dev@x-wrt.com>
# Copyright 2022-2023 sirpdboy  

include $(TOPDIR)/rules.mk

NAME:=netwizard
PKG_NAME:=luci-app-$(NAME)
PKG_VERSION:=1.8.5
PKG_RELEASE:=20231128

PKG_LICENSE:=GPLv3
PKG_LICENSE_FILES:=LICENSE
PKG_MAINTAINER:=Chen Minqiang <ptpt52@gmail.com>

LUCI_TITLE:=LuCI Support for Wizard
LUCI_DEPENDS:=+luci-compat
LUCI_PKGARCH:=all


define Package/$(PKG_NAME)/conffiles
/etc/config/netwizard
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
