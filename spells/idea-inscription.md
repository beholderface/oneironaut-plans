# Idea Inscription
A way to store data in the noosphere, and access it from anywhere. Not a great spell, but it requires enlightenment. You do not have to be in the noosphere to use these, they work across dimensions.

Book entry says something like "Now that the barriers that once shackled my mind have been shattered, I seem to be able to access the space on the other side at my leisure. Perhaps a realm of thought like this would be a good place to store information."

# Inscribe Idea
Vec, Any ->

Records an iota to the noosphere at the coordinates represented by the vector, which gets floored before inscription. An iota stored in this manner lasts for approximately three in-game days before the media comprising the iota will have diffused too much to be readable. Casting this again at the same coordinates overwrites any previous iota, and refreshes the duration. Cannot write truenames. Costs 1 amethyst dust.

# Retrieve Idea
Vec -> Any

Fetches an iota from the noosphere which corresponds to the (floored) input coordinates. Returns Garbage if used with a vector with no existing iota. Costs 1 amethyst dust.



# Note:
I'm not sure how to implement this without it being "better akashic library". The iota decay is the only idea I have which isn't just "make it really expensive".
