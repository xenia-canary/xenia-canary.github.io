---
layout: single
title: "Final Fantasy XIII"
permalink: /FinalFantasyXIII/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
    - Games without aspect ratio patch
tags:
    - Game
title_ids: 535107E4
title_id_serials: SQ-2020
media_ids:
    - 602A3E5A
    - 40E764B6
    - 0FE8E2F9
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids[0] }}<br>{{ page.media_ids[1] }}<br>{{ page.media_ids[2] }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/946)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
