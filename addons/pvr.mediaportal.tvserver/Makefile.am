#
# Makefile for the Mediaportal add-on for XBMC PVR
#
# See the README for copyright information and
# how to reach the author.
#

ADDONBINNAME    = XBMC_Mediaportal
ADDONNAME       = pvr.mediaportal.tvserver
LIBNAME         = libmediaportal-addon
lib_LTLIBRARIES = libmediaportal-addon.la

LIBS            = @abs_top_srcdir@/lib/tinyxml/libtinyxml.la

include ../Makefile.include.am

INCLUDES+=-Isrc

libmediaportal_addon_la_SOURCES = src/Cards.cpp \
                                  src/channels.cpp \
                                  src/client.cpp \
                                  src/DateTime.cpp \
                                  src/epg.cpp \
                                  src/GenreTable.cpp \
                                  src/GUIDialogRecordSettings.cpp \
                                  src/pvrclient-mediaportal.cpp \
                                  src/recordings.cpp \
                                  src/Socket.cpp \
                                  src/timers.cpp \
                                  src/uri.cpp \
                                  src/utils.cpp \
                                  src/lib/tsreader/ChannelInfo.cpp \
                                  src/lib/tsreader/DeMultiplexer.cpp \
                                  src/lib/tsreader/DvbUtil.cpp \
                                  src/lib/tsreader/FileReader.cpp \
                                  src/lib/tsreader/MultiFileReader.cpp \
                                  src/lib/tsreader/PacketSync.cpp \
                                  src/lib/tsreader/PatParser.cpp \
                                  src/lib/tsreader/PidTable.cpp \
                                  src/lib/tsreader/PmtParser.cpp \
                                  src/lib/tsreader/Section.cpp \
                                  src/lib/tsreader/SectionDecoder.cpp \
                                  src/lib/tsreader/TSHeader.cpp \
                                  src/lib/tsreader/TSReader.cpp
libmediaportal_addon_la_LDFLAGS = @TARGET_LDFLAGS@

