## The libraries

Now that you have installed Asset Management, the first thing to do is to take care of your libraries.

2 cases are possible.

   * The first is that you have upgraded the addon and you need to retrieve your libraries.
   * The second is that you are a new user and you will need to create your 
     first library.
   

### 1. Recover my libraries

If you are an old user of Asset Management (before Blender 2.80) and have 
enabled the _"use custom filepath"_ option in the preferences, you can 
retrieve the library paths stored in the _"custom_filepaths"_ file.

Open the libraries options (the gear on the right) and click on 
the operator _"Load Blender 2.79 libraries"_

<img src="http://blscripts.com/asset_management_doc/images/LOAD_BLENDER_2_79_LIBRARIES.jpg" />

The filebrowser will open then, navigate to the _"extra_files"_ folder of 
your old main library.

Finally, double click on the _"custom_filepaths"_ file

<img src="http://blscripts.com/asset_management_doc/images/CUSTOM_FILEPATHS.jpg" />

!!! info " Info"
    
     If you can't find the _"custom_filepaths"_ file, don't worry. You may 
     simply not have enabled the _"use custom filepaths"_ option. You will 
     just have to load your old libraries manually as described in the 
     next paragraph.

### 2. Load/Create library

!!! error " **CAUTION !**"
    
     Asset management requires a certain hierarchy of starting folders.
     If you want to create a virgin new library, add a new folder from the 
     filebrowser. <font size="+1"><strong>Don't use an existing folder not created by the addon</strong></font>.

     If you want to add an existing library, <font size="+1"><strong>select one created by the addon</strong></font>.

To load an existing library or to create a new one, the basis is the same.
Open the libraries options (the gear on the right) and click on 
the operator _"Load/Create library"_

<img src="http://blscripts.com/asset_management_doc/images/LOAD_CREATE_LIBRARY.jpg"/>

The filebrowser will open.

Navigate to the location of your library. If you want to create a new one, add a folder via the operator provided.
double-click on the library, add the asset types you need then, click on 
_"Load/Create library"_ at the bottom of the file browser.

CREATE A NEW LIBRARY

<img src="http://blscripts.com/asset_management_doc/images/CREATE_NEW_LIBRARY.jpg"/>

LOAD EXISTING LIBRARY

<img src="http://blscripts.com/asset_management_doc/images/LOAD_EXISTING_LIBRARY.jpg"/>

