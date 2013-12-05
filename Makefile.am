ACLOCAL_AMFLAGS = -I m4

SUBDIRS = src

if ENABLE_TESTS
SUBDIRS += tests
endif

DIST_SUBDIRS = $(SUBDIRS)

autotools_template_valadocdir = ${prefix}/doc/autotools-template-vala
autotools_template_valadoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


EXTRA_DIST = \
	$(autotools_template_valadoc_DATA)

uninstall-local:
	-rm -r $(autotools_template_valadocdir)
