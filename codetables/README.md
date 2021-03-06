# Codetable
This is my repository for a codetable class that manages information about lower bounds and constructions of linear codes. It uses Sagemath's coding theory module.

# Current functionality
These methods search for linear codes with optimal linear distance. First add some sage codes to the codetable. Next the methods look for optimal codes obtained through: shortenings, lengthenings, truncations, juxtaposition and (u|u+v) construction of the input. The best attained distance is stored in a dict. A human readable log of the construction for each length and dimension [n,k] is stored.

Please see instructions.py for a demonstration of how to use this class.

# Note:
I use the nonstandard term 'derived from' to mean 'obtained through code shortening or lengthening'. The results of these trivial transformations are:

Shortening: [n,k,d] -> [n-s,k-s,d]

Lengthening: [n,k,d] -> [n+s,k,d]
