---
layout: single
title: "Project Gotham Racing 3"
permalink: /ProjectGothamRacing3/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with 720p patch
    - Games with aspect ratio patch
    - Games with FPS cap
    - Games with FPS patch
    - Games with sub-720p resolution
    - Games without media ID
tags:
    - Game
title_ids: 4D5307D1
title_id_serials: MS-2001
#media_ids:
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/287)
| Resolution(s)               | 1024x600
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
