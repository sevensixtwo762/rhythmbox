pluginincludedir = $(includedir)/rhythmbox/plugins
plugininclude_HEADERS = rb-plugin-macros.h

SUBDIRS =						\
	audiocd						\
	audioscrobbler					\
	dbus-media-server				\
	generic-player					\
	iradio						\
	mmkeys						\
	mpris						\
	power-manager

if ENABLE_PYTHON
SUBDIRS +=						\
	artsearch					\
	im-status					\
	lyrics						\
	magnatune					\
	pythonconsole					\
	rbzeitgeist					\
	replaygain					\
	sendto						\
	rb

if WITH_WEBKIT
SUBDIRS += context
endif

endif # ENABLE_PYTHON

if WITH_LIRC
SUBDIRS += lirc
endif

if USE_IPOD
SUBDIRS += ipod
endif

if HAVE_LIBBRASERO_MEDIA
SUBDIRS += brasero-disc-recorder
endif

if USE_LIBDMAPSHARING
SUBDIRS += daap
endif

if USE_MTP
SUBDIRS += mtpdevice
endif

if ENABLE_FM_RADIO
SUBDIRS += fmradio
endif

if USE_CLUTTER
SUBDIRS += visualizer
endif

if USE_NOTIFY
SUBDIRS += notification
endif

if ENABLE_GRILO
SUBDIRS += grilo
endif
