## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = src test 

unittestsvaladocdir = ${prefix}/doc/unittestsvala
unittestsvaladoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


EXTRA_DIST = $(unittestsvaladoc_DATA)


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(unittestsvaladocdir)
