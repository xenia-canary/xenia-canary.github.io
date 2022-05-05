---
layout: single
title: "Halo 3"
permalink: /Halo3/
categories:
    - Games
    - Games with aspect ratio patch
    - Games without 720p patch
    - Games without FPS patch
tags:
    - Game
title_ids: 4D5307E6
title_id_serials: MS-2022
media_ids: 699E0227
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/178)
| Resolution(s)               | ####x###
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
