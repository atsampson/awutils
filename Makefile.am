bin_PROGRAMS = log2bin awimage awflash

log2bin_SOURCES = \
	log2bin.c

awimage_SOURCES = \
	awimage.c \
	imagewty.h \
	parsecfg.c \
	parsecfg.h \
	rc6.c \
	rc6.h \
	std_defs.h \
	twofish.c \
	twofish.h

awflash_CPPFLAGS = @LIBUSB_CFLAGS@
awflash_LDADD = @LIBUSB_LIBS@
awflash_SOURCES = \
	awflash.c

EXTRA_DIST = \
	COPYING \
	README \
	TODO
