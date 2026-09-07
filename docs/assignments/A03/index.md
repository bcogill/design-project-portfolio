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

**Step 1:**
Before beginning the actual design of the bar I began by implementing all of my calculations/values into the global variables tab so that the values of the bar are secure and that nothing would change if I set a value wrong. I set the equations for the length and the cross sectional area inside the parameter/global variables settings making sure the set value was what the equation equaled. This allows me to easily select all the values throughout the creation of the bar, so that I don't need to type out my values, which takes up time and ends up slowing down the entire process. Below is the image of my parameters 

<img width="795" height="321" alt="Screenshot 2026-09-06 195231" src="https://github.com/user-attachments/assets/fd4cbda2-cc87-4e24-bbcb-412cfbba0850" />



## Decide


## Communicate

