#
# Makefile for caching inode integrity data (iint)
#

obj-$(CONFIG_INTEGRITY) += integrity.o

integrity-y := iint.o

subdir-$(CONFIG_IMA)			+= ima
obj-$(CONFIG_IMA)			+= ima/built-in.o
