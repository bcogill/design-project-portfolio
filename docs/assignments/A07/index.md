# A7 – [FEA of Bracket]

## Objective

**Objectives:**

- Use Finite Element Analysis (FEA) to improve the bracket design from previous assignments.
- Ensure high stiffness, strength, and lightweight optimization through iterative design.
- Conduct multiple FEA simulations, refining geometry based on results.
- Perform static stress analysis, including constraints, loading, and meshing selection.
- Interpret data by identifying max stress, displacement, and safety factors.
- Optimize the design by modifying geometry to enhance performance.
- Document the entire process with images, calculations, and insights.
- Reflect on key engineering lessons learned and time spent.
<img width="693" height="217" alt="Screenshot 2026-10-20 190206" src="https://github.com/user-attachments/assets/e086c4d9-1dbb-4a8d-aa53-1e8d97dd41a7" />

**Description:**

Your task is simply to create a high stiff, high strength, and lightweight component. Use Finite Element analysis to drive your decision making process throughout your design. Each step of the analysis and before you make geometric changes make sure the component’s results (stress/displacement/Safety Factor) converge on a 7% difference. Achieve this by modifying the number of elements. If after three attempts to converge use the stiffness and stress from the finer mesh size use the finest mesh size and proceed through the process.

<img width="552" height="445" alt="Screenshot 2026-10-20 190213" src="https://github.com/user-attachments/assets/4995d682-79cf-490d-9aa0-230e6e6566f4" />

## Analyze

**Design 1**

For the first test, I decided to use my original design to see where it stood from the beginning, wanting to get to that 7% convergence. I began by using a 600lb load and applied it to the cylinder of the bracket and the back plate holding up the top brace of the bracket. I completed 3 FEA simulations on the part using fine/course mesh, course mesh and fine mesh, I was able to get Mesh's 2 and 3 within the 7% convergence. This means I need to try some other designs to better my brackets performance. 
<img width="935" height="700" alt="Screenshot 2026-10-20 174101" src="https://github.com/user-attachments/assets/c11d83e3-a9f0-4dfe-bb70-9d04d34fa193" />
<img width="877" height="768" alt="Screenshot 2026-10-20 192236" src="https://github.com/user-attachments/assets/3ad951ca-cee6-437a-94c4-5526169f71d3" />

**Mesh 1:**
<img width="1312" height="768" alt="Screenshot 2026-10-20 192651" src="https://github.com/user-attachments/assets/7d26694e-189e-4e2c-9ef2-dcac2d99c4d0" />
<img width="751" height="437" alt="Screenshot 2026-10-20 195956" src="https://github.com/user-attachments/assets/3552a8a5-e80a-4fab-b54b-0fb42105853b" />

**Mesh 2:**
<img width="642" height="408" alt="Screenshot 2026-10-20 193811" src="https://github.com/user-attachments/assets/6ed52603-c183-4b99-9c04-06f70cb8ef2e" />
<img width="742" height="462" alt="Screenshot 2026-10-20 194248" src="https://github.com/user-attachments/assets/cf5222a2-fd89-4200-9036-5d63d6781477" />

**Mesh 3:** 

<img width="623" height="388" alt="Screenshot 2026-10-20 202833" src="https://github.com/user-attachments/assets/20e68eb5-05dc-469e-b279-7c133cc536c8" />
<img width="757" height="448" alt="Screenshot 2026-10-20 194646" src="https://github.com/user-attachments/assets/f4960db2-59cb-43a7-8da9-edf8bd7ded2e" />

**Design 1 Convergence Calculations for the Meshes.**
<img width="2424" height="2103" alt="Scan_20261020_202239" src="https://github.com/user-attachments/assets/31fcf30b-5561-4bd2-8173-2696a48083fa" />

**Design 2**

For design number 2, I decided to add a rounded edge to the cylinder and backplate of the brackets stand. This adds some change in the design while also changing the orientation of the part itself, this will cause the changes of the stress and displacement to occur and in the images below this is apparent. I added a rounded edge to stand of about 0.2 which isn't much but it changed the stress and displacement enough to please me in the results. I ran the same 3 mesh types to ensure that results could be compared between all three different designs. Once again the convergence for Meshes 2 and 3 were within the threshold of 7% convergence but 1 and 2 were still under in the safety factor but the max stress was within the limits, so this tells I need to make a few more adjustments for my bracket.  
<img width="620" height="628" alt="Screenshot 2026-10-20 173916" src="https://github.com/user-attachments/assets/6bc3833d-6a15-487a-ae70-5c49cd937adb" />

**Mesh 1:**
<img width="711" height="517" alt="Screenshot 2026-10-20 210711" src="https://github.com/user-attachments/assets/be374220-937b-407f-9586-3a5aae5edd6c" />
<img width="631" height="487" alt="Screenshot 2026-10-20 210839" src="https://github.com/user-attachments/assets/f5a13bbf-5bd3-48f4-a5ee-6d17eeca625d" /> 

**Mesh 2:**
<img width="710" height="445" alt="Screenshot 2026-10-20 212608" src="https://github.com/user-attachments/assets/cd9806aa-d79f-491d-a505-a308d82dcc99" />
<img width="631" height="412" alt="Screenshot 2026-10-20 211646" src="https://github.com/user-attachments/assets/efa180b2-8815-4bfa-bf51-be9518af8e8c" />

**Mesh 3:** 
<img width="700" height="458" alt="Screenshot 2026-10-20 213610" src="https://github.com/user-attachments/assets/50bafd74-9ce9-48e4-bda8-921da3b9ae5a" />
<img width="626" height="431" alt="Screenshot 2026-10-20 213632" src="https://github.com/user-attachments/assets/eb183307-7547-45a8-96c3-29e96e93362f" />

**Design 2 Convergence Calculations for Meshes**












## Decide


## Communicate

