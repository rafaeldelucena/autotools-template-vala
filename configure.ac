AC_INIT(autotools-template-vala, 0.1)

AC_CONFIG_HEADERS([config.h])

AM_INIT_AUTOMAKE([1.11])

AM_SILENT_RULES([yes])

AC_PROG_CC

LT_INIT


AM_PROG_VALAC([0.10.0])


PKG_CHECK_MODULES(AUTOTOOLS_TEMPLATE_VALA, [glib-2.0])

AC_ARG_ENABLE(tests, AS_HELP_STRING([--enable-tests], [Enable the build of the tests [default=no]]))
AS_IF([test "x$enable_tests" = "xyes"],[
    AM_CONDITIONAL([ENABLE_TESTS], [true]),
    AC_CONFIG_FILES([tests/Makefile])
],[
    AM_CONDITIONAL([ENABLE_TESTS], [false])
])


AC_OUTPUT([
Makefile
src/Makefile
])
