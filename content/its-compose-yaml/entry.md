---
aliases:
  - its-compose-yaml
category: docker
classification: public
date: 2023-12-06T09:54:33
date_modified: 2024-09-23T16:47:06
draft: false
id: 20231206095433
image: 
links:
  - https://github.com/compose-spec/compose-spec/blob/master/spec.md
local_archive_links:
  - attachments/its-compose-yaml.html
pinned: false
print: false
series: 
tags:
  - compose
  - docker
  - github
  - specification
title: It's compose.yaml
type: tech-note
---

Nowadays, you should name your Docker Compose files `compose.yaml`.

> The default path for a Compose file is compose.yaml (preferred) or compose.yml that is placed in the working directory. Compose also supports docker-compose.yaml and docker-compose.yml for backwards compatibility of earlier versions. If both files exist, Compose prefers the canonical compose.yaml.
>
> — [compose-spec/spec.md](https://github.com/compose-spec/compose-spec/blob/master/spec.md)