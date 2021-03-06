---
layout: single
title: "Final Fantasy XIII-2"
permalink: /FinalFantasyXIII2/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without media ID
tags:
    - Game
title_ids:
    - 53510806
    - 53518810 # Demo
title_id_serials:
    - SQ-2054
    - SQ-34832 # Demo
media_ids: 4835CB45
---
{% capture title_patch %}{{ page.title_ids[0] }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids[0] }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids[0] }} ({{ page.title_id_serials[0] }})<br>Demo: {{ page.title_ids[1] }} ({{ page.title_id_serials[1] }})
| Media ID(s)                 | Demo: {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/947)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
* [{{ page.title_ids[1] }} - {{ page.title }} Demo](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} Demo.patch.toml)
