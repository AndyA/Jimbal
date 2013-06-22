DIST_SUBDIRS = m4

# EXTRA_DIST = jd_path.h jd_utf8.h

SUBDIRS = .

ACLOCAL_AMFLAGS = -I m4

bin_PROGRAMS = flypi

flypi_SOURCES = flypi.c flypi.h

flypi_CFLAGS = $(MAVLINK_CFLAGS)
flypi_LDFLAGS = $(MAVLINK_LDFLAGS)

test: all
	cd t && $(MAKE) test

