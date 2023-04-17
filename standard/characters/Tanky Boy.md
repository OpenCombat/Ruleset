# Tanky Boy
**Health**: 11  
**Movement**: 3  

### General Info
Tanky Boy can only react to damage taken to himself not damage inflicted to allies.

### Default Bonk
Tags: damage, time-interval = 4  
Damages one enemy by 1 damage on one of the 4 cardinal directions. 1 range

### Guard Counter
Tags: only-reaction, time-interval = 0  
Halfs the taken damage from the attacker and inflicts 1 damage back to the attacker.
So you take the following damage floor(n / 2) → 3 damage would then inflict 1

### Interpose
Tags: time-interval = 3  
Swaps places with one adjacent ally on one of the 4 cardinal directions.
This can be used to react upon damage inflicted to allies.

### Low blow
Tags: damage, time-interval = 3  
Inflicts 2 damage to one enemy on one of the 4 cardinal directions.
The enemy taking the damage will be slowed for the next turn by 1 if their movement speed is under 5 and by 2 for everyone else. range 1
