**Author:** Marduk1779
**Version:** 1
**Description:**  
Watches buffs/debuffs and sends messages to alts when you gain certain ones. Also, automatically uses Remedy if you get silenced, swaps gear if you get slept, holy waters for doom and uses panaceas for everything else.

**Abbreviation:** //medic

**Commands:**
 1. ifak watch &lt;buffname&gt; --adds buffname to the tracker
 2. ifak unwatch &lt;buffname&gt; --removes buffname from the tracker
 3. ifak trackalt --Toggles alt buff/debuff messages on main (this requires send addon)
 4. ifak sitrack --When sneak/invis begin wearing passes this message to your alts
 5. ifak list --lists buffs being tracked
 6. ifak toggle --Toggles off automatic item usage (in case you need this off. does not remain off across loads.)
 

ifak requires a sets.WakeUp to be defined in your gear lua to switch to that deals damage and wake you up else you will depend on cures.
ifak will also alert the party if you are chamred, terrorized or paralyzed.