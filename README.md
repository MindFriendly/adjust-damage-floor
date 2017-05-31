# adjust-damage-floor
RPG Maker MV plugin: Modifies the amount of damage done by damage floor tiles
Region IDs can be used on top of damage floor tiles.

Allows developer to adjust default floor damage.
Can be a flat damage or percent of the characters HP.
=====================================================

Flat Values - Just enter in the number of HP you want the characters to lose.
(Default 10)

HP Percentage - Enter the decimal number of current HP you want the 
characters to lose. (1% == .01) Percentages of 100% or more and decimals of 
1.0 or more will be ignored at treated as 0.
 
When a Region ID is placed on a damage floor tile, the Region ID can be given
a specific value.
