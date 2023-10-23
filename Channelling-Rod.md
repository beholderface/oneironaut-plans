# Channelling Rod
A casting item that keeps casting its hex every tick as long as you hold rclick. Acts like a trinket in that it can be recharged but cannot access external media supplies. Crafted using a mindflayed component of some sort.

Unlike wisps, it doesn't have any upkeep cost, but it also can't easily transfer arbitrary data between casts. There are, however, a few patterns specifically for this item. Additionally, using Charon's Gambit to fully exit a cast kicks you out of channelling by applying a 1-second cooldown to the rod (in the vanilla method similar to ender pearls and other casting items).

# Clockwork Reflection
-> Num

When cast with a Channelling Rod, returns how many ticks you've been channelling it for.

Note: With how this addon may have to hard-depend on Hexal, I might have Clockwork Reflection instead return the initial tick timestamp, so that you have to calculate ticks yourself using Timekeeper's Reflection.

# Paintbrush Reflection
-> Vec

When cast with a Channelling Rod, returns your look vector from the moment you began channelling.

# Paintbrush Reflection II
-> Vec

When cast with a Channelling Rod, returns your eye position from the moment you began channelling.
