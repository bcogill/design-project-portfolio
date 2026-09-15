# A4 – [Topic]

## Objective

We are told to design a motor mount for a given motor size shown in Appendix A, giving us the dimensions to create and design a motor mount that will be able to hold and utilize the motor whenever need be. We must design with the yield strength in mind and make sure that we are within the 0.30 deflection limit making sure to check the stress and deflection analysis to make the motor mount be as efficient as possible. The motor and mount depicted below is the general design of what we are creating, we must use headers to separate the features and model design. 

<img width="800" height="407" alt="Screenshot 2026-09-14 114543" src="https://github.com/user-attachments/assets/e72d1789-f987-46e0-b9d8-8c8062d9e22e" />

## Analyze

**Feature 1**

For feature 1, I looked at Appendix B for the rough design of the feature 1, and using that design started by making my FBD. I used the rigid wall idea and create a sketch of my feature 1, finding the Ltot and M along the way looking max strength of feature 1. I made sure to list my knowns and unknowns, for knowns most of the info is given to us from the description and the unknowns come from the stress and deflection that we will solve in this section. Below is my work for all the sections for feature 1, I have symbolically and numerically solved for the stress and deflection, starting with symbolically solving them and moving the values into the symbolically solved equations to get a numerical value. Below my work, I have also attached a picture of Feature 1 from Appendix B

**Feature 1 Written Work**
<img width="2428" height="3063" alt="Scan_20260914_123748" src="https://github.com/user-attachments/assets/7a0c1630-5310-4b1d-ad98-507297cba222" />

**Appendix B (Feature 1)**
<img width="607" height="145" alt="Screenshot 2026-09-14 130455" src="https://github.com/user-attachments/assets/aeda9d15-b3ca-489f-a230-82b82c469f60" />

**Feature 2**

Feature 2 begins with the wall of the mount, repeating the same steps as feature 1, I began by creating a FBD at the top right of my worksheet. I also decided that I should create a FBD of the front view showing the dimensions of the front body, including the holes for the end of the motor and also to show the distances and dimensions between the holes and end of the wall. I listed my knowns and unknowns which included more unknowns than Feature 1 due to the number of holes and differences in the feature. Then I started to work on the stress analysis starting with symbolically and then working into numerically adding the values into the symbolically solved equations to get the stress and deflection limits for the wall of the motor mount. Below I have my work displayed, solving for Ltot and M as well to determine the mounts limit. All this info will lead into the CAD Model design of the assignment, getting dimensions and the creation of the part itself. I have also attached the Feature 2 image from Appendix B. 

**Feature 2 Written Work**
<img width="2428" height="2912" alt="Scan_20260914_135320" src="https://github.com/user-attachments/assets/191c288b-7e26-4472-a4bb-551bcf910c7d" />

**Appendix B (Feature 2)**
<img width="503" height="236" alt="Screenshot 2026-09-14 135509" src="https://github.com/user-attachments/assets/4608c3bd-08e0-41d1-93c0-1cb7c5dc1802" />

**Sketch of Motor Mount (Hand Drawn)**
<img width="2428" height="1153" alt="Scan_20260914_202723" src="https://github.com/user-attachments/assets/1106171f-ed5e-495e-9892-7ed57a867b6a" />
This is my hand drawn sketch of the mount that I am about to talk about below. I figured out the dimensions for the mount from the calculations and work done on my worksheet above, I came out with a 60mm base length and width of 40mm and the wall is 60mm tall and 40mm wide letting the motor fit comfortably inside the mount. 

**Feature 1 CAD Model**

**Feature 1 and 2 CAD Model Sketch**
<img width="1630" height="965" alt="Feature 1 and 2 Model" src="https://github.com/user-attachments/assets/dab487ac-1f21-49d7-be7e-3fb01fa315e6" />
Above are my dimensions and sketch for my Feature 1 and 2 motor mount, the dimensions were solved from the work in the headers above this image and section. I started by sketching the entire layout of the mount so that it was more convenient for me to just do both the first and second feature at the same time, to well save time. This sketch was then extruded to the right length to fit the dimensions of the motor that were given to us at the bottom of the instructions in Appendix A. Making sure that the thickness for both the wall and base were correct for both feature 1 and 2.  

**Spin Rod Hole and Mounting Holes**
<img width="1172" height="934" alt="Screenshot 2026-09-14 175630" src="https://github.com/user-attachments/assets/431f6996-c91c-47c8-8114-2395e2d47dbf" />
This is what I'm calling the base of the mount with the motors spin rod and mounting holes placed in the cut extruded base where they may fit smoothly and rotate freely. Making sure the holes had the 3.4mm clearance that is described in the instructions of the assignment, also making sure the spin rod hole is wide enough to fit and spin at a rapid speed (the spin rod hole is not in this image but is in the final part). I made a flat base on top of the spin rod hole so that the motor can sit in and be screwed down with the mounting holes, this makes sure that the motor will not fly off of the mount itself. Lastly the flat base hole to hold in the motor and spin rod is 22mm in diameter letting the motor sit snug in the mount. 

**Feature 2 CAD Model**

**Feature 1 and 2 Sketch**
<img width="1630" height="965" alt="Feature 1 and 2 Model" src="https://github.com/user-attachments/assets/de402183-c83b-490b-b721-ebc9a5d458dc" />
I put the same image in for both features 1 and 2 because I did them together, but now I will talk about the parts of feature 2 from the same image. I dimensioned what I am calling the wall of the motor mount where I sketched the entire body of the mount but for feature 2, I made sure that the wall thickness was correct and that the length width of the section were from my hand written work. 

**Wall Mounting Holes**
<img width="1686" height="976" alt="Screenshot 2026-09-14 174430" src="https://github.com/user-attachments/assets/2a512414-1414-4a25-9fa7-4d0f05c24524" />
For the wall mounting holes, I created the dimensions from the hand written work and the clearance hole limit that the instructions gave us and they are the same diameter as the holes on the base of the mount. I used a parameter circle to put all the mounting holes in the correct locations so that can be in place for the motor when it is fitted to the mount. Once the holes were in the correct location I Cut Extruded them all the way through so that they can be used to hold the motor to the mount using for example screws and a nut. 

**Material Choice**

<img width="1630" height="604" alt="Screenshot 2026-09-14 181223" src="https://github.com/user-attachments/assets/28b68058-fa30-4806-b04c-bfae2716adb9" />
I decided to create a custom material that is made with my motor mount in mind having the yield strength, modulus elasticity, etc. Making the part feel the part, and that fit the requirements, I named it A4 PLA, PLA is a type of plastic that is create from 3D printer which should have enough strength to hold the mound firmly and cause little to no issues. Below are the values and requirements that I placed in my custom part material, it applied nicely and I think will work really well. 


**CAD Model**

Here are some different angles of my CAD Model of the Motor Mount, I can now show the full mount create and assembled.

**Isometric View**
<img width="1366" height="856" alt="Screenshot 2026-09-14 214416" src="https://github.com/user-attachments/assets/9e3aaf29-2fe8-4c79-a5e8-afa8ee516623" />

**Top Down View**
<img width="1691" height="1066" alt="Screenshot 2026-09-14 214434" src="https://github.com/user-attachments/assets/8b3cc4e1-fec7-4a89-87ba-3e67a4bc56f5" />

Click Here to Download my CAD File: [AssignmentA4MotorMountDesign.zip](https://github.com/user-attachments/files/32219940/AssignmentA4MotorMountDesign.zip)

Click Here for a PDF of my work: [Assignment A4 Motor Mount.pdf](https://github.com/user-attachments/files/32219983/Assignment.A4.Motor.Mount.pdf)



## Decide
I decided to create my mount with the intent to hold the entire motor and have clearance in mind, the mount would look a lot different without all the instructions and descriptions of the motor itself. I wanted to be similar to the given image in Appendix B that I have attached below but also make sure it met all the requirements, I looked at the linked motor itself from the website linked in the description for reference and it helped a lot of the decisions I made throughout this assignment. I think anyone can do this assignment with this info, if granted the same part/motor and design it there one way, maybe there was something you didn't like about mine and can make it better, because I believe there are ways to improve my design. 

<img width="1128" height="440" alt="Screenshot 2026-09-06 103646" src="https://github.com/user-attachments/assets/db35e863-c832-4658-bd32-085890dcbbcd" />

I spent 9 Hours on this Assignment. 



