# A8 – Gears

## Objective
- Design a gearbox that can be assembled and disassembled.

- Analyze and size input and output shafts for strength.

- Design journal bearings to support shafts.

- Create a gearbox housing with proper clearance and fastening.

- Use parametric CAD modeling to generate a final design.

- Document calculations, sketches, and lessons learned.

Description:

Design a gearbox that can be assembled and disassembled. The spur gears have a gear ratio of 24:9 and are listed in the resource section. The output gear torque and speed are to be 1.25 in-lbf and 1100 rpm, respectively. The input (pinion,power-transmission) and output (gear, short shaft) shaft diameters are .125 and .25 inches respectively and each have a length of 1 inch. Use the appropriate equations in the Machinery’s Handbook for empirical units. The critical features of the gearbox include the shafts and the journal bearings.

## Input Shaft Design

This analysis verified that the baseline 0.125-inch diameter and 1in length of the input (power-transmission) shaft are structurally sufficient to withstand the applied operating loads. Accounting for the 24:9 gear ratio, the input speed and torque were scaled to 2933.33 RPM and 0.46875 in · lbf, respectively. After formulating the free-body diagram and modeling the torsional shear stress equations from the Machinery's Handbook, the numerical shear stress was evaluated at 1222.30 psi, well below the allowable yield strength of 4000 psi. Furthermore, solving for the minimum required diameter yielded approximately 0.0841 in (compared to the 0.125 in baseline), confirming that the initial dimensions are more than sufficient and require no modification.

![hellothere](PWRSHAFT.PNG)

## Output Shaft Design

For the output (short) shaft, the design process mirrored the input analysis to evaluate structural integrity under the direct output specifications of 1100 RPM and 1.25 in*lbf torque across a 0.25 in diameter and 1 in  length. Utilizing an allowable yield strength of 8500 psi, the torsional equations were modeled algebraically and solved numerically. The resulting shear stress was calculated to be 407.43 psi, safely below the allowable limit. Additionally, the minimum required diameter was calculated to be approximately 0.0910 in, validating that the baseline 0.25 in shaft diameter provides an ample safety margin and is completely adequate for the gearbox assembly.   

![GeneralKenobi](ShortShaft.PNG)

## Design Journal Bearings.


![yep](BearingMaterial.PNG)

## Journal Bearing Thickness

![si](BearingThickness.PNG)

## Gearbox Hand-drawn Design

## Modeling & CAD

