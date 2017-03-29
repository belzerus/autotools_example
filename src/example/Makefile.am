AM_CFLAGS = -I$(top_srcdir)/src/lib
AM_CPPFLAGS = -I$(top_srcdir)/src/lib
bin_PROGRAMS = example_binary example_binary_cxx
example_binary_SOURCES = example_binary.c
example_binary_cxx_SOURCES = example_binary_cxx.cpp
example_binary_LDADD = $(top_builddir)/src/lib/libexample.a
example_binary_cxx_LDADD = $(top_builddir)/src/lib/libexamplecxx.a
