ifneq ($(TARGET_BUILD_VARIANT),user)
EXTRA_CFLAGS += -DDEBUG_HISI_CAMERA
endif
ccflags-y += -Idrivers/media/huawei/camera/hisp
ccflags-y += -Idrivers/media/huawei/camera

obj-y += hisp110.o
EXTRA_CFLAGS += -Wno-error=incompatible-pointer-types
