bin_PROGRAMS = mmcli

mmcli_CPPFLAGS = \
	$(MMCLI_CFLAGS) \
	-I$(top_srcdir) \
	-I$(top_srcdir)/include \
	-I$(top_builddir)/include \
	-I$(top_srcdir)/libmm-glib \
	-I${top_srcdir}/libmm-glib/generated \
	-I${top_builddir}/libmm-glib/generated

mmcli_SOURCES = \
	mmcli.h \
	mmcli.c \
	mmcli-common.h \
	mmcli-common.c \
	mmcli-manager.c \
	mmcli-modem.c \
	mmcli-modem-3gpp.c \
	mmcli-modem-cdma.c \
	mmcli-modem-simple.c \
	mmcli-modem-location.c \
	mmcli-modem-messaging.c \
	mmcli-modem-time.c \
	mmcli-modem-firmware.c \
	mmcli-bearer.c \
	mmcli-sim.c \
	mmcli-sms.c

mmcli_LDADD = \
	$(MMCLI_LIBS) \
	$(top_builddir)/libmm-glib/libmm-glib.la
