ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/Driver_trunk_4th_Gen/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include/
ccflags-y += -I$(srctree)/drivers/watchdog/mediatek/
ccflags-y += -I$(srctree)/drivers/watchdog/mediatek/wdt/
ccflags-y += -I$(srctree)/drivers/watchdog/mediatek/wdt/$(MTK_PLATFORM)/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/i2c/$(MTK_PLATFORM)/
EXTRA_CFLAGS +=-Wno-error=date-time
obj-$(CONFIG_TOUCHSCREEN_FTS)		+= fts.o fts_gui.o fts_driver_test.o fts_lib/
