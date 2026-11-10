# A9 – Pulley Design

## Objectives

**Description:**

- Design a pulley system to transfer power between two parallel axes separated by a center distance of 4–6 inches. The system must meet the following requirements:
- Pulley Diameter: Both pulleys shall have a diameter of 3 inches.
- Rotational Speed: Select an operating speed between 1000–2000 rpm.
- Belt Tension (Static): Select a belt tension between 4–6 lbf under stationary conditions.
- Material: Pulleys may be made from aluminum, ABS, or steel, and may include a groove and shaft diameter of your choosing (within reasonable manufacturing limits).
- Safety Factor: The design must satisfy a minimum safety factor of 3.

<img width="550" height="205" alt="Screenshot 2026-11-08 231944" src="https://github.com/user-attachments/assets/9514b65e-feeb-41e0-9307-db2fd6166f00" />

## Belt Selection

**Knowns, Unknowns, and Forces acting on Belt**

To find out which belt would work best, I started by writing down all the given information and making a quick sketch of the belt and pulley setup. This helped me get a better idea of how everything would fit together. I decided to use aluminum for the pulley since it has a friction coefficient of 0.3, and I used a safety factor of 3. I then organized the known and unknown values and made a free body diagram to help understand how the belt and pulley would interact. To calculate the forces occuring on the belt, I needed to find the tension on both the tight side (F2) and the loose side (F1). I started by using the static equilibrium equation (Eq. 1), which shows that the two belt tensions added together equal twice the selected static tension. I then used the flat belt friction equation (Eq. 2) to find the individual forces. For this calculation, I assumed the pulley wrap angle was π and used a friction coefficient of 1.0. After plugging in the values and solving for each tension, I got 0.414 lbf for the loose side (F1) and 9.586 lbf for the tight side (F2).
<img width="2409" height="3214" alt="Scan_20261109_132400" src="https://github.com/user-attachments/assets/7ddb7aca-b7d4-4e5f-9664-734113a061a4" />

**Solving for Belt Diameter and Circumference** 

I then worked on finding the belt diameter and outer circumference using the normal stress and yield strength equations while including the safety factor. Once I found the belt diameter, I used the cross-sectional area equation to determine its size. I also calculated the outer circumference using the pulley diameter and length. Based on these calculations. 
<img width="2408" height="1305" alt="Scan_20261109_122103" src="https://github.com/user-attachments/assets/8615c8f6-1658-47c7-822b-ab917d095eec" />

**McMaster-Carr's 5/16 Polyurethane Rubber Round Belt (1835T748)**

I decided to go with a standard round belt that has a diameter of 5/16 in because it was the closest available size that was larger than my calculated minimum diameter of 0.2788 in. Choosing this size helps keep the normal stress below the allowed limit while still meeting the required safety factor of 3.0. The belt I selected is the polyurethane rubber belt from McMaster-Carr, part number (1835T748).
<img width="963" height="755" alt="Screenshot 2026-11-09 144330" src="https://github.com/user-attachments/assets/89ba433a-ef14-4f28-a7d8-41a964abef79" />
<img width="582" height="332" alt="Screenshot 2026-11-09 144344" src="https://github.com/user-attachments/assets/a11e00a4-95fb-4d87-9b4a-203a1053600a" />

## Shaft and Journal Bearings 

**Diameter of Shaft**

Using the free body diagram, I was able to look at the shaft dimensions and calculate the allowable torsional shear stress using the given equation (Eq. 1). Since the shaft is solid and round, I used the polar moment of inertia equation, which includes the shaft diameter. After plugging that into the torsion equation and solving for the diameter, I got a minimum shaft diameter of 0.1441 inches.
<img width="2428" height="1204" alt="Scan_20261109_122116 (1)" src="https://github.com/user-attachments/assets/9d312622-6f3d-4ded-be47-7a369fe99e9c" />

**Journal Design Bearings**

Using the free body diagram of the journal bearing and shaft, I first added up the forces to find the total force acting on the bearing. I then used that value to calculate the pressure, which came out to 66.7 psi. Next, I used the shaft diameter and rotation speed to calculate the velocity, making sure to convert the diameter from inches to feet. This gave me a velocity of 58.905 ft/min. Finally, I used the pressure and velocity values to find the PV rating, which came out to 3928.954 psi·ft/min.
<img width="2428" height="3220" alt="Scan_20261109_122745 (1)" src="https://github.com/user-attachments/assets/c79bd540-09c2-45fe-8244-5357e72289d5" />

**The Journal Bearings Material Selections**

After looking through Table 4 in Machinery’s Handbook, I decided that porous bronze would be the best material for the journal bearing based on our calculations. It has a maximum bearing pressure of 4500 psi, a maximum surface speed of 1500 ft/min, and a PV rating of 50,000 psi·ft/min. These limits show that porous bronze is a good option for handling the forces and speed from our pulley system.
<img width="868" height="630" alt="Screenshot 2026-11-09 153421" src="https://github.com/user-attachments/assets/4bdb17f4-8dac-4437-b279-d5e8e9535aa2" />

## Full Frame Design and Lessons Learned

**Frame Design**

I added 0.25 inches of solid material between the pulley housing and journal bearing to support the forces acting on the system. I chose a frame depth of 1.25 inches to leave enough room for the pulleys and shaft while also keeping enough material around the mounting holes. I also removed some unnecessary material to make the design lighter while keeping the frame strong enough to support the system. The overall height was set to 3.25 inches, slightly larger than the pulley diameter, to provide enough support. I used Appendix A as a reference when designing the pulley frame. I kept the frame circular to make the best use of the material and added mounting holes along the sides so it could be attached to a vertical wall.
<img width="2409" height="3214" alt="Scan_20261109_132231 (1)" src="https://github.com/user-attachments/assets/46e8eadf-a53e-4b56-ad83-7b8fe313d1e8" />
<img width="708" height="297" alt="Screenshot 2026-11-09 162323" src="https://github.com/user-attachments/assets/4944202b-35c0-4e97-9f82-8f333ceefc39" />

**Lesson Learned** 

This assignment took me about 7 hours. One of the biggest things I learned from this assignment was how to use torque equations to help find the correct dimensions, using PV values to choose the right bearing material, and calculate the tight and loose belt forces. I was already somewhat familiar with torque and stress equations, but I had not used torque as much to figure out dimensions, so that was helpful to learn. I also got more practice using the PV tables and understanding how to choose the right material. Calculating the tight and loose belt forces was something new for me and helped me better understand how the forces work together. As someone who enjoys racecars and machinery, this assignment also helped me better understand how certain belt systems work in things like flywheels, belt-driven mills, etc.

[Downloadable Handwritten Work.pdf](https://github.com/user-attachments/files/34602487/Downloadable.Handwritten.Work.pdf)










