---
layout: default
title: Home
---
# Welcome to ENiGMA½ BBS Software!

ENiGMA½ BBS was started in October 2015, driven through a lack of diversity in the BBS scene and no modern open 
source solutions being available. You can read the original Reddit annoucement
[here](https://www.reddit.com/r/bbs/comments/3qmo35/enigma%C2%BD_bbs_software_on_github/).

ENiGMA½ is written in Node.js, and has a very active development community. Lead by [NuSkooler](https://github.com/NuSkooler),
numerous other developers have since contributed to the ENiGMA codebase and multiple boards have started to appear in 
the scene!

Some key features;
  - Multi platform: ENiGMA½ works anywhere Node.js runs (Linux, FreeBSD, OpenBSD, OS X and Windows)
  - Message networks with FidoNet Type Network (FTN) + BinkleyTerm Style Outbound (BSO) message import/export.
  - [Gazelle](https://github.com/WhatCD/Gazelle) inspired File Bases including full text search, #tags, and HTTP(S) temporary download URLs using a built in web server. Legacy X/Y/Z modem also supported!
  - Door support including common dropfile formats for legacy DOS doors. Built in [BBSLink](http://bbslink.net/), [DoorParty](http://forums.throwbackbbs.com/), [Exodus](https://oddnetwork.org/exodus/) and [CombatNet](http://combatnet.us/) support!
  - Telnet, SSH, and both secure and non-secure [WebSocket](https://en.wikipedia.org/wiki/WebSocket) access built in.
  - MCI code support for lightbars, toggles, input areas etc.

<center><iframe width="600" height="400" src="http://www.youtube.com/embed/6uyL5UHrjO4?modestbranding=1&showinfo=0" frameborder="0" allowfullscreen></iframe></center>

## Recent News

<ul class="posts">
    {% for post in site.posts limit:3 %}
    <li>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        <span class="posted-date">- {{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
    {% endfor %}
</ul>