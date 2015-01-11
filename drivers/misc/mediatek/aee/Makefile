#$(call all-subdir-src-or-makefile)
ifneq ($(CONFIG_MTK_PLATFORM),"mt6589")
obj-$(CONFIG_MTK_AEE_FEATURE)	+= aed/
obj-$(CONFIG_MTK_AEE_FEATURE)	+= common/
obj-$(CONFIG_MTK_AEE_FEATURE)	+= ipanic/
else
obj-y += mt6589/
endif
