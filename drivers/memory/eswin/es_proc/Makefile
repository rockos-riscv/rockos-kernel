# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_ESWIN_PROC)	+= es_proc.o
ccflags-y := -DDEBUG

ES_PROC_HEADER := $(srctree)/drivers/memory/eswin/es_proc/include/linux

COPY_HEADERS := $(shell mkdir -p include/linux && cp $(ES_PROC_HEADER)/*.h include/linux)
