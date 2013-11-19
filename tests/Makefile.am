noinst_PROGRAMS = $(TEST_PROGS)

AM_CPPFLAGS = \
	$(AUTOTOOLS_TEMPLATE_VALA_CFLAGS)

AM_CFLAGS = -Werror \
			-Wall \
			-g


TEST_PROGS = unittests 

unittests_SOURCES = unittests.vala 

unittests_LDFLAGS =

unittests_LDADD = $(AUTOTOOLS_TEMPLATE_VALA_LIBS)

unittestsvala_VALAFLAGS = 

check_PROGRAMS = $(TEST_PROGS)

TESTS = $(TEST_PROGS)
