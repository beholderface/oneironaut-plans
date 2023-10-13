# Spatial Interchange
[vec, vec], [vec, vec], Imprint -> 

Exchanges the blocks contained within a cuboid in the dimension you're currently in with those within a cuboid in another dimension. The first set of vectors is used for your current dimension, and the second set is for the other one. The two cuboids must have the exact same dimensions (and rotation). If you are in the noosphere, the Imprint may be any non-blacklisted non-noosphere dimension. If you are in such a dimension yourself, the Imprint must point to the noosphere. Nonliving entities such as armor stands and minecarts are teleported automatically, any other entities must be sitting on/in a nonliving entity in order to be teleported.

Unbreakable blocks (such as bedrock) present within the cuboid on either side cause the blocks the unbreakable block's cuboid-relative coordinates on both sides to be unaffected. Blocks native to the noosphere (and many blocks crafted from them) are also unaffected, allowing you to more finely control a swapped area without having to calculate many smaller cuboids. Additionally, certain blocks seem... *reluctant* to exist in certain dimensions, resulting in them being treated as unbreakable if the swap would send them to such a dimension.

The cost is proportional to the volume of the cuboid, with each cubic meter in the volume (which is only counted once, not separately per-dimension) costing one amethyst dust. Blocks that are not transferred still count towards the cost. Non-decorative entities each add 5 charged amethyst to the cost.

All blocks in the cuboid in your current dimension must be within your ambit.

*Domain Expansion.*
