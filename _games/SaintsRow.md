---
layout: single
title: "Saints Row"
permalink: /SaintsRow/
categories:
    - Games
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without FPS patch
tags:
    - Game
title_ids: 545107D1
title_id_serials: TQ-2001
media_ids: 24367742
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/104)<br>[canary](https://github.com/xenia-canary/game-compatibility/issues/20)
| Resolution(s)               | ####x###
| FPS                         | 60

## Patches
* [{{ title_patch }} (TU1)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (TU1).patch.toml)
