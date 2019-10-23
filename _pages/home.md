---
permalink: /
title: ""

toc: true
toc_label: "Table of Contents"
toc_icon: "file-alt"
toc_sticky: true
---

# Personal Projects

## Monster Slayer GO
<div style="float:left;margin-right:20px;">
<video width="300" muted autoplay controls loop>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/images/audio.mp4" type="video/mp4">
</video>
</div>
Monster Slayer GO is a multiplayer, location-based RPG game. Players take on the role of a medieval knight in a fantasy world that is based on real map data. Features turn-based combat with various monsters, PvP battles, equipment, inventory, shop systems, and much more.

<b>Technical aspects:</b>
- [x] Client-server architecture. Whole game logic and data is on server with clients only displaying the view.
- [x] The backend is a Java Spring Boot application with REST API, hosted on Heroku. Frontend was created in Unity.
- [x] JSON format is used for serializing and transmitting structured data.
- [x] PostgreSQL relational database on the backend. [Click to see Entity Relationship Diagram (ERD).](/assets/diagrams/ERD.svg)
- [x] Integration with Mapbox Maps SDK for real map data. 
- [x] Sign-in with Google, Facebook or custom account with email verification. Integration with Firebase Authentication.
- [x] Free-to-play model with rewarded video ads and premium currency. Integration with Unity Ads and Unity IAP.
- [x] See some BPMN diagrams for more details about the app processes: [Sign-in](/assets/diagrams/sign-in.svg), [IAP](/assets/diagrams/IAP.svg), [PvP invitation](/assets/diagrams/pvp-invitation.svg), [PvP battle](/assets/diagrams/pvp-battle.svg).

<a href='https://play.google.com/store/apps/details?id=com.bstanasiuk.MonsterSlayerGo&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img width="250" class="align-center" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png'/></a>

## Volcano Runner
<div style="float:left;margin-right:20px;">
<video width="300" muted autoplay controls loop>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/images/audio.mp4" type="video/mp4">
</video>
</div>
Volcano Runner is an endless runner game placed on a 3D hexagonal grid. The player wakes up on a volcano that has just erupted. To survive he has to climb as high as possible, evade blowing geysers, and avoid falling into deadly lava at all cost.

<b>Technical aspects:</b>
- [x] Game was made in Unity.
- [x] Optimized for mobile devices (meshes, shaders, particles, map generation).
- [x] The volcano is fully procedurally generated. [Click to see it in action.](/assets/videos/test.mp4)
- [x] Different seed is used for every generated map. Each volcano is unique but still balanced for the gameplay.

<a href='https://play.google.com/store/apps/details?id=com.bstanasiuk.volcanorunner&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img width="250" class="align-center" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png'/></a>

## Checkers Extended
<div style="float:left;margin-right:20px;">
<video width="300" muted autoplay controls loop>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/images/audio.mp4" type="video/mp4">
</video>
</div>
Checkers Extended is another take on traditional checkers game with lots of customization options. Features different board sizes (6x6, 8x8, 10x10, 12x12), three game modes (local PvP, player vs AI, AI vs AI), scalable AI difficulty, and customization for other rules such as first move or move tip.

<b>Technical aspects:</b>
- [x] Game was made in Unity.
- [x] Negamax algorithm with alpha beta pruning was used for AI.
- [x] The decision making algorithm uses an original evaluation function and move ordering heuristics.
- [x] Checkerboard is procedurally generated and is scalable to any size. Due to smartphone hardware limitations, the size is constrained to 12x12 board.

<a href='https://play.google.com/store/apps/details?id=com.bstanasiuk.checkersextended&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img width="250" class="align-center" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png'/></a>

## VR Head Collisions

<div style="margin-bottom:15px;">
<video class="align-center" width="600" muted autoplay controls loop>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/videos/vr-collisions.mp4" type="video/mp4">
</video>
</div>

This experiment was part of my master's thesis: <i>Methods for implementing user movement in VR</i>. In the paper a comparison of selected algorithms used to handle VR head collisions was presented. The following four methods were chosen and implemented: screen fade, delayed push-back, instant push-back, and teleportation. The paper examined what effects these methods have on VR sickness, the sense of presence, and the usability level. The screen fade method turned out to be the most efficient one of the four solutions and should be the first choice for VR developers. [Click to read more in my master's thesis.](/assets/docs/master-thesis.pdf)

<div style="margin-bottom:60px; text-align: center">
<a href="{{ site.url }}{{ site.baseurl }}/assets/builds/VR-Collisions.zip" class="btn btn--primary">Download experiment (Windows only, HTC Vive required)</a>
</div>

# 48hr Game Jams

## Fifty-Fifty Game Jam 2019
<div style="margin-bottom:15px;">
<video class="align-center" width="600" muted autoplay controls loop>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/videos/vr-collisions.mp4" type="video/mp4">
</video>
</div>

<b>Game Title:</b> 
<br><i>Billy & Betty</i>

5th place at <i>Fifty-Fifty Game Jam</i> in 2019 with a theme of <i>long hair</i>.

<b>Meet the team:</b> 
<br>Dela Morcian - art
<br>Piotr Samborowski - game design
<br>Bartłomiej Stanasiuk - programming

<div style="margin-bottom:60px; text-align: center">
<a href="https://bstanasiuk.itch.io/billy-betty" class="btn btn--primary">Play in the browser on itch.io</a>
</div>

## TK Game Jam 2019
<div style="margin-bottom:15px;">
<video class="align-center" width="600" muted autoplay controls loop>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/videos/vr-collisions.mp4" type="video/mp4">
</video>
</div>

<b>Game Title:</b> 
<br><i>Super QZ0; Fighters</i>

1st place at <i>TK Game Jam</i> in 2019 with a theme of <i>synthetic / asylum / progress / contrast</i>.

<b>Meet the team:</b> 
<br>Bartosz Jakubczyński - game design
<br>Sebastian Kowalik - 3D modelling
<br>Adam Małek - programming
<br>Maciej Sozański - programming
<br>Bartłomiej Stanasiuk - programming
<br>Michał Winkler - programming

<div style="margin-bottom:60px; text-align: center">
<a href="https://reeposter.itch.io/qz0" class="btn btn--primary">Play in the browser on itch.io</a>
</div>

## Sensei Game Jam 2018
<div style="margin-bottom:15px;">
<video class="align-center" width="600" muted autoplay controls loop>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/videos/vr-collisions.mp4" type="video/mp4">
</video>
</div>

<b>Game Title:</b> 
<br><i>Samurai Showdown</i>

14tht place at <i>Sensei Game Jam</i> in 2018 with a theme of <i>darkness is your ally</i>.

<b>Meet the team:</b> 
<br>Michał Dunat - programming
<br>Jakub Misztal - game design, art
<br>Bartłomiej Stanasiuk - programming
<br>Kacper Szkodziński - game design
<br>Marta Włóczyk - art

<div style="margin-bottom:60px; text-align: center">
<a href="https://denaturatus.itch.io/samurai-show" class="btn btn--primary">Play in the browser on itch.io</a>
</div>

## Akademia F2P Game Jam 2017
<div style="margin-bottom:15px;">
<video class="align-center" width="600" muted autoplay controls loop>
    <source src="{{ site.url }}{{ site.baseurl }}/assets/videos/vr-collisions.mp4" type="video/mp4">
</video>
</div>

<b>Game Title:</b> 
<br><i>Squid Trouble</i>

5tht place at <i>Akademia F2P Game Jam</i> in 2017 with a theme of <i>free-to-play game</i>.

<b>Meet the team:</b> 
<br>Kinga Jaroszewicz - art
<br>Kornel Kocjan - game design
<br>Kamil Maślanka - programming
<br>Bartłomiej Stanasiuk - programming

<div style="margin-bottom:60px; text-align: center">
<a href="https://bstanasiuk.itch.io/squid-trouble" class="btn btn--primary">Play in the browser on itch.io</a>
</div>