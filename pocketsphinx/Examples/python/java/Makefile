# DO NOT EDIT: instead edit ../../..//mnt/c/swigwin-3.0.12/Examples/python/java/Makefile
# and run (cd ../../../ && ./config.status) to regenerate
TOP_BUILDDIR_TO_TOP_SRCDIR = /mnt/c/swigwin-3.0.12/
SRCDIR = ../../..//mnt/c/swigwin-3.0.12/Examples/python/java/

TOP        = ../..
SWIGEXE    = $(TOP)/../swig
SWIG_LIB_DIR = $(TOP)/../$(TOP_BUILDDIR_TO_TOP_SRCDIR)Lib
CXXSRCS    =
TARGET     = example
INTERFACE  = example.i
LIBS       = -lm

check: build
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' python_run

build: Example.class Example.h
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' CXXSRCS='$(CXXSRCS)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	TARGET='$(TARGET)' INTERFACE='$(INTERFACE)' \
	CXXSHARED="gcj -fpic -shared Example.class" DEFS='' LIBS="-lstdc++" python_cpp

clean:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' python_clean
	rm -f $(TARGET).py
	rm -f *.class Example.h

Example.class Example.h: $(SRCDIR)Example.java
	gcj -d . -fPIC -C -c -g $(SRCDIR)Example.java
	gcjh Example.class
