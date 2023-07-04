ARCHS = arm64 arm64e
TARGET := iphone:clang:latest:16.0
#INSTALL_TARGET_PROCESSES =  


include $(THEOS)/makefiles/common.mk

LIBRARY_NAME = libSupport

libSupport_FILES = jailed.mm
libSupport_CFLAGS = -fobjc-arc -fvisibility=hidden
libSupport_CCFLAGS = -fobjc-arc -fvisibility=hidden
libSupport_FRAMEWORKS = UIKit
libSupport_INSTALL_PATH = @executable_path/Frameworks

libSupport_LINKAGE_TYPE = dynamic

ibSupport_LDFLAGS += -lsupport

include $(THEOS)/makefiles/library.mk
