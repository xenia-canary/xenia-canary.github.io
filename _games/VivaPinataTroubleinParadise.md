---
layout: single
title: "Viva Piñata: Trouble in Paradise"
permalink: /VivaPinataTroubleinParadise/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
    - Games without aspect ratio patch
tags:
    - Game
title_patch: "Viva Pinata Trouble in Paradise"
title_ids: 4D53085F
title_id_serials: MS-2143
media_ids: 76A44A5D
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/292)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ page.title_ids }} - {{ page.title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids }} - {{ page.title_patch }}.patch.toml)
