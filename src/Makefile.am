# Sources for snapper

module_DATA = \
  modules/Snapper.rb \
  modules/SnapperDbus.rb

client_DATA = \
  clients/snapper.rb

yncludedir = @yncludedir@/snapper
ynclude_DATA = \
  include/snapper/wizards.rb \
  include/snapper/dialogs.rb \
  include/snapper/helps.rb

desktop_DATA = \
  desktop/snapper.desktop

EXTRA_DIST = $(module_DATA) $(client_DATA) $(ynclude_DATA) $(scrconf_DATA) $(desktop_DATA)

include $(top_srcdir)/Makefile.am.common
