## Process this file with automake to produce Makefile.in

## Created by Anjuta



AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\" \
	$(PRODUCTIONCODE_CFLAGS)

AM_CFLAGS =\
	 -Wall\
	 -g

bin_PROGRAMS = productioncode

productioncode_SOURCES = \
	productioncode.vala config.vapi

productioncode_VALAFLAGS = 

productioncode_LDFLAGS = \
	-Wl,--export-dynamic

productioncode_LDADD = $(PRODUCTIONCODE_LIBS)
