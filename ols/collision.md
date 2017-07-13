---
title: Collision logics 
---

# Collision logics

## Communicative role

An illusion of physical space is provided by the fact that some game objects occlude the movement of others.

## Abstract process

Detection of overlaps between subsets of entities and/or regions of space and the automatic triggering of reactions when such overlaps occur.

## Abstract operations

* (Alter/Check) which entities could be said to collide with which other entities or regions of space (e.g. collision layers or flags, or hurt vs hit boxes)
* Check if two entities or regions are overlapping or touching
* (Alter/Check) the region of space taken up by an entity (e.g. grow or shrink an entity or change its collision polygon)
* Enumerate the entities or regions overlapping or touching an entity or region
* Separate the positions of two or more entities or regions such that they touch but do not intersect
* Determine how far an entity could move towards another entity or region without touching or causing an overlap
* Whenever a combination of the above checks becomes true (or remains true, or becomes false), perform some abstract operation of this or another operational logic involving the objects considered in those checks

## Presentation

* Shapes or images for each entity or region of space, whose extents and appearance correspond to the extents of the corresponding entity, and whose positions on screen correspond to their positions in space
* Sound effects or visual effects indicating collision when particular objects or re- gions of space begin/continue/cease to touch or overlap
* Textual descriptors detailing the sizes or shapes of entities and whether they are touching or overlapping
* The presence or absence of textual descriptors of entities when describing a region of space
* Textual messages describing the event when objects begin/continue/cease to touch or overlap

## Required concepts

* Entities and their positions
* Space

## Provided concepts 

* Collision
* Overlapping
* The extents of objects in space
