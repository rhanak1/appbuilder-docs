---
title: The Android Icon (Adaptive) tab
sidebar_position: 1
slug: /android-icon-tab
---

# The Android Icon (Adaptive) tab {#23780858a4b680fb8c20c25fea0e1191}

Devices from Android version 8.0 to Android 11 support Adaptive Icons. It is important to define an adaptive icon for your app, otherwise the icon will not be shown well on those phones. Foreground and background layers are specified separately. Users can decide which shape they want their icons, and the Android system will use the background layer to fill that shape, then place the foreground layer on top.

![](/notion_imgs/android-icon-tab.23780858-a4b6-80b5-98df-dbbd933d703d.png)

:::tip

_If your target phones include any Android versions earlier than 8.0, you will need to specify a Legacy Android Icon as well. It may make more sense to start with creating the legacy icon, add all the various sizes (which will also add a base adaptive icon) and then finalize the adaptive icon. You can create all the sizes using a tool like_ _**IconKitchen**_ _(see Legacy icons below)._

:::

You can adjust the foreground layer image using the percentage slider. Aim to have the image just a tiny bit larger than the circled area.

