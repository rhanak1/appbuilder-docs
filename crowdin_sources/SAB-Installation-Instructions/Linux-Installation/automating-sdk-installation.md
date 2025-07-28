---
title: Automating Android SDK installation
sidebar_position: 4
slug: /automating-sdk-installation
---



# **Automating Android SDK installation** {#22d80858a4b6801f9ef5dac732760aa5}


The **android-sdk-installer** will prompt you to accept the license for the Android SDK. To automate the installation (e.g. in an Ansible playbook), pre-seed the answer to this question.


```bash
echo android-sdk-installer android-sdk-installer/accepted-android-sdk-eula boolean true | sudo debconf-set-selections
sudo apt-get install android-sdk-installer
```

