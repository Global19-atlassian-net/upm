upm_mixed_module_init (NAME biss0001
    DESCRIPTION "Passive Infrared (PIR) Motion Sensor"
    C_HDR biss0001.h
    C_SRC biss0001.c
    CPP_HDR biss0001.hpp
    CPP_SRC biss0001.cxx
    IFACE_HDR iMotion.hpp
    FTI_SRC biss0001_fti.c
    CPP_WRAPS_C
    REQUIRES mraa)
