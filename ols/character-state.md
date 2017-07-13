---
Title: Character-state logics 
---

# Character-state logics

## Communicative role

Game entities act in different ways or have different capabilities at different times, intrinsic to each such entity.

## Abstract process

Governing the finite, discrete states of a set of game characters or other entities. Updating states when necessary. Conditioning the operators of other logics on entities' discrete states.

## Abstract operations

* (Alter/Check) the discrete state of an entity according to a given (fixed) transition system.
* Whenever an entity's discrete state changes, perform some operators of this or another logic.
* Synchronize state changes between several entities.

## Presentation

* Change an entity's sprite, animation, or visual effects according to state.
* Textual or icon labels/descriptors to indicate state.
* Audio/visual/text effects on state change.

## Required concepts

* Entities
* Condition predicates for making transitions

## Provided concepts

* Entity states
* State transitions and related events

## Notes

Note that an entity may be attached to several concurrent transition systems, and these must be composed somehow. In this document, we use "discrete state" to refer to an entity's overall, combined state, e.g. "jumping while ducking" or "poisoned, hasted, and confused". [Concurrent Hierarchical State Machines](http://chsm.sourceforge.net) provide one possible semantics.

Also note that resource logics may also involve discrete state (e.g. number of health units), but this seems somewhat ambiguous with character-states (e.g. current set of power-ups; in a Metroid example, whether the Varia suit upgrade has been obtained). The key guidelines for whether such a piece of state is a resource or an entity-state are:

1. If the statistic "feels" more categorical than numeric (even if an ordering could be given), entity-state is likely more appropriate.
2. If the statistic is numeric and is ever "spent", or if it acts as a cap on a numeric resource which is spent, or if it otherwise engages with a resource economy in a similar way, it is likely a resource and not an entity-state.

In particular, RPG character statistics are usually best thought of as resources, whereas status effects are more like entity-states.
