---
title: FCBH Digest Analytics
sidebar_position: 1
slug: /fcbh-digest-analytics
---



# **FCBH Digest Analytics** {#23880858a4b680eebfd9e4682f7582fa}


FCBH Digest Analytics is the most simple analytics service requiring almost no additional setup. Faith Comes By Hearing (FCBH) has established an analytics service for use with Scripture App Builder. By selecting FCBH Digest Analytics as the Account Type, your app will send a small daily digest (about 300 bytes for each day the app is used) of compressed, completely anonymous data (no personal, phone, or GPS location information) via an encrypted transport (https) to an Amazon data center in Asia, when the device is connected to the Internet (via cell or WIFI) while the app is running.


FCBH uses the resulting data for two purposes: 1) They make semi-annual contributions to text-holder organizations, proportional to the usage of corresponding audio recordings, and 2) They show usage data to visitors and donors to encourage and inspire involvement. Access to this service (data and dashboards) is available to interested partners (e.g. app builders) so they can easily track usage. Send an email to [sab-analytics@fcbhmail.org](mailto:sab-analytics@fcbhmail.org) to request access.


Data is aggregated by an FCBH server and analyzed using Splunk.  A snapshot of one dashboard is below. The dashboard is interactive and allows drill-down to specific apps or versions or countries. The dashboard is a work in progress and interested ministry partners are welcome to contribute or build their own dashboards on the Splunk server.


![](/notion_imgs/fcbh-digest-analytics.23880858-a4b6-8066-94a8-ead6f34de445.png)


While no location information is uploaded, Amazon’s servers record the IP addresses where data uploads occur from. FCBH then uses [Maxmind's](https://www.maxmind.com/en/geoip2-databases) free database to estimate device locations (at approximately 99% and 95% accuracy for country and city respectively).

