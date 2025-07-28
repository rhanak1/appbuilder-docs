---
title: Installing the app on your phone
sidebar_position: 3
slug: /installing-the-app-on-your-phone
---

# Installing the app on your phone {#23780858a4b6800ab798cca000e66268}

In the above section, you have seen how to compile an Android app. The result is an APK file, the installation file for an Android app. You now need to copy this APK file to your phone, install it and launch the app.

:::note

_Because you are installing your APK directly (a process called side-loading) instead of through the Play Store, your phone may alert you to the fact that this is a suspicious file and require an extra step for permitting the install and/or a virus scan. This is normal, but if you are sharing your APK this way, you will want to prepare users that they may encounter these checks._

:::

There are several ways to do this:

**Copy the APK via WIFI transfer**

Use a WIFI transfer app (Xender, WhatsApp) on your phone and computer. Open the _APK output folder_, select your APK and copy it or send it to your phone. Locate the APK file and tap on it to install.

**Copy the APK directly**

If you have a USB data cable, connect your phone to your computer so that it shows up as a device (like an external hard drive or USB drive). Open the _APK output folder_, select your APK and copy it to an easily-found folder (e.g. Downloads) on your phone. Then, on the phone, find the APK and tap to install.

**Automatically install the APK from within SAB**

This is a very convenient way to test your APK and worth setting up. Use the following steps:

1. Connect your Android phone to your computer using a **USB data cable**.

(Sometimes you get cheap USB cables that can only charge a phone but cannot transfer data, so make sure you have the right kind of cable.)

:::tip

_When you connect your phone to your computer, if your phone appears as an icon under “This PC”, you have a data cable._

:::

2. Ensure that **Developer Options →** **USB Debugging** is enabled on your phone. By default, on new phones, Developer Options is turned off. This is how you can enable it:

i. Open the **Settings** menu of your phone.

ii. Scroll down to the bottom of the menu and tap on **About Phone**.

iii. Find the **Build Number**. This could be on the About Phone page, or under a sub-menu such as ‘Software Information’.

:::tip

_If you have trouble finding the Build Number, search for “****Build Number****” in the settings Search bar._

:::

iv. Tap on the Build Number **seven times**. As you do this, you will see a series of messages appearing: “You are now 3 steps away from being a developer”, “You are now 2 steps away from being a developer”, “You are now 1 step away from being a developer”, “You are now a developer!”.

![](/notion_imgs/installing-the-app-on-your-phone.23780858-a4b6-8089-9b4c-ca62660ec469.png)

v. Now return to the Configuration menu of your phone. Look for the Developer Options menu item. You might see **Developer Options** above the **About Phone** menu item. If you do not see it here, it could be in **System** settings, under **Advanced**.

:::tip

_If you have trouble finding the Developer Options, search for “****Developer Options****” in the settings Search bar. You can even just search for “****USB Debugging****” to go directly to that setting._

:::

Different phones place Developer Options in different places, so look around your Configuration menu until you find it (see image below).

![](/notion_imgs/installing-the-app-on-your-phone.23780858-a4b6-80a4-8bc0-cb4631964f2d.png)

vi. Tap on **Developer Options** and ensure that it is turned on.

vii. Scroll down the Developer Options page and find **USB Debugging**. Enable this setting.

![](/notion_imgs/installing-the-app-on-your-phone.23780858-a4b6-80a9-afcb-deb4e2c8bead.png)

![](/notion_imgs/installing-the-app-on-your-phone.23780858-a4b6-802f-9cbc-f6c56df6a24c.png)

When you do this, you will probably get a message “Allow USB Debugging?” Tap **OK**.

![](/notion_imgs/installing-the-app-on-your-phone.23780858-a4b6-8075-b341-dd05fef00361.png)

If you see a message box like this, check the box “**Always allow from this computer**” and tap **OK**:

3. In Scripture App Builder, click the **Install APK** button on the toolbar at the top right of the screen.

A window will open and the APK file will be copied to your phone and installed. The app will then be launched.

If this does not work, look at the command window to see if there is an error message. If you see a message such as “No devices/emulators found”, it means that your phone and computer are not connected correctly, your phone is locked, or that you have not enabled USB debugging on your phone.

:::tip

_Described above is a two-step process:_ _**Build App**_ _and then_ _**Install APK**_. _If you prefer, you can tell Scripture App Builder to do this in one step, i.e. for the APK to be installed and launched automatically after building an app. See_ _**Tools**_ _→_ _**Settings…**_ _→_ _**After Build**_ _to enable this feature._

:::



