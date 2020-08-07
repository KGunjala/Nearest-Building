Assuming a point of interest lies in the centre of the image, this code finds the nearest building or road in such a way that this point is "facing" the building or road.
The point - called the 'Anchor' pt - can lie in/on a building. The wall closest to this point would be our wall of reference from which the word "facing" takes its meaning. Here, facing is defined strictly
as being in a 90 degree field of vision to the wall of reference. If the 'Anchor' lies outside a building, then no such directional constraints are placed and the closest structure
is identified and the distance from this structure.
