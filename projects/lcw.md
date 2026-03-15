---
layout: post
title: 'London Craftweek Fashion Show'
date: 'May 2022'
tag: 'Light Design | WLED | ESP32'
---
Light design and AV show for [Clara Pinto](https://www.instagram.com/laclarapinto/){:target="_blank" rel="noopener"}'s fashion show during London Craftweek 2022.

Together with a team of wonderful artists and designers ([@catalinajoy](https://www.instagram.com/catalinajoy/){:target="_blank" rel="noopener"}, [@kamolaaskarova](https://www.instagram.com/kamolaaskarova/){:target="_blank" rel="noopener"}) we intervened the Argentinean Ambassador's residence in London to convert it into a surreal landscape. From what you see on the left to what you see on the right:

![London Craftweek Clara Pinto Fashion Show]({{ site.url }}/projects/lcw/lcw-1.jpg)

Inspired by videogame visuals, our goal was to turn the runway into a playful journey with highlighted stops where the models would pause and reveal the designs. I built custom LED controllers based on ESP32 that run [WLED](https://kno.wled.ge/){:target="_blank" rel="noopener"} and can be controlled over-the-air using Artnet DMX. The rest of the stage lights in the setup are also controlled in realtime using DMX. The software used to run the show was [Protopixel](https://www.protopixel.io/){:target="_blank" rel="noopener"}. Here are some pics of the final result:

{% include slide-carousel.html id="lcwCarousel" images=site.data.lcw.images alt="London Craftweek Clara Pinto Fashion Show" %}

Here is a video of the show:
<iframe width="100%" height="330" src="https://www.youtube.com/embed/aPoZaW3Fb3c" frameborder="0" allowfullscreen></iframe>

More pics in [this post](https://www.instagram.com/p/CdbHcJVI0dk/){:target="_blank" rel="noopener"}.
