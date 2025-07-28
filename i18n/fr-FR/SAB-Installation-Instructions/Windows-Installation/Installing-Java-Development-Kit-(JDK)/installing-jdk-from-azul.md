---
title: Installing the JDK from the Azul website
sidebar_position: 1
slug: /installing-jdk-from-azul
---

# **Installing the JDK from the Azul website** {#22d80858a4b680138298c9f8dba0a1aa}

We recommend you use Zulu, which is a free distribution of OpenJDK from Azul.

 ```
 1. Go to the **Download Zulu Builds of OpenJDK** website: [https://www.azul.com/downloads/?version=java-17-lts&os=windows&architecture=x86-64-bit&package=jdk#zulu](https://www.azul.com/downloads/?version=java-17-lts&os=windows&architecture=x86-64-bit&package=jdk#zulu)             There are many downloads on this page, but the above link will filter the ones you see (Java Version: Java 17 LTS; Operating System: Windows; Architecture: x86 64-bit; Java Package: JDK).
 2. Scroll down the page until you see the downloads:
 
 ![](/notion_imgs/installing-jdk-from-azul.22d80858-a4b6-8019-b630-c26eef19eccf.png)
 
 1. You have a choice between a zip file and an msi file. **Download the .msi file** since it comes with its own installer program. The file you download will have a filename something like this:  **zulu17.44.15-ca-jdk17.0.8-win_x64.msi**
 2. **Double-click the msi file** and follow the instructions in the installation wizard to install it. By default, the .msi installer will install the JDK to the following folder: C:\Program Files\Zulu\zulu-17\
 ```

:::info

<u>**Important**</u>: If you change the JDK install folder to something other than the default folder, you will need to remember the location of the folder so you can tell your App Builder where to find the JDK.

:::



