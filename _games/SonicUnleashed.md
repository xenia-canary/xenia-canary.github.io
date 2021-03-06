---
layout: single
title: "Sonic Unleashed"
permalink: /SonicUnleashed/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with 720p patch
    - Games with aspect ratio patch
    - Games with FPS cap
    - Games with FPS patch
    - Games with sub-720p resolution
    - Games without media ID
tags:
    - Game
title_ids: 53450812
title_id_serials: SE-2066
media_ids: 4BED0DDE
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/300)
| Resolution(s)               | 880x720
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
* [{{ title_patch }} (TU2)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (TU2).patch.toml)
