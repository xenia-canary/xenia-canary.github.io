---
layout: single
title: "Skate 2"
permalink: /Skate2/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with FPS cap
    - Games with FPS patch
    - Games with sub-720p resolution
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without media ID
tags:
    - Game
title_ids: 4541087F
title_id_serials: EA-2175
#media_ids:
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/243)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
