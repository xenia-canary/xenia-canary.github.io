---
layout: single
title: "Halo 3: ODST"
permalink: /Halo3ODST/
categories:
    - Games
    - Games with aspect ratio patch
    - Games without 720p patch
    - Games without FPS patch
tags:
    - Game
title_ids: 4D530877
title_id_serials: MS-2167
media_ids: 2299898F
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title | remove: ":" }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/179)
| Resolution(s)               | ####x###
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
