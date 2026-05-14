---
layout: post
title: 'Kinder x Harry Potter x Funko AR'
date: 'Jun 2025'
tag: 'WebAR | PlayCanvas | MediaPipe'
---

Web app and AR game for Kinder, launched as a special Easter treat in 2026: scanning the leaflet inside Kinder Eggs unlocks the experience. The game stars multiple **Harry Potter** characters in a quick, approachable chase built for short play sessions on mobile.

Players summon the **Golden Snitch** by scanning the card, then steer their chosen hero by **moving the phone** to chase it. The build runs in **PlayCanvas** with **gyroscope** input only, which keeps the interaction flexible and responsive. **Three difficulty levels** each tune snitch speed and drag so the challenge scales cleanly.

<div class="row post-gif-row">
  <div class="col-6">
    <img src="{{ site.url }}/projects/kinder-hp-funko/hpcollab-1.gif" class="img-fluid d-block mx-auto" alt="Kinder x Harry Potter x Funko AR — scan the leaflet to start">
  </div>
  <div class="col-6">
    <img src="{{ site.url }}/projects/kinder-hp-funko/hpcollab-2.gif" class="img-fluid d-block mx-auto" alt="Kinder x Harry Potter x Funko AR — Snitch chase gameplay">
  </div>
</div>

Completing the game unlocks a **Harry Potter–themed face filter** in a **Funko Pop**–style look: users can capture a photo or record a video. The filter follows the face using **[MediaPipe](https://github.com/google-ai-edge/mediapipe){:target="_blank" rel="noopener"}** face mesh tracking so the character sits naturally on different faces.

The experience was delivered for **Kinder Europe** and **Kinder China** in collaboration with the [Unit9](https://www.unit9.com){:target="_blank" rel="noopener"} team.

I acted as **Tech Lead** for the project, directing development and working closely with creatives to ship the full flow from leaflet scan through gameplay and the reward filter.
