# Warhammer40brew

## Motivation 
Making a wargame that is fast paced, balanced enjoyable, allowing any player to play with any model from their collection. Warhammer 40k is a wargame that exist first and foremost to sell models and associated rulebooks, not to be a good game. 
A lot of odd design choices in mainline 40k (any edition) is a consequence of trying to differentiate units because they are separate product, not because it would make lore sense.  
 
   
## Identified problems

### Rule themselves           
The IGO UGO structure of the turn lead to very passive gameplay for one of the player       
The IGO UGO structure of the turns lead to a massive emphasis on player order : The one that get to shoot first at their opponent units have a massive advantage, or the one that manage to hide it's unit (eg  : reserve) get a massive advantage.           
Getting shot at is not very fun and uninteractive. You don't make choices outside of the odd stratagem or rerolling a failed save.          
Stratagems are a decent idea (meta special abilities) implemented badly and unevenly accross armies.            
Too many profiles for what is essentially the same thingy (eg : A boltgun vs a super special boltgun)                

### Datasheet
Some things that should be USR are not                    
Too many units have no defined roles or suck at it                    
Poor internal balance and poor external balance of too many armies                      
 
### Army building
Points are just a ressource in army building. You cannot balance everything with just points, as some armies have a very deep datasheet list or "aspect warriors" style units doing a job well with dedicated special weapons while others don't.     
    
### Missions          
While current rules are much better than past "kill everyone" or "score point for killing" missions, they feel very gamey and lack narrative that would justify sacrificing a chapter master and it's squad of terminators for 1 turn on an objective.              
Trading is encouraged, surviving is not.        

## Design philosophy 

-Players action should be fast paced and done as interactively as possible : EG being LOTR, Kill Team         
-Armies should have playstyles that separate them from each others             
-Each unit should have a role that their rules allow them to do well, so that balance can come from points/other ressource spending and not making a garbage unit so cheap that their new role become being a filler.      
-Similar guns should have the same profile accross all armies      
-All the rules to play a unit should be present on the datasheet         
-Army wide rules should fit on a single page          
-A ressource other than points need to exist to balance army composition
-Missions should be actual tactical puzzle to accomplish an objective, not just always a midfield brawl            
-Most guns should be able to shoot from one side of the table to the other    
-Indirect fire guns should award victory points, not hits 20m away. It makes defending those guns a compelling narrative for the attacker, and the defender is rewarded for doing so.             
    
In real life, the reason you don't have squad of 10 atgm or squad of 10 stingers is because one is enough to give a squad the ability do reliably deal with a threat, and it's much better to disperse those around a frontline for a greater coverage and then moving the asset in response to a threat rather than concentrating the asset from the beginning. 
On the tabletop, this sucks because a single missile launcher in a tactical squad doesn't really give you a reliable ability to deal with armoured threat, much betterto stack those ATGM in dedicated anti-tank squads and have this squad deal with a tank a turn.             
    
From this balance consideration, we get into a core decision of which level of verisimulute/overall gameplay we want our game to go : 
-High lethality if you are seen and a gun hit you you are dead           
-Gamey arcade health bars that slowly deplete                 
-Which level of rock/paper/scissors exist for units against each other ?                  
-Which level of reliability/lethality for weapon systems ? (eg : a missile deal always 10 damage a tank is 10hp but the missile hit only 1/3 of the time (average shot to kill per tank = 3), or a missile deal 5 damage, the tank is 10HP but the missile hit 2/3 of the time (average shot to kill per tank = 3).               
-How much accountant work on the tabletop (tracking wounds, variable profile, etc...)              
-Which level of abstraction : eg Each model fire and each loss depelete the unit firepower vs the unit fire as a whole until removed and models are just visual representation of HP for the unit)                   
 

Answers : 
Game should be "high swing" instead of "reliable". Reliable is better for video game, high swing better for "le epic narrative moment".               
Accounting should be limited to direct gameplay interactions              
Most infantry units should only have 1W : the model is either combat effective or mission kill. Mission kill doesn't mean that the model is dead, just unable to fight.                
        
Basic gameplay should be alternate activation            
When being shot at, player can order their unit to "take cover", giving the shot massively reduced lethality but also rendering the shot at unit combat ineffective for a turn.       


## USR     

### Guided-Missile
A unit containting a model firing a Guided-Missile can make no further movement this turn. Moreover, a shooting unit can only assign each target unit with only one Guided-Missile weapon per activation.

### Lock-On
If the model firing a Lock-On weapon had LOS on the target unit when the firing model unit was first activated this turn, add +1 to the hit roll.

### Fire and Forget
A Fire and Forget weapon that is also a Guided-Missile weapon ignore the restriction to movement of the Guided-Missile rule. The firing unit can move as if the weapon did not have the Guided-Missile rule.     
