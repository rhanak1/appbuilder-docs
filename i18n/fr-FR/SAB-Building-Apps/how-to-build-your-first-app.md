---
title: How to build your first app
sidebar_position: 2
slug: /how-to-build-your-first-app
---

# How to build your first app {#23380858a4b680bf9ccce752dbc11638}

To build your first app with Scripture App Builder, you should use the **New App** wizard.

:::note

_The wizard will offer many choices in setting up your app. If you do not yet know exactly what you need, just choose the default option for now. All the app elements can be added or modified later within SAB, before you publish the app. Each page in the wizard will have explanatory text to help you in choosing options._

:::

1. Launch **Scripture App Builder** from its icon on the desktop.
2. Click **New App** on the toolbar. The New App wizard will appear.

:::note

_If this is your very first app, or you have no projects opened in SAB, the_ _**New App**_ _button will show in the middle of screen._

:::

3. On the first page of the wizard, specify the **App Name**, such as “Dogon Bible”, “Livre de Luc”, “Supyiré NT”, etc. This is the main title of your app and will appear under the app icon on the user’s phone. Do not include underscores or hard to understand abbreviations and try to keep the length under about 20 characters. (You can modify this later under **App** → **App Name**.)

Click **Next** to move to the next page.

4. On the second page of the wizard, specify the **Package Name**-a dot-separated string which uniquely identifies your app. (You can modify this later under **App** → **Package**.)

More details about choosing a good package name can be found in the section _How should I choose the package name?_

Click **Next** to move to the next page.

5. On the **Book Type** page, choose if you want an app with text or an audio-only app. Most Scripture apps will have text. If you choose audio-only, the wizard will present several screens asking which books you want to add and which image you want to display while the audio is playing. Then continue with step 7.

6. If you choose to add books with text, the next page of the wizard is titled **Books.** Click **Add Books…** and select the books you want to see in the app. These can be USFM (Paratext) files, USX files, Digital Bible Library text release bundles, Word documents (docx) or a zipped file of USFM or USX files. (You can add more books later under **Books** → [**Collection Name**] → **Book Collection →** **Add Books**.)

Click **Next** to move to the next page.

7. If you have selected Scripture books, the next page will be titled **Book Order**. Choose the book ordering according to the church tradition of the target users. (You can modify this later under **Books** → [**Collection Name**] → **Book Order**.)

Click **Next** to move to the next page.

8. If the book names are in all-caps, the next page of the wizard is titled **Book Names** and will allow you to change them to mixed case if desired.

Click **Next** to move to the next page.

9. On the page of the wizard titled **Language**, specify the language code and name of the main language used in the app. Click **Select…** to choose the language code from a list of languages. If required, select the checkbox to specify additional identification information, such as the script, region and variant. (You can modify this later under **Books** → [**Collection Name**] → **Language**.)

Click **Next** to move to the next page.

10. On the **Copyright and Licensing** page, specify the copyright and licensing information that you would like to appear on the About box in the app. This includes the copyright owner for the text. Use the **Copyright Helper** wizard to help you.

If you do not know what to put here, please ask the publishing department of your organization for advice. They will want to make sure you get this right and do not simply make a guess as to what to include. (You may add this information at a later time if you do not have it available right now under **Books** → [**Collection Name**] → **Copyright & Licensing**. Also see more on where and how to include copyright information in the _About Page_ section.)

Click **Next** to move to the next page.

11. On the page of the wizard titled **Font**, choose the font. You can either select from the given list of fonts or specify a different TrueType font file. (You can modify this later under **Appearance** → **Fonts →** **Main Font**.)

Click **Next** to move to the next page.

12. If this next page is titled **Choice of Fonts**, choose some more fonts to add to the app. The app user will be able to change the default font to one of these fonts in the font chooser and in the Verse on Image editor. (You can modify these settings later under **Appearance** → **Fonts →** **Font Files**.)

Click **Next** to move to the next page.

13. On the page of the wizard titled **Font Handling**, you can select GeckoView if you know that the standard Android components will have trouble displaying the text correctly (e.g. if it is a complex script). (You can modify this setting later under **Appearance** → **Fonts →** **Font Handling**.) More information on GeckoView can be found in the _Fonts_ section of this document.

Click **Next** to move to the next page.

14. On the page of the wizard titled **Color Scheme**, choose the color scheme for the app. The color you choose is the one that will be used for the main app bar. (You can modify this later under **Appearance** → **Colors →** **Color Scheme**.) Individual colors for text, titles, links, backgrounds, etc. can be customised later.

Click **Next** to move to the next page.

15. On the page of the wizard titled **Default Interface Language**, choose the language you want users to see when they first enter the app (the language for the app menus). This can be the current system language, but you can specify a default language just in case--perhaps a _language of wider communication_. (You can modify this later under **Appearance** → **Interface →** **Languages**.)

Click **Next** to move to the next page.

16. On the page of the wizard titled **Interface Languages**, choose the app interface languages that the user can choose between in the app settings. (You can modify this later under **Appearance** → **Interface**.)

Click **Next** to move to the next page.

17. On the page of the wizard titled **Features**, choose the features you want to enable in the app.

You can modify the details for the Verse of the Day (and the Daily Reminder) later under **Engagement** → **Notifications**.

You can modify the details for saving as a video later under **Engagement** → **Verse on Image**.

:::note

_If you have audio versions of the books in your app, you have the option of allowing users to share verse audio with others. They can also share a video that combines the text and audio together. See_ _**Configuring Verse on Image in the App Builder**_ _for more details._

:::

Click **Next** to move to the next page.

18. On the page of the wizard titled **Icon**, choose the application launcher icon. You can select one of the images in the table or if you have your own PNG image files for the icon, click **Browse** and select them. (You can see more options for creating an icon and/or modifying the icon later under **Appearance** → **Icons**.)

Click **Next** to move to the next page.

19. On the page of the wizard titled **Signing**, you need to specify the keystore and alias to use to sign the app. A keystore is a digital certificate file that ensures the app is legitimate. An app must be signed in this way so that it can installed on a phone.

If you already have created a keystore for another app, see _reusing a keystore_. If you do not already have a keystore file (which you are unlikely to have if this is your first time using the program):

i. Click **Create KeyStore**.

ii. Enter a new filename for the keystore, such as “keystore1.” Specify a password. Click **Next** to continue.

iii. Enter an alias name for a key to create within your new keystore, such as the default “key1”. Specify a password, which can be the same as the password you entered on the previous page.

:::note

_It is very important to securely store the password for your keystore. Once the app is published, it cannot be updated without the keystore password. Make sure someone else in your organization has access to the app keystore passwords._

:::

Click **Next** to continue.

iv. On the **Certificate Issuer** page, provide details of your organisation in at least one of the fields. Click **Next** to continue.

v. A new keystore will be created for you. Click **Close**.

20. Back on the **Signing** page of the New App wizard, you need to specify the keystore password, select the key alias and enter the alias password--just as you entered them in the step above. (You can modify your keystore settings later under **App** → **App Signing**.)

Click **Next** to continue.

1. On the page of the wizard titled **Project**, you can enter or modify the project name and add an optional description of the app project. Neither of these will be visible to the user of your app. They are just for your own use and might help you distinguish between multiple app projects. (You can modify this later under **App** → **Project**.) See the _Project section_ under the explication of the App menu.

:::note

_SAB will create a project folder using the title of your project. It is recommended that you don’t include any special characters in the project name as they may not be compatible with the folder name rules._

:::

Click **Finish** to continue. The New App wizard will close, and the app project definition will be added to the tree view on the left of the screen.

Take a look at each of the app configuration pages by selecting them in the tree view on the left. Look in each of the tabs on each page to verify that you have the settings you want. You can always go back to them later to change them if you find you need to make modifications to fonts, colors, styles, etc.

When you have finished configuring the app, click the **Build Android App** button on the toolbar at the top of the screen.

If something is not configured correctly for the build to work, you will be notified.

:::note

_If you need to see the error information at a later time (e.g. to send to one of the support staff for help), you can find it on the menu bar under_ _**Tools**_ _→_ _**View Logs… →**_ _**Error Log**__._

:::

A compilation window will appear. Wait while the app is compiled. It may take several minutes or more.

The first time the build process is run, the compiler needs to connect to the internet to download some files. After this, subsequent app builds will not require internet access. See **Tools** → **Settings…** → **Build Settings** to turn on offline mode after the first app build.

If the build succeeds, you will have a new APK file – the installation file for an Android app.

:::note

_To understand more about where SAB stores files like your APK file, see_ _**How SAB stores your project data files**__._

:::

The next section describes how to copy this APK file to your phone and launch the app

