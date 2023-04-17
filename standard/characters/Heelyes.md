# Heelyes
**Health**: 7
**Movement**: 4

### General Info 
Has mana between 1 and 6. After each turn one is replenished. Starts with 3 mana.

### Default Bonk
Tags: damage, time-interval = 2
One enemy on the 8 adjacent tiles get damaged by 1.

### Heal ally
Tags: healing, time-interval = 2
Consumes 1 mana. Heals an ally by 2 damage. Cannot be reacted upon by an enemy. Only up to the max health of the ally.

### Heal yourself
Tags: healing, time-interval = 3
Consumes 2 mana. Heals yourself by 2 damage. Cannot be reacted upon by an enemy. Only up to the max health of yourself.

### Emergency Tactics
Tags: movement, time-interval = 0
Consumes 2 mana. You can do two more actions with this character before your turn ends, but you can only use the abilities “Heal ally” and “Heal yourself”. If your mana runs out the second turn is lost.

### Mana Ball
Tags: damage, time-interval = 3
Consumes 4 mana. Throws a mana ball dealing 3 damage in one of the 4 diagonals.
If the mana ball hits a terrain piece it will destroy.
