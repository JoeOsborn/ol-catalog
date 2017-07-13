---
Title: Selection logics 
---

# Selection logics

## Communicative role

We can mark a subset of items out of a larger set as "selected", and there might be several currently active selections with different semantics. 

## Abstract process

Remember sets of selected objects out of larger sets, and pass around or enumerate those sets for other logics.

## Abstract operations

* Add or remove an object from a selection
* List the objects in a selection, or which could be selected
* Perform some action when objects are selected or deselected
* Constrain the maximum or minimum size of a selection

## Presentation

* Highlight the selected item graphically, by putting an icon next to it, or by altering or annotating its text label
* When a selection changes, play a visual or sound effect or have the selected/deselected item play an animation

## Required concepts

* Things that can be selected and types of selections

## Provided concepts

* Selected object identifiers and measures on selection sets

## Notes

These are often used for menus or for RTS control (interacting with control logic), but also show up in crafting systems and many other places.  Sometimes there are several selection categories which can be active at once, e.g. "the item slot you selected for 'from' and the item slot you are about to select for 'to'".
