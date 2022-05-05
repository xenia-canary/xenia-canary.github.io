---
layout: single
title: "Fable II"
permalink: /FableII/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with 720p patch
    - Games with FPS cap
    - Games with FPS patch
    - Games with sub-720p resolution
    - Games without 720p patch
    - Games without aspect ratio patch
tags:
    - Game
title_ids: 4D5307F1
title_id_serials: MS-2033
media_ids: 716F0A0D
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/205)<br>[canary](https://github.com/xenia-canary/game-compatibility/issues/74)
| Resolution(s)               | 1120x720
| FPS                         | 30

## Patches
* [{{ page.title_ids }} - {{ page.title }} (GOTY_Platinum Edition)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids }} - {{ page.title }} (GOTY_Platinum Edition).patch.toml)
* [{{ page.title_ids }} - {{ page.title }} (GOTY_Platinum Edition, TU1)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids }} - {{ page.title }} (GOTY_Platinum Edition, TU1).patch.toml)
