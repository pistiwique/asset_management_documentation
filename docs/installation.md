## Requirements

* Windows, MacOS or Linux
* Blender 2.93(LTS), Blender 3.0

!!! error " Experimental and custom builds"

    Experimental versions and custom builds are not supported. This doesn't 
    mean that the addon will not work properly, just that bug fixes will 
    not be made for these versions of blender.

!!! info " Support"
    
    If you need to contact us to report an error or misbehavior of the 
    addon, please follow these instructions.
    [Support](support.md)


### 1. Fresh installation

   * start blender and go to the preferences
   * in the "Add-ons" tab, click on the **"Install..."** button on the top right
   * navigate to the asset_management.zip file and double-click it
   * activate the addon by ticking the checkbox
   * save your preferences (if you have disabled the automatic saving option)

### 2. Update installation

   * deactivate the addon by unchecking the box and save the preferences (if you have disabled the automatic saving option).
   * remove the addon by clicking on the **"Remove"** button at the bottom 
     right of the addon preferences
   * <font size="+1" color=red><strong>restart blender</strong></font> and 
     go to the preferences
   * in the "Add-ons" tab, click on the **"Install..."** button on the top right
   * navigate to the asset_management.zip file and double-click it
   * activate the addon by ticking the checkbox
   * save your preferences (if you have disabled the automatic saving option)

### 3. Installation of the Pillow module (Recommended)
Since the 2.6.0 version, Asset management integrates the <a href="https://github.com/3dninjas/3dn-bip" target="_blank">3dn-bip</a>
module which allows to load thumbnails instantly.

This module needs the Pillow library to work. To install it, just click on 
the button provided in the addon preferences (This operation need few 
secondes).

<img src="http://blscripts.com/asset_management_doc/images/INSTALL_PILLOW.jpg" />

To take in account the changes, please <font size="+1" color=red><strong>restart blender</strong></font>

!!! info " Info"
    
     The Pillow module is not required for the addon to work.
     If you don't want to install it, the icons will simply load more slowly.

     If you don't see the operator, it simply means that the Pillow module 
     is already installed
     