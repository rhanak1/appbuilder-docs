---
title: Installing without Android SDK
sidebar_position: 3
slug: /installing-without-android-sdk
---

# **Installing without Android SDK** {#22d80858a4b68093a205e778dae80b90}

The **android-sdk-installer** package is a recommended package for the **app-builder** package. If the Android SDK is already installed, your App Builder can use the current installation.

```bash
sudo apt-get update
sudo apt-get install (replace with app builder name)-app-builder --no-install-recommends
```

Set the ANDROID_HOME environment variable to the path of the Android SDK installation to allow your App Builder to find it automatically. Otherwise you can use the **Tools** → **Settings** dialog in your App Builder to specify the path.

