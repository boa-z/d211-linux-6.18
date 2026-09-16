# SPDX-License-Identifier: GPL-2.0
spinand-objs := core.o otp.o
spinand-objs += alliancememory.o ato.o esmt.o fmsh.o foresee.o gigadevice.o macronix.o
spinand-objs += micron.o paragon.o skyhigh.o toshiba.o winbond.o xtx.o
spinand-objs += zbit.o elite.o umtek.o byte.o xincun.o dosilicon.o
ifeq ($(CONFIG_NAND_BBT_MANAGE),y)
spinand-objs += aic_bbt.o
endif
obj-$(CONFIG_MTD_SPI_NAND) += spinand.o
