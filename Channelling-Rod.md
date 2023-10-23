# Reverberation Rod
A casting item that keeps casting its hex every tick as long as you hold rclick. Acts like a trinket in that it can be recharged but cannot access external media supplies. Recipe involves an echo shard and a mindflayed component of some sort.

Uses the innate resonance of the echo shard to sustain the cast. Disruptions to this resonance (mishaps, or using Charon's Gambit to fully halt a hex) render the rod nonfunctional for a moment (applies a cooldown with the vanilla system like ender pearls and other casting items have).

Unlike wisps, it doesn't have any upkeep cost, but it also can't easily transfer arbitrary data between casts. There are, however, a few patterns specifically for this item.

# Clockwork Reflection
-> Num

When cast with a Reverberation Rod, returns how many ticks you've been channelling it for.

Note: With how this addon may have to hard-depend on Hexal, I might have Clockwork Reflection instead return the initial tick timestamp, so that you have to calculate ticks yourself using Timekeeper's Reflection.

# Baton Reflection
-> Vec

When cast with a Reverberation Rod, returns your look vector from the moment you began channelling.

# Baton Reflection II
-> Vec

When cast with a Reverberation Rod, returns your eye position from the moment you began channelling.
