---
title: S3 Digest Analytics
sidebar_position: 2
slug: /s3-digest-analytics
---



# S3 Digest Analytics {#23880858a4b6807eb513e02e57bd6ab7}


S3 Digest Analytics uses the same mechanism as FCBH Digest Analytics to report a small digest of analytics data. However, you are responsible for hosting the Amazon S3 Bucket and processing the received data. Files are uploaded to the S3 Bucket and in a sub-folder based on the format (e.g. the current format is f1) and stored with a unique filename using a randomly generated [GUID](https://en.wikipedia.org/wiki/Universally_unique_identifier) as the basename. We are working with FCBH to package a Splunk configuration so that you can deploy your own server to analyze the data.


To use S3 Digest Analytics, ensure you have admin permissions to an Amazon AWS account, and go to:


[https://aws.amazon.com/console/](https://aws.amazon.com/console/)


You will need to:


1. Click **Sign In to the Console** at the top right of the screen.


2. Create an S3 Bucket.


a. Go to the **S3** Service and click **Create bucket**, enter a Bucket name, select a Region near where the app will be distributed, and click **Next**.


b. On the **Set properties** and **Set permissions** steps, use the defaults and click **Next**.


c. Review the configuration and click **Create bucket**.


d. Copy the **Bucket name** into the **S3 Bucket ID** field in Scripture App Builder.


3. Create a Federated Identity.


a. Go to the **Cognito** Service and click **Manage Federated Identities**. The first time you use this service it will start creating an identity pool for you. If the AWS account already has identity pools, then it will show a grid of existing one. If this is the case then click **Create new identity pool**.


b. Enter an **Identity pool name**, click **Enable access to unauthenticated identities** (which allows users of the app to submit analytics without logging into some service), and click **Create**.


c. Click **Show Details** to see the **Role Name** for the unauthenticated identities (in the next step, we will give them permission to put objects in the bucket created in the previous step). Click **Allow**.


d. Copy the **Identity pool ID** value inside the quotes in the **Get AWS Credentials** section of the **Sample code** page shown after completion of the previous step. Copy this string into the **Identity Pool ID** field in Scripture App Builder.


4. Give permission to put data into the S3 Bucket.


a. Go to the **IAM** Service and click **Roles**


b. Click on the Role created in step #3 (e.g. Cognito_{IdentityPoolName}Unauth_Role).


c. Click **Add inline policy**, click **Service** and choose **S3**.


d. Click **Actions**, type in _PutObject_ to search for actions, and check **PutObject** to select that action.


e. Click **Resources**, use default Specific, click on **Add ARN** link, enter the **Bucket name** from step #1 into the **Bucket name** field, click the **Any** checkbox at the end of the **Object name** field, and click **Add**.


f. Click **Review policy**, enter a name in the **Name** field, and click **Create policy**.

