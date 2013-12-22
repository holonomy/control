# control

define how a holon controls itself

## design

In any implementation, a holon should be controlled by its subholons. Subholons determine the control mechanism when the holon is created. Various control mechanisms are possible, eg. subholons could possibly have different amounts of power in the holon.

## paradoxes

Consider an economy with 3^n individuals organized into holons into threes, then nines, all the way up to a root node, the world holon, in this height n, 3-splitting tree. Suppose every holon is controlled by a majority-rules voting process among its 3 subholons. Then to control the world holon, one only needs to control 2^n individuals: one must control two of the three subholons of the world holon, two of their subholons, and so on down to 2^n individual holons. 2^n may sound large, but it is a fraction of 3^n which tends to 0 exponentially fast as n increases.

Though the 2^n control the world holon, they control a tiny minority of all holons, (2/3)^(n-m) at height m, so in particular control very little of the low level holons. Thus, if resources are concentrated at the bottom, this is not actually as powerful a position for the 2^n as it might first appear.

Further, this setup is unstable in that if any of the 2^n individuals defects, control of the world holon is lost. The setup can be made more robust by adding membership relations among the holons controlled by the 2^n. However, the 2^n control a small minority of all holons, so if membership relations are added at random, many relations between the holons controlled by the 2^n and the rest will be added, and these tend to break control of the world holon.
