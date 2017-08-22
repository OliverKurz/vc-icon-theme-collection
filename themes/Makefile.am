## Process this file with automake to produce Makefile.in
themesdir = /usr/share/icons
themes_DATA = \
    Blade_Icons.tar.gz \
    H2O_Icons.tar.gz \
    HUD_Icons.tar.gz \
    HUD_Machine_Blue_Icons.tar.gz \
    HUD_Machine_Green_Icons.tar.gz \
    HUD_Machine_Launch_Icons.tar.gz \
    HUD_Machine_Pink_Icons.tar.gz \
    HUD_Machine_Purple_Icons.tar.gz \
    HUD_Machine_Red_Icons.tar.gz \
    HUD_Machine_Slate_Icons.tar.gz \
    Magnum_Icons.tar.gz \
    Poison_Icons.tar.gz \
    Steampunk_Icons.tar.gz \
    Toxic_Blue_Icons.tar.gz \
    Toxic_Icons.tar.gz

EXTRA_DIST = $(themes_DATA) import.sh

#install the .tar.gz packages properly
install-data-hook:
	$(srcdir)/import.sh "$(DESTDIR)" "$(themesdir)"
