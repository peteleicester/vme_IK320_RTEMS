TOP = ../..
include $(TOP)/configure/CONFIG

ADL_DIR = adl
UI_DIR  = ui/autoconvert
EDL_DIR = edl/autoconvert
OPI_DIR = opi/autoconvert
BOB_DIR = bob/autoconvert

# Install the edl files
DIRS += symbol
DIRS += edl
DIRS := $(wildcard $(DIRS))

include $(CONFIG)/RULES_DIRS

-include $(SUPPORT)/configure/RULES_OPI
