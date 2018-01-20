---
layout: page
title: Features
permalink: /features/
---
ENiGMA½ is a modern BBS software with a nostalgic flair!


Some of the available features include:

 * Multi platform: Anywhere [Node.js](https://nodejs.org/) runs, ENiGMA½ works - Linux, FreeBSD, OpenBSD, OS X and Windows
 * [Message networks](docs/msg_networks.md) with FidoNet Type Network (FTN) + BinkleyTerm Style Outbound (BSO) 
 message import/export
 * [Gazelle](https://github.com/WhatCD/Gazelle) inspirted File Bases including indexed full text search (FTS), 
 hashtags, and HTTP(S) temporary download URLs using a built in [web server](docs/web_server.md). Legacy X/Y/Z modem 
 also supported!
 * [Door support](docs/doors.md) including common dropfile formats for legacy DOS doors. Built in 
  [BBSLink](http://bbslink.net/), [DoorParty](http://forums.throwbackbbs.com/), 
  [Exodus](https://oddnetwork.org/exodus/) and [CombatNet](http://combatnet.us/) support!
 * Unlimited multi node support (for all those BBS "callers"!)
 * **Highly** customizable via [HJSON](http://hjson.org/) based configuration, menus, and themes in addition to 
 JavaScript based mods.
 * MCI support for lightbars, toggles, input areas, and so on plus many other other bells and whistles.
 * Telnet, **SSH**, and both secure and non-secure [WebSocket](https://en.wikipedia.org/wiki/WebSocket) access 
 built in! Additional servers are easy to implement!
 * [CP437](http://www.ascii-codes.com/) and UTF-8 output.
 * [SyncTerm](http://syncterm.bbsdev.net/) style font and baud emulation support. Display PC/DOS and Amiga style 
 artwork as it's intended! In general, ANSI-BBS / [cterm.txt](http://cvs.synchro.net/cgi-bin/viewcvs.cgi/*checkout*/src/conio/cterm.txt?content-type=text%2Fplain&revision=HEAD) / [bansi.txt](http://www.bbsdocumentary.com/library/PROGRAMS/GRAPHICS/ANSI/bansi.txt) are followed for expected BBS behavior.
 * Full [SAUCE](http://www.acid.org/info/sauce/sauce.htm) support
 * Renegade style pipe color codes
 * [SQLite](http://sqlite.org/) storage of users, message areas, and so on
 * Strong [PBKDF2](https://en.wikipedia.org/wiki/PBKDF2) backed password encryption
 * [Bunyan](https://github.com/trentm/node-bunyan) logging
 * Upload processor supporting [FILE_ID.DIZ](https://en.wikipedia.org/wiki/FILE_ID.DIZ) and 
 [NFO](https://en.wikipedia.org/wiki/.nfo) extraction, year estimation, and more!
 * ANSI support in the Full Screen Editor (FSE), file descriptions, and so on.
 
 ....and much much more!