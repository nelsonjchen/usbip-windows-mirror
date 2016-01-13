AM_CPPFLAGS := -I$(top_srcdir)/libsrc
AM_CFLAGS   := @EXTRA_CFLAGS@ @PACKAGE_CFLAGS@

sbin_PROGRAMS := usbip

usbip_SOURCES = usbip.c usbip_network.c usbip_network.h usbip_windows.c usbip_platform.h windows/getopt.c windows/getopt_long.c
usbip_LDADD = -lws2_32 -lsetupapi -lusbip
usbip_LDFLAGS = -L$(top_builddir)/libsrc
