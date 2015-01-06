
include $(srctree)/drivers/misc/mediatek/Makefile.custom

# Module project related part

ifeq ($(CONFIG_MTK_AP3220),y)
obj-y	+=  alsps/ap3220/
endif

ifeq ($(CONFIG_MTK_BMA222E_AUTO),y)
obj-y   +=  accelerometer/bma222E_auto/
endif

ifeq ($(CONFIG_MTK_BMA250E_AUTO),y)
obj-y   +=  accelerometer/bma250E_auto/
endif

ifeq ($(CONFIG_MTK_KXTJ2_AUTO),y)
obj-y   +=  accelerometer/kxtj2_auto/
endif

ifeq ($(CONFIG_MTK_MPU3000),y)
obj-y   +=  gyroscope/mpu3000/
endif
ifeq ($(CONFIG_MTK_L3GD20),y)
obj-y   +=  gyroscope/l3gd20/
endif
ifeq ($(CONFIG_MTK_MPU3050C),y)
obj-y   +=  gyroscope/mpu3050c/
endif

ifeq ($(CONFIG_MTK_BMG160),y)
obj-y   +=  gyroscope/bmg160/
endif
ifeq ($(CONFIG_MTK_BMM050-NEW),y)
obj-y	+=  magnetometer/bmm050-new/
endif
ifeq ($(CONFIG_MTK_BMC156_MAG),y)
obj-y	+=  magnetometer/bmc156_mag/
endif

ifneq ($(CONFIG_ARCH_MTK_PROJECT),)
ARCH_MTK_PROJECT := $(shell echo $(CONFIG_ARCH_MTK_PROJECT))
obj-y	+= core/
obj-y	+= dct/dct/
endif

obj-y   +=  lcm/
#obj-y	+=  hdmi/
obj-y	+=  camera/camera/
obj-y	+=  imgsensor/hi253_yuv/
obj-y	+=  imgsensor/ov2659_yuv/
obj-y	+=  imgsensor/ov8825_mipi_raw/
obj-y	+=  imgsensor/ov8826_mipi_raw/
obj-y	+=  imgsensor/ov8827_mipi_raw/
obj-y +=  flashlight/constant_flashlight/
obj-y	+=  vibrator/
obj-y	+=  leds/
obj-y	+=  lens/
obj-y	+=  keypad/
obj-y	+=  sound/
obj-y	+=  accdet/
obj-y	+=  wmt/
