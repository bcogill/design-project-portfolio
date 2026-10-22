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
<img width="523" height="568" alt="Screenshot 2026-10-21 093003" src="https://github.com/user-attachments/assets/94bccd73-74bb-4a47-a89b-c5056f6fa36c" />

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

<img width="2408" height="1820" alt="Scan_20261020_223032" src="https://github.com/user-attachments/assets/f98aeb0f-8551-42c5-87ac-6e70456c1e21" />

**Design 3**

For Design 3, I started by extending the back plate letting it cover the entire back end of the part, this will instill that the top slot is held up securely and will increase the overall strength of the bracket. I then added a front panel that will help support the front end of the part, counter balancing the structural integrity of the bracket. I decided to make some major changes this time around for my final design, I creating these rigid structures helped with the stress and deformation that was occurring at sections A, and adding to section B only made it more resistant. With all of these changes and additions the 600lb load that has been applied to the bracket is now barely causing any deformation or stress to the body of the part. This let the part fall within the 7% convergence limit and should not fail, within this range. 
<img width="859" height="756" alt="Screenshot 2026-10-21 173037 (1)" src="https://github.com/user-attachments/assets/5c0b449a-920a-4d5a-a4aa-2db00ead7614" />
<img width="1381" height="788" alt="Screenshot 2026-10-21 172619 (1)" src="https://github.com/user-attachments/assets/5c43a417-27e7-421c-9e77-2a3add07ef72" />

**Mesh 1:**
<img width="707" height="450" alt="Screenshot 2026-10-21 181927" src="https://github.com/user-attachments/assets/96d3740e-c71a-4c08-8961-0a517e8e4e55" />
<img width="702" height="466" alt="Screenshot 2026-10-21 182424" src="https://github.com/user-attachments/assets/b340c390-6671-4734-ace6-269cbf695874" />

**Mech 2:**
<img width="712" height="447" alt="Screenshot 2026-10-21 183053" src="https://github.com/user-attachments/assets/7ac30578-87cd-48d9-8ea9-1666354dd516" />
<img width="822" height="506" alt="Screenshot 2026-10-21 183309" src="https://github.com/user-attachments/assets/e2492a7f-5c2f-41e1-beea-5ed2fef36b8d" />

**Design 3 Convergence Calculations for Meshes:**

<img width="2408" height="1300" alt="Scan_20261021_200646" src="https://github.com/user-attachments/assets/1b6d2edc-162c-4471-a8fa-aac2ea1e096a" />

**CAD Files**

[A7BracketDesign1fea.prt.zip](https://github.com/user-attachments/files/33786368/A7BracketDesign1fea.prt.zip)

[A7BracketDesign2fea.prt.zip](https://github.com/user-attachments/files/33786390/A7BracketDesign2fea.prt.zip)

[A7BracketDesign3fea.prt (2).zip](https://github.com/user-attachments/files/33790867/A7BracketDesign3fea.prt.2.zip)

## Decide

**Reflection/Lessons Learned**

This project showed us how to take our bracket design and preform load simulation to test our parts, max stress, displacement, and safety factor. I learned that when you make slight changes to your design, it can affect the design quite a bit especially when its something as simple as a added chamfer, rounded edge, or changing the length of a section on the part. These changes cause variations in your simulations changing the max stress, displacement, etc. But you can limit the errors in your designs, making tiny tweaks to improve on the design you original were going for. The most important lessons learned during this project was the mesh simulations and convergence calculations, repeating the mesh simulations with different types helps to understand where your model stands in stress, displacement, etc. The calculations were simple to solve but checking for the error % and double checking work can take some time to make sure everything is correct. I felt very good about this project and that finding the max stress, displacement, safety factor, and designs were important in improving on the overall brackets design and limitations. 

## Communicate

