---
title: The Multiple APKs tab
sidebar_position: 3
slug: /multiple-apks-tab
---



# The Multiple APKs tab {#23780858a4b68014b267e6306fe2ab30}


There are 4 types of Android phone architectures, and an APK file is designed to work on any of them. However, certain features (e.g. allowing saving as a video or the inclusion of GeckoView) can make the APK much bigger. Since these features depend on the phone architecture, smaller, device-specific APKs (known as Android App Bundles or AABs) can be built to target each architecture. The downside is that this prevents the sharing of the app bundle to another phone with a different architecture.


:::note

_To Publish to the Play Store you will need to create Android App Bundles (AABs). When a user installs an app from the Play Store, they receive the AAB associated with their phone’s specific architecture, not a (universal) APK.  To explicitly create AABs, go to the_ _**Compile**_ _menu in the main SAB menu bar and select_ _**Compile Android App Bundle**_. _If you are using Scriptoria, you can create the AABs there._
_If you want to distribute you app on SD cards or other direct means to ANY phone, you will have to build an APK._

:::



