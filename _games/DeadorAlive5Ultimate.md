---
layout: single
title: "Dead or Alive 5 Ultimate"
permalink: /DeadorAlive5Ultimate/
categories:
    - Games
    - Games with aspect ratio patch
    - Games without 720p patch
    - Games without FPS patch
tags:
    - Game
title_ids: 4B5607E8
title_id_serials: KV-2024
media_ids: 4C6BA48E
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/1303)
| Resolution(s)               | ####x###
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
