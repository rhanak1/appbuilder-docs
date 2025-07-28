---
title: Can I build apps when I do not have internet access?
sidebar_position: 9
slug: /build-apps-without-internet
---

# **Can I build apps when I do not have internet access?** {#23780858a4b68030a1a8c532f3567e6b}

The first time you build an app, you will need to be connected to the internet otherwise the compiler will fail. It will download a set of libraries used by the Gradle compiler. After that you can set the 'offline' version in **Settings** so you can work offline.

If you want to be able to build your first app without needing internet access, it is possible to copy the Gradle cache files from another computer that has already downloaded them. This will only work, however, if the absolute path to the files is exactly the same on the computer from which the files are taken as on your computer, e.g. “C:\gradle” on computer A and “C:\gradle” on computer B. It will not work if you have “C:\Users\John\.gradle” or computer A and “C:\Users\Jenny\.gradle” on computer B (which is the default Gradle cache folder).

So, on computer A, to get the cache files to distribute:

1. Go to **Tools** → **Settings** → **Build Settings** → **Gradle Cache Folder**.

2. Enter “C:\gradle” and OK.

3. Build an app. The Gradle cache files will be downloaded to C:\gradle.

Then, on computer B:

1. Copy the C:\gradle folder from computer A to C:\gradle.

2. Go to **Tools** → **Settings** → **Build Settings** → **Gradle Cache Folder**.

3. Enter “C:\gradle” and OK.

