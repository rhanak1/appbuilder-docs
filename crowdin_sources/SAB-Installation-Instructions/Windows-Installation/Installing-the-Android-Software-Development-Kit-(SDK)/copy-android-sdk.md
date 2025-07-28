---
title: Copying the Android SDK files from someone else
sidebar_position: 1
slug: /copy-android-sdk
---



# **Copying the Android SDK files from someone else** {#22d80858a4b680b489b3d994bf6c0483}


If you know someone who has already downloaded and installed the Android SDK and is successfully building apps with it, you can copy all of their Android SDK files to a folder on your computer.


You need to look for the top-level Android SDK folder, such as **c:\sdk**, and copy the whole folder and its contents to your computer. A location such as c:\sdk is good. If it makes it easier, you can zip the folders and then unzip them onto your computer.


Note that there is <u>no setup program to run</u>. Copying the files from one computer to another is sufficient.


**Tip**: A typical Android SDK folder can be quite large (over 1 GB, depending on which additional packages have been installed). To build an app, you do not need all of the Android SDK files. If you want to cut down the number of files, here is a list of the essential and optional folders:


| **Android SDK Folder**   | **Required for building apps?**                            |
| ------------------------ | ---------------------------------------------------------- |
| cmdline-tools (or tools) | Yes                                                        |
| build-tools              | Yes  (you only need the sub-folder for the latest version) |
| platforms                | Yes  (you only need android-34)                            |
| platform-tools           | Yes                                                        |
| add-ons                  | No                                                         |
| docs                     | No                                                         |
| emulator                 | No, unless you want to use an emulator                     |
| extras                   | No                                                         |
| licenses                 | Yes                                                        |
| sources                  | No                                                         |
| system-images            | No, unless you want to use an emulator                     |
| temp                     | No                                                         |

