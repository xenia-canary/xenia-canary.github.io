---
layout: single
title: "Boogie Bunnies"
permalink: /BoogieBunnies/
categories:
    - Games
    - Games with 720p patch
    - Games with non-720p resolution
    - Games with blur
    - Games without aspect ratio patch
    - Games without FPS patch
tags:
    - Game
title_ids: 584108D3
title_id_serials: XA-2259
media_ids: 6AA3404F
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/1925)
| Resolution(s)               | 1920x1080
| FPS                         | 60

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
