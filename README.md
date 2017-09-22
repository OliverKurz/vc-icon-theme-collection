VC Icon Theme Collection
========================
This is a complete collection of Linux icon theme ports.

![VC_Icon_Theme_Collection](https://github.com/OliverKurz/vc-icon-theme-collection/raw/master/images/Preview.png)

Installation Walkthrough
------------------------
1. Install a Linux distribution that supports any of the following Desktop Environments:
* MATE
* XFCE
* LXDE
* LXQt
2. cd into the directory this archive was cloned or copied into and type the following commands:

```
$ ./autogen.sh
$ make
$ sudo make install
```

3. In the Desktop Environment's Appearance Settings select the icon theme, and apply it. In most cases the icon pack should be fully applied.

4. If the icons haven't changed restart your file manager or logout.

5. Uninstalling these icon themes for now can be done by cding as administrator into the /usr/share/icons directory and searching for folders to delete with the tag _Icons.

Known Issues
------------
1. Icon themes do not uninstall using `sudo make uninstall`.

2. SVG icons for folder-icon-color aren't scaling correctly in icon view when caja is set to a zoom ration of 150% or higher in 17.10(1) (currently they appear about 50% smaller compared to other icons also at higher zoom ratios).

Credits
--------
Original icon designs by Mr GRiM, Razorsedge, Tsujan, and others.