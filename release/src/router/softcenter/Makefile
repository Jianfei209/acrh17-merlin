include ../common.mak

all:

install:
	install -d $(INSTALLDIR)/sbin
	install -d $(INSTALLDIR)/usr/sbin
	install -d $(INSTALLDIR)/lib
	install -d $(INSTALLDIR)/usr/bin
	install -d $(INSTALLDIR)/usr/share
	install -d $(INSTALLDIR)/usr/lib
	install -d $(INSTALLDIR)/www/js
	install -d $(INSTALLDIR)/www/res
	install -d $(INSTALLDIR)/www/images/New_ui
	install -d $(INSTALLDIR)/rom/etc/softcenter/bin
	install -d $(INSTALLDIR)/rom/etc/softcenter/res
	install -d $(INSTALLDIR)/rom/etc/softcenter/res/layer
	install -d $(INSTALLDIR)/rom/etc/softcenter/res/layer/mobile
	install -d $(INSTALLDIR)/rom/etc/softcenter/res/layer/mobile/need
	install -d $(INSTALLDIR)/rom/etc/softcenter/res/layer/theme
	install -d $(INSTALLDIR)/rom/etc/softcenter/res/layer/theme/default
	install -d $(INSTALLDIR)/rom/etc/softcenter/webs
	install -d $(INSTALLDIR)/rom/etc/softcenter/perp
	install -d $(INSTALLDIR)/rom/etc/softcenter/scripts
	install -d $(INSTALLDIR)/rom/etc/softcenter/perp/.boot
	install -d $(INSTALLDIR)/rom/etc/softcenter/perp/.control
ifeq ($(BUILD_NAME), $(filter $(BUILD_NAME), GT-AC2900 GT-AC5300))
	install -d $(INSTALLDIR)/rom/etc/softcenter/ROG/res
	install -d $(INSTALLDIR)/rom/etc/softcenter/ROG/webs
endif
# softcenter
	install -m 0755 softcenter/bin/base64_encode $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/jq $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/softcenter.sh $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/softcenter-mount.sh $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/softcenter-net.sh $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/softcenter-wan.sh $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/perpboot $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/perpctl $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/perpd $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/perphup $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/perpls $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/perpok $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/perpstat $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/sissylog $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/tinylog $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/bin/versioncmp $(INSTALLDIR)/rom/etc/softcenter/bin
	install -m 0755 softcenter/res/icon-default.png $(INSTALLDIR)/rom/etc/softcenter/res
	install -m 0755 softcenter/res/upgrade.png $(INSTALLDIR)/rom/etc/softcenter/res
	install -m 0755 softcenter/res/softcenter.js $(INSTALLDIR)/rom/etc/softcenter/res
	install -m 0755 softcenter/res/softcenter.css $(INSTALLDIR)/rom/etc/softcenter/res
	install -m 0755 softcenter/res/proceding.gif $(INSTALLDIR)/rom/etc/softcenter/res
	install -m 0755 softcenter/res/layer/layer.js $(INSTALLDIR)/rom/etc/softcenter/res/layer
	install -m 0755 softcenter/res/layer/mobile/layer.js $(INSTALLDIR)/rom/etc/softcenter/res/layer/mobile
	install -m 0755 softcenter/res/layer/mobile/need/layer.css $(INSTALLDIR)/rom/etc/softcenter/res/layer/mobile/need
	install -m 0755 softcenter/res/layer/theme/default/icon.png $(INSTALLDIR)/rom/etc/softcenter/res/layer/theme/default
	install -m 0755 softcenter/res/layer/theme/default/icon-ext.png $(INSTALLDIR)/rom/etc/softcenter/res/layer/theme/default
	install -m 0755 softcenter/res/layer/theme/default/layer.css $(INSTALLDIR)/rom/etc/softcenter/res/layer/theme/default
	install -m 0755 softcenter/res/layer/theme/default/loading-0.gif $(INSTALLDIR)/rom/etc/softcenter/res/layer/theme/default
	install -m 0755 softcenter/res/layer/theme/default/loading-1.gif $(INSTALLDIR)/rom/etc/softcenter/res/layer/theme/default
	install -m 0755 softcenter/res/layer/theme/default/loading-2.gif $(INSTALLDIR)/rom/etc/softcenter/res/layer/theme/default
	install -m 0755 softcenter/webs/Main_Soft_center.asp $(INSTALLDIR)/rom/etc/softcenter/webs
	install -m 0755 softcenter/webs/Main_Soft_setting.asp $(INSTALLDIR)/rom/etc/softcenter/webs
	install -m 0755 softcenter/perp/perp.sh $(INSTALLDIR)/rom/etc/softcenter/perp
	install -m 0755 softcenter/perp/.boot/rc.log $(INSTALLDIR)/rom/etc/softcenter/perp/.boot
	install -m 0755 softcenter/perp/.boot/rc.perp $(INSTALLDIR)/rom/etc/softcenter/perp/.boot
	install -m 0755 softcenter/perp/.control/perpd.pid $(INSTALLDIR)/rom/etc/softcenter/perp/.control
	install -m 0755 softcenter/scripts/base.sh $(INSTALLDIR)/rom/etc/softcenter/scripts
	install -m 0755 softcenter/scripts/ks_app_install.sh $(INSTALLDIR)/rom/etc/softcenter/scripts
	install -m 0755 softcenter/scripts/ks_tar_intall.sh $(INSTALLDIR)/rom/etc/softcenter/scripts
	#install -m 0755 softcenter/scripts/pluginbase.sh $(INSTALLDIR)/rom/etc/softcenter/scripts
ifeq ($(BUILD_NAME), $(filter $(BUILD_NAME), GT-AC2900 GT-AC5300))
	install -m 0755 softcenter/ROG/res/softcenter.css $(INSTALLDIR)/rom/etc/softcenter/ROG/res
	install -m 0755 softcenter/ROG/webs/Main_Soft_center.asp $(INSTALLDIR)/rom/etc/softcenter/ROG/webs
	install -m 0755 softcenter/ROG/webs/Main_Soft_setting.asp $(INSTALLDIR)/rom/etc/softcenter/ROG/webs
endif
	install -m 0755 jffsinit.sh $(INSTALLDIR)/usr/sbin
	install -m 0755 plugin.sh $(INSTALLDIR)/usr/sbin
	install -m 0755 helper.sh $(INSTALLDIR)/usr/sbin
	install -m 0755 i18n.js $(INSTALLDIR)/www/js
	install -m 0755 scCN.json $(INSTALLDIR)/www/res
	install -m 0755 scEN.json $(INSTALLDIR)/www/res
	install -m 0755 scTW.json $(INSTALLDIR)/www/res
	install -m 0755 Softcenter.asp $(INSTALLDIR)/www
	install -m 0755 Softcenter_mount.asp $(INSTALLDIR)/www
	install -m 0755 tools.png $(INSTALLDIR)/www/images/New_ui

clean:
