ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

dtbo-$(CONFIG_BOARD_F7B) += \
    violet-sm6150-overlay.dtbo

violet-sm6150-overlay.dtbo-base := qcom-base/sm6150.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
