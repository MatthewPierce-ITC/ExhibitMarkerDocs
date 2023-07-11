---
layout: page
title: Rebuild PDF File
permalink: /rebuildpdffile/
nav_order: 6
parent: Working With Files
---

### Rebuild PDF File

The Portable Document Format (PDF) has been around for decades, and its specifications are quite voluminous.  There are also hundreds of third-party tools available to generate PDFs, but not all of these tools are created equal.

There are times when, for a multitude of reasons, a PDF file will not accept a Stamp or Brand correctly.  A Stamp might be placed in the bottom right corner of a document, but after saving, it appears in a different location, perhaps with altered dimensions ("squished", according to some reports).  These anomalies are often due to how the PDF was initially generated.  In most cases, they result from exporting a document to PDF from another program, like Excel.

If a Stamp or Brand does not appear as it did in the preview after being applied and saved, a "Rebuild PDF" operation could solve the problem.  First, revert the PDF to its original form, then right-click on the PDF and select "Rebuild PDF."  

> ![Screen Grab - Right-Click Menu - Rebuild PDF option](../../assets/working_with_files_assets/working_with_files_rebuildpdf_01_menuitem.png)

This operation will recreate the PDF from scratch.  That is, the existing PDF will be exported as individual, high-resolution TIFF images, and then a new PDF with the same filename will be created from these images in the same location.

It's important to note that this is a processor-intensive operation, which may take quite some time to complete.  The larger the PDF (in terms of both physical dimensions and page count), the longer the operation will take.  This is another reason why we have limited this to a single-PDF operation, rather than selecting a group of PDFs for rebuilding.  The dialog window that appears during the rebuild process will update you as the process moves through the required operations.

> ![Screen Grab - Right-Click Menu - Rebuild PDF option](../../assets/working_with_files_assets/working_with_files_rebuildpdf_03_rebuildprogress.png)

Also, files processed in this manner often increase in size - sometimes significantly. Please check the resulting file size after the operation; if it's too large for your purposes, use existing Adobe Acrobat tools to reduce the PDF size before you apply a Stamp or Brand for optimal results. This action, performed inside Acrobat, should have no impact on the ability to Stamp and Brand the resulting PDF. However, if the original document contained OCR, you will need to re-OCR the document.