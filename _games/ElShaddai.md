---
layout: single
title: "El Shaddai"
permalink: /ElShaddai/
categories:
    - Games
    - Games with 720p patch
    - Games with sub-720p resolution
    - Games without aspect ratio patch
    - Games without FPS patch
tags:
    - Game
title_ids: 494F07D1
title_id_serials: IO-2001
media_ids: 640B378B
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/413)
| Resolution(s)               | 1120x584
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
