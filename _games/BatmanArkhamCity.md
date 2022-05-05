---
layout: single
title: "Batman: Arkham City"
permalink: /BatmanArkhamCity/
categories:
    - Games
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without FPS patch
    - Games without media ID
tags:
    - Game
title_patch: "Batman Arkham City"
#title_ids:
title_id_serials: WR-2050
#media_ids:
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | <!--[master](https://github.com/xenia-project/game-compatibility/issues/)-->
| Resolution(s)               | ####x###
| FPS                         | 60

## Patches
* [{{ page.title_ids }} - {{ page.title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids }} - {{ page.title_patch }}.patch.toml)
* [{{ page.title_ids }} - {{ page.title_patch }} (TU6)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids }} - {{ page.title_patch }} (TU6).patch.toml)
