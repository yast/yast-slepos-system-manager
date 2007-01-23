# Makefile.am for slepos-system-manager/src

yncludedir = @yncludedir@/slepos-system-manager

client_DATA =			\
	slepos-system-manager.ycp

ynclude_DATA =			\
	helps.ycp		\
	wizards.ycp		\
	dialogs.ycp		\
	subdialogs.ycp		\
	subwizards.ycp		\
	uifunctions.ycp		\
	routines.ycp

desktop_DATA =			\
	slepos-system-manager.desktop

module_DATA =			\
	SleposSystemManager.ycp

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA) $(desktop_DATA)

slepos-system-manager:
	ln -sf . slepos-system-manager

ycpchook = slepos-system-manager

include $(top_srcdir)/Makefile.am.common
