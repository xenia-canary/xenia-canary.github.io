---
layout: single
title: "Halo: Reach"
permalink: /HaloReach/
categories:
    - Games
    - Games with aspect ratio patch
    - Games without 720p patch
    - Games without FPS patch
tags:
    - Game
title_ids: 4D53085B
title_id_serials: MS-2139
media_ids: 566C10D3
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title | remove: ":" }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/52)
| Resolution(s)               | ####x###
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
