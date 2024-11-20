obj-$(CONFIG_ESWIN_IOMMU_RSV) += iommu_rsv.o

ES_IOMMU_RSV_HEADER := $(srctree)/drivers/memory/eswin/es_iommu_rsv/include/linux

COPY_HEADERS := $(shell mkdir -p include/linux && cp $(ES_IOMMU_RSV_HEADER)/*h include/linux)
