---
author: TurtleP
categories:
- game
color: '#7a6a24'
created: '2015-08-29T03:59:28Z'
description: A fixed-axis shooter with netplay
download_page: https://github.com/TurtleP/TurtleInvaders/releases/tag/v1.0.2
downloads:
  TurtleInvaders.zip:
    size: 5546969
    url: https://github.com/TurtleP/TurtleInvaders/releases/download/v1.0.2/TurtleInvaders.zip
github: TurtleP/TurtleInvaders
icon: https://db.universal-team.net/assets/images/icons/turtleinvaders.png
image: https://db.universal-team.net/assets/images/images/turtleinvaders.png
layout: app
license: other
license_name: Other
scripts:
  TurtleInvaders.3dsx:
  - file: TurtleInvaders.zip
    message: Downloading TurtleInvaders.zip...
    output: /TurtleInvaders.zip
    repo: TurtleP/TurtleInvaders
    type: downloadRelease
  - file: /TurtleInvaders.zip
    input: TurtleInvaders.3dsx
    message: Extracting TurtleInvaders.3dsx...
    output: '%3DSX%/TurtleInvaders/TurtleInvaders.3dsx'
    type: extractFile
  - file: /TurtleInvaders.zip
    input: game
    message: Extracting game...
    output: '%3DSX%/TurtleInvaders/game'
    type: extractFile
  - file: /TurtleInvaders.zip
    message: Deleting TurtleInvaders.zip...
    type: deleteFile
  TurtleInvaders.cia:
  - file: TurtleInvaders.zip
    message: Downloading TurtleInvaders.zip...
    output: /TurtleInvaders.zip
    repo: TurtleP/TurtleInvaders
    type: downloadRelease
  - file: /TurtleInvaders.zip
    input: TurtleInvaders.cia
    message: Extracting TurtleInvaders.cia...
    output: /TurtleInvaders.cia
    type: extractFile
  - file: /TurtleInvaders.cia
    message: Installing TurtleInvaders.cia...
    type: installCia
  - file: /TurtleInvaders.cia
    message: Deleting TurtleInvaders.cia...
    type: deleteFile
  - file: /TurtleInvaders.zip
    message: Deleting TurtleInvaders.zip...
    type: deleteFile
source: https://github.com/TurtleP/TurtleInvaders
systems:
- 3DS
title: TurtleInvaders
update_notes: '<p>[Bugs Fixed]</p>

  <ul>

  <li>Shooting while using mega cannon</li>

  </ul>

  <p><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/59255b50350ba434ab35997b1a1d7b208de116605180173f0f268bf7e00edc8d/68747470733a2f2f63686172742e676f6f676c65617069732e636f6d2f63686172743f6368733d32353078323530266368743d71722663686c3d6874747073253341253246253246646c2e64726f70626f7875736572636f6e74656e742e636f6d253246752532463937363339333437253246547572746c65496e7661646572732e636961"><img
  src="https://camo.githubusercontent.com/59255b50350ba434ab35997b1a1d7b208de116605180173f0f268bf7e00edc8d/68747470733a2f2f63686172742e676f6f676c65617069732e636f6d2f63686172743f6368733d32353078323530266368743d71722663686c3d6874747073253341253246253246646c2e64726f70626f7875736572636f6e74656e742e636f6d253246752532463937363339333437253246547572746c65496e7661646572732e636961"
  alt="" data-canonical-src="https://chart.googleapis.com/chart?chs=250x250&amp;cht=qr&amp;chl=https%3A%2F%2Fdl.dropboxusercontent.com%2Fu%2F97639347%2FTurtleInvaders.cia"
  style="max-width:100%;"></a></p>'
updated: '2016-06-30T04:51:24Z'
version: v1.0.2
version_title: 3DS Stable Release 1.0.2
wiki: https://github.com/TurtleP/TurtleInvaders/wiki
---