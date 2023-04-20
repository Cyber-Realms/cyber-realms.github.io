---
layout: post
title: "Weekly Progress #5"
subtitle: "Camera Movement"
background: '/img/posts/Prototype/Proto2.png'
---


## What We Did

During this week, we were able to implement our camera movement as well as room changing. We decided to use Unity Cinemachine to control the camera. Using Cinemachine, we were able to set up soft zones and dead zones where the camera can and cannot go. These dead zones also represent when the camera will pull into the direction of the player. With the camera, we also created the teleporter between different rooms. By using empty game objects with a script that teleports the player to a selected game object, we were able to move the player between rooms. However, the rooms would stay active, so we made a script to act as a event control.

