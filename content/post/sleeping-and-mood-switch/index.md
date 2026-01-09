---
title: "Sleeping and Mood Switch: A Radar-Driven Sleep-to-Light Switch"
summary: "A 2018 build that uses a Walabot radar sensor and Raspberry Pi to detect sleep and toggle a relay-controlled light or device."

# Link this post with a project
projects: []

# Date published
# Use original project date
date: "2018-02-27T00:00:00Z"

# Date updated
lastmod: "2018-02-27T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

authors:
  - admin

tags:
  - Wearables
  - Arduino
  - Sensors
  - Prototyping

categories:
  - Projects
---

In 2018 I built **Sleeping and Mood Switch**, a prototype that connects sleep detection to the power switch of lights or other smart devices. The system uses a Walabot radar sensor and heart-rate/breathing signal patterns to decide when someone is asleep, then flips a relay to switch devices automatically.

## Project snapshot

- **Concept:** radar-based sleep detection drives a relay so lights or apps turn off when someone falls asleep.
- **Core hardware:** Walabot Developer Pack, Raspberry Pi 3 Model B, relay shield, and a simple LED test load.
- **Behavior:** if the Walabot signal statistics stay below thresholds, the relay toggles the light off; otherwise it stays on.

## Why I made it

I wanted a gentle, hands-free way to connect sleep to the environment. The goal was to stop bedtime stories or lights without checking in manually, saving energy and avoiding wake-ups.

## Code highlight

The core Python loop reads Walabot image energy, calculates simple statistics, and toggles a GPIO pin that drives the relay. The full script and setup steps are available in the project write-up.

## See the full build

- Full write-up, code, and photos: [Sleeping and Mood Switch on Hackster](https://www.hackster.io/user557511283/sleeping-and-mood-switch-691e96)
- Demo video: [YouTube walkthrough](https://youtu.be/Pjwq2aAWFH0)

If you build your own version, I’d love to hear how you adapt it for different lighting or environments.
