include $(srctree)/drivers/misc/mediatek/Makefile.custom

ifeq ($(CONFIG_CUSTOM_KERNEL_HDMI),"nxp_tda19989")
	ccflags-y += 	-DHDMI_TDA19989
endif

ccflags-y += 	-DMTK_HDMI_FENCE_SUPPORT
ccflags-y += 	-DMTK_HDMI_ION_SUPPORT

obj-y	:= hdmi_buffers_manager.o hdmi_dpi_config.o hdmitx_platform.o hdmitx.o debug.o hdmitx_test.o