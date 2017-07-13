---
title: Resource logics 
---
# Resource Logics

## Communicative role

Generic or specific resources can be created, destroyed, converted, or transferred between abstract or concrete locations.

## Abstract process

Creating, destroying, and exchanging (usually) discrete quantities of generic or specific resources in or between abstract or concrete locations on demand or over time; triggering other actions when these transactions take place.

## Abstract operations

* Check if a transaction involving some units of certain resources is possible for some given locations.
* Perform a resource transaction.
* Perform an action of another logic when a transaction occurs.
* Perform an action of another logic when the quantity of resources within a location crosses a threshold.

## Communicative strategies

* Resource types are icons or text, quantities are numeric labels, locations are distinct regions of the screen (Or, in textual logics, separate lines or sections of the text) 
* Resource types and quantities have intertwined representation, e.g. ten units of resource R appear as ten identical grouped icons or text labels communicating R; again, distinct regions of the screen express location (Or, in textual logics, separate lines or sections of the text)
  * This refers to e.g. Zelda "hearts" if the "capacity" of the location is also shown; this could also apply to health bars or what have you, where the length or color of a bar is a proxy for resource quantity
* As in the previous case, but different quantities of the same resource map onto different iconic representations * Transactions may be described as lists of prerequisite resources and quantities (as above) and lists of result resources and quantities (again as above, but not necessarily in the same way). The interface elements affording the execution of that transaction may be dimmed if the transaction is not allowed, or the individual prerequisite resources if they are not present, or the result resource indicators may be dimmed. (Where dimming may be broadly construed as affording non-interaction)
* An attempt to perform a disallowed transaction may be met with graphical, textual, or aural feedback
* When a transaction occurs, text labels indicating the resource and quantity (via color, size, text content, etc) may appear for a time on screen (perhaps near the locations the transaction took place) or more permanently in a log, possibly along with aural feedback or animations
* Locations with spatial semantics may be communicated as appropriate for those semantics, with resources assigned individually or in groups to "physical" objects in those spaces. Common examples include "inventories" in adventure and especially role playing games. In any event the communication is somewhat deferred to the other logics which provide the spatial model; often this spatial view is not used in e.g. crafting systems of the same game, where aggregate counts are used instead

## Required concepts

* Resource types
* Locations for resources
* A way to enumerate and count resources in those locations, e.g. to map a Diablo inventory onto a crafting system
* Ways to remove resources from and add resources to locations
  
## Provided concepts

* Resource transactions (available, allowed, and disallowed)
* Resource quantities and thresholds

## Notes

In many cases there will be only one location, or resources of a given type will only be created, etc. The generic/specific language used here distinguishes e.g. "Minerals" from "Copper Sword"s. The two types of locations are ones which cannot be physically located in the game (abstract) and those which can (concrete).

Cellular automata are a special case, especially since they are often communicated by mapping cells/locations onto physical space in a metric way, and quantities onto a dimension of space/color/etc
