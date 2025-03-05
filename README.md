How to center an element with Position: Absolute

It is important having good sample practices to help people to understand how to utilize certain properties. 
A common question among begginers is how to centralize an element in a webpage. 

This simple project is just an exercise to explain how to align an object in the center of a container.

It is possible to use position: absolute to center an element on a webpage . Then, add top: 50% and left: 50%. 
It would just centralize the element, but the position would be a bit off since it would centralize the left
and top part of the element and not the middle of it. In this way, it is needed to use transform: translate(-50%, -50%). 
It will disconsider 50% on the top and left of the element which would make the element be aligned exactly 
in the middle of the container.

