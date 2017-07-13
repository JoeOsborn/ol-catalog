---
title: Control logics 
---

# Communicative role

Different entities are controlled by different inputs at different times.

# Abstract process

Map button inputs, AI intentions, network socket messages, etc onto high-level game actions, possibly grouped onto specific loci of control like characters according to the event source.

# Abstract operations

* Change which character the player (or another event source) is controlling
* Change the mapping between low-level inputs and high-level actions
* Determine the available high-level actions at a given time for a given actor

# Presentation

* Show a graphical indicator like a triangle or colored circle around the character being controlled (perhaps mapping colors to event sources).
* List the available moves for an actor in a menu overlay.
* Show a picture of e.g., a keyboard or a controller with labeled lines illustrating which buttons perform which high-level actions.

# Required concepts

* High-level actions
* Event sources/actors
* Loci of control (e.g., game entities)

# Provided concepts

* Available actions for a given actor
* Which actor controls which locus
* Which actors are present/active
