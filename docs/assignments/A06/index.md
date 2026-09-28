# A6 – [Bracket Drawing Part 1]

## Objective

**Description:**

As part of this assignment, we will be needing to generate a comprehensive solid model and a multi-view engineering drawing that accurately represents your designed bracket, incorporating all features to ensure both strength and stiffness requirements are met.
<img width="608" height="305" alt="Screenshot 2026-09-27 211324" src="https://github.com/user-attachments/assets/446d1f0e-365d-4694-85a9-742522698696" />

## Analyze

**Step 1, Parametric Feature Designs:**







**Step 2, Generate a Multiview Drawing**







## Decide

**Reflecting:**

**A)**

A tighter three-decimal-place tolerance was used for the width of Feature E to ensure proper alignment and reduce unwanted movement. This was especially important because Feature E is subjected to a moment from the applied load while resting against the rigid T-beam rail, which has a width of 0.550 inches. In comparison, the diameter of the cylindrical pin at Feature A, measuring 0.8 inches, was given a more relaxed tolerance because it is considered a non-critical dimension. The strap only needs to remain securely supported by the pin, so extremely precise sizing is not necessary.

The sliding connections were also accounted for by specifying limits on the key clearance dimensions. The nominal "a" gap was assigned a tolerance of 0.59 +0.00 / −0.10 in, while the larger horizontal clearance was specified as 1.500 +0.000 / −0.001 in. These limits establish the amount of clearance available at the sliding interfaces and ensure that the drawing provides the necessary control over the free-moving fit shown in Figure 1. This approach follows the requirement for nominal dimension "c," where maintaining accurate positioning while limiting excessive play is important for proper function.

**B)**

Feature D is designed with a -0.001" tolerance because it needs to function as a sliding connection with its mating component. This amount of clearance gives the bracket enough freedom to move into position without making the connection excessively loose. The tolerance was selected based on the part's function rather than simply making the dimensions as precise as possible.

Using extremely tight tolerances throughout the entire part would also make the manufacturing process more expensive and time-consuming. A dimension requiring a 0.0001" tolerance would require much more careful machining and inspection than one with a 0.001" tolerance. The machinist would have to make smaller adjustments and remove material more gradually to avoid exceeding the required dimension. By allowing a slightly larger tolerance where the design permits it, the part can still perform properly while being faster and less expensive to manufacture.




## Communicate

