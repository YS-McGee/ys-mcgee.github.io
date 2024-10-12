---
title: Debian Update Script
date: 2024-10-13
categories: [linux,admin]
tags: [debian,ubuntu,update,script] # TAG names should ALWAYS be LOWERCASE
---

## How to Update Debian-like machines

Clone the script from the repo, and remember to use ```chmod +x ./update.sh``` to make executable.

```bash
git clone https://github.com/YS-McGee/update-script.git
```

```script
#!/bin/bash

sudo apt update -y 
sudo apt full-upgrade -y
sudo apt autoremove -y
sudo apt autoclean -y
```

## that's it!