# Egotists vs collaborationists
 Simple survival model where egotists compete with collaborationists

egostism_vs_collaboration.nlogo is a NetLogo file. 

In this model we start with two groups of equal user defined size. One group of isolated agents (blue turtles) and one group of agents linked between each other (each one creates 3 links with others, red turtles). 

Both agents lose energy at each tick and can regenerate when they sit on grass (a green patch). In that case, they "eat" the grass and their level of energy increases by a user defined quantity.

Grass appears randomly (3% of the time) by clusters of user-defined size.

Turtles can reproduce when they reach a certain level of energy (twice the birth energy). Their hatch comes in with a user defined birth energy).

Blue turtles move randomly in all directions to try and find grass.
Red turtles move randomly too but it one finds grass, it will call the linked turtles which will move on the same patch, assuming that more grass is around.
