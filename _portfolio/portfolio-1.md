---
title: "spotiFUCK"
excerpt: "more than 2TB database of FREE music streaming live from my Linux server in Corticella, Bologna"
collection: portfolio
---

In a world increasingly dependent on the cloud, having knowledge and tools that no one can disable or charge you for becomes increasingly important.<br/>I never suffered Spotify, Deezer, Amazon/Youtube Music and many other music streaming services that bind you to subscriptions and fees, so I built-up my own music streaming system based on Subsonic project and customized for my needs.<br/> It streams directly from my home Peppermint 10 linux server in Bologna providing almost 2TB of high-quality music collection.<br/>
The mantra is <em>no advertising, no costs, no interruptions</em> opposite to the most famous subscription apps philosophy!

<img src='/images/spotifuck_bckgnd.png' width="20%">

SOME TECH. INFO ABOUT ARCHITECTURAL SCHEMA, INFO, ETC.

- Host: Asus eeePC Seashell - Intel Atom N550 @ 1.50GHz - RAM 2GB
- OS: Peppermint 10 Linux (based on Ubuntu 18.04 LTS)
- Backend engine: Subsonic Premium 6.1.6 (build 0cfa60)
- Server: Java 8 - jetty-6.1.x, java 1.8.0_362
- https redirect: local NGINX server configuration
- Database: in-process/embedded HSQLDB
- NAS management and sharing: Samba SMB/CIFS + SSH
- Custom registration page: Python backend + HTML5 frontend
- Download sources and sharing: CD-ripping, Torrent, Soulseek
- MP3 transcoding: ffmpeg tool based on libmp3lame
- ID3 tag management: python scripts based on Beets + MusicBrainz
- Internationalization & translation: i18next
- Icons, fonts & images: fontawesome.com

<img src='/images/diagram_black.png' width="66%">

[ENJOY SPOTIFUCK!](https://erick.ns0.it)


