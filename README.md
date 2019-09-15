# Asset Management Blender 2.8
v2.4.6
* The IBL options are now displayed for Cycles too in the world panel
* Auto pack for the textures after exporting the asset
* Added an operator to turn the ibl on the Z axis directly from the viewport
 (CTRL+SHIFT+MIDDLEMOUSE by default)
 ---
v2.4.5
* From now, clicking on the name of a category displays its subcategories in
 addition to always passing it to the active category. The operation of the
 arrow on the left remains unchanged
* Added OpenGl render for scenes thumbnails (with and without camera)
* Removed OpenGl render for materials thumbnails
* Fixed bug exporting collections that shouldn't be exported
* Added option to import the mesh type asset to the 3D cursor if there's no
mesh or no selection in the scene
---
v2.4.4
* Removed "Edit asset" option for hdri asset.
* Added "move category" function to move the active category to another
category.
Also works if the category is in another library.
* Modification of the order of display of asset types to match the version
prior to 2.8
* Fixed bug displaying the preview in alphabetical order after adding an asset
* Added OpenGl render for thumbnails
---
v2.4.3
* IBL setting were moved in the World panel.
* Added the rename asset function.
* Fixed the overlapping faces between assets and ground with the auto
thumbnail rendering.
* Added "move asset" function to move the active asset to another category.
Also works if the category is in another library.
---
v2.4.2
* Fixed the bug for asset export with "Thumb" option enabled that display the
asset in duplicate in the preview with the "replace" option activated.
* Fixed the bug when exporting collections that sent all the objects present
 in the collection (even those not selected)
* Deleting the "blends" and "hdri" folders if the latter are empty (to avoid
 an empty preview)
 ---
v2.4.1
* Fixed bug for asset export with "Thumb" option enabled that did not save
the filename in the addon data
---
v2.4.0
* Little changes in the UI
  * removed ".blend" in the preview assets name
  * assets type take a little more place
* The asset's collections are now kept when we add or import them in the 
library
* Fixed bug when an asset is added with an empty
* Added asset rendering settings in the preferences
---
v2.3.9
* fixed a bug that prevented to display the "Add asset type" panel if the library did not already have at least 1 asset type
* fixed release note display bug
* changed delete confirmation from "CONFIRM" to "YES"
* Added auto thumbnail rendering for assets
* Removed "library path" from the preferences and replaced by a button to 
search the file "custom_filepaths" to add the old 2.79 libraries 
* Added youtube link for installation
---
v2.3.8
* changed of the "library_path" property in the preferences that was confusing.
You now have to select the "custom_filepaths" file to add your old libraries.
This file is located at "your_old_main_library/extra_files/custom_filepaths"
* added options for mesh assets
   * Selected objects: Add selected objects if enabled else, only active object
   * Parents: Automatically adds all the object's parents from the hierarchy
   * Childrens: Automatically adds all the object's childrens from the 
   hierarchy
* fixed bug on the asset name when multiple preview are displayed
---
v2.3.7
* Added auto thumbnail rendering for materials
---
v2.3.6
* fixed bug on the setup previous settings if the library haven't got any 
asset type
* fixed bug on the add new library
---
v2.3.5
* fixed import bug with several preview displayed
* resize preview to the maximum width of the N panel
---
v2.3.4
* link datas in the scene when we use the editing asset tool
* remove the invalid libraries from the database
* "lock import" added (to avoid importing an asset when you choose in the preview)
* fixed bug when exporting ibl to the library
---
v2.3.3
* Added replace asset with an option to use the existing thumbnail
* Added a ALT+click on any category to hide the hierarchy
* Fixed bug on the rename category
* Added edit asset tool
---
v2.3.2
* added preview visibility in the hierarchy
* fixed bug if the active category of the previous blender session was deleted
* added an error report if the targeted material is not found in the .blend 
(in case of the material in the .blend does not have the same name as the 
thumbnail)
* fixed bug on adding ibl asset
---
v2.3.1
* auto path correction for "From computer" thumbnails
* fixed bug for thumbnail in "Rendered" mode if it's different from "Render Result"
* Reset the update of the "library_path" property to update the json
---
v2.3.0
* New hierarchy system to replace collections/categories
* Remove assets
* Displaying several previews
---
v2.2.9
* Export IBL with auto thumbnails render
* Export scenes asset with rendered (in image editor) or existing thumbnail 
(on your computer).
* Moved "Preview size" and "Popup icon size" from assets to thumbnail 
preferences.
---
v2.2.8
* Export material asset with rendered (in image editor) or existing thumbnail 
(on your computer).
* Added option in the tool panel to display the IBL settings from meshes, 
materials and scenes asset type.
---
v2.2.7
* Fixed bug when creating a category that did not display the default icon
* Fixed poor management of invalid libraries
* Draw enum items in alphabetical order
* Set the newest asset as active in the preview
* Delete the default icon if the category is empty when adding a new
 asset
 ---
v2.2.6
* Fixed the bug that prevented the libraries from being displayed correctly 
* Added list of lost libraries in the addon preferences
* Link for asset's collections (like groups for 2.79)
* Export mesh asset with rendered (in image editor) or existing thumbnail 
(on your computer).
* Added options for preview size and popup icon size
---
v2.2.5
* Fixed preview's bug that did not display the content of some categories
---
v2.2.4
* fixed bug for the categories (Beyond the first 9 collections, the categories 
were no longer displayed)
* fixed bug due to the bl_idname of the class menu
---
v2.2.3
* automatic update detector
* library manager
* import/link assets
