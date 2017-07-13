---
Title: Game Mode logics 
---

# Game Mode logics

## Communicative role

The game switches between different screens in which different controls, information, and actions are available.

## Abstract process

Set up, activate, suspend, and clean up different game modes (potentially in parallel) like title screens, save/load screens, navigation versus menu or battle modes, etc.

## Abstract operations

* Activate a new game mode, optionally deactivating the old mode
* Determine the currently active game modes

## Presentation

* Change the visual layout of the screen, the background, or some text to illustrate the active mode
* Play a transition visual or sound effect to highlight a change in mode

## Required concepts

* A set of game modes and conditions under which they might change

## Provided concepts

* Which game modes are currently active

## Notes

This will often work in concert with persistence logic so that while you're in the in-game menu or pause screen nothing changes in the world.
