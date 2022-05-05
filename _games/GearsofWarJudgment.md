---
layout: single
title: "Gears of War: Judgment"
permalink: /GearsofWarJudgment/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
    - Games without aspect ratio patch
tags:
    - Game
title_ids: 4D530A26
title_id_serials: MS-2598
media_ids: 6DCAF3C2
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title | remove: ":" }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/585)<br>[canary](https://github.com/xenia-canary/game-compatibility/issues/45)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
