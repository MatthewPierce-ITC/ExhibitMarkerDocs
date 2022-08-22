---
layout: page
title: Locating Missing Files
permalink: /locatingmissingfiles/
nav_order: 5
parent: Working With Files
---

### Locating Missing Files

After the project is created and files are added, there may be instances where some or all of the files are moved.  Each time ExhibitMarker&trade; opens a project it checks all the individual file paths for each PDF that is currently loaded.  If a file is not present at the recorded location, ExhibitMarker&trade; will alert the user by highlighting the file in yellow and placing exclimation points in the Status columns for the PDF.

> ![Screen Grab - Missing Exhibits](working_with_files_assets/working_with_files_locatingmissing_01_lostpdfs.png)

Additionally, the user my manually initiate file locaiton verification via the Project menu by selecting Verify File Locations.

> ![Screen Grab - Missing Exhibits](working_with_files_assets/working_with_files_locatingmissing_06_projectmenuverifylocations.png)

To recitfy the situation, select and right-click the missing files in the PDF Files list.  Choose the Locate Missing Files option, which will bring up a Folder selection dialog.

> ![Screen Grab - Locate Missing Files Folder Dialog](working_with_files_assets/working_with_files_locatingmissing_03_selectnewlocationfolder.png)

After selecting the new location where the files are currently located, ExhibitMarker&trade; will verify that the missing files are indeed there and update the database accordingly.

> > ![Screen Grab - All Files Located](working_with_files_assets/working_with_files_locatingmissing_04_allfileslocatedmessage.png)

If all or some of the files are not in the selected location, ExhibitMarker&trade; will notify the user how many were located.

> > ![Screen Grab - All Files Located](working_with_files_assets/working_with_files_locatingmissing_05_somefileslocated.png)

Once complete, each entry in the PDF Files list will be updated to remove the missing highlight indicator and exclimation points.

> ![Screen Grab - All Files Located](working_with_files_assets/working_with_files_locatingmissing_07_foundpdfs.png)