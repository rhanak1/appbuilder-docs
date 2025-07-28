---
title: Add SIL repository for Ubuntu
sidebar_position: 0
slug: /add-sil-repo
---



# **Add SIL repository for Ubuntu** {#22d80858a4b680828cd9dcbb2b7776fd}


To install packages from the SIL repository for Ubuntu, the repository must be added to the APT sources.


Note: **Wasta-Linux** already includes configuration for the SIL repository for Ubuntu and so you can skip this section.


If you are using another **Ubuntu-based distribution**, please follow the instructions below (from the section “Enable access to SIL software and fonts in Ubuntu” on [https://packages.sil.org](https://packages.sil.org/)).

1. Open a Terminal window.
2. Add the repository security key:

```bash
(wget -O- https://packages.sil.org/keys/pso-keyring-2016.gpg | sudo tee /etc/apt/trusted.gpg.d/pso-keyring-2016.gpg)&>/dev/null
```

1. Add source:

```bash
(. /etc/os-release && sudo tee /etc/apt/sources.list.d/packages-sil-org.list>/dev/null <<< "deb http://packages.sil.org/$ID $VERSION_CODENAME main")
```

