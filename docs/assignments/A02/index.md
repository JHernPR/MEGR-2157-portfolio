# A2 – Truss Stress Analysis

## Objective
The purpose of this assignment was to design a truss with given parameters and distances from point to point, along with given loads at two of the points. We had a window from 20 to 30 kN to choose from; I went with 25 kN. The original prompt calls for A500 steel, but because SolidWorks doesn't have it, I chose AISI 1020 Steel, Cold-Rolled, and gathered any needed information directly from the SolidWorks Materials tab. The final design was modeled and analyzed in SolidWorks to verify whether it could meet the required strength and safety factors.

+ Design a lightweight planar truss using A500 steel or an alternative material.
+ Create free body diagrams (FBDs) for joints and critical pins.
+ Calculate the required cross-sectional area of truss elements with a safety factor.
+ Determine pin sizes based on shear forces with a safety factor.
+ Solve equations symbolically and numerically for both truss and pin design.
+ Estimate the total weight of the truss and pins.
+ Create a CAD model with accurate dimensions and connections.
+ Compare CAD weight predictions with hand calculations.
+ Document key engineering lessons learned from the process.

![Initial Blueprint](A2_blueprint.PNG)
## Analyze
The image shows the boundary and essential factors. The structure had two load points, one at D and one at C; these were 0.4 m apart horizontally. The force at point C was going towards the Joint, and at point D was going away from the Joint. Point A is a pin, and Point B is a roller. Point A is .4m away horizontally and .3m vertically from point D. The same information applies for point B in relation to point C. 


## Decide

![Initial Blueprint](A2_Initial_design.PNG)


_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

I chose a trapezoid-style geometry with internal beams to increase overall support, while keeping it simple. Using Pythagoras' theorem, I quickly calculated the lengths of BC and AD because they form a 3-4-5 triangle. The structure's symmetry also helped during the calculation process. Although it was an initial sketch, I included as much given information as possible to create a clear visual of my goal.

### Free-Body Diagram

![FBD](A2_FBD.PNG)
After crafting my initial design, I started creating free body diagrams for each joint algebraically to understand what was happening without doing the calculations first. I solved each Joint to find the horizontal and vertical forces. Although I only had to do one side and could've mirrored the formulas to the other side of the centerline, I solved them all as an extra step to validate my work. There were only seven forces to look for, as that's all the beams in the system. The other purpose behind the FBS's and doing it algebraically first is your brain isnt focused on numbers just yet, youre using common sense to find equilibriums. 

### Supports

![Supports](A2_Supports.PNG)

Once I sketched and properly labeled the FBDs with their respective forces, I started finding support reactions before solving for my forces, since these support reactions are essential to solving for internal forces. 

### Numerically Solving Formulas

![Num](A2_num_forces.PNG)

Now that I have all the information needed to solve for forces, it's just plug-and-play with my variables. One piece that stuck out to me during initial calculations was that there were only two force results, either positive or negative, between 20.83 kN and 16.66 kN. Beam CD ended up being zero, which makes sense as the system is symmetrical. 

### Cross Sectional Area

![Crossc](A2_crossectional.PNG)

Solving for all my internal forces numerically not only confirmed the structure is symmetrical but also confirmed equilibrium. This set of problems also identifies which beams are in compression and which are in tension; all of my answers for internal forces are correct, but the ones that say (c) are members acting in compression, while the other beams are in tension. As shown by the algebraic solution, you needed variables from the support reactions to solve for all internal forces. The way I wrote them down allowed me to start from top to bottom, solving these problems while pulling valuable info from the known variables. 

### Weight
![Weight](A2_Weight.PNG)
Now that I found my maximum internal force, I could start working on finding the cross-sectional area of the elements with a 3.5 safety factor

## Communicate




