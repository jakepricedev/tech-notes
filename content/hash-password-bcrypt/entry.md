---
aliases:
  - hash-password-bcrypt
category: cli
classification: public
date: 2023-01-11T08:49:41
date_modified: 2024-09-23T19:04:20
draft: false
id: 20230111084941
image: 
links:
  - https://unix.stackexchange.com/a/419855/331627
local_archive_links:
  - attachments/hash-password-bcrypt.html
pinned: false
print: false
series: 
tags:
  - bcrypt
  - caddy-security
  - hash
  - password
title: Hash a Password using bcrypt
type: tech-note
---

It's surprisingly not that straightforward to find a tool to create a bcrypt hashed password.

```sh
htpasswd -bnBC 10 "" <password> | tr -d ':\n' | sed 's/$2y/$2a/'
```

To do it with a password prompt:

```sh
htpasswd -nBC 10 jprice | tr -d ':\n' | sed 's/$2y/$2a/'
```

More on [StackExchange](https://unix.stackexchange.com/a/419855/331627)