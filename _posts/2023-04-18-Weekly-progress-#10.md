---
layout: post
title: "Weekly Progress #10"
subtitle: "Sprite and UI Fixes"
background: '/img/spriteUI.png'
---


## What We Did

For this week, we had a bit of issues getting the gun working with our player sprite. During our first prototype, one of the feedback we got was to implement a way to tell where the cursor is so the player knows where they are shooting. We decided to use a gun model and rotate it around the player wherever the mouse goes so that the player knows where they are aiming. Along with this, we had an issue with the dash bar in our UI. When the dash is pressed repeatedly, it would keep triggering the bar to empty even if the player could not dash. As such, we quickly fixed that bug so that it would only do the animation when the player's dash was used. 

![](/img\posts\uiSample.png)
UI

![](/img\spritesheet.png)
Player Sprite