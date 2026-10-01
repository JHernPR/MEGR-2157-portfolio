# A6 – Bracket Drawing (Drawings Part 1)

## Objective
The objective of this project was to continue from last week's project using the bracket. This time, accounting for fits, along with making an engineering drawing that accurately represents your bracket and displays proper tolerances found from the book.

## Parametric Design
All of the dimensions were gathered from A5 using the stress calculations. Parts C and E will be different because I realized a crucial mistake and fixed it in my actual part. 

![Global](Parametric.PNG)

For my design, I went with the same structure that was given in A5, started with Part A and went all the way until Part E. While doing this, I was also declaring my assumed and determined variables. 

![P1](Part1.PNG) 
![P2](Part2.PNG)
![P3](Part3.PNG)
![P4](Part4.PNG)
![P5](Part5.PNG)
![apple](DefinedPart.PNG)

## Drawing 

![Drawing](A6drawing.PNG)

## Reflection 

Propagating a design change. I later found an error in the A5 calculation: I used the wrong formulas. This affected Parts C and E. After correcting the input parameter, Part E changed from .0667in to .6481in. Features that referenced that dimension, such as the heigh, updated automatically. The lesson is that a model only responds as completely as its relationships are defined. Any feature I dimensioned independently of the driving equation became a place where the error could survive.

Tolerance as a consequence of function. On the drawing, I applied [tight tolerance, e.g., ±.005] to the pin bore because it is a mating function where clearance directly determines whether the parts assemble and move as intended. I applied [loose tolerance, e.g., ±.02] to [feature, e.g., the overall bracket length] because it is a non-critical feature that does not mate with another part, so variation there does not affect function. Holding a non-critical feature to a tight tolerance would force slower machining, additional finishing operations, tighter inspection, and a higher scrap rate, raising cost without improving performance. Tolerance should be assigned feature by feature according to function.


