---
layout: page
title: Batch Process ID Editing
permalink: /batchidedit/
nav_order: 2
parent: ID Editing
---

### Batch ID Editing

Batch editing of Exhibit IDs is done via the Rename ID tab.  Click View > Batch Rename ID to display the Rename ID tab.

> ![Screen Grab - Rename ID Tab](id_editing_assets/idedit_02_renameidtab.png)

In our example, we will be removing the text after the hyphen in the ID field.  To do this, first enter the search text in the Find What field.  It is important to note that spaces must be accounted for.  While in this example we want to remove the text to isolate the ID, if just the hyphen is used this will leave two spaces.

> ![Screen Grab - Find Space Hyphen Space](id_editing_assets/idedit_03_findspacehyphenspace.png)

```
US Ex. 0001 - Microsoft's Actual and Projected Share of PC Operating System Market
US Ex. 0002 - Microsoft's Share of the Browser Market
US Ex. 0003 - MIcrosoft's Share of the Browser Market
US Ex. 0004 - Microsoft's Share of the Browser Market
US Ex. 0005 - Microsoft's Share of the Browser Market Compared to Netscape's Share
```

For the Action option, select **Remove Everything After, including search text**

> ![Screen Grab - Remove Everythying After](id_editing_assets/idedit_04_removeeverythingincluding.png)

With an exhibit selected, clicking the Preview New ID button will generate an example of what the new Exhbit IDs will look like.  It is highly recommended that you test several of the exhibits if you have complicated naming structures for the exhibits, as the batch rename process is not an operation that can be undone.

Once statisifed with the search and replace parameters, click the Apply button.  A pop-up winidow will indicate when the operation is complete.  The resulting Exhibit IDs should now look like this:

```
US Ex. 0001
US Ex. 0002
US Ex. 0003
US Ex. 0004
US Ex. 0005
```