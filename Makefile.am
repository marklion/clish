## Process this file with automake to generate Makefile.in
AUTOMAKE_OPTIONS        = foreign nostdinc

AM_CPPFLAGS             = -I. -I$(top_srcdir)
AM_LD                   = $(CXX)

if DEBUG
  DEBUG_CFLAGS = -DDEBUG
endif

AM_CFLAGS               = -ansi -pedantic -Werror -Wall -D_POSIX_C_SOURCE=199309 $(DEBUG_CFLAGS)

bin_PROGRAMS            =
lib_LTLIBRARIES         =
lib_LIBRARIES           =
nobase_include_HEADERS  =

EXTRA_DIST              =  \
    bin/module.am          \
    clish/module.am        \
    lub/module.am          \
    lubheap/module.am      \
    tinyrl/module.am       \
    tinyxml/module.am      \
    test/module.am         \
    xml-examples/module.am \
    doxygen.config         \
    clish.xsd              \
    LICENCE                \
    README                 \
    CHANGES                \
    ISSUES

include $(top_srcdir)/bin/module.am
include $(top_srcdir)/clish/module.am
include $(top_srcdir)/lub/module.am
include $(top_srcdir)/lubheap/module.am
include $(top_srcdir)/tinyrl/module.am
include $(top_srcdir)/tinyxml/module.am
include $(top_srcdir)/test/module.am
include $(top_srcdir)/xml-examples/module.am
