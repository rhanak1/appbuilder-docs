---
title: Analytics
sidebar_position: 0
slug: /analytics
---

# Analytics {#23880858a4b680d78f87da9badb9373a}

If you enable Analytics, the app will connect to the internet from time to time to send app usage information to one or more analytics accounts. This will give you an idea of the extent to which people are interacting with the app.

The information sent will include the model of the device (such as ‘Google Nexus 7’, ‘Samsung Galaxy S4’), the Android version (such as ‘4.2’), the mobile network provider and an approximate location (city/country). No personal information is included.

You can configure your app to send usage data to one or more of the following analytics engines:

| _**FCBH Digest Analytics**_ | Sends a digest of analytics data to Faith Comes By Hearing (FCBH). |
| --------------------------- | ----------------------------------------------------------------------------------------------------- |
| _**S3 Digest Analytics**_   | Sends a digest of analytics data to an Amazon S3 Bucket of your choice.               |
| _**Amplitude Analytics**_   | Sends data to an Amplitude account of your choice.                                    |
| _**Firebase Analytics**_    | Sends data to a Google Firebase Analytics account of your choice.                     |

To set up analytics:

1. Select **Enable Analytics**.

2. Choose whether users can opt out of sharing user data

3. Click **Add Analytics Account…**

4. Choose an account type and enter your analytics account information.

- For FCBH Analytics, you do not need any additional ID information.
- For S3 Digest Analytics, you will need an S3 Bucket ID and an Identity Pool ID.
- For Amplitude Analytics, you will need an API Key.
- For Firebase Analytics, you will need a google-services.json configuration file for your account.
