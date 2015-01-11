ifneq ($(CONFIG_ARCH_MT6589), y)
obj-$(CONFIG_MTK_AEE_MRDUMP) += mrdump.o
mrdump-y := mrdump_full.o

obj-$(CONFIG_MTK_AEE_IPANIC) += mrdump_mini.o

ifeq ($(CONFIG_ARCH_MT6582), y)
  obj-y += mt6582/
endif

ifeq ($(CONFIG_ARCH_MT6572), y)
  obj-y += mt6572/
endif
else
  obj-y += mt6589/
endif
