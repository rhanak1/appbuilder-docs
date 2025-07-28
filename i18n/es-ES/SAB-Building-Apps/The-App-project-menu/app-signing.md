---
title: App Signing
sidebar_position: 6
slug: /app-signing
---

# App Signing {#23780858a4b680a790aad9e2600b19fc}

Your app must be “signed” to have permission to be installed on an Android phone. Signing means providing a way to authorize its installation by confirming that it is indeed created by you, the developer, and is not malware or a virus (or just an illegal app) in disguise. This is done by creating an encrypted, password-protected “certificate” file called a keystore.

If you don’t have one already, create a keystore by clicking on the **Create Keystore**… button which launches the **Create New Keystore** wizard.

:::note

_If you want, you can use the same keystore for all your apps. However, for various reasons, you may want to have a single, shared keystore for just a selection of apps—perhaps all the apps for a particular language. If you ever need to give your projects to someone else, they will need the password to be able to change the app._

:::

i. Enter a new filename for the keystore, such as “keystore1.” Specify a password. Click **Next** to continue.

ii. Enter an alias name for a key to create within your new keystore, such as the default “key1”. Specify a password, which can be the same as the password you entered on the previous page.

:::note

_It is very important to securely store the password for your keystore. Once the app is published, it cannot be updated without the keystore password. Make sure someone else in your organization has access to the app keystore passwords._

:::

Click **Next** to continue.

iii. On the **Certificate Issuer** page, provide details of your organisation in at least one of the fields. Click **Next** to continue.

iv. A new keystore will be created for you. Click **Close**.

Select your desired keystore and enter the password.

