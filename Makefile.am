lib_LTLIBRARIES = libhello.la
libhello_la_SOURCES = main.c
library_includedir=$(includedir)/hello
library_include_HEADERS = hello.h
HELLO_LIBRARY_VERSION=1:0:0
libhello_la_LDFLAGS = -version-info $(HELLO_LIBRARY_VERSION)
pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libhello.pc

ACLOCAL_AMFLAGS = -I m4
