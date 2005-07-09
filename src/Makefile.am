lib_LTLIBRARIES = libFS.la

libFS_la_SOURCES = 	\
	FSCloseFt.c	\
	FSClServ.c	\
	FSConnServ.c	\
	FSErrDis.c	\
	FSErrHndlr.c	\
	FSFlush.c	\
	FSFontInfo.c	\
	FSFtNames.c	\
	FSGetCats.c	\
	FSlibInt.c	\
	FSlibint.h	\
	FSlibos.h	\
	FSListCats.c	\
	FSListExt.c	\
	FSMisc.c	\
	FSNextEv.c	\
	FSOpenFont.c	\
	FSOpenServ.c	\
	FSQGlyphs.c	\
	FSQuExt.c	\
	FSQXExt.c	\
	FSQXInfo.c	\
	FSServName.c	\
	FSSetCats.c	\
	FSSync.c	\
	FSSynchro.c	\
	fs_transport.c

AM_CFLAGS = $(DEP_CFLAGS)
libFS_la_LIBADD = $(DEP_LIBS)

INCLUDES = -I$(top_srcdir)/include/X11/fonts



#
# Library version info.  Check the libtool docs for
# instructions on when and how to change this value
#
# bump when the ABI changes
FS_CURRENT=2
# bump for non-ABI changes, reset to zero when CURRENT changes
FS_REVISION=0
# bump when the ABI changes in backward-compatible fashion
FS_AGE=2

libFS_la_LDFLAGS = -version-info ${FS_CURRENT}:${FS_REVISION}:${FS_AGE} -no-undefined

libFSincludedir = $(includedir)/X11/fonts
libFSinclude_HEADERS = \
	$(top_srcdir)/include/X11/fonts/FSlib.h
