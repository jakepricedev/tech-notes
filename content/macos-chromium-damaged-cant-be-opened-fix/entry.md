---
aliases:
  - macos-chromium-damaged-cant-be-opened-fix
category: macos
classification: public
date: 2022-01-09T17:41:01
date_modified: 2024-09-23T21:50:33
draft: false
id: 20220109174101
image: 
links:
  - https://old.reddit.com/r/MacOS/comments/q9d772/homebrew_chromium_is_damaged_and_cant_be_openend/
local_archive_links:
  - attachments/macos-chromium-damaged-cant-be-opened-fix.html
pinned: false
print: false
series: 
tags:
  - application
  - attribute
  - chromium
  - damaged
  - macos
  - xattr
title: Fix "... Damaged Can't be Opened" on MacOS
type: tech-note
---

How to fix "Chromium is Damaged Can't Be Opened".

```sh
xattr -cr /Applications/Chromium.app
```