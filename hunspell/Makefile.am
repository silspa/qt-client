lib_LTLIBRARIES = libhunspell-1.2.la
libhunspell_1_2_includedir = $(includedir)/hunspell
libhunspell_1_2_la_SOURCES=affentry.cxx affixmgr.cxx csutil.cxx \
		     dictmgr.cxx hashmgr.cxx hunspell.cxx \
	             suggestmgr.cxx license.myspell license.hunspell \
	             phonet.cxx filemgr.cxx hunzip.cxx replist.cxx

libhunspell_1_2_include_HEADERS=affentry.hxx htypes.hxx affixmgr.hxx \
	        csutil.hxx hunspell.hxx atypes.hxx dictmgr.hxx hunspell.h \
		suggestmgr.hxx baseaffix.hxx hashmgr.hxx langnum.hxx \
		phonet.hxx filemgr.hxx hunzip.hxx w_char.hxx replist.hxx \
		hunvisapi.h

libhunspell_1_2_la_DEPENDENCIES=utf_info.cxx
libhunspell_1_2_la_LDFLAGS=-no-undefined

AM_CXXFLAGS=$(CFLAG_VISIBILITY) -DBUILDING_LIBHUNSPELL

EXTRA_DIST=hunspell.dsp makefile.mk README utf_info.cxx
