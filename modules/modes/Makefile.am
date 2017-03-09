## Process this file with automake to produce Makefile.in
DEFS = @DEFS@ 
AM_CPPFLAGS = -I. -I../.. $(INCLTDL) -I../../lib

EXTRA_DIST = ofb.h cfb.h nofb.h cbc.h ecb.h stream.h ncfb.h ctr.h
pkglib_LTLIBRARIES = @INSTALL_MODE_MODULES@

EXTRA_LTLIBRARIES = ofb.la cfb.la nofb.la cbc.la ecb.la stream.la ncfb.la \
	ctr.la
noinst_LTLIBRARIES = @NOINSTALL_MODE_MODULES@

ofb_la_SOURCES = ofb.c
ofb_la_LDFLAGS =  -module -avoid-version -no-undefined -rpath $(pkglibdir)
ctr_la_SOURCES = ctr.c
ctr_la_LDFLAGS =  -module -avoid-version -no-undefined -rpath $(pkglibdir)
cfb_la_SOURCES = cfb.c
cfb_la_LDFLAGS =  -module -avoid-version -no-undefined -rpath $(pkglibdir) 
ncfb_la_SOURCES = ncfb.c
ncfb_la_LDFLAGS =  -module -avoid-version -no-undefined -rpath $(pkglibdir)  
nofb_la_SOURCES = nofb.c
nofb_la_LDFLAGS =  -module -avoid-version -no-undefined -rpath $(pkglibdir)  
ecb_la_SOURCES = ecb.c
ecb_la_LDFLAGS =  -module -avoid-version -no-undefined -rpath $(pkglibdir)  
cbc_la_SOURCES = cbc.c
cbc_la_LDFLAGS =  -module -avoid-version -no-undefined -rpath $(pkglibdir)  
stream_la_SOURCES = stream.c
stream_la_LDFLAGS =  -module -avoid-version -no-undefined -rpath $(pkglibdir)
