# DO NOT EDIT: instead edit ../../..//mnt/c/swigwin-3.0.12/Examples/csharp/template/Makefile
# and run (cd ../../../ && ./config.status) to regenerate
TOP_BUILDDIR_TO_TOP_SRCDIR = /mnt/c/swigwin-3.0.12/
SRCDIR = ../../..//mnt/c/swigwin-3.0.12/Examples/csharp/template/

TOP        = ../..
SWIGEXE    = $(TOP)/../swig
SWIG_LIB_DIR = $(TOP)/../$(TOP_BUILDDIR_TO_TOP_SRCDIR)Lib
CXXSRCS    =
TARGET     = example
INTERFACE  = example.i
SWIGOPT    =
CSHARPSRCS = *.cs
CSHARPFLAGS= -nologo -debug+ -out:runme.exe

check: build
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' csharp_run

build:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' CXXSRCS='$(CXXSRCS)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	SWIGOPT='$(SWIGOPT)' TARGET='$(TARGET)' INTERFACE='$(INTERFACE)' csharp_cpp
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' CSHARPSRCS='$(CSHARPSRCS)' CSHARPFLAGS='$(CSHARPFLAGS)' csharp_compile

clean:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' csharp_clean
