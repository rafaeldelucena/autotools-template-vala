AM_CFLAGS =\
	 -Wall\
	 -g

lib_LTLIBRARIES = libautotools-template-vala.la

libautotools_template_vala_la_VALASOURCES = \
	autotools-template-vala.vala

libautotools_template_vala_la_SOURCES = \
	$(libautotools_template_vala_la_VALASOURCES)

libautotools_template_vala_la_VALAFLAGS = \
	--vapi autotools-template-vala.vapi \
	--library autotools-template-vala\
	-H autotools-template-vala.h\
	--pkg gio-2.0

libautotools_template_vala_la_CPPFLAGS = \
	$(AUTOTOOLS_TEMPLATE_VALA_CFLAGS)

libautotools_template_vala_la_LIBADD = \
	$(AUTOTOOLS_TEMPLATE_VALA_LIBS)

libautotools_template_vala_la_LDFLAGS =

libautotools_template_vala_la_includedir = \
	$(includedir)/autotools-template-vala

libautotools_template_vala_la_include_HEADERS = \
	autotools-template-vala.h

vapidir = $(datadir)/vala/vapi

dist_vapi_DATA = \
	autotools-template-vala.vapi

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = autotools-template-vala.pc

EXTRA_DIST = \
	autotools-template-vala.pc.in

MOSTLYCLEANFILES = \
	$(libautotools_template_vala_la_SOURCES:.vala=.c) \
	autotools-template-vala.vapi
