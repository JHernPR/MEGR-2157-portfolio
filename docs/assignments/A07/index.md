# A7 – FEA Bracket





## Objectives:
- Use Finite Element Analysis (FEA) to improve the bracket design from previous assignments.

- Ensure high stiffness, strength, and lightweight optimization through iterative design.

- Conduct multiple FEA simulations, refining geometry based on results.

- Perform static stress analysis, including constraints, loading, and meshing selection.

- Interpret data by identifying max stress, displacement, and safety factors.

- Optimize the design by modifying geometry to enhance performance.

- Document the entire process with images, calculations, and insights.

- Reflect on key engineering lessons learned and time spent.

## Instructions

Your task is simply to create a high-stiffness, high-strength, and lightweight component. Use Finite Element Analysis to drive your design decisions throughout. At each analysis step, before making geometric changes, ensure the component results (stress/displacement/Safety Factor) converge to within 7%. Achieve this by modifying the number of elements. If after three attempts to converge use the stiffness and stress from the finer mesh size use the finest mesh size and proceed through the process.

## Initial

![Fixed](Fixed_geometryA7.PNG)
![Force](ForceApplied.PNG)

## Design 1 - Original Bracket

### Mesh 1: Coarse

![stressL](D1STRESSLOW.PNG)
![DispL](D1DISPLOW.PNG)
![FOSL](D1FOSLOW.PNG)

### Mesh 2: Mid
![stressM](D1STRESSMIDDLE.PNG)
![DispM](D1DISPMIDDLE.PNG)
![FOSM](D1FOSMIDDLE.PNG)

### Mesh 3: Fine
![stressH](D1STRESSHIGH.PNG)
![DispH](D1DISPHIGH.PNG)
![FOS1H](D1FOSHIGH.PNG)


| Design 1 | Coarse | Default | Fine |
| :--- | :--- | :--- | :--- |
| Max Stress (N/m^2) | 1.841e + 09 | 2.172e + 09 | 2.442e + 09 |
| Max Deflection (mm) | 5.192 | 5.745 | 1.000e -30 |
| Mass (lb) | 1.07 | 1.07 | 1.07 |
| Min FOS | .1358 | .1151 | .1358 |
| # Elements | 1425 | 9690 | 64165 |
| Stress % | | 15.2% | 11.0% |

Because the results did not converge, we will use the finest mesh simulation, as stated in the instructions.

## Second Design

### Mesh 1: Coarse

![stressL](D2STRESSLOW.PNG)
![DispL](D2DISPLOW.PNG)
![FOSL](D2FOSLOW.PNG)

### Mesh 2: Mid
![stressM](D2STRESSMIDDLE.PNG)
![DispM](D2DISPMIDDLE.PNG)
![FOSM](D2FOSMIDDLE.PNG)

### Mesh 3: Fine
![stressH](D2STRESSHIGH.PNG)
![DispH](D2DISPHIGH.PNG)
![FOS1H](D2FOSHIGH.PNG)

Second Design

| Second Design | Coarse | Default | Fine |
| :--- | :--- | :--- | :--- |
| Max Stress (N/m^2) | 1.741e + 09 | 2.157e + 09 | 2.440e + 09 |
| Max Deflection (mm) | 0.331 | 0.401 | 0.444 |
| Mass (lb) | 1.05 | 1.05 | 1.05 |
| Min FOS | 0.064 | 0.057 | 0.044 |
| # Elements | 1425 | 9690 | 64165 |
| Stress % | | 19.3% | 13.1% |

## Third design

![stressL](D3STRESSLOW.PNG)
![DispL](D3DISPLOW.PNG)
![FOSL](D3FOSLOW.PNG)

### Mesh 2: Mid
![stressM](D3STRESSMIDDLE.PNG)
![DispM](D3DISPMIDDLE.PNG)
![FOSM](D3FOSMIDDLE.PNG)

### Mesh 3: Fine
![stressH](D3STRESSHIGH.PNG)
![DispH](D3DISPHIGH.PNG)
![FOS1H](D3FOSHIGH.PNG)

| Third Design | Coarse | Default | Fine |
| :--- | :--- | :--- | :--- |
| Max Stress (N/m^2) | 5.869e + 07 | 5.480e + 07 | 5.172e + 07 |
| Max Deflection (mm) | 1.810e - 01 | 1.786e - 01 | 1.814e - 01 |
| Mass (lb) | 1.12 | 1.12 | 1.12 |
| Min FOS | 4.6 | 4.6 | 3.9 |
| # Elements | 1425 | 9690 | 64165 |
| Stress % | | 6.6% | 5.6% |
| Deflection % | | 1.3% | 1.6% |
| FOS % | | 0.0% | 15.2% |

After modifying the part, I achieved a deflection below 7%.

## Conclusion

Throughout this finite element analysis assignment, the bracket design underwent a rigorous iterative optimization process consisting of both inner-loop mesh convergence validations and outer-loop geometric modifications. Starting from the initial concept design (Design 1), high stress concentrations near the fillet regions resulted in a minimum factor of safety well below allowable limits. Through subsequent geometric improvements in Design 2 and Design 3, material was successfully redistributed to optimize the structure for enhanced strength and stiffness/ By the final iteration, the mesh convergence evaluations successfully dropped below the required 7% threshold, and the minimum factor of safety increased to a safe operating level between 3.9 and 4.6. This iterative process provided practical insights into how element size selection, computational solution time, and geometric profiling directly influence FEA accuracy and component performance.

## Part files

![Original](Design1JHA.SLDPRT)

![2nd version](Design2JHA.SLDPRT)

![3rd version](Design3JHA.SLDPRT)


## 2157 Only

## Third design

![stressL](P1STRESSLOW.PNG)
![DispL](P1DISPLOW.PNG)
![FOSL](P1FOSLOW.PNG)

### Mesh 2: Mid
![stressM](P1STRESSMID.PNG)
![DispM](P1DISPMID.PNG)
![FOSM](P1FOSMID.PNG)

### Mesh 3: Fine
![stressH](P1STRESSHIGH.PNG)
![DispH](P1DISPHIGH.PNG)
![FOS1H](P1FOSHIGH.PNG)


