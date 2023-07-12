---
layout: page
title: Destination Folder
permalink: /destinationfolder/
nav_order: 2
parent: Working With Files
---

### Destination Folder

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/823047327?h=6a4358a9a3&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="5 - New Destination for Stamped"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

#### __<u>Selecting a Destination Folder</u>__

As soon as you add documents to your new project, ExhibitMarker&trade; will prompt you to select a Destination Folder for the marked exhibits.  It is highly suggested that you select a folder other than the source folder, as this will enable you to undo stamps and brands should you make an error during the marking process.

> ![Animation - Select Destination Folder](../../assets/working_with_files_assets/working_with_files_01_SelectDestination.gif)

There are two options available via Settings that impact the Destination folder selection.  The first is [Preserve Folder Structure](#preserve-folder-structure-option), and the second is [Force Overwrite](#force-overwrite-option).

#### __<u>Preserve Folder Structure Option</u>__

This option is especially useful if you have a population of documents that have been broken up into folders for organizational purposes.

> ![Screen Grab - Preserve Folder Structure](../../assets/working_with_files_assets/working_with_files_PreserveFolderStructure.png)

When this option is selected, the current location of the original PDF files will be appended to the destination folder that you select for saving the marked exhibits.  For example, if your original files are located at:

> ```
d:\CaseName\Witnesses\Smith_John\Documents
```

and the selected output directory is

> ```
c:\CaseMaterials\Documents\Marked
```

The resulting path will be:

> ```
c:\CaseMaterials\Documents\Marked\CaseName\Witnesses\Smith_John\Documents
```

It is important that you pay close attention to the file paths that will be generated because of this option.  Windows has a limit on the number of characters allowed (260) for any given path.  To assist with this, ExhibitMarker&trade; will alert you if the specified output path using this option will exceed this limit.

#### __<u>Force Overwrite Option</u>__

> ![Screen Grab - Force Overwrite](../../assets/working_with_files_assets/working_with_files_ForceOverwrite.png)

This feature is for edge cases where there is an existing organization breakup of the folders, described above in [Preserve Folder Structure](#preserve-folder-structure-option), with the added catch that there are native documents (Excel, Word, Video, etc.) that need to be preserved as well.  In these instances, overwriting the source PDF is the only solution.

This is a feature that is available, but __not suggested__.  If you select this option, be sure to make a backup copy of your exhibits before you begin any Stamping or Branding of your documents.  There will be no way to undo any mistakes via the [Revert to Original](working_with_files_unmarking.markdown) option.