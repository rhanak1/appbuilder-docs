---
title: How can I include pictures in my apps?
sidebar_position: 7
slug: /how-to-include-pictures
---



# How can I include pictures in my apps? {#23780858a4b680c6b647f834c0417e2b}


You can include JPG or PNG image files in the text of the app. There are a few ways of doing this:


_**Method 1: Specify the image filenames within the Paratext USFM or USX files**_


The app recognises the USFM illustrations markers \fig…. \fig*:


**\fig** DESC|<u>**FILE**</u>|SIZE|LOC|COPY|<u>**CAP**</u>|<u>**REF**</u>**\fig***


i.e. 7 parameters, separated by six vertical line characters.


The only required parameter is FILE – the filename. If the file extension is .tif, the app will look for a file with the same name but with a .png or .jpg extension instead.


You can optionally include captions (CAP) and chapter/verse references (REF).


Examples:


\fig |picture1.jpg||||This is a picture|5:3\fig*


\fig |picture2.tif||||This is another picture|\fig*


\fig |picture3.jpg|||||\fig*


\fig picture3.jpg\fig*


Add the image files to the **Media** → **Illustrations** page of Scripture App Builder so they can be included in the app.


_**Method 2: Include the images inside a Word document**_


If your book is specified by a Word document, you can embed the images directly in the  document between the lines of text.


_**Method 3: Use the image placement feature**_


You can tell Scripture App Builder to place an image at a certain point in a text without modifying the source file for the text. To do this:

1. Go to the **Media** → **Illustrations**
2. Click Add Image and select the image file(s) to add. Then do one of the following:
3. Either Double-click on each image in the table, select the **Placement** tab, and click **Add Placement…** to specify where the image should be placed in the text, OR specify a reference to the image in a book file, using either the **\img** marker (which places the images at the top of the page and lets the text scroll independently underneath) or the **\fig…\fig*** marker which puts the image in the text at the specified place (and it will scroll with the text). See _Picture Story Books_ for more info on adding images in SFM (text) files.

The images will be included in the app assets and compiled into the final APK, so try to keep them as small as possible.

