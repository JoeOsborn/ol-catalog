# Entity-state logics

Game entities act in different ways or have different capabilities at different times, intrinsic to each such entity, and communicated by different appearances or effects.

## Abstract process

Governing the finite, discrete states of a set of game characters or other entities. Updating states when necessary. Conditioning the operators of other logics on entities' discrete states.

## Abstract operations

* (Alter/Check) the discrete state of an entity according to a given (fixed) transition system.
* Whenever an entity's discrete state changes, perform some operators of this or another logic.
* Synchronize state changes between several entities.

## Communicative strategies

* Change an entity's sprite, animation, or visual effects according to state.
* Textual or icon labels/descriptors to indicate state.
* Audio/visual/text effects on state change.

## Interpretive affordances

* Lead-in/follow-through/stun/etc (combined with control logics)
* Temporary or permanent changes in health/condition (e.g. poison in an RPG setting)
* Intention, decision, and action (e.g. walking vs running, in concert with other logics)

## Authorial affordances

* Finite state machines
  * 1-hot encoding (one Boolean per state, of which only one is ever true)
  * "Current state" enum value
  * State pattern (object-oriented style)
* Ad-hoc sets of Booleans and enums (implicit state machines)
* Coroutines

## Ontological requirements

* Entities

## Ontological provisions

* Entity states
* State transitions

## Notes

Note that an entity may be attached to several concurrent transition systems, and these must be composed somehow. In this document, we use "discrete state" to refer to an entity's overall, combined state, e.g. "jumping while ducking" or "poisoned, hasted, and confused". [Concurrent Hierarchical State Machines](http://chsm.sourceforge.net) are one possible semantics; another is a simple product state machine with some combined states being forbidden.

Also note that resource logics may also involve discrete state (e.g. number of health units), but this seems somewhat ambiguous with entity-states (e.g. current set of power-ups; in a Metroid example, whether the Varia suit upgrade has been obtained). The key guidelines for whether such a piece of state is a resource or an entity-state are:

1. If the statistic "feels" more categorical than numeric (even if an ordering could be given), entity-state is likely more appropriate.
2. If the statistic is numeric and is ever "spent", or if it acts as a cap on a numeric resource which is spent, or if it otherwise engages with a resource economy in a similar way, it is likely a resource and not an entity-state.

In particular, RPG character statistics are usually best thought of as resources, whereas status effects are more like entity-states.
