DIST_SUBDIRS = m4

SUBDIRS = .

ACLOCAL_AMFLAGS = -I m4

bin_PROGRAMS = mavrelay

mavrelay_SOURCES = mavrelay.c

mavrelay_CFLAGS = $(MAVLINK_CFLAGS)
mavrelay_LDFLAGS = $(MAVLINK_LDFLAGS)

test: all
	cd t && $(MAKE) test

