---
title: Paratext files for Bible books
sidebar_position: 1
slug: /paratext-files-for-bible-books
---



# Paratext files for Bible books {#23380858a4b6805a9985db70aba087b3}


SAB can import text from Paratext USFM (Unified Standard Format Marker) files. These are the files used in Paratext projects – one per book of the Bible. See example below:


> \c 5  
> \s Kilɛ Kafila yɛrɛ lemu lʼa pye faaboboŋɔ ki ɲuŋɔ ni ge  
> \p  
> \v 1 Ayiwa, ba Yesu ya sipyiire ti ɲa wɛ, na dugi tiin faaboboŋɔ ki ɲuŋɔ ni. A wu wo kalaapiire tʼi fulo wu na.  
> \v 2 A wu ɲɔ kɔn na pu kalaa na:  
> \s Piikɛ pʼi ɲɛ duba nagoo pu wɛ?  
> \r (Luka 6:20-23)  
> \q1  
> \v 3 «Piimu pʼa li cɛ na funmɔ fɛɛ pee ɲɛ  
> \q2 Kilɛ shizhaa na ge,  
> \q2 pee ɲɛ duba nagoo,  
> \q1 bani pee wuuro ti ɲɛ  
> \q2 fugba saanra te.


In USFM files, the chapters, section headings and paragraphs are marked by standard format markers such as \c, \s and \p. For more details, please see [http://paratext.org/about/usfm](http://paratext.org/about/usfm).


For more information about how SAB and Paratext work together, see _Using SAB with Paratext files_.


It is recommended that you run the Paratext Basic Checks to ensure the text is as clean as possible for publishing. Select **Checking** → **Run Basic Checks…** from the Paratext main menu.


Critical checks:

- **Chapter/Verse Numbers**: Checks for duplicate or invalid chapter or verse numbers. Checks that all chapters and verses defined in the versification for the project are present.
- **Markers**: Checks you are using valid USFM markers and they are not in unexpected places.
- **References**: Checks that Scripture references, e.g. “Mat 6:1-5”, follow exact abbreviations and syntax. If not, they will not work as links in the app.

Important checks:

- All of the remaining basic checks: Characters, Punctuation, Capitalization, Repeated Words, Unmatched Pairs of Punctuation, Quotations, Numbers.
- **Spelling**: In Paratext, select **Checking** → **Spell Check Current Book…**
