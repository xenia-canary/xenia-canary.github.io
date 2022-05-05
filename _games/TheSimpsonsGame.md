---
layout: single
title: "The Simpsons Game"
permalink: /TheSimpsonsGame/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
    - Games without aspect ratio patch
tags:
    - Game
title_ids: 45410809
title_id_serials: EA-2057
media_ids: 05631042
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/542)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
