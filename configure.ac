#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT

# Checks for programs.
AC_PROG_INSTALL
AC_PROG_MKDIR_P

AC_SUBST([CONFIG_BIN_FILES])
CONFIG_BIN_FILES=" \
	config/bin/practicerom-pkg \
	config/bin/practicerom-pkg-deb \
	config/bin/practicerom-pkg-init \
	config/bin/practicerom-pkg-target \
	"
AC_SUBST([CONFIG_DATA_FILES])
CONFIG_DATA_FILES=" \
	config/share/practicerom-pkg/targets/deb-all \
	"
AC_SUBST([CONFIG_SYSCONF_FILES])
CONFIG_SYSCONF_FILES=" \
	"

AC_CONFIG_FILES([Makefile ${CONFIG_BIN_FILES} ${CONFIG_DATA_FILES} ${CONFIG_SYSCONF_FILES}])
AC_OUTPUT
