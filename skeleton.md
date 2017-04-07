What happens to the layout when you resize the screen to less than 550px?
The grid lines stack on top of each other

How do you think that works?
Skeleton.css includes the following media query which means once the screen width
becomes less than 550px, the grid becomes active and the grid lines will stack on top of each other:
/* Larger than phablet (also point when grid becomes active) */
@media (min-width: 550px) {}
