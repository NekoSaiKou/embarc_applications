## embARC application makefile template ##
### You can copy this file to your application folder
### and rename it to makefile.
##

# Application name
APPL ?= ARC-TEAM4

# Optimization Level
# Please Refer to toolchain_xxx.mk for this option
OLEVEL ?= O2

##
# Current Board And Core
##
BOARD ?= emsk
BD_VER ?= 22
CUR_CORE ?= arcem7d

##
# select debugging jtag
##
JTAG ?= usb

##
# Set toolchain
##
TOOLCHAIN ?= gnu

#
# root dir of embARC
#
EMBARC_ROOT = ./../..

MID_SEL = 

# application defines
APPL_DEFINES =


# application source dirs
APPL_CSRC_DIR = .
APPL_ASMSRC_DIR = .

# application include dirs
APPL_INC_DIR = .

# include current project makefile
COMMON_COMPILE_PREREQUISITES += makefile

### Options above must be added before include options.mk ###
# include key embARC build system makefile
override EMBARC_ROOT := $(strip $(subst \,/,$(EMBARC_ROOT)))
include $(EMBARC_ROOT)/options/options.mk