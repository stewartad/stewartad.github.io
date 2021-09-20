---
title: "SeekerBot 1.1.0"
date: 2021-02-26
draft: false
categories:
- SeekerBot
tags:
- python
- discord
- transformers tcg
draft: false
weight: 3

---

# SeekerBot Version 1.1.0 Changelog
- Fixed `!stats` command for users without games logged in the current week and month
- implemented `!undo` command
    - undo can only be done within 5 minutes of the original report
    - only one of the participants can undo the match (even if it was reported by someone else)
- Fixed reporting mistakes
<!--more-->
