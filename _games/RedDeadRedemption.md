---
layout: single
title: "Red Dead Redemption"
permalink: /RedDeadRedemption/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with aspect ratio patch
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
tags:
    - Game
title_ids: 5454082B
title_id_serials: TT-2091
media_ids:
    - 2AAB34E2
    - 3EE87B76 # GOTY
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids[0] }}<br>GOTY: {{ page.media_ids[1] }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/108)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ title_patch }} (Original, NTSC)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (Original, NTSC).patch.toml)
* [{{ title_patch }} (Original, NTSC, TU9)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (Original, NTSC, TU9).patch.toml)
* [{{ title_patch }} (GOTY, Disc 1)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (GOTY, Disc 1).patch.toml)
* [{{ title_patch }} (GOTY, Disc 2)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (GOTY, Disc 2).patch.toml)
