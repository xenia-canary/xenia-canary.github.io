---
layout: single
title: "Batman: Arkham Asylum"
permalink: /BatmanArkhamAsylum/
categories:
    - Games
    - Games without 720p patch
    - Games without aspect ratio patch
    - Games without FPS patch
tags:
    - Game
title_ids: 5343080B
title_id_serials: SC-2059
media_ids: 71D29B88
---
{% capture title_patch %}{{ page.title_ids }} - {{ page.title | remove: ":" }}{% endcapture %}

| Box art                     |
| :-----:                     | :-
| ![Boxart](https://download-ssl.xbox.com/content/images/66acd000-77fe-1000-9115-d802{{ page.title_ids | downcase }}/1033/boxartlg.jpg)
| Title ID(s)                 | {{ page.title_ids }} ({{ page.title_id_serials }})
| Media ID(s)                 | {{ page.media_ids }}
| Game compatibility issue(s) | [master](https://github.com/xenia-project/game-compatibility/issues/165)
| Resolution(s)               | ####x###
| FPS                         | 60

## Patches
* [{{ title_patch }} GOTY](https://github.com/xenia-canary/game-patches/blob/main/patches/{{ title_patch }} GOTY.patch.toml)
