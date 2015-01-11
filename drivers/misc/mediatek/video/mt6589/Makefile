include $(srctree)/drivers/misc/mediatek/Makefile.custom

obj-$(CONFIG_MTK_FB) := dsi_drv.o dpi_drv.o  lcd_drv.o dpi1_drv.o
# tvc_drv.o tve_drv.o tvrot_drv.o
ccflags-y += 	-I$(srctree)/drivers/misc/mediatek/videox/ \
		-I$(srctree)/drivers/misc/mediatek/video/mt6589/ \
		-I$(srctree)/drivers/misc/mediatek/dispsys/mt6589/