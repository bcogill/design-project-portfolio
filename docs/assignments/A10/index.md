# A10 – Lead Screw Translating System

## Objective

The objective of this project was to design a Tensile tester with a leadscrew system with a group of team members. This included designing the various components, including the leadscrews, crosshead, nut flanges, and frame. In the next project, the motor systems will also be added. This project provided practice in designing based off of given restraints, utilizing the values from one component to determine the needed properties of another component. It also required us to pick real world parts that best matched our needs for the leadscrew, flange nut, and frame.

## Analyze

**> Given Constraints**

In this project, we were given a concept of a Tensile Tester we were able to use to understand the design of the machine. The design includes two lead screws connected via a crosshead, with two motors driving the two lead screws. The crosshead was supported by nut flanges, with the entire system surrounded by a box-like frame.

<img width="503" height="621" alt="TensileTesterEx" src="https://github.com/user-attachments/assets/27965303-be65-4676-8dd6-7f44b302521b" />

As for the key constraints, an axial load capacity of 2 kN for the system is provided, not just for each leadscrew. Also, a speed range of 1-50 mm/min was given with a minimum leadscrew length of 18 inches. Finally, a safety factor of 4 was provided.

In our case, we decided to go with the minimum leadscrew length of 18 inches due to the availability of sizes found on McMaster. We also chose 1018 Low Carbon Steel as the leadscrew material for our preliminary calculations, with a yield strength of 370 MPa and shear strength of 300 MPa.

## Decide

**> Combined: Leadscrew Calculations**

To determine the needed geometry and strength of the leadscrew, we began by finding the minimum diameter needed. Using axial stress, we determined that the axial stress on each leadscrew was half of the axial load capacity, making it 1 kN for each leadscrew. Using the shear strength, safety factor, and load, we determined a minimum diameter of 0.137 inches for each leadscrew.

<img width="1560" height="1021" alt="IMG_0183" src="https://github.com/user-attachments/assets/ad973cc5-2dc6-487d-84eb-50aae0f9b9a9" />

We then determined the range of rotational speed given the linear speed of 1-50 mm/min. by dividing the minimum and maximum linear speed by the length of the leadscrew, we found a minimum rotational speed of 0.0002187 rev/min and a maximum rotational speed of 0.0109 rev/min.

<img width="1560" height="827" alt="IMG_0184" src="https://github.com/user-attachments/assets/900808af-7259-4b70-8255-b3d1533b640d" />

Finally, we determined the max torque needed to provide the 2 kN tension to the test sample.  Using shear strength and calculated minimum diameter, we found a max torque of 3.01 Nm.  

<img width="1529" height="672" alt="IMG_0185" src="https://github.com/user-attachments/assets/4069ef95-547b-4d8c-85ef-88bd94c5211e" />

Based on these values, we pinpointed leadscrew model 93255A233 on McMaster as the ideal choice, meeting the length of 18 inches with a diameter of 0.75 inches, which is well above the minimum needed for safe use. It also is made of 1018 Low Carbon Steel, which was the material assumed in our calculations.

**> Brandon Cogill: Nut/Flange Calculations**

For the lead screw system, we selected the 3/4-5 ACME bronze flange nut from McMaster-Carr (Part #95120A123) to go with our 18-inch lead screws. The nut is made from 932 bearing bronze and has an engagement length of 1.5 inches, giving us about 7.5 engaged threads. Since our final design uses two lead screws to move the crosshead, we assumed the 2 KN load would be split evenly between the two flange nuts, making each nut carry 1000 N. This gives us an estimated force of 133.33 N per thread for each screw. We also used a bronze yield strength of 14,000 psi and a factor of safety of 4, giving us an allowable bending stress of 3,500 psi. We created an FBD showing both lead screws, flange nuts, and the crosshead to represent how the load is transferred through the system. The remaining step is to calculate the actual bending stress in the internal threads and verify that the selected flange nuts meet the required safety factor.
<img width="2409" height="3214" alt="Scan_20261115_211944" src="https://github.com/user-attachments/assets/9a0f86ef-4387-4e2c-89c1-bed9b02239c4" />

**> Bruno Salvi: Crosshead Calculations**

Utilizing the previous flange calculations, it was time to calculate the crosshead dimensions. Using a flange diameter of 2 inches, I set the base dimension to 2.5 inches to allow the flange to sit flush on the crosshead without any material hanging off. I then set the lead screw span length to 6 inches to fully define the geometry to find the crosshead thickness needed. Finally, I decided to make my crosshead out of 6061-T6 aluminum to keep the design lightweight.

Using these values and a safety factor of 4, I drew a free body diagram, finding the support forces to be 1 kN each to support the 2 kN load capacity. To find the needed thickness, I first used stress as the driving variable, finding a thickness of 0.402 inches.

<img width="1560" height="1154" alt="IMG_0186" src="https://github.com/user-attachments/assets/2afe275a-ed45-4528-9f36-2cd36d34179d" />

I then used deflection, with a max deflection of 0.1 mm. This parameter yielded a thickness of 0.627 inches. Since the deflection thickness was higher, it marked the minimum thickness needed for a strong enough design. To make the crosshead easier to manufacture, I set the thickness to 0.8 inches, leading to the final dimensions of 8.5in x 2.5in x 0.8in.

<img width="1549" height="1046" alt="IMG_0187" src="https://github.com/user-attachments/assets/756c4171-f9f4-4f40-a20c-f88d936b2388" />

To fully define the crosshead, I then drew multiview drawing with the given dimensions, with a front, top, and right view. I also included the flange nuts being utilized, with a 4-screw mounting solution for each nut. This ensures that they will stay secured onto the crosshead for full functionality of the tensile tester. To ensure the mounting solution is defined, I also located parts to mount the flange nut, with hex bolts and hex nuts being provided.

<img width="1640" height="1259" alt="IMG_0188" src="https://github.com/user-attachments/assets/2ccff535-92af-47f8-bbcb-936fc0b8f4e5" />

**> Brandon Cogill: Bill of Materials**

This bill of materials lists the mechanical and structural components for our Lead Screw Assembly, totaling $637.03 across five individual pieces. It includes two 3/4"-5 zinc-plated carbon steel Acme lead screws from McMaster-Carr at $35.49 each ($70.98 total) with two matching 932 bearing bronze Acme flange nuts at $160.09 each ($320.18 total). Rounding out the bill is a single 40 Series rectangular T-slot frame sourced from Grainger for $245.87.

| Item Number | Quantity | Name | Cost/Item | Cost | Purchase Link |
| :---: | :---: | :--- | :---: | :---: | :--- |
| 1 | 2 | 3/4"-5, Zinc-Plated Carbon Steel Acme Lead Screw | $35.49 | **$70.98** | https://www.mcmaster.com/93255A233/ |
| 2 | 2 | 3/4"-5, 932 Bearing Bronze Acme Flange Nut | $160.09 | **$320.18** | https://www.mcmaster.com/95120A123/ |
| 3 | 1 | Rectangle, 40 Series, T-Slot Framing System - 804T48 - Grainger | $245.87 | **$245.87** | https://www.grainger.com/product/80-20-T-Slot-Framing-System-Rectangle-804T48 |
| **TOTAL MATERIAL COST** | | | | **$637.03** | |

**> Jason Key: Parametric Modeling**

For the 3D modeling, I downloaded links for the frame, flange nuts, and leadscrews. Then, using our crosshead design dimensions, I created our crosshead in SolidWorks. For the frame, I had to find a generic frame type from Grainger and dimensions that would hold the width and length of the crosshead as well as the length of the leadscrews. With these in mind, I made the length of the bottom of the frame to be 1/3 of the vertical length of the frame design. Finally, I mated all necessary parts, and the 3D model was complete.

**Crosshead**

<img width="1280" height="746" alt="A10 Crosshead (1)" src="https://github.com/user-attachments/assets/a917c10c-4a54-4665-993d-09b7994e439c" />
<img width="1280" height="747" alt="A10 Crosshead Holes (1)" src="https://github.com/user-attachments/assets/307a0c9f-1576-4d4d-a7de-0fd92b63b4fb" />
<img width="1280" height="755" alt="A10 Crosshead Flange Holes (1)" src="https://github.com/user-attachments/assets/e27faaf1-1b4f-468d-897c-71429788e5b0" />

**Frame/Full Assembly**

<img width="1280" height="771" alt="A10 Frame Design 2" src="https://github.com/user-attachments/assets/d3e3e854-0b74-4bd5-93bd-28cec0397834" />
<img width="1280" height="755" alt="A10 Frame Design" src="https://github.com/user-attachments/assets/c33df735-abb3-4268-903b-fe14eb74ced7" />
<img width="1280" height="765" alt="A10 3D Model" src="https://github.com/user-attachments/assets/a4a0fa73-567f-4ca0-90ab-9e9435afada7" />

**Flange**

<img width="1280" height="755" alt="A10 Flange Nut" src="https://github.com/user-attachments/assets/cbb1b236-166b-4ffc-9535-f1ce92289d49" />

**LeadScrew**

<img width="1280" height="760" alt="A10 Leadscrew" src="https://github.com/user-attachments/assets/70765673-f05d-4548-bf53-727092afadd2" />


Download the 3D model using this link.
[Lead Screw Design Assembly.zip](https://github.com/user-attachments/files/34943499/Lead.Screw.Design.Assembly.zip)

## Communicate

**Lesson Learned**

For this assignment, I learned the importance of managing my time and double-checking the values and calculations I found. This was my first group assignment where the work was split into three different sections, and each section depended on the others being completed correctly. Because of this, it was important to make sure the equations and values I used were correct so that I did not cause extra work for another group member. I also learned more about 3D modeling, especially when working with assemblies. When I downloaded the parts, I needed to change their lengths, but trying to do this directly in the assembly caused some issues because changing one part also changed the other parts that used the same original file. To fix this, I created two separate parts with the correct lengths and then added them to the assembly, which worked without any problems. Overall, I spent about 6 hours completing my portion of the assignment.





