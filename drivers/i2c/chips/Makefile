#
# Makefile for miscellaneous I2C chip drivers.
#
# Do not add new drivers to this directory! It is DEPRECATED.
#
# Device drivers are better grouped according to the functionality they
# implement rather than to the bus they are connected to. In particular:
# * Hardware monitoring chip drivers go to drivers/hwmon
# * RTC chip drivers go to drivers/rtc
# * I/O expander drivers go to drivers/gpio
#

obj-$(CONFIG_SENSORS_MT9T013)	+= mt9t013.o
obj-$(CONFIG_MAX9877) += max9877.o
obj-$(CONFIG_GALAXY_LIGHTSENSOR) += lightsensor.o
obj-$(CONFIG_GP2AP) += gp2ap.o
obj-$(CONFIG_AKM8973) += akm8973.o
obj-$(CONFIG_BMA150) += bma150.o

ifeq ($(CONFIG_I2C_DEBUG_CHIP),y)
EXTRA_CFLAGS += -DDEBUG
endif

