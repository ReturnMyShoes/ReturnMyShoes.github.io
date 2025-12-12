---
layout: single
title: "Git Commands & Website Setup" # <-- NEW TITLE
date: 2025-12-11
collection: garden
tags: [evergreen, meta, philosophy]
---
# Start
Create ur repository in github, name it "ur-repo-name"

--- 
cd into the folder
# To establish whos working these files
git config --global user.name " ur-name"
# For ur communications
git config --global user.email “ur-email”
# To set the color of git in CLI
git config --global color.ui auto   -----optional
# to establish its a git file
git init
# Establish the remote
git remote add origin https://github.com/your-username/your-repo-name.git
# Add and commit
git add .
git commit -m "Your first meaningful commit message"
# Push to GitHub (use -u only on the first push)
git push -u origin main