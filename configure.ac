#
# configure.ac
#
# Copyright (C) 2013 by 
# Jeffrey Fulmer - <jeff@joedog.org>, et al.
# This file is distributed as part of libjoedog
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
#


AC_PREREQ([2.59])
AC_INIT([libjoedog], [0.1.2], [jeff@joedog.org])
AC_CONFIG_SRCDIR([config.h.in])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_MACRO_DIR([m4])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([fcntl.h memory.h stdlib.h string.h strings.h sys/time.h sys/times.h syslog.h time.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_REALLOC
AC_CHECK_FUNCS([memchr memmove memset strchr strdup strerror strrchr snprintf vsnprintf])

AC_LIBTOOL_DLOPEN
AC_PROG_LIBTOOL

AC_CONFIG_FILES([src/Makefile
                 include/Makefile
                 Makefile
                 ])
AC_OUTPUT
