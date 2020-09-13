version 2: not only outputs the distance to the nearest structure, but would also output the number of structures facing this point. This number can be termed as the visibility of the structure of interest. Visibility is computed within a certain angle/distance. 
This would be very useful while determining the optimal location to place advertisements where they might garner maximum visibility.

version 1: Assuming a point of interest, this code computes the distance from the nearest building or road in such a way that this point is "facing" the building or road.
The point - called the 'Anchor' pt - can lie in/on a building. The wall closest to this point would be our wall of reference from which the word "facing" takes its meaning. Here, facing is defined strictly as being in a 90 degree field of vision to the wall of reference. If the 'Anchor' lies outside a building, then no such directional constraints are placed and the closest structure is identified.
