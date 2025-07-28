---
title: Where do the default book names and abbreviations come from?
sidebar_position: 5
slug: /default-book-names
---



# **Where do the default book names and abbreviations come from?** {#23780858a4b68043a732f10834e01064}


If your books are in a Paratext project, the first place SAB will look for the book names is in the BookNames.xml file in the same folder as the USFM files. This file contains the names specified in the **Scripture Reference Settings** (found at **Project** → **Scripture Reference Settings…** within Paratext):


If your books are not in a Paratext project or if the Scripture Reference Settings are blank, SAB will look for the book names within the book files themselves. The USFM standard is to use **\toc2** for the short book name and **\toc3** for abbreviations:


\toc1 The Gospel according to Matthew        (long book name)


\toc2 Matthew                                                (short book name)


\toc3 Mat                                                         (abbreviation)


If Scripture App Builder does not find \toc2 or \toc3, it tries to guess the book name and abbreviation from \mt (main title) and \h (heading), but it is best to provide them in the toc fields.


![](/notion_imgs/default-book-names.23780858-a4b6-80b7-82cc-c81a7ae7b48d.png)


For the Digital Bible Library text release bundles, the book names come from the metadata.xml file within the bundle.


You can change the book names and abbreviations on the book page for each book found here:


**Books → [Collection Name] → [Book Name] → Book**.

