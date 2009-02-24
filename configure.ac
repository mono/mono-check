AC_PREREQ(2.61)
AC_INIT([mono-check], [0.2], [mhabersack@novell.com])
AC_COPYRIGHT([Copyright (c) 2009 Novell, Inc])
AC_CONFIG_SRCDIR([mono-check/mono-check])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([1.10])
AM_MAINTAINER_MODE

scripts_dir="share/mono-check/scripts"
top_monocheck_dir="\$(prefix)/share/mono-check/"
AC_SUBST(top_monocheck_dir)
AC_SUBST(scripts_dir)

AC_OUTPUT([
Makefile
man/Makefile
mono-check/mono-check.conf
mono-check/Makefile
mono-check/scripts/Makefile
mono-check/scripts/checks/Makefile
mono-check/scripts/checks/generic/Makefile
mono-check/scripts/checks/suse/Makefile
mono-check/scripts/generic/Makefile
mono-check/scripts/suse/Makefile
])
