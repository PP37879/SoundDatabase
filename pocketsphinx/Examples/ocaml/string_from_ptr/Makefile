# DO NOT EDIT: instead edit ../../..//mnt/c/swigwin-3.0.12/Examples/ocaml/string_from_ptr/Makefile
# and run (cd ../../../ && ./config.status) to regenerate
TOP_BUILDDIR_TO_TOP_SRCDIR = /mnt/c/swigwin-3.0.12/
SRCDIR = ../../..//mnt/c/swigwin-3.0.12/Examples/ocaml/string_from_ptr/

TOP        = ../..
SWIGEXE    = $(TOP)/../swig
SWIG_LIB_DIR = $(TOP)/../$(TOP_BUILDDIR_TO_TOP_SRCDIR)Lib
SWIGOPT    = -c++
SRCS       =
TARGET     = example
INTERFACE  = foolib.i
MLFILE     = foolib.ml
PROGFILE   = example_prog.ml
OBJS       =

check: build
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' TARGET='$(TARGET)' ocaml_run

build: static static_top

static:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' SRCS='$(SRCS)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	SWIGOPT='$(SWIGOPT)' TARGET='$(TARGET)' INTERFACE='$(INTERFACE)' \
	MLFILE='$(MLFILE)' PROGFILE='$(PROGFILE)' OBJS='$(OBJS)' \
	ocaml_static_cpp

static_top:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' SRCS='$(SRCS)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	SWIGOPT='$(SWIGOPT)' TARGET='$(TARGET)' INTERFACE='$(INTERFACE)' \
	MLFILE='$(MLFILE)' PROGFILE='$(PROGFILE)' OBJS='$(OBJS)' \
	ocaml_static_cpp_toplevel

dynamic:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' SRCS='$(SRCS)' \
	SWIG_LIB_DIR='$(SWIG_LIB_DIR)' SWIGEXE='$(SWIGEXE)' \
	SWIGOPT='$(SWIGOPT)' TARGET='$(TARGET)' INTERFACE='$(INTERFACE)'
	MLFILE='$(MLFILE)' PROGFILE='$(PROGFILE)' OBJS='$(OBJS)' \
	ocaml_dynamic_cpp

clean:
	$(MAKE) -f $(TOP)/Makefile SRCDIR='$(SRCDIR)' MLFILE='$(MLFILE)' ocaml_clean
