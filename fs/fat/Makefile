#
# Makefile for the Linux fat filesystem support.
#
CFLAGS_dir.o += -Wno-maybe-uninitialized
obj-$(CONFIG_FAT_FS) += fat.o
obj-$(CONFIG_VFAT_FS) += vfat.o
obj-$(CONFIG_MSDOS_FS) += msdos.o

fat-y := cache.o dir.o fatent.o file.o inode.o misc.o
vfat-y := namei_vfat.o
msdos-y := namei_msdos.o
