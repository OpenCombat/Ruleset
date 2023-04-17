# Geomancer
**Health**: 6  
**Movement**: 5  

### Default Bonk
Tags: damage, time-interval = 2  
One enemy on the 8 adjacent tiles get damaged by 1.

### Terraform
Tags: damage, time-interval = 5, forming  
Create a terrain piece in one of the 4 cardinal directions. Cannot be placed above allies.
If placed above an enemy the enemy gets to move in one of the 3 cardinal directions not occupied by anything. If there is no free space the enemy can move to he dies immediately

**Damage Map**:
| Max-Health | Damage taken |
| --- | --- |
| 1-6 | 2 |
| 7-9 | 3 |
| 10- | 4 |

Cooldown is 2 turns.

### The Shovel
Tags: time-interval = 4, forming  
Destroyed one terrain piece in one of the 4 cardinal directions.
Cooldown is 3 turns.
