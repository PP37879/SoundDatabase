# DO NOT EDIT: instead edit ../../../../../..//mnt/c/swigwin-3.0.12/Examples/python/import_packages/from_init1/py2/pkg2/Makefile
# and run (cd ../../../../../../ && ./config.status) to regenerate
TOP_BUILDDIR_TO_TOP_SRCDIR = /mnt/c/swigwin-3.0.12/
SRCDIR = ../../../../../..//mnt/c/swigwin-3.0.12/Examples/python/import_packages/from_init1/py2/pkg2/

TOP        = ../../../../..
SWIGEXE    = $(TOP)/../swig
SWIG_LIB_DIR = $(TOP)/../$(TOP_BUILDDIR_TO_TOP_SRCDIR)Lib
SWIGOPT    =
LIBS       =

build:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	SWIGOPT='$(SWIGOPT)' LIBS='$(LIBS)' TARGET='foo' INTERFACE='foo.i' python_cpp
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	SWIGOPT='$(SWIGOPT)' LIBS='$(LIBS)' TARGET='bar' INTERFACE='bar.i' python_cpp

static:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	SWIGOPT='$(SWIGOPT)' LIBS='$(LIBS)' TARGET='foo' INTERFACE='foo.i' python_cpp_static
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	SWIGOPT='$(SWIGOPT)' LIBS='$(LIBS)' TARGET='bar' INTERFACE='bar.i' python_cpp_static

clean::
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' TARGET='foo' python_clean
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' TARGET='bar' python_clean
