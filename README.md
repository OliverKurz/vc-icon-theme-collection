VC Icon Theme Collection
========================
This is a complete collection of Linux icon themes.

![VC_Icon_Theme_Collection](https://github.com/OliverKurz/vc-icon-theme-collection/raw/master/images/Preview.png)

Installation Walkthrough
------------------------
1. Choose a Linux distribution that supports MATE, Xfce, LXDE, or LXQt.

2. `cd` into the directory the archive was cloned or copied to and enter the commands:

```
$ ./autogen.sh
$ make
$ sudo make install
```

3. From the Desktop Environment's Appearance Settings select an icon theme and apply it. In most cases the custom icon pack is applied.

4. If icons haven't changed, restart the file manager being used, or logout.

* Uninstalling the icon themes can be achieved by `cd`ing as admin into `/usr/share/icons` and searching for folders to delete with the name _Icons.

Known Issues
------------
1. Icon themes don't uninstall using `sudo make uninstall`.

2. SVG icons for folder-icon-color aren't scaling correctly in icon view when caja is set to a zoom ratio of 150% or higher in 17.10(1) (currently they appear about 50% smaller compared to other icons also at higher zoom ratios).

Credits
--------
Original icon designs by Mr GRiM, Razorsedge, Tsujan, and others.