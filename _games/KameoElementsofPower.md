---
layout: single
title: "Kameo: Elements of Power"
permalink: /KameoElementsofPower/
categories:
    - Games
    - Games with aspect ratio patch
    - Games with 30 FPS cap
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without media ID
tags:
    - Game
title_ids:
    - 4D5307D2
    - 4D5387E9 # Demo
    - 4D5387E0 # Kiosk demo
title_id_serials:
    - MS-2002
    - MS-34793 # Demo
    - MS-34784 # Kiosk demo
#media_ids:
---
{% capture title_patch %}{{ page.title_ids[0] }} - {{ page.title[0] | remove: ":" }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids[0] | lowercase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids[0] }} ({{ page.title_id_serials[0] }})<br>Demo: {{ page.title_ids[1] }} ({{ page.title_id_serials[1] }})<br>Kiosk demo: {{ page.title_ids[2] }} ({{ page.title_id_serials[2] }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/173)<br>[canary](https://github.com/xenia-canary/game-compatibility/issues/50)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
* [{{ page.title_ids[1] }} - {{ page.title_patch }} (demo)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids[1] }} - {{ page.title_patch }} (demo).patch.toml)
* [{{ page.title_ids[2] }} - {{ page.title_patch }} (kiosk demo)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ page.title_ids[2] }} - {{ page.title_patch }} (kiosk demo).patch.toml)
