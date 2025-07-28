---
title: Data Payload for FCBH and S3 Digest Analytics
sidebar_position: 3
slug: /data-payload-for-fcbh-and-s3-digest-analytics
---

# **Data Payload for FCBH and S3 Digest Analytics** {#23880858a4b680e3bab6fbe12b19d6f9}

Both FCBH Digest Analytics and S3 Digest Analytics use the same JSON payload format. A complete sample data payload is below:

{"startTime":"20180306T0835Z","period":1440,"id":"12db7e3f-93d9-4370-b12b-fe048804e4f5","package":"org.fcbh.hndwtc.n2","version_name":"1.0.1","sessions":1,"sessionMins":21,"shares":3,"dams":[{"damid":"HNDWTCN2DA","playMins":25,"chaps":["MRK 1","MRK 1","MRK 2","MRK 2","MRK 3","MRK 4","MRK 4"]}]}

The payload is 296 bytes uncompressed and 224 bytes compressed. This sample is comprised of the following fields:

- One day of activity (1440 minutes), starting on 2018-03-06.
- The id is a [GUID](https://en.wikipedia.org/wiki/Universally_unique_identifier) which was randomly generated on the phone when the app was first launched, enabling determination of how many unique installations of the app are in use (but no user-identifying information).
- Package and version indicate which app is in use.
- This report was for a single 21-minute session. This (and other) values would be incremented if the app had been used multiple times within the reporting period.
- The user pressed Share in the app 3 times.
- The app played FCBH audio HNDWTCN2DA, which is a **Fileset ID** from FCBH’s [Bible Brain](https://biblebrain.com/).
- The app played audio for 25 minutes. Since this is greater than 21 minute session time, the audio must have been playing while the screen was off for 4 minutes. Comparison of these fields enable some rough comparison of audio-only use, versus use of audio in combination with text.
- Mark 1-4 were played. Mark 1 and 4 being listed twice each indicates that the user pressed play twice in each chapter (and thus, also pressed stop in each).
