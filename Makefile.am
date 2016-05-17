lib_LTLIBRARIES=libpcd8544.la
libpcd8544_la_CPPFLAGS= -DCLIENT_LIB_VERSION=0x$(shell cd ~/libpcd8544;git log -1 --pretty=format:%h)
libpcd8544_la_LDFLAGS=-lwiringPi
libpcd8544_la_SOURCES= \
	src/PCD8544.c
libpcd8544_la_DEPENDENCIES=

libpcd8544_la_includedir= \
	$(includedir)
libpcd8544_la_include_HEADERS= \
	src/PCD8544.h

libpcd8544_la_LIBADD=
