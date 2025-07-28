---
title: Deferred Deep Linking
sidebar_position: 3
slug: /deferred-deep-linking
---



# Deferred Deep Linking {#23980858a4b68063ae1eed8e63e43aa3}


The deep links described above will only work if the user already has the app installed. If they do not have the app, when they tap on the link, their device will not recognise it and an error message will appear.


**Branch** ([branch.io](https://www.branch.io/deep-linking/)) provides a way of handling **deferred deep links**. If a user taps on a link to the app but does not have the app installed yet, the link will first redirect the user to the app store to download the app. Then after the app is installed and launched for the first time, the user will be taken to the deep link page.


_**Setting up the app to use Branch**_


To use Branch for deferred links:


1. Go to the **Branch** website, [https://branch.io/](https://branch.io/) and **Sign Up** for an account if you do not already have one.


2. Create a new app in the Branch dashboard.


3. Go to the **Link Settings** page, find the **Android** section and click the checkbox ‘I have an Android App’.


4. Enter the custom URI scheme and where to download the app (e.g. on Google Play).


5. Within Scripture App Builder, go to the **App** Ø **Deep Linking**


6. Select **Use Branch for Deferred links**.


7. Enter the **Branch Key** for this app. This can be found on the **Account Settings** page in Branch and will be something like:


key_live_abCdEF2GQ7ID9rLPlxk91khczmpGZl71


8. Enter the **Default Link Domain** for this app. This can be found on the **Link Settings** page in Branch and will be something like:


mamara-bible.app.link


_**Creating deferred links**_


Deep links using Branch will look something like this:


https://mamara-bible.app.link?ref=JHN.3.16


where mamara-bible.app.link is the **Default Link Domain** specified on the Branch **Link Settings** page.


Please note that you need to use the **?ref=** method of specifying the reference. You cannot use https://mamara-bible.app.link/JHN.3.16.

