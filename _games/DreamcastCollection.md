---
layout: single
title: "Dreamcast Collection"
permalink: /DreamcastCollection/
categories:
    - Games
    - Games with resolution patch
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without FPS patch
tags:
    - Game
title_ids: 5345085A
title_id_serials: SE-2138
media_ids: 6876EE29
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | <!--[master](https://github.com/xenia-project/game-compatibility/issues/)-->
| Resolution(s)               | 640x480
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
