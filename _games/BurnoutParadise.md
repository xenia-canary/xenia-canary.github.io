---
layout: single
title: "Burnout Paradise"
permalink: /BurnoutParadise/
categories:
    - Games
    - Games with 30 FPS cap (conditional)
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without FPS patch
    - Games without media ID
tags:
    - Game
title_ids: 45410806
title_id_serials: EA-2054
#media_ids:
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/1900)
| Resolution(s)               | ####x###
| FPS                         | 60, 30

## Patches
* [{{ page.title_ids }} - {{ page.title }} (1.00)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids }} - {{ page.title }} (1.00).patch.toml)
* [{{ page.title_ids }} - {{ page.title }} (Screenshot)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids }} - {{ page.title }} (Screenshot).patch.toml)
