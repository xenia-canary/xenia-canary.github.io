---
layout: single
title: Games
permalink: /games/
---

{% for games in site.games %}
- [{{ games.title }}]({{ games.url }})
{% endfor %}
