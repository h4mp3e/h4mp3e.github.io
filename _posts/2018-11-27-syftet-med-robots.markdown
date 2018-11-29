---
layout: post
comments: true
title:  "Syftet med Robots.txt"
date:   2018-11-26 07:02:49 -0600
categories: jekyll update
---
Syftet med att ha en robots.txt är att berätta för robotarna på webben vad dem kan få tillgång till på webbsidan. 
Dock finns det "malware" robotar som letar efter sårbarheter och dem kan ignorera robots.txt och se allt på webbsidan ändå.
robots.txt-filen ska alltid läggas i "rotmappen", annars hittar inte robotarna den.

I och med att bland annat google kräver att få tillgång till css och javascript-filerna så har jag valt att ge alla robotar tillgång till mina eventuella css och javascript-filer.