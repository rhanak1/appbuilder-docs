---
title: Creating Deep Links
sidebar_position: 2
slug: /creating-deep-links
---

# Creating Deep Links {#23980858a4b680cdbbdec09d277bca97}

This section explains how you create deep links to content in the app. We will look at how to specify Bible references (books, chapters, verses), book collections, and how to turn the audio toolbar on when the app opens.

_**Specifying Bible references in a deep link**_

A reference is specified in the form BBB.C.V, where BBB is the book ID, C is the chapter number and V is an optional verse number.

Examples:

LUK.15             Luke chapter 15

JHN.3.16          John chapter 3 verse 16

EPH.2.8            Ephesians chapter 2 verse 8

Please note that:

- The reference is case insensitive, so luk.15, Luk.15 and LUK.15 are all recognised as referring to Luke chapter 15.
- The app will recognise [OSIS book abbreviations](https://wiki.crosswire.org/OSIS_Book_Abbreviations) as well as Paratext codes, such as Luke.15, 1Thess.3.5, 1Pet.2.

There are two ways of specifying the reference in a deep link:

**Method 1:** Append the reference immediately after the link scheme, e.g.

mamara-bible://JHN.3.16

https://mamara.org/bible/JHN.3.16

**Method 2:** Specify the reference in a query string, after ‘?’ and ‘ref=’, e.g.

mamara-bible://?ref=JHN.3.16

https://mamara.org/bible?ref=JHN.3.16

When someone taps on this link, the app (if installed) will open at the specified book, chapter and verse, using the currently selected layout and book collections.

_**Specifying book collections in a deep link**_

You can specify a book collection in the deep link, using a reference of the form DDD/BBB.C.V, where DDD is the book collection ID.

Here are some examples:

mamara-bible://MYK/JHN.3.16

https://mamara.org/bible/MYK/JHN.3.16

https://mamara.org/bible?ref=MYK/JHN.3.16

If you specify a book collection, the app will ensure that this book collection is being displayed:

- If the app is in single pane layout, the book collection will be changed to the specified collection if it is not there already.
- If the app is in two pane or verse-by-verse layout, and if the specified book collection is not among the two or three on the screen, the layout will be changed to single pane with the specified book collection.

_**Turning on the audio toolbar in a deep link**_

You can turn on the audio toolbar when the app launches, with the addition of the **audio=1** parameter in the query string of the deep link.

Here are some examples:

mamara-bible://JHN.3.16?audio=1

https://mamara.org/bible/MYK/JHN.3.16?audio=1

Note that a query string begins with the question mark (?) character before the first parameters, and then an ampersand (&) before subsequent parameters. So if you are using the ‘ref=’ method of specifying a reference, you will need to use ‘&’, e.g.

mamara-bible://?ref=JHN.3.16&audio=1

https://mamara.org/bible?ref=JHN.3.16&audio=1

