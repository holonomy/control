# control

define how a holon controls itself

## design

In any implementation, a holon should be controlled by its subholons. Subholons determine the control mechanism when the holon is created. Various control mechanisms are possible, eg. subholons could possibly have different amounts of power in the holon.

## paradoxes

Consider an economy with 3^n individuals organized into holons into threes, then nines, all the way up to a root node, the world holon, in this height n, 3-splitting tree. Suppose every holon is controlled by a majority-rules voting process among its 3 subholons. Then to control the world holon, one only needs to control 2^n individuals: one must control two of the three subholons of the world holon, two of their subholons, and so on down to 2^n individual holons. 2^n may sound large, but it is a fraction of 3^n which tends to 0 exponentially fast as n increases.
