# A8 – Gears

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





## Decide


## Communicate

