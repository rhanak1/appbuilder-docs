---
title: Setting up the database in Google Firebase console
sidebar_position: 2
slug: /setting-up-database-in-google-firebase-console
---



# Setting up the database in Google Firebase console {#23880858a4b6805cb76cef5edd38ae55}


To set up the database, which will contain the registered users’ information, you need to add Firebase to your app, create a database, set up authentication and configure rules.


**Add Firebase to your app**


Follow the instructions in setting up a Firebase project, described in the section above on _Firebase Features_.


**Create a Database**


To create a database:


1. In your Firebase project console, select **Realtime Database** from the menu on the left of the screen (the option below Firestore Database).


2. Click the **Create database** button.


3. On the first page of **Set up database**, choose where you would like the data to be stored, then click **Next**.


4. On the second page of **Set up database**, choose **Start in locked mode**, and click **Enable**.


**Set up Authentication**


To set up authentication:


1. In your Firebase project console, select **Authentication** from the menu on the left of the screen.


2. Select the **Sign-in method** tab.


3. Click on **Email/Password** and enable this authentication method to allow users to sign up using their email address and password.


4. Click **Save** to confirm your changes and return to the Sign-in method tab.


**Configure Rules**


Rules are required to tell Firebase who will have access rights to read and write to the database. To configure the database rules:

1. In your Firebase project console, select **Realtime Database** from the menu on the left of the screen.
2. Select the **Rules** tab.
3. Change the rules to be as follows:

{


"rules": {


"authenticated-users": {


"$uid": {


".read": "$uid === auth.uid",


".write": "$uid === auth.uid"


}


}


}


}


This rule says that only authenticated users will have right to read and write their own data. Unauthenticated users will not be able to see or change anything, and authenticated users will not have the right to see or change someone else’s data.


4. Click **Publish** to confirm your changes.

