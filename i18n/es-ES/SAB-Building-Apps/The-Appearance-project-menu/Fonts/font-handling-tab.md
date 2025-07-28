---
title: The Font Handling tab
sidebar_position: 3
slug: /font-handling-tab
---

# The Font Handling tab {#23880858a4b68040aa5cc7d59b04513a}

Use the Font Handling tab to activate the GeckoView font handling component. If you are using a non-Roman script or a Roman script with combining diacritics, it is possible that Android devices will not display your fonts correctly. To overcome these problems, try using the GeckoView library.
GeckoView is a viewer component from Mozilla that replaces the standard Android viewer. It can render Graphite fonts correctly.
In the screenshots below, the standard viewer is used in the left image and GeckoView is used in the right image. Notice the dotted circles on the left, indicating that the font is not being rendered properly.

![](/notion_imgs/font-handling-tab.23880858-a4b6-80fa-a6d0-dfde0d5cd416.png)

_Using the standard viewer_

![](/notion_imgs/font-handling-tab.23880858-a4b6-8030-9b0f-d63782e768d5.png)

_Using GeckoView_

The required GeckoView library files will add at least 55 MB to your app size, so do not enable GeckoView unless you know you need it to display your fonts correctly.

You will find that when you build an Android APK with GeckoView, the APK size will be at least 200 MB larger than without GeckoView. This is because it contains the GeckoView libraries for four different device architectures (32-bit ARM, 64-bit ARM, 32-bit Intel and 64-bit Intel). In practice, your app users do not need to install such a large file.

- For **online app distribution**, you need to upload an AAB file (app bundle) to Google Play rather than an APK. The AAB file contains all the GeckoView libraries for all four device architectures, but when a user installs an app from Google Play, Google will create a tailored APK for them, with just the libraries and components their phone needs. The AAB file might be over 300 MB, but the actual size of the app for any user will be much smaller.
- For **offline app distribution**, you can ask for Scripture App Builder to create multiple APKs, one for each device architecture. Do this on the **App** → **APK** Each of these APKs will be significantly smaller (around 55 MB extra for GeckoView). You just need to choose the right one(s) to distribute, according to the types of phones people have. Many of the phones today will use the 64-bit ARM APK. Otherwise, the 32-bit ARM APK is used for most older phones. Intel phones are less common, but it will depend on the phones being sold in your country.
