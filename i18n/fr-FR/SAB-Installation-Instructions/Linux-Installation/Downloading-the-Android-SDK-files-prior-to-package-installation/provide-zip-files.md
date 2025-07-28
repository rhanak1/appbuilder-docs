---
title: Provide zip files during the package install
sidebar_position: 1
slug: /provide-zip-files
---

# **Provide zip files during the package install** {#22d80858a4b6801fb24ed92b9ed8bab4}

Use **debconf** to pre-seed the package with the location of the files and install the package.

```bash
echo android-sdk-installer android-sdk-installer/dldir string ~/Downloads/android-sdk-zips | sudo debconf-set-selections
sudo apt-get install android-sdk-installer
echo android-sdk-installer android-sdk-installer/dldir string | sudo debconf-set-selections
```

