# A6 – Bracket Drawing (Drawings Part 1)

## Objective
The objective of this assignment was to advance the parametric design of the bracket developed in the previous project by incorporating precision sliding fits and creating a fully detailed engineering drawing. The design process focused on applying the stress and tolerance requirements determined in A5 to the CAD model. The final model and drawing were developed to accurately represent the functional geometry, assembly interfaces, dimensions, and tolerances required for manufacturing.

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

## 2157 Section
This is my work for the link using dimensions from last week. 
![Link](Bracket.PNG)
![Linkeq](Linkequations.PNG)
![Bracket](Bracketdrawing.PNG)

## Reflection 

Propagating a design change. I later found an error in the A5 calculation: I used the wrong formulas. This affected Parts C and E. After correcting the input parameter, Part E changed from .0667in to .6481in. Features that referenced that dimension, such as the heigh, updated automatically. The lesson is that a model only responds as completely as its relationships are defined. Any feature I dimensioned independently of the driving equation became a place where the error could survive.

Tolerance as a consequence of function. On the drawing, I applied [tight tolerance, e.g., ±.005] to the pin bore because it is a mating function where clearance directly determines whether the parts assemble and move as intended. I applied [loose tolerance, e.g., ±.02] to [feature, e.g., the overall bracket length] because it is a non-critical feature that does not mate with another part, so variation there does not affect function. Holding a non-critical feature to a tight tolerance would force slower machining, additional finishing operations, tighter inspection, and a higher scrap rate, raising cost without improving performance. Tolerance should be assigned feature by feature according to function.

While working on the link, I learned how important it is to ensure part-to-part compatibility through proper tolerancing. Tolerances help ensure that mating parts fit together as intended and can function properly without excessive interference or looseness. I also learned that dimensioning and tolerancing communicate the design intent and functional requirements of a part. A drawing should provide enough information for a machinist to manufacture the part accurately while avoiding unnecessary or confusing dimensions. Clear and properly applied dimensions and tolerances reduce the potential for manufacturing errors and help ensure that the finished part meets the intended design requirements.

## CAD Files & Drawings

![A6Part](A6JHA.SLDPRT)

![Link](BracketPiece.PNG.SLDPRT)

![Link Drawing](BracketPiece.PNG.SLDDRW)

![A6Drawing](A6JHA.SLDDRW)

