################################################################################
#                       NORTH CAROLINA STATE UNIVERSITY
#
#                              FabScalar Project
#
# FabScalar Copyright (c) 2007-2011 by Niket K. Choudhary, Salil Wadhavkar,
# and Eric Rotenberg.  All Rights Reserved.
#
# This is a beta-release version.  It must not be redistributed at this time.
#
# Purpose:
# This is the Makefile for compiling the FabMem CAM estimation tool (cam_est).
################################################################################

# Use "make" or "make all" to compile the tool.
# Use "make clean" to clean the directory.


TOOL_NAME = cam_est

all:
	gcc -O3 -g -lm  -o $(TOOL_NAME) regfile_sim.c parameters.c print_file.c

clean:
	rm -f $(TOOL_NAME)
