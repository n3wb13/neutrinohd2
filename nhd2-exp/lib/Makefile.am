SUBDIRS = \
	connection \
	libeventserver \
	sectionsdclient \
	timerdclient \
	libconfigfile \
	libmd5sum \
	libnet \
	libxmltree \
	libtuxtxt \
	libdvbsub \
	libupnpclient \
	jsoncpp

if !BOXTYPE_COOLSTREAM
SUBDIRS += libdvbapi
endif

if !ENABLE_GSTREAMER
SUBDIRS += libeplayer3
endif

if ENABLE_LCD
SUBDIRS += liblcddisplay
endif





