#
# src/Makefile.am
#
# Copyright (C) 2013 by 
# Roman Mohr - <roman@fenkhuber.at>
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

lib_LTLIBRARIES   = libjoedog.la 

libjoedog_la_LDFLAGS = -version-info 1:2:1

libjoedog_la_CFLAGS = -I$(top_srcdir)/include

libjoedog_la_SOURCES = \
memory.c   memory.h    \
notify.c   notify.h    \
perl.c     perl.h      \
util.c     util.h      \
snprintf.c snprintf.h  \
stralloc.c stralloc.h

