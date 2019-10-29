---
layout: post
title: Simultaneous Sparklies
subtitle: A program to have LEDs mimic the flash patterns of fireflies, simultaneously
image: hannahtager.github.io/img/sparkliesPic.png
tags: [projects, electronic textiles, computer science]
comments: true
---

This program shows LEDs lighting up in 4 flash patterns of fireflies.  Pin 5 flashes brightly for a half second, every four seconds, starting at second 0.
Pin 6 flashes brightly for 0.2 seconds in a series of 3 flashes (separated by 0.1s each)
Pin 7 glows linearly every 3 seconds, increasing by 30 every 0.1 seconds.
Pin 8 sustains a continuous glow that fluctuates randomly by 50 every 0.5 seconds.

As a tip, I would say to not be too stubborn about using millis. That function is not great for a LilyPad output since there is a delay with any LED outputs that throws off the timing of the program.

Check out some of the LEDs at work below!

![Photo of the simultaneous sparklies project.](https://hannahtager.github.io/img/sparkliesPic.png)
