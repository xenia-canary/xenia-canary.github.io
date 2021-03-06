---
layout: single
title: "Lollipop Chainsaw"
permalink: /LollipopChainsaw/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with FPS cap
    - Games with FPS patch
    - Games without 720p patch
    - Games without aspect ratio patch
tags:
    - Game
title_ids: 565707D0
title_id_serials: VW-2000
media_ids:
    - 31BE13D9
    - 3759EFF2
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids[0] }}<br>{{ page.media_ids[1] }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/983)<br>[canary](https://github.com/xenia-canary/game-compatibility/issues/40)
| Resolution(s)               | ####x###
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
* [{{ title_patch }} (Premium Edition)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (Premium Edition).patch.toml)
