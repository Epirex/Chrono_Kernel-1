#
# Makefile for the Linux IPX layer.
#

obj-$(CONFIG_IPX) += ipx.o

ipx-y			:= af_ipx.o ipx_route.o ipx_proc.o
ipx-$(CONFIG_SYSCTL)	+= sysctl_net_ipx.o

include $(srctree)/scripts/Makefile_build.thumb2
