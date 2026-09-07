# A3 – [Parametric Bar Design and FEA Analysis]

## Objective
- Use axial deflection modeling to design its dimensions
- Use parametric design to determine a bars length
- Introduce you to FEA (Finite Element Analysis)
- Introduce you to linking dimensions to appropriate parameters in CAD.
- Compare and contrast the different analysis

**Description**

We are told to design a bar which needs to have a circular cross section that has the values of the criteria given for the material, max deflection, and the load. We need to determine the bar's minimum geometry through a parametric design while it is under direct tension, then verify the geometry through finite element analysis.


## Analyze

**1(a,b,c): Parametrically design a bar in CAD with an applied direct load between 300 lbf < F < 500 lbf. The max axial deflection of the bar is .009 inches. The bar is to be designed from Aluminum with a range of Young’s Modulus from (8.5 - 11.5) x 106 psi.**

**(a,b):** After reading through all the given parts of the assignment, I started by choosing my Cross Sectional Area. For the circular bar, I decided to go with a diameter of 0.55in which gave me a cross sectional area of 0.2376in^2, I decided to use 400lbf to make sure I am within that 300lbf to 500lbf direct load range. Below is a image of my calculations where I solved for the parametric length for my CAD model length, where I ended on a length of 53.46 inches. I decided to do a deflection check as well to make sure that was within the 0.009in max axial deflection range and while I was within the range of < 0.009 max deflection, I was a little to close for comfort only being 0.00008 within the range. 

<img width="2428" height="2357" alt="Scan_20260907_092831" src="https://github.com/user-attachments/assets/36ea484b-673b-4400-9571-26ff774e5938" />

**CAD Design**

**Step 1 (Parameters/Global Variables):**

Before beginning the actual design of the bar I began by implementing all of my calculations/values into the global variables tab so that the values of the bar are secure and that nothing would change if I set a value wrong. I set the equations for the length and the cross sectional area inside the parameter/global variables settings making sure the set value was what the equation equaled. This allows me to easily select all the values throughout the creation of the bar, so that I don't need to type out my values, which takes up time and ends up slowing down the entire process. Below is the image of my parameters 

<img width="795" height="321" alt="Screenshot 2026-09-06 195231" src="https://github.com/user-attachments/assets/fd4cbda2-cc87-4e24-bbcb-412cfbba0850" />

**Step 2 (Sketch/Extrude):**

To begin the design of the bar, I created a sketch of the circular bar with a diameter of 0.55in from my design decision. This is made easy by the parameters letting me select the diameter from the smart dimension and easily set the diameter. Then I selected the Boss/Extrude option letting me set the length of the bar which creates a 3D circular bar that I can then start the simulation process. But before we can do that I changed the material from a steel alloy to the required aluminum alloy, I decided to choose the 7075-O(SS) which was used by most students from past semesters projects. Below is my sketch of the part, the extrusion of the bar and the editing of the material. 

**The Sketch of the Circular Bar**

<img width="2000" height="1052" alt="Screenshot 2026-09-06 192615 (1)" src="https://github.com/user-attachments/assets/d8e1628d-168a-405a-803a-a1ddb9ca65a4" />

**Extruding the Sketch of the Circular Bar**

<img width="2022" height="1059" alt="Screenshot 2026-09-06 192659 (1)" src="https://github.com/user-attachments/assets/ef86e334-3323-40ba-81a6-d1459b8cb438" />

**Editing the Material**

<img width="830" height="602" alt="Screenshot 2026-09-06 192743" src="https://github.com/user-attachments/assets/afef0771-5240-48bd-b617-e2e2eff4b9f6" />

**Step 3 (The FEA):**

To start the simulation on the bar in Solidwork's, I switched to the simulation tab where you can start a new study, you then find the fixtures tab, where I selected the front face of the bar. Selecting the front plate sets that side of the bar as the wall that holds the bar (fixed geometry) in place while the force is applied to the other side of the bar. Which was the next step, we have to add a external force to the other side of the bar which will let us simulate the idea of stress and displacement on the bar. Below are two images of me applying the fixture and the external force (Fixture = Green, and External Force = Purple).

**Applying the Fixture:**

<img width="1680" height="980" alt="Screenshot 2026-09-06 193754" src="https://github.com/user-attachments/assets/97675853-e383-44a5-96c7-e4314ac708c0" />

**Applying the External Force:**

<img width="890" height="466" alt="Screenshot 2026-09-06 193734" src="https://github.com/user-attachments/assets/1247c0dd-4bb9-432b-aef7-078e102dc936" />

**Step 4 (Deflection Map and Stress Map Analysis):**

The last step of the design process and simulation is to run the simulation and see the how well my bar stood up to the force applied to it, I used 400lbf to be right in the middle of the 300lbf - 500lbf range. Below are two images of the Displacement Map and the Stress Map showing where the displacement is across the bar and the total amount of stress being applied to the entire bar. And below the images I will include whether or not I was within the 40ksi strength limit. 

**Displacement Map**

<img width="1684" height="1045" alt="Screenshot 2026-09-06 193247" src="https://github.com/user-attachments/assets/db87fc9c-1e65-4399-bee3-ff940e2c01dc" />

**Stress Map**

<img width="1694" height="1060" alt="Screenshot 2026-09-06 193258" src="https://github.com/user-attachments/assets/2d7dfa08-0b87-4929-8a3e-38d4358b142e" />


 






## Decide


## Communicate

