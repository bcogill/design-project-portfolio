# A9 – Pulleys

## Objective

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

<img width="2408" height="1305" alt="Scan_20261109_122103" src="https://github.com/user-attachments/assets/8615c8f6-1658-47c7-822b-ab917d095eec" />
I then worked on finding the belt diameter and outer circumference using the normal stress and yield strength equations while including the safety factor. Once I found the belt diameter, I used the cross-sectional area equation to determine its size. I also calculated the outer circumference using the pulley diameter and length. Based on these calculations, I selected the McMaster-Carr Rubber Round Belt 3044K605, which has a diameter of 3/16" and a circumference of 21.5".






## Decide


## Communicate

