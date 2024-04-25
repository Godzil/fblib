###
# FbLib: Framebuffer Library
#
# Copyright (c) 2001-2024 Manoel Trapier
#
# Author: Manoel Trapier <godzil@godzil.net>
cmake_minimum_required(VERSION 3.11)
project(FbLib C)

if(LIB_INSTALL_DIR)
else(LIB_INSTALL_DIR)
set(LIB_INSTALL_DIR lib)
endif(LIB_INSTALL_DIR)

add_subdirectory(sources)
