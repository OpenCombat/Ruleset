# I Like Pain
**Health**: 9  
**Movement**: 4  

### General
Has a damage meter that can store up to 6 received damage.

### Default Bonk
Tags: damage, time-interval = 3  
One enemy on the 8 adjacent tiles get damaged by 1 and damages himself by 1 damage.
If no enemy is present you can inflict self damage with this.

### The Pull
Tags: damage, time-interval = 3, movement  
Damages a character by the damage meter and pulls them to self. Only works if at least 1 damage in the meter as well as the character standing in one of the 4 cardinal directions with 1 space in-between you and the target. (2 range)
Only the target can react to this ability.
Resets damage meter

### The Ring of Damage
Tags: damage, time-interval = 5, aoe  
Damages enemies in a 5*5 area around yourself, based on the damage meter. This ability can only be used if your have more or equal damages stored than enemies in your vicinity. Every enemy takes the same damage determined by the damage meter divided by the count of enemies, rounded down.
If an enemy reacts upon this ability and blocks the damage for some other enemy he will receive twice the damage and the enemy chosen to remain unaffected will take no damage.
If an enemy reacts upon this ability and moves out of the damage area he will not take any damage. Every other enemy will take the same damage calculated beforehand.
Resets damage meter

### Grand Slam
Tags: damage, time-interval = 4  
Grabs one enemy in one of the 4 cardinal directions with maximum 1 space in-between yourself and the enemy (2range). This ability will deal all of the damage meter as damage.
You can only use this ability with at least 3 damage in the meter.
The enemy will be pushed back by 2 spaced and you will stand right next to the enemy afterwards. The pushback cannot be reacted upon. If a terrain piece comes before the 2 spaces the movement will be blocked by the terrain piece.
Resets damage meter
