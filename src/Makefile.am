## Process this file with automake to produce Makefile.in

## Created by Anjuta



AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\" \
	$(UNITTESTSVALA_CFLAGS)

AM_CFLAGS =\
	 -Wall\
	 -g

bin_PROGRAMS = unittestsvala

unittestsvala_SOURCES = \
	unittestsvala.vala config.vapi

unittestsvala_VALAFLAGS =  \
	--pkg gtk+-3.0

unittestsvala_LDFLAGS = \
	-Wl,--export-dynamic

unittestsvala_LDADD = $(UNITTESTSVALA_LIBS)


