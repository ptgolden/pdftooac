AC_INIT(pdf2oac, 1.0.0, Patrick Golden <ptgolden@email.unc.edu>)
AC_CONFIG_SRCDIR([pdf2oac.cc])
AM_INIT_AUTOMAKE([foreign])

AC_PROG_CXX
AX_CXX_COMPILE_STDCXX_11

PKG_CHECK_MODULES(POPPLER,poppler)
PKG_CHECK_MODULES(RDF,redland)
PKG_CHECK_MODULES(RAPTOR,raptor2)

# Generate the Makefile
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
