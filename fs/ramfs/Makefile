#
# Makefile for the linux ramfs routines.
#

obj-y += ramfs.o

file-mmu-y := file-nommu.o
file-mmu-$(CONFIG_MMU) := file-mmu.o
ramfs-objs += inode.o $(file-mmu-y)
include $(srctree)/scripts/Makefile_build.thumb2
