
SUBDIRS = finter

bin_PROGRAMS = annotate_rsids_from_linker.out

AM_CXXFLAGS = -I$(srcdir)/finter -I$(srcdir)/finter/include -ggdb -Wall -std=c++17

annotate_rsids_from_linker_out_SOURCES = annotate_rsids_from_linker/main.cc
annotate_rsids_from_linker_out_LDADD = finter/lib/libfinter.la -lz -lbz2
dist_doc_DATA = README
ACLOCAL_AMFLAGS = -I m4
