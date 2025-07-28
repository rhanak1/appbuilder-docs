---
title: The Push Notifications tab
sidebar_position: 3
slug: /push-notifications-tab
---

# The Push Notifications tab {#23880858a4b680469d3cd95f3b4f38a7}

You can send direct messages over the internet to all the users who have your app installed on their phone.

Such messages could include:

- Sending greetings on special occasions.
- Sharing news of app updates, new resources and special offers.
- Encouraging people to use the app.

**Setting up Firebase Cloud Messaging**

To set up the push notifications feature:

1. If you have not already done so, follow the instructions on setting up a **Firebase project**, described in the section above on _Firebase Features_.

2. In Scripture App Builder, go to the **Data & Analytics** → **Firebase** tab and enable **Firebase Messaging**.

**Sending messages**

To send a push notifcation message to all users of your app:

1. Go to the **Firebase Console** for your Firebase project.

2. Select **Cloud Messaging** from the menu on the left of the screen.

3. Click **Send your first message**.

4. Enter the **Notification title** and **Notification text**, then click **Next**.

5. In the **Target** section, you want to send messages to users of your app. Click **Next**.

6. For **Scheduling**, you want **Now** (unless you choose another time). Then click **Next**.

7. Accept all the other default options and then click **Review** at the bottom of the screen.

8. Re-read your message to verify that all is OK, then click **Publish** to send it. The message will be sent to all the app users (if they are connected or connect to the internet).

