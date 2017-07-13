---
title: Camera logics 
---

# Communicative role

What we see is one of potentially several viewports onto a game world, and our viewport can pan, zoom, rotate, etc.  On-screen and off-screen parts of the world might act differently, and we might see several viewports at once.

# Abstract process

Moving or altering the shape or position of a camera's projection; mapping this onto other surfaces, e.g., a sub-region of the game screen.

# Abstract operations

* Alter the world position of the camera or other aspects of its transform (e.g., pan, zoom, rotate)
  * Potentially performing some camera wipe or other transition
* Choose whether or not to draw certain objects on certain cameras

# Presentation

* Show the viewport on the game screen where the player can see it
* Project the viewport onto something in world space

# Required concepts

* World coordinate space

# Provided concepts

* Camera views
