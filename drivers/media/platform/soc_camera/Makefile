obj-$(CPTCFG_SOC_CAMERA)		+= soc_camera.o soc_mediabus.o
obj-$(CPTCFG_SOC_CAMERA_PLATFORM)	+= soc_camera_platform.o

# soc-camera host drivers have to be linked after camera drivers
obj-$(CPTCFG_VIDEO_ATMEL_ISI)		+= atmel-isi.o
obj-$(CPTCFG_VIDEO_MX1)			+= mx1_camera.o
obj-$(CPTCFG_VIDEO_MX2)			+= mx2_camera.o
obj-$(CPTCFG_VIDEO_MX3)			+= mx3_camera.o
obj-$(CPTCFG_VIDEO_OMAP1)		+= omap1_camera.o
obj-$(CPTCFG_VIDEO_PXA27x)		+= pxa_camera.o
obj-$(CPTCFG_VIDEO_SH_MOBILE_CEU)	+= sh_mobile_ceu_camera.o
obj-$(CPTCFG_VIDEO_SH_MOBILE_CSI2)	+= sh_mobile_csi2.o

ccflags-y += -I$(backport_srctree)/drivers/media/i2c/soc_camera
