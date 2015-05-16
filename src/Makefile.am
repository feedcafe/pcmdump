## Process this file with automake to produce Makefile.in

## Created by Anjuta

AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\"

AM_CFLAGS =\
	 -Wall -I include \
	 -g -lpthread -lsbc

bin_PROGRAMS = pcmdump

pcmdump_SOURCES = \
	parser/hci.c    \
	parser/lmp.c    \
	parser/amp.c    \
	parser/parser.c \
	parser/sdp.c    \
	parser/att.c    \
	parser/l2cap.c  \
	lib/sdp.c       \
	lib/hci.c       \
	lib/bluetooth.c \
	pcmdump.c

pcmdump_LDFLAGS = 

pcmdump_LDADD = 

