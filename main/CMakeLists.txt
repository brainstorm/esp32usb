# Edit following two lines to set component requirements (see docs)
cmake_minimum_required(VERSION 3.13)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS "main.c" "usb.c" "usb_asm_1bit.S")
set(COMPONENT_ADD_INCLUDEDIRS "")

register_component()
