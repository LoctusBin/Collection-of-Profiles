#**MAGE Leveing profile**
In the Frost version you can think of taking away the firespells and putting in some of the frost spells. Will update this with the time. The frost version is in alpha as for now. The setup is still the same.

###**ROTATIONS:**
**CONSUMABLE:**
- Drinks health potions when low
- Cast conjure and drink/eat
- Uses managem in combat if low on mana
- Few times use Evocation for mana regain

**BUFFS:**
- Frost Armor / Ice Armor
- Intellect
- Dampen magic
- Ice barrier before combat and in combat
- Mana Shield if really low on health
- Combustion if not up and out of battle

**PULLING:**
- Pyroblast if available
- If not will pull with Frostbolt
- Or else will pull with Fireball

**COMBAT:**
- Fireball as allways
- Scorch as final blow (sometimes?)
- Scorch later on to stack buff a little. (edit chance or remove if not spec)
- Use blastwave if over 2 enemies, if spec.
- Frost nova, then walk back a little. on 1 or over 2 enemies.
- Sheep if over 1 enemy. will sheep off target with macro.
- Fireblast on cooldown
- Wand if out of mana. (autoattack if no wand in the bars)


###**HOW TO USE:**

NB! You need to edit some Item ID's in the profile so it will not conjure for ever.
You will also need to edit scorch if you think it is spamming it and you dont have the talent. or if you place the sheep macro another place
every line you will need to edit are marked and easy to find.

Make the sheep macro and put it in bar 2 slot 9. or edit in profile.
This will target next target, cast sheep then go back to your last target.


**SHEEP MACRO:**

/script TargetNearestEnemy();

/cast Polymorph

/script TargetLastTarget()
