IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.2.2
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0

PROJECT_NAME := plc-lfe-gem
PROJECT_PATH := ../../plc-lfe-gem/plc-lfe-gem.tsproj
PLC := plc_lfe_gem

PYTMC_OPTS := 
PREFIX := PREFIX

include $(IOC_TOP)/iocBoot/templates/Makefile.base
