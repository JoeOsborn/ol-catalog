#Collision logics
##Abstract process
Detection of overlaps between subsets of entities and/or regions of space and the automatic triggering of reactions when such overlaps occur.
##Abstract operations
* (Alter/Check) which entities could be said to collide with which other entities or regions of space (e.g. collision layers or flags, or hurt vs hit boxes)
* Check if two entities or regions are overlapping or touching
* (Alter/Check) the region of space taken up by an entity (e.g. grow or shrink an entity or change its collision polygon)
* Enumerate the entities or regions overlapping or touching an entity or region Separate the positions of two or more entities or regions such that they touch but do not intersect
* Determine how far an entity could move towards another entity or region without touching or causing an overlap
* Whenever a combination of the above checks becomes true (or remains true, or becomes false), perform some abstract operation of this or another operational logic involving the objects considered in those checks
##Communicative strategies
* Shapes or images for each entity or region of space, whose extents and appearance correspond to the extents of the corresponding entity, and whose positions on screen correspond to their positions in space
* Sound effects or visual effects indicating collision when particular objects or re- gions of space begin/continue/cease to touch or overlap
* Textual descriptors detailing the sizes or shapes of entities and whether they are touching or overlapping
* The presence or absence of textual descriptors of entities when describing a region of space
* Textual messages describing the event when objects begin/continue/cease to touch or overlap
##Interpretive affordances
* Solidity (walls, barriers, shields, ...)
* Harm (with appropriate character-state or resource logics)
* Safety (if presence of an entity in a region of space prevents access by an opposed entity, or helps the first entity in some way)
* Obtention (with appropriate logics, or by changing the shape of the obtaining or obtained entity, or removing the obtained entity)
* Connection (if multiple entities remain touching or overlapping while moving, or an entity simultaneously overlaps or touches two or more non-adjacent entities) Occlusion (requires/implies 3D space, even if trivial depth axis)
* Constrained vision (e.g. in stealth games)
* Selection (moving into a region to select an option, or moving a cursor) Targeting (with a crosshairs or reticle sprite)
##Authorial affordances
* Geometric collision detection
* Spatial data structures (broad/narrow phase)
* ...
##Ontological requirements
* Entities
##Ontological provisions 
* Space
* Regions of space
* Position of entities in space
* Shapes and extents of entities in space