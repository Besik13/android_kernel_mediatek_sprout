obj-y += gpu.o
gpu-$(CONFIG_ARCH_MT6589) := mtk_gpu_utility_6589.o

ifeq ($(CONFIG_ARCH_MT6572), y)
  obj-y += mt6572/
endif
ifeq ($(CONFIG_ARCH_MT6582), y)
  obj-y += mt6582/
  gpu-y := mtk_gpu_utility.o
endif
ifeq ($(CONFIG_ARCH_MT6589), y)
  obj-y += mt6589/
endif

