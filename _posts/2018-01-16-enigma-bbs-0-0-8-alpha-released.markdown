---
layout: post
title:  "ENiGMA½ 0.0.8-alpha Released!"
date:   2018-01-16 00:00:00 +0000
categories: releases
---
ENiGMA½ 0.0.8-alpha has been released, merged to master as is available for install via all of the usual methods.

Some of the notable changes include:
* [Mystic BBS style](http://wiki.mysticbbs.com/doku.php?id=displaycodes) extended pipe color codes. These allow for example, to set "iCE" background colors.
* File descriptions (FILE_ID.DIZ, etc.) now support Renegade pipe, PCBoard, and other less common color codes found commonly in BBS era scene releases.
* New menu stack flags: `noHistory` now works as expected, and a new addition of `popParent`. See the default `menu.hjson` for usage.
* File structure changes making ENiGMA½ much easier to maintain and run in Docker. Thanks to RiPuk ([Dave Stephens](https://github.com/davestephens))! See [UPGRADE.md](https://raw.githubusercontent.com/NuSkooler/enigma-bbs/master/UPGRADE.md) for details.
* Switch to pure JS [xxhash](https://github.com/mscdex/node-xxhash) instead of farmhash. Too many issues on ARM and other less popular CPUs with farmhash ([Dave Stephens](https://github.com/davestephens))
* Native [CombatNet](http://combatnet.us/) support! ([Dave Stephens](https://github.com/davestephens))
* Fix various issues with legacy DOS Telnet terminals. Note that some may still have issues with extensive CPR usage by ENiGMA½ that will be addressed in a future release.
* Added web (http://, https://) based download manager including batch downloads. Clickable links if using [VTXClient](https://github.com/codewar65/VTX_ClientServer)!
* General VTX hyperlink support for web links
* DEL vs Backspace key differences in FSE
* Correly parse oddball `INTL`, `TOPT`, `FMPT`, `Via`, etc. FTN kludge lines
* NetMail support! You can now send and receive NetMail. To send a NetMail address a external user using `Name <address>` format from your personal email menu. For example, `Foo Bar <123:123/123>`. The system also detects other formats such asa `Name @ address` (`Foo Bar@123:123/123`)
* `oputil.js`: Added `mb areafix` command to quickly send AreaFix messages from the command line. You can manually send them from personal mail as well.
* `oputil.js fb rm|remove|del|delete` functionality to remove file base entries
* Users can now (re)set File and Message base pointers
* Add `--update` option to `oputil.js fb scan`
* Fix @watch path support for event scheduler including FTN, e.g. when looking for a `toss!.now` file produced by Binkd.

...and LOTS more!
                                                                    
For more info, check out [WHATSNEW.md](https://github.com/NuSkooler/enigma-bbs/blob/master/WHATSNEW.md), the 
[commits on GitHub](https://github.com/NuSkooler/enigma-bbs/commits/master) or try it out on Xibalba or fORCE9 BBS!                                                                          
