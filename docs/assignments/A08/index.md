# A8 – Gearbox Design

## Objective

- Design a gearbox that can be assembled and disassembled.
- Analyze and size input and output shafts for strength.
- Design journal bearings to support shafts.
- Create a gearbox housing with proper clearance and fastening.
- Use parametric CAD modeling to generate a final design.
- Document calculations, sketches, and lessons learned.

**Description:**

Design a gearbox which can be assembled and disassembled. The spur gears have a gear ratio of 24:9 and are listed in the resource section. The output gear torque and speed are to be 1.25 in-lbf and 1100 rpm relative. The input (pinion,power-transmission) and output (gear, short shaft) shaft diameters are .125 and .25 inches respectively and each have a length of 1 inch. Use the appropriate equations in the Machinery’s Handbook for empirical units. The critical features of the gearbox include the shafts, and the journal bearings.

**Assumptions:**

- Assume appropriate strength of shafts, use Machinery’s Handbook.
- The gear train is ideal.
- The moment of the radial force from the gear train is small enough to be ignored.

<img width="693" height="522" alt="Screenshot 2026-11-01 202403" src="https://github.com/user-attachments/assets/156a1726-c39e-45c1-a324-1284a92e87c1" />

## Analyze

**The Input and Output Shaft Design Calculations**

After looking through my machinery handbook and find the proper equations to solve for the power, torque and speed. Given a 24:9 Ratio, The shafts dimensions were found using equations obtained from the Machinery’s Handbook to make sure they could safely handle the required conditions. Different max shear stress limits were applied to each shaft, 4000 psi used for the input shaft and 8500 psi for the output shaft. Using the values, I calculated the minimum required diameters based on the power and torque transmitted through each shaft. After comparing the dimensions to the original design, both shafts meet the requirements. This makes the existing shaft diameters compatible so I didn't need to change anything.

**Input Shaft Calculations**

For the input shaft, beginning with the knowns and unknowns we know the required length and diameter while also making sure to calculate the required force and RPM speed. However we do need to find the required torque and power that is within the given conditions, I used the Machinery's Handbook to find the proper equations to solve for the torque and power algebraically and numerically. Making sure to include a FBD of the longer Input Shaft. 
<img width="2428" height="1097" alt="Scan_20261102_114906" src="https://github.com/user-attachments/assets/dc3cd18a-6999-4a0b-9e00-c0b6bdb14403" />

**Output Shaft Cacluations**

The Output Shaft, since we completed the input shaft the output shaft was about the same, the only difference was that the knowns were a little different due to the length and diameters being different for each shaft. This obviously results in the torque and power being different for both shafts. I once again solved for both the torque and power algebraically and numerically making sure that the results are within the required conditions.  
<img width="2428" height="1225" alt="Scan_20261102_115141" src="https://github.com/user-attachments/assets/d50c12e1-1ab2-48c1-908d-df4ca4636a6e" />

**Journal Bearing Designs**

Making my journal bearings selections, I first looked through the options in the McMaster-Carr catalog. Before choosing my bearings, I needed to figure out what material and dimensions would work best for our design. I started by assuming a bearing length of 1/4 inch and used the RC5 table to find the correct inner diameters for both shafts since the bearings needed to allow a sliding fit. After finding the dimensions I calculated the pressure, velocity, and PV rating to help narrow down the material choices. From these results, dry graphite was my best option for the bearings. Once the material was selected, I moved on to finding the required bearing thickness. I used the force acting on each bearing with its cross-sectional area in the pressure formula to calculate the thickness needed for both bearings.

**Input Journal Bearing Calculations**

I mostly did the same thing for the bearings as the shaft designs listing the knowns and unknowns, and I focused on all the required parts of the assignments and solved for the unknowns algebraically and numerically making sure to break down ever part of the solutions. Creating the FBD was simple, making sure to add the As and Fr abbreviations to the diagrams.  
<img width="2408" height="1371" alt="Scan_20261102_115102" src="https://github.com/user-attachments/assets/5893bf77-e807-4d17-bf55-20f64b1a6c49" />

**Output Journal Bearing Calculations**

For the output journal bearings, I recreated the FBD and made sure to change around the abbreviations so that they matched the knowns of the journal bearings. Then solving the unkowns algebraically and numerically to get my psi and ft/min values.  
<img width="2446" height="749" alt="Scan_20261102_135521" src="https://github.com/user-attachments/assets/43f04d17-a668-4e71-8cf5-4a32ae48de27" />

**Bearing Thickness**

For the Journal Bearings Thickness, I made sure to list the knowns and unknown, starting with the input using the Machinery Handbook to find the right equation for 't' then taking the known values, plugged them in to the equation to get my thickness value for the input. The McMaster-Carr journal bearing best suited for the application for the input was **SAE81419368T98**. Then working on the output thickness was the same concept just using the values need to solve for the output thickness itself. I made sure the FBD represented these results and were the forces were acting on the bearing. The McMaster journal bearing that was selected and a best fit was the **SAE8419368T11**. 
<img width="2408" height="1600" alt="Scan_20261102_114953" src="https://github.com/user-attachments/assets/1679290d-3030-401c-9df7-069d5e4e4290" />

**Hand-Drawn Design**

<img width="2414" height="727" alt="Scan_20261102_115012 (1)" src="https://github.com/user-attachments/assets/0d6f935d-9e90-4ba5-91a6-ddbe5ff29a49" />

**CAD Model/Assembly Images**

Since McMaster-Carr provides downloadable models for the gear, pinion, and journal bearings, my only main tasks were to design the shafts and housing. Designing the shafts was fairly simple since I just used the provided diameters and lengths. I also added chamfers to the shafts to help with the press fit. For the housing, I used the dimensions of the gear, pinion, and bearings to create a design that would fit all the parts properly and keep everything in place. For the housing connection I had the option of using either bolts or a snap fit, I decided to go with a snap fit because the gear and pinion were fairly small and using bolts would have been unnecessary. This would also help reduce the amount of material needed during manufacturing. Once all the parts were finished, I used SolidWorks Assembly to put everything together (My assembly file is not working when someone downloads it). To mate the gear and pinion, I used the mate tool with a 24:9 ratio. All these dimensions in SolidWorks were in Imperial units (in).

**Equations/Properties**

<img width="787" height="549" alt="Screenshot 2026-11-02 172508" src="https://github.com/user-attachments/assets/be991fd2-ee88-4e7c-80f9-971c028794dd" />

**Input Shaft**

The input shaft was a simple concept, using the diameter that I came up with I used the circle tool to create a circle where I could extrude it to correct length that I wanted for the input shaft. I then added a chamfer to both ends of the shaft so that they would fit perfectly with gears and Gearbox. 
<img width="1716" height="920" alt="Screenshot 2026-11-02 180557" src="https://github.com/user-attachments/assets/56e97ad9-d81c-4446-ac19-1dc9ac010cca" />
<img width="1496" height="745" alt="Screenshot 2026-11-02 181359" src="https://github.com/user-attachments/assets/23c6828a-13ba-4ebd-83c9-a9efc3e0fd1a" />

**Output Shaft**

Output shaft was the same as the input shaft where I created a circle that was then extruded to the correct length and specifications. Also chamfering both ends of the shafts, keeping the chamfer value similar to that of the input shaft. 
<img width="1677" height="948" alt="Screenshot 2026-11-02 180624" src="https://github.com/user-attachments/assets/2fc0f4f0-153d-42ef-bd4a-2438cc912ceb" />
<img width="1431" height="769" alt="Screenshot 2026-11-02 181417" src="https://github.com/user-attachments/assets/00834deb-b795-468e-9dd7-cf0234fa04eb" />

**Input Journal Bearing**

<img width="581" height="890" alt="Screenshot 2026-11-02 180722" src="https://github.com/user-attachments/assets/60647c72-819b-4927-871b-92391855aa1f" />
<img width="1019" height="739" alt="Screenshot 2026-11-02 180736" src="https://github.com/user-attachments/assets/5d7617de-1057-4029-8734-436ea6d03610" />

**Output Journal Bearing**

<img width="1587" height="930" alt="Screenshot 2026-11-02 180813" src="https://github.com/user-attachments/assets/36797e83-d430-4303-9376-24c5dcde635f" />
<img width="1168" height="851" alt="Screenshot 2026-11-02 180836" src="https://github.com/user-attachments/assets/0c37a22b-7624-4f2b-8d99-e8d54d18d819" />

**Gear**

<img width="817" height="933" alt="Screenshot 2026-11-02 180137" src="https://github.com/user-attachments/assets/f3d091d1-51e7-4b05-bec6-a68098ce2e10" />

**Pinion**

<img width="1172" height="961" alt="Screenshot 2026-11-02 180925" src="https://github.com/user-attachments/assets/fbfa867e-cab4-47f1-9109-d491143efacd" />
<img width="971" height="709" alt="Screenshot 2026-11-02 180953" src="https://github.com/user-attachments/assets/9f3ab884-2347-4326-a357-35f724303d8d" />

**Gearbox Side 1 Snap Fit**

For the first side of the gearbox snap fit, I made the trapezoid outer shape of the part and extruded it to the expected width, the using a cut extrude, hollowed out the inside of that extrusion. Adding the holes for the input and output shafts on the outer part of the gearbox. I included the top bit of the gearbox where the other side can snap into place by going under the other side. 
<img width="1533" height="888" alt="Screenshot 2026-11-02 181201" src="https://github.com/user-attachments/assets/cb055918-8b82-44c5-ba13-d97a0e671deb" />

**Gearbox Side 2 Snap Fit**

The second side of the Gearbox is a reflections of that first side and makes sure to line up with the other side so that the shafts, gear, pinion, etc, are all lined up correctly with the entire gearbox. Making sure to include the holes and cut outs for the shafts themselves, and lastly adding the top snap on bit where the two sides may converge into one main assembly. 
<img width="1390" height="929" alt="Screenshot 2026-11-02 181019" src="https://github.com/user-attachments/assets/297bc586-54ab-421e-a7d6-a09dc40b1949" />

**Assembly**

<img width="662" height="881" alt="Screenshot 2026-11-02 211714" src="https://github.com/user-attachments/assets/7202a839-8519-4a45-b0a8-c60e34d4dcd4" />
<img width="477" height="487" alt="Screenshot 2026-11-02 205530" src="https://github.com/user-attachments/assets/8a910177-2973-42a8-91cb-372e0c12d05c" />

**Downloadable CAD File and Handwritten Calculations PDF**

[A8 Gearbox CAD Design.zip](https://github.com/user-attachments/files/34300385/A8.Gearbox.CAD.Design.zip)    **Assembly File does not work**

[Handwritten Calculations_Work.pdf](https://github.com/user-attachments/files/34300656/Handwritten.Calculations_Work.pdf)

## Decide

**Reflection/Lessons Learned**

This project took me about 7 hours to fully complete. I want to start this reflection with this was one of the most simple projects with the McMaster-Carr system letting me download some of those must need parts, but I still worked very hard to make sure that everything for this assignment was in order and done correctly. Working through the shafts and gearbox design was very challenging given that we needed to shape it to McMaster-Carr gear, pinion, and bearings. Even with this challenging I took my time and made it through the entire process. One main lesson I learned while working through the calculations, I noticed I was a little closer to the limits/conditions that were provided but I did this because previous assignments I had done had been well within these margins and those could have been more likely to fail. So that's why I decided to be within the limits where I was to far off either side of the spectrum so that I am more comfortable with the results.  



