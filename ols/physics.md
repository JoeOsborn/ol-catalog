---
title: Physics logics 
---

# Communicative role

Physical laws govern the movement of some in-game entities.

# Abstract process

Update and honor objects' physical properties like position, velocity, density, etc., according to physical laws integrated over time.

# Abstract operations

* Alter the physical properties of objects (mass, moment of inertia, coefficients of friction, etc).
* Apply impulses, continuous forces, heat, etc., to objects.
* Integrate physics forward (or rewind it backwards) for one or more objects.
* Determine an object's physical quantities based on terms from some other logic (e.g., character-state, resource).

# Presentation

* Map physical quantities like energy or mass onto visual qualities of the objects
* Show changes in physical quantities with visual or sound effects

# Required concepts

* Game entities, including their positions, shapes, and extents
* Physical properties of entities and the world

# Provided concepts

* Physical quantities and behaviors

# Notes

This is usually, but maybe not always, in simulated continuous time and space.
