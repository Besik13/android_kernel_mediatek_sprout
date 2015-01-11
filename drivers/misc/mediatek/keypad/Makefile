include $(srctree)/drivers/misc/mediatek/Makefile.custom
ifeq ($(CONFIG_ARCH_MT6589), y)
	obj-$(CONFIG_MTK_KEYPAD) := kpd-mt6589.o
	obj-y += mt6589/
else
	obj-$(CONFIG_MTK_KEYPAD) := kpd.o

		ifeq ($(CONFIG_ARCH_MT6572), y)
			obj-y += mt6572/
		endif
		ifeq ($(CONFIG_ARCH_MT6582), y)
			obj-y += mt6582/
		endif

endif
