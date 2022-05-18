---
layout: single
title: "The Orange Box"
permalink: /TheOrangeBox/
categories:
    - Games
    - Games with 30 FPS cap
    - Games with 720p patch
    - Games with anti-aliasing
    - Games with FPS cap
    - Games with FPS patch
    - Games with sub-720p resolution
    - Games without aspect ratio patch
tags:
    - Game
title_ids: 4541080F
title_id_serials: EA-2063
media_ids: 651A85DA
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/255)
| Resolution(s)               | 1280x720
| FPS                         | 30

## Patches
* [{{ title_patch }} (engine_360.dll)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (engine_360.dll).patch.toml)
* [{{ title_patch }} (shaderapidx9_360.dll)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (shaderapidx9_360.dll).patch.toml)
* [{{ title_patch }} (tf-bin-Client_360.dll)](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} (tf-bin-Client_360.dll).patch.toml)

## Recommended config options
See game compatibility issue.
