---
layout: post
title: Learning Git
date: 2024-10-14
categories: [linux,git]
tags: [git] # TAG names should ALWAYS be LOWERCASE
---

### Initialise A Local Repo
```bash
git init

# or 
git init -b <branch_name>
# Initialise a Git repo and set the name for the initial branch.
```

### Two Steps of Committing
```bash
git status
# Show the status of the working directory and the staging area.
```

### Configuration File 
```bash
git config --global --list
# List the variables in the global Git configuration file and their values.

git config --global user.name "johndoe"
# Set the user's name in the global Git config file.

git config --global user.email "example@example.com"
# Set email address in the global Git config file.
```


