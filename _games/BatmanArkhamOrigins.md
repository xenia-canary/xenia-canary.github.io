---
layout: single
title: "Batman: Arkham Origins"
permalink: /BatmanArkhamOrigins/
categories:
    - Games
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without FPS patch
    - Games without media ID
tags:
    - Game
title_ids: 57520828
title_id_serials: WR-2088
#media_ids:
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title | remove: ":" }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | <!--{{ page.media_ids }}-->
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/534)
| Resolution(s)               | ####x###
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
* [{{ title_patch }} (TU3)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (TU3).patch.toml)
