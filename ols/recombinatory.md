---
Title: Recombinatory logics 
---

# Recombinatory logics

## Communicative role

Some things are built out of smaller (recognizable) things.

## Abstract process

From a fixed set of (possibly parameterized) atoms, build a structured object (a room, a dungeon, a description, a magic item) according to some rules and constraints (possibly conditioned on operators of other logics) with some optional post-processing.

## Abstract operations

* Generate an object or behavior out of some set of atoms with some parameters
* Enumerate valid outputs for some given constraints

## Presentation

* For text which is filled in a "mad libs" style, underline or otherwise highlight the dynamic part of the text
* Show a seed value identifying the generated object

## Required concepts

* Atoms to be recombined
* Conditions governing valid combinations

## Provided concepts

* Object/behavior generators
* Parameters and measures associated with generated objects 

## Notes

These can be used for procedural content generation or for monster formations or even for monster combat scripting, text generation, etc.

### Examples

Diablo rooms come from a fixed set and are connected arbitrarily through doorways; Rogue rooms come from a fixed set and are connected by gluing passages between them; Markov-chain text uses fixed characters and chooses the next according to the current character and some probabilities encoded in a Bayes network; Eliza produces a new string by picking a template based on whether key words were found in the input string by a pattern matching logic, with the templates parameterized by rooted/transformed versions of the input to the pattern matching logic.

These can roughly be characterized in terms of how complex the choice structure is, how many/how fine-grained the intermediate structures produced by the operators are, and how much post-processing is done to ensure consistency or otherwise “fix up” the generated stuff.  I suspect that constraint-solver-based methods would live in here too.
