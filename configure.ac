AC_PREREQ(2.61)
AC_INIT([mono-aspnetcheck], [0.1], [mhabersack@novell.com])
AC_COPYRIGHT([Copyright (c) 2009 Novell, Inc])
AC_CONFIG_SRCDIR([aspnetcheck/aspnetcheck])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([1.10])
AM_MAINTAINER_MODE

scripts_dir="share/mono-aspnetcheck/scripts"
top_aspnetcheck_dir="\$(prefix)/share/mono-aspnetcheck/"
AC_SUBST(top_aspnetcheck_dir)
AC_SUBST(scripts_dir)

AC_OUTPUT([
Makefile
man/Makefile
aspnetcheck/aspnetcheck.conf
aspnetcheck/Makefile
aspnetcheck/scripts/Makefile
aspnetcheck/scripts/checks/Makefile
aspnetcheck/scripts/checks/generic/Makefile
aspnetcheck/scripts/checks/suse/Makefile
aspnetcheck/scripts/generic/Makefile
aspnetcheck/scripts/suse/Makefile
])
