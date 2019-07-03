## Process this file with automake to produce Makefile.in

libdir = @plugindir@

AM_CPPFLAGS = -I@srcdir@ -I@srcdir@/../login -I@builddir@/../login
AM_CFLAGS = @CFLAGS@ @EXTRA_CFLAGS@

lib_LTLIBRARIES = sasl-plain.la

sasl_plain_la_SOURCES = client-plain.c
sasl_plain_la_LDFLAGS = -module -avoid-version
