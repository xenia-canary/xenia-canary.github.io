---
layout: single
title: "Perfect Dark Zero"
permalink: /PerfectDarkZero/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with 720p patch (broken)
    - Games with aspect ratio patch
    - Games with FPS cap
    - Games with FPS patch
    - Games with sub-720p resolution
    - Games without anti-aliasing
tags:
    - Game
title_ids: 4D5307D3
title_id_serials: AV-2013
media_ids: 2CB96AE4
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | 4D5307D3 (AV-2013)
| Media ID(s)                 | 2CB96AE4
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/175)<br>[canary](https://github.com/xenia-canary/game-compatibility/issues/77)
| Resolution(s)               | 1216x640
| FPS                         | 30

## Patches
* [{{ title_patch }}](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }}.patch.toml)
