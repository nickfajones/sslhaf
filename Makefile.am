
ACLOCAL_AMFLAGS= -I m4

SUBDIRS= $(GENERIC_LIBRARY_NAME)

DIST_SUBDIRS = $(GENERIC_LIBRARY_NAME)
EXTRA_DIST = LICENSE gen_sslhaf_suites.pl suites.csv

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = sslhaf.pc

doxygen doxygen-pdf:
	@(cd docs && $(MAKE) $@)
