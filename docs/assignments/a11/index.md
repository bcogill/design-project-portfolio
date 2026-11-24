# A11 – Motor Selection

## Objective

**Objective**

The objective of this assignment is to design a motorized drive and frame for a 2 kN tensile tester. Through calculations and design work, a motor needs to be selected, confirm frame integrity, and mounting design for the motor. These design decisions will allow the smooth translation of the crosshead under a safe torque and speed for tensile tester of a high load. Pictured below are the given constraints and values for this assignment.

<img width="563" height="545" alt="Screenshot 2026-11-23 205118" src="https://github.com/user-attachments/assets/b567844b-152e-4e3c-abd9-9dc6b2db0d0d" />

**Description:**

A tensile tester is a mechanical testing device used to measure how materials respond to uniaxial tension. It applies a controlled pulling force to a specimen while recording the resulting elongation, allowing engineers to determine properties such as yield strength, ultimate tensile strength, and elongation at break. This data is essential for understanding a material’s mechanical behavior and suitability for design applications.

<img width="666" height="562" alt="Screenshot 2026-11-23 210626" src="https://github.com/user-attachments/assets/bec027b5-8f7b-49ef-b094-a8be75031164" />

Develop the motorized drive and structural integration for the 2 kN tensile tester, focusing on motor selection, mounting, frame stability, and clamp design. This phase will ensure that the crosshead moves smoothly under controlled torque and speed while maintaining precise load alignment and secure specimen gripping.

## Analyze

**Motor Selection**

For the motor selection, we used values for one half of the needed 2000 N load to find what each motor needed to provide. A 30% efficiency value was used to find a torque value that will not be overused but can still provide the needed torque to translate the crosshead vertically. With these values found, a torque of 2.695 Nm was required or 381.64 in-ozf. A RPM range of 0.197 to 9.84 was calculated to find a motor. From the McMaster website, NEMA 23 6627T923, square body motor was selected. The maximum holding torque is valued at 467.3 in-ozf and a maximum rotation speed of 300 RPM. This motor provided sufficient torque as well as RPM range for our needed values.
<img width="3000" height="3000" alt="IMG_3125" src="https://github.com/user-attachments/assets/9a5b3822-5026-4c8f-a3ab-70fa64e6c8c9" />
<img width="1050" height="811" alt="6627T923_Stepper MotorX" src="https://github.com/user-attachments/assets/e7c387ab-7bfc-4e9e-ae7c-e3e4072920b0" />
<img width="1007" height="758" alt="6627t923-@2x_1695134526" src="https://github.com/user-attachments/assets/6eb21294-e00e-467b-bb9c-1423ccb3e9a0" />

**Motor Bracket Design**

After selecting the motor, the next step was to design a bracket that will secure the motor to the frame to ensure the leadscrew to be turned properly. First, the knowns and unknowns were listed then a Free Body Diagram was drawn to further find the needed thickness value to hold the force and torque of the motor. After calculations, the thickness needed to be a minimum of 0.0717 mm. With this in mind, a thickness of the bracket was selected to be 6 mm to hold the motor well with the power required without any issues of mounting.
<img width="4284" height="5712" alt="IMG_3123" src="https://github.com/user-attachments/assets/502c896a-39f0-4652-b7b9-81d4e03d090c" />

Then, a SolidWorks model was created to create a design for our 3D modelled assembly.

<img width="1280" height="762" alt="A11 Motor Bracket" src="https://github.com/user-attachments/assets/b5cff72a-ec9f-43b8-8ae0-fd9d3f160afa" />

**Coupler**

For the Coupler, we selected a flexible shaft coupler to connect the motor shafts to the lead screws. We used the coupler specifications to find the maximum torque it could handle and used torsional stress equations to calculate the minimum wall thickness needed. We also checked the selected coupler's dimensions against the calculated thickness to make sure it could handle the twisting force.
<img width="2428" height="3239" alt="Scan_20261123_191042" src="https://github.com/user-attachments/assets/68c24054-a5ef-413f-9b5b-9a8a71b4b87e" />

**Twist Analysis for Brakcet**

The Twist Analysis, we looked at the twisting forces created by the two motors and how those forces affect the top of the frame. We calculated the total reaction torque from both motors and used it to determine the forces acting on the frame connections. We also looked at different T-slot brackets, bolts, and connectors that could be used to attach the top horizontal frame to the vertical supports while keeping the frame stable.
<img width="2409" height="3239" alt="Scan_20261123_191055" src="https://github.com/user-attachments/assets/0204a20e-9d43-4579-9212-183d05623c0f" />











## Journal Bearing Mount

Finally, a journal bearing mount is needed to connect the bottom of the leadscrews to the frame. Using the RC 3 fit table 8a in the Machinery's Handbook on page 654, I found the needed tolerance of the diameter to be +0.0005 / -0.0000 inches. Using a Free Body Diagram, a thickness minimum was found to be 1.65 mm but to be safe, I selected a value of 12 mm. A vertically standing mount was chosen with a nominal inner diameter of 19.05 mm and an outer diameter of 40 mm. Then, I modeled the mounting design in SolidWorks.
<img width="3024" height="4032" alt="IMG_3124" src="https://github.com/user-attachments/assets/d4061a50-912e-4bcb-8d02-49ed2801deaf" />
<img width="1280" height="766" alt="A11 Journal Bearing Mount (1)" src="https://github.com/user-attachments/assets/53e53f97-bacb-4e42-aea7-29362455527c" />

**Bill of Materials and Labor Costs**

| Item Number | Quantity | Name | Cost/Item | Cost | Purchase Link |
| :---: | :---: | :---: | :---: | :---: | :--- |
| 1 | 2 | Stepper Motor | $308.46 | $616.92 | https://www.mcmaster.com/6627T923/ |
| 2 | 2 | Couplers | $413.44 | $826.88 | https://www.mcmaster.com/6259K37/ |
| 3 | 2 | Lead Screw | $35.49 | $70.98 | https://www.mcmaster.com/93255A233/ |
| 4 | 2 | Nut/Flange | $160.09 | $320.18 | https://www.mcmaster.com/95120A123/ |
| 5 | 1 | T-Slot Framing | $245.87 | $245.87 | https://grainger.com |
| | | | **Total Cost** | **$2,080.83** | |

### Design Cost

| Person | Hours worked | cost/ hour | cost |
| :---: | :---: | :---: | :---: |
| Bruno | 10 | 35 | 350 |
| Brandon | 8 | 35 | 280 |
| Jason | 10 | 35 | 350 |
| | | **Total Cost** | **980** |

**Total Cost of Project:** **$3,060.83**

**Lessons Learned**





## Communicate
