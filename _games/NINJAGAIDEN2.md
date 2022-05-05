---
layout: single
title: "NINJA GAIDEN 2"
permalink: /NINJAGAIDEN2/
categories:
    - Games
    - Games with 720p patch
    - Games with sub-720p resolution
    - Games without aspect ratio patch
    - Games without FPS patch
tags:
    - Game
title_ids: 544307D5
title_id_serials: TC-2005
media_ids: 69F555CB
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/296)
| Resolution(s)               | 1120x584
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
* [{{ page.title_ids }} - {{ page.title }} (TU3)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids }} - {{ page.title }} (TU3).patch.toml)
