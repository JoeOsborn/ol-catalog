# Resource Logics

## Abstract process
Creating, destroying, and exchanging (usually) discrete quantities of generic or specific resources in or between abstract or concrete locations on demand or over time. In many cases there will be only one location, or resources of a given type will only be created, etc. the generic/specific case distinguishes e.g. "Minerals" from "Copper Sword"s. The two types of locations are ones which cannot be physically located in the game and those which can.

Cellular automata are a special case, especially since they are often communicated by mapping cells/locations onto physical space in a metric way, and quantities onto a dimension of space/color/etc

## Abstract operations

* Check if a quantity Q of a resource R in a location L exceeds a threshold (or an aggregate of such quantities across different locations)  
* Check if a transaction T is possible, where transaction T consumes Qi units of resources Ri in locations Li and produces Qj units of resources Rj in locations Lj, possibly with additional guards borrowed from other logics. Other guards may include "is there enough physical space in a location to contain the new resources"
* Perform such a transaction  
* Perform an action of another logic whenever a transaction T occurs or the number of resources (in a location?) changes  
* Perform a transaction T whenever a condition of another logic becomes true  

## Communicative strategies  
* Resource types are icons or text, quantities are numeric labels, locations are distinct regions of the screen (Or, in textual logics, separate lines or sections of the text)  
* Resource types and quantities have intertwined representation, e.g. ten units of resource R appear as ten identical grouped icons or text labels communicating R; again, distinct regions of the screen express location (Or, in textual logics, separate lines or sections of the text)  
  * This refers to e.g. Zelda "hearts" if the "capacity" of the location is also shown; this could also apply to health bars or what have you, where the length or color of a bar is a proxy for resource quantity  
* As in the previous case, but different quantities of the same resource map onto different iconic representations  
* Transactions may be described as lists of prerequisite resources and quantities (as above) and lists of result resources and quantities (again as above, but not necessarily in the same way). The interface elements affording the execution of that transaction may be dimmed if the transaction is not allowed, or the individual prerequisite resources if they are not present, or the result resource indicators may be dimmed. (Where dimming may be broadly construed as affording non-interaction)  
* An attempt to perform a disallowed transaction may be met with graphical, textual, or aural feedback  
* When a transaction occurs, text labels indicating the resource and quantity (via color, size, text content, etc) may appear for a time on screen (perhaps near the locations the transaction took place) or more permanently in a log, possibly along with aural feedback or animations  
* Locations with spatial semantics may be communicated as appropriate for those semantics, with resources assigned individually or in groups to "physical" objects in those spaces. Common examples include "inventories" in adventure and especially role playing games. In any event the communication is somewhat deferred to the other logics which provide the spatial model; often this spatial view is not used in e.g. crafting systems of the same game, where aggregate counts are used instead  

## Interpretive affordances  
* Gain/loss  
* Growth (Physical, emotional, mental...)  
* Decay  
* Trade  
* Production  
* Harm  
* Recovery  
* Qualification ("you must be at least this tall")  
* ?  

## Authorial affordances  
* Numeric variables
* multisets
* Petri nets
* term rewriting
* arrays
* aggregators
* ...  

## Ontological requirements  
* Resource types  
* Locations for resources  
  * And a way to enumerate and count resources in those locations, e.g. to map a Diablo inventory onto a crafting system  
  * And ways to remove and add resources from/to those locations, again with the example being inventory vs crafting  
  
## Ontological provisions  
* Resource transactions  
* Resource quantities  
