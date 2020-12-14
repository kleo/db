---
author: trainboy2019
autogen_scripts: true
categories:
- game
color: '#872217'
created: '2017-06-18T17:05:01Z'
description: Is this good?
download_page: https://github.com/trainboy2019/ButtonPresser3DS/releases/tag/2.0
downloads:
  3ds.zip:
    size: 1897892
    url: https://github.com/trainboy2019/ButtonPresser3DS/releases/download/2.0/3ds.zip
  ButtonPresser3DS.cia:
    size: 2289088
    url: https://github.com/trainboy2019/ButtonPresser3DS/releases/download/2.0/ButtonPresser3DS.cia
github: trainboy2019/ButtonPresser3DS
icon: https://raw.githubusercontent.com/trainboy2019/ButtonPresser3DS/master/icon.png
image: https://raw.githubusercontent.com/trainboy2019/ButtonPresser3DS/master/resources/Banner.png
layout: app
qr:
  ButtonPresser3DS.cia: https://db.universal-team.net/assets/images/qr/buttonpresser3ds.cia.png
scripts:
  ButtonPresser3DS.3dsx:
  - file: 3ds.zip
    message: Downloading 3ds.zip...
    output: /3ds.zip
    repo: trainboy2019/ButtonPresser3DS
    type: downloadRelease
  - file: /3ds.zip
    input: 3ds/ButtonPresser3DS.3dsx
    message: Extracting ButtonPresser3DS.3dsx...
    output: '%3DSX%/ButtonPresser3DS.3dsx'
    type: extractFile
  - file: /3ds.zip
    message: Deleting 3ds.zip...
    type: deleteFile
source: https://github.com/trainboy2019/ButtonPresser3DS
systems:
- 3DS
title: ButtonPresser3DS
update_notes: '<p>The buttons have gotten a few tweaks to make the app even better!</p>

  <p>Changes:</p>

  <ul>

  <li>Press up or down to change the color of your button.</li>

  <li>Press left or right to change the style of your button.</li>

  <li>You can now see how many times you''ve pressed the button!</li>

  <li>Press R to reset your score.</li>

  </ul>

  <p>Just scan this QR code!</p>

  <p><a target="_blank" rel="noopener noreferrer" href="https://github.com/trainboy2019/ButtonPresser3DS/blob/master/Button%20QR%20Code%202.png?raw=true"><img
  src="https://github.com/trainboy2019/ButtonPresser3DS/blob/master/Button%20QR%20Code%202.png?raw=true"
  alt="QR 2.0" style="max-width:100%;"></a></p>'
updated: '2017-06-22T02:42:08Z'
version: '2.0'
version_title: Button Presser 3DS 2.0
wiki: https://github.com/trainboy2019/ButtonPresser3DS/wiki
---