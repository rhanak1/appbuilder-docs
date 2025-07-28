---
title: The Android Icon (Legacy) tab
sidebar_position: 2
slug: /android-icon-legacy-tab
---



# **The Android Icon (Legacy) tab** {#23780858a4b6808caba8c004ea0bb8b4}


Legacy icons (those for versions of Android earlier than 8.0) need to be specified in a variety of sizes, and the phone’s operating system will select which icon size that is best to display.  Rather than creating all the sizes by hand, it is better to use a tool like [IconKitchen](https://icon.kitchen/), which is linked to from this tab in SAB. IconKitchen will create a .zip file that you can download with all the various sizes. Use **Add Icon Images…** to select the downloaded zip and SAB will open the file and assign all the various sizes.


:::tip

_While IconKitchen has some basic tools to design an icon from scratch, you might prefer experimenting with using an AI picture generator like CoPilot or Playground AI to make a base icon image that you can then select into IconKitchen, adjust and download._

:::




SAB will create a series of folders under the project data folder’s **Images** sub-folder, one for each icon size. (See _Project-specific data folders_). You can see these folder names under the **Filename** column of the Legacy icon display list. Each icon name is identical: **ic_launcher.png**


:::note

_If you want to publish your app on the Google Play store, you will need the 512 x 512 icon image stored in the_ _**drawable-web**_ _subfolder. You may want to use this image as part of the required Feature Graphic, too._

:::



