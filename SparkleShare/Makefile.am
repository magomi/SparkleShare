SUBDIRS =	\
	Nautilus \
	Mac

ASSEMBLY = SparkleShare
TARGET = exe

LINK = $(REF_SPARKLESHARE) $(NOTIFY_SHARP_LIBS) $(WEBKIT_SHARP_LIBS)


SOURCES =  \
	SparkleAbout.cs \
	SparkleBubble.cs \
	SparkleController.cs \
	SparkleEntry.cs \
	SparkleInfobar.cs \
	SparkleIntro.cs \
	SparkleInvitation.cs \
	SparkleLinController.cs \
	SparkleLink.cs \
	SparkleLog.cs \
	SparkleShare.cs \
	SparkleSpinner.cs \
	SparkleStatusIcon.cs \
	SparkleUI.cs \
	SparkleUIHelpers.cs \
	SparkleWindow.cs

include $(top_srcdir)/build/build.mk

bin_SCRIPTS = sparkleshare

dist_man_MANS = $(top_srcdir)/man/sparkleshare.1

Applicationsdir = $(datadir)/applications
dist_Applications_DATA = sparkleshare.desktop
