#                                               -*- Autoconf -*-
# configure.ac -- Autoconf script for codec codec test
#

# Process this file with autoconf to produce a configure script

# Requires autoconf tool later than 2.61
AC_PREREQ(2.61)
# Initialize the DAC and mercury codec test app package version 1.0.0
AC_INIT([dac_mer_testapp],1.0.0)
# Does not strictly follow GNU Coding standards
AM_INIT_AUTOMAKE([foreign])
# Disables auto rebuilding of configure, Makefile.ins
AM_MAINTAINER_MODE
# Verifies the --srcdir is correct by checking for the path
AC_CONFIG_SRCDIR([dac_mer_testapp.c])
# defines some macros variable to be included by source
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIR([m4])


# Checks for programs.
AM_PROG_AS
AC_PROG_CC
AM_PROG_CC_C_O
AC_PROG_CXX
AC_PROG_LIBTOOL
AC_PROG_AWK
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET
PKG_PROG_PKG_CONFIG

AC_CONFIG_FILES([ \
        Makefile \
        ])

AC_OUTPUT
