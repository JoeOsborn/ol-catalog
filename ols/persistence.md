---
Title: Persistence logics 
---

# Persistence logics

## Communicative role

Some things in the world stay the same, for example across sessions, between rooms, or when scrolled offscreen; while others change or reset.

## Abstract process

Determining which entities, assets, and variables are in a particular scope (e.g., saved-game scope, current-level scope, visible-area scope) and persisting or resetting those as the scope changes.

## Abstract operations

* Determine or alter which persistence scopes are active.
* Set, clear, or restore the facts associated with a particular scope.
* Trigger an action of another logic when scopes change, are saved, or are restored.

## Presentation

* Give audiovisual feedback when scopes change or when variables have been reset.
* When the player is about to leave a scope, give textual descriptions of what data will be preserved and what will be lost.

## Required concepts

* Abstract objects and facts governed by scoping rules.
* A set of possible scopes.

## Provided concepts 

* Active and inactive scopes
* Save and reset events

## Notes

This is generally how you address concepts like "bullets disappear when they go off-screen" or "remember opened treasure chests and defeated bosses but not regular enemy health/positions".
