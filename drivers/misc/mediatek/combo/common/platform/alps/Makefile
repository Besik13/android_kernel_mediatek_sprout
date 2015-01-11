MTK_PLATFORM := $(subst ",,$(CONFIG_MTK_PLATFORM))
ARCH_MTK_PROJECT := $(subst ",,$(CONFIG_ARCH_MTK_PROJECT))

ccflags-y += -I$(srctree)/arch/arm/mach-$(MTK_PLATFORM)/$(ARCH_MTK_PROJECT)/dct/dct 
ccflags-y += -I$(src)/../../linux/include \
						 -I$(src)/../../core/include \
						 -I$(src)/../../include \
						 -I$(src)/ \
						 -I$(src)/../../../../common_detect/$(MTK_PLATFORM)



ifeq ($(CONFIG_MTK_COMBO),y)
PLAT := alps
obj-y	+= wmt_plat_$(PLAT).o
obj-y	+= wmt_plat_stub.o
obj-y	+= mtk_wcn_cmb_hw.o


endif