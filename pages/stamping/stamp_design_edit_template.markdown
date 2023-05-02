---
layout: page
title: Edit Stamp Design
permalink: /editstampdesign/
nav_order: 2
parent: Stamping
---

### Edit a Stamp Design

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/823046938?h=4ccfc51572&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="4 - Stamp Design"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

The default stamp design contains multiple elements, all of which are customizable.  The color, size, position, and content can be modified with with a few simple mouse clicks.

The StampBase element is selected by default, and this allows you to change the fill and border color of the stamp, the shape of the stamp corners (square or rounded), the border thickness, and the overall size.

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_01_defaultStampDesign.png)

Below, we have changed the fill color of the stamp from white to yellow.  An immediate change in the UI that should be noticable is that the Save icon has changed to red.  This is to alert you that the design of the stamp has changed and should be saved before moving to other tasks.

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_02_changeFillColor.png)

If you want to save the stamp with a different name, click the Save As button to the right of the Save button.  This will bring up a dialog box allowing you to enter a name for the new stamp.

<!-- > ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_03_saveChangesNotification.png) -->

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_04_saveWithNewName.png)

After saving the stamp with a new name, Defendant Exhibit in this case, we move on to the border settings.  Below you can see the realtime changes to the border thickness and corner shape with the controls below.

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_05_changeBorderWidthAndCorners.gif)

The StampBase element is the only compound element in the stamp.  That is, its contents impact multiple aspects of the stamp.  All of the other elements, Text elements, ExhibitID, and Lines, are edited individually.

When you have selected an individual element, the controls to modify its appearance change according to the type.  Additionally, slider bars appear to the left and bottom of the preview stamp.  You can modify each element's position by moving the horizontal or vertical sliders, as seen below.

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_06_selectAndMoveTextElement.gif)

By default, ExhibitMarker&trade; centers all elements.  Modifying the horizontal position will not change via the slider bars unless you first uncheck the Centered option.  Turning the option back on after you have moved an element will automatically recenter the element.

If you decide that an element is no longer needed, simply right-click on the element and select the Delete Element option.

You may also add new elements this way, in addition to the Add Line, Text, and Exhibit ID buttons above the Stamp Element list window.

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_07_deleteSelectedElement.png)

You can change the Text elements by selecting the element and editing the content of the Text box.  You can also modify the Font, Weight, Size and Color via the provided controls.

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_08_editTextElement.gif)

The ExhibitID element is a placeholder.  ExhibitMarker&trade; dynamically updates its content each time a new document is selected for stamping with the [Exhibit ID](../id_editing/id_editing.markdown) of the document.  We suggest that you enter a value that represents the longest ID in your document population, then modify the Font Size of the element to achieve the desired look of the stamp.

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_10_editExhibitIDPlaceholder.png)

The Line element can be repositioned in the same manner as the Text and ExhibitID elements.  When you select a Line element, new controls for modifying the Length and Thickness of the line are loaded.

> ![Screen Grab - Stamp Design Tab](../../assets/stamp_design_assets/editStampDesign_09_editLineElement.gif)

Be sure to click the Save or Save As button when you have completed the design.