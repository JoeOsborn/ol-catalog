* Consider turn ordering in fft, or action order in ff for that matter: I swept it under rug as resource logic but really there's some kind of scheduler I interpret as a player—ct and action charge times are not foregrounded enough in fft to suggest that, unlike atb in chrono trigger    
    * But as you play more you read it as a resource logic, or at least see how ct is spent on actions/movement and gained every tick. Charge time for actions is still mysterious and best understood using the at list--like actions are scheduled in ticks but characters get ct and activate when they have enough. There's not much support for a reading that actions are like characters but they clearly are separate from characters' ct and often speed    
* evaluation?? Necessary? Analytic vs empirical balance? Also an issue for advancement.    
* Composition of logics in Game Maker    
    In Game Maker (ignoring for a moment its textual scripting language), there are distinct languages for objects' /triggers/ and their /actions/; triggers include collision but also other predicates, and actions include physics behaviors as well as other changes to game state. The only forms of composition Game Maker supports in its graphical interface are causal implication, Boolean combination of predicates, and sequencing of actions; actions can also be conditioned on the same set of predicates. The predicates and actions themselves come from a variety of operational logics. ...
* Rpg entity script logic? Maybe separable from character state machine because not primarily graphical communication?    
    * Gotta work better at distinguishing state machine abstract process from character state logics from game modes From game progress or event scripting    
    * Ff7 uses per entity scripts and coroutines almost like gen servers; ff6 uses per entity instruction queues that the centralized event code sets up. Fft uses one centralized script that moves everybody else around.    
* OL accounting for FF will be tough, DQ3 even harder--char creation during play!    
* New OL Qs    
    * Are interpretive affordances only of one logics, or can they be of several? Are they recombinable? Are they different from micro rhetorics on the abstract end, or from visual perception on the concrete end?    
    * Do all affordances come from models?    
        * Interpretive? Authorial? Both?    
        * Can we call transform.x an authorial affordance of a collision or physics logic? No, it's of space/entity. What about velocity.y? Provided by physics, model of movement    
            * In a sense an "X logic" is a logic which induces a model of X (on its own?)    
                * What models are eligible for this single OL realization? Simple ones that don't have many operations or interfaces with cultural knowledge? Unambiguous ones that have limited instantiations? "Procedure"-y ones?    
            * So either: you can make a physics logic in PuzzleScript; or you can model physics in PuzzleScript without a physics logic.    
            * Are OLs just small models that recur frequently?    
                * Counter: how big before not an OL? Composition? Etc?    
            * Are models just big OLs with very abstract processes?    
                * Counter: implementability    
            * I think most logics have a corresponding model but they aren't the same thing. Logics are fewer and more composable than models? And a logic doesn't have to induce the same model in all its uses, unless the model is extremely abstract like "resources"    
            * Is it a logic iff you can define its abstract process (or other parts?) without reference to cultural knowledge?    
        * Are interpretive affordances of physical movement just gestalt stuff, or do they come from the model of space + the communicative strategy + the OL?    
            * I think we have to include the model of space in the interpretation, it can't be avoided, even if it's implicit in the mapping onto a 2d canvas    
            * Interpretive affordances of resource and collision logics are even more tightly bound to models    
            * The model has the obligations which the logic fulfills, and the model works for interpretation by players if its obligations are fulfilled    
            * Do all models come from OLs? Even e.g. space, persistent entities, ...? I think they must? Collision and physics create space.    
* Players come with a model in mind    
    * Partial model or partially justified model    
    * From game name, look of controller, cabinet, prior knowledge...    
* Players try to justify that model in terms of game behaviors/instantial assets? But they also do some bottom up reasoning from OLs, and hopefully that leads to the proposed model.    
    * If it doesn't, that's a "videogameism" or a "ludonarrative dissonance" or an "inconsistency/incoherence"    
    * Meaning derivations to nowhere    
* Mechanics are concrete OL engagements (even with instantial assets or some cultural knowledge??), while models can be satisfied by distinct combinations of mechanics/OL engagements--mechanics are like a shorthand for talking about OL related premises and inferences? "Jumping" mechanic really is "jumping model via..."