# A6 – [Bracket Drawing Part 1]

## Objective

**Description:**

As part of this assignment, we will be needing to generate a comprehensive solid model and a multi-view engineering drawing that accurately represents your designed bracket, incorporating all features to ensure both strength and stiffness requirements are met.
<img width="608" height="305" alt="Screenshot 2026-09-27 211324" src="https://github.com/user-attachments/assets/446d1f0e-365d-4694-85a9-742522698696" />

**Make Sure to Include**
- Document the process which includes many pictures with an overview of images.
- Make sure to post a picture of the parametric table in CAD.
- Detail any mistakes throughout the process.
- Actual time it took from start to finish.
- Have a Lessons Learned section

## Analyze

**Step 1, Parametric Feature Designs:**

**Parameters:**

Below I have listed my parameters for the assignment which is essentially, the parts properties/dimensions where we can learn a lot about the CAD Model before even seeing it. This section can be changed and styled in any way making it easy to label and dimension your parts/sections of your design, I decided to alphabetically name my parts as not to get mixed up with the other sections of the model. Lastly, I wanted to say that I decided to use Creo for this assignment this time round because we can easily see the drawing template and the parameters that were are told to implement into our CAD Model design. 
<img width="942" height="713" alt="Screenshot 2026-09-28 215615" src="https://github.com/user-attachments/assets/89a2a15e-2488-44bf-9d95-db9bb229ef3f" />

**Part A:**

I started by getting the diameter of section A letting me extrude the part to correct length. This part is a very simple, creating a circle a from the toolbar and using the extrude tool to create the solid body part. I decided to label this parameter as DA in the materials, for "Design A" knowing its the correct part. 
<img width="906" height="588" alt="Screenshot 2026-09-28 140231" src="https://github.com/user-attachments/assets/fe6273ab-1e08-4719-89e5-93589ff58d80" />

**Part B:**

Section B is the back plate that holds up the frame of the T-Beam, it is a very important part to the entire model, and connects to the back of the cylinder (Part A). This part was made by using the rectangle tool, starting off as a simple rectangle with the correct height and width, this was then extruded to length and then chamfered to the cylinder (Part A) connecting the parts together. This part was labeled as BD and BH, which give you the initial height before connecting and the thickness of the plate. 
<img width="667" height="658" alt="Screenshot 2026-09-28 173039 (1)" src="https://github.com/user-attachments/assets/e90ffcd5-46e4-43f8-b8e6-b70c6b50c619" />


**Part C:**

The image below is the sketch of Section C, I decided to show the sketch of this one because of the dimensions it holds, knowing that the length and width of the section is 3in and 1in. This was then extruded to the appropriate thickness/height, creating the base part of the T-Beam making enough space to fit whatever goes on the bracket. This section was labeled as CH, CW, and Cl, simply just giving the dimensions of the section, the dimension of 0.3 is the thickness/height of Section C. 
<img width="1141" height="589" alt="Screenshot 2026-09-28 173114" src="https://github.com/user-attachments/assets/b756c23d-a042-4f25-a0d3-89dd3d3f9e2b" />

**Part D:**

Section D is the stands that will hold whatever is going in the bracket together and within the bracket itself. I created a sketch on top of Section C which were two skinny rectangles on both sides of the base, they were then extruded upward to a height of 1.959in which gives me decent height to work with. This section was labeled as DH, DW, and DL, this seemed like the most simple strategy to label most of sections/parts, you can label the dimensions and parts themselves making them easy to search for and find values quickly. 
<img width="995" height="797" alt="Screenshot 2026-09-28 173141" src="https://github.com/user-attachments/assets/4c3223b2-dccc-463c-ae20-9d532aaeff02" />

**Part E**

The last section of this assignment is Section E, which are the top plates that will keep whatever is fitting the bracket inside the hold with the stands and the bottom plate. I create a sketch on the two skinny rectangle stands creating two rectangles spanning most of the top plate, this sketch was then extruded to the correct thickness/height making sure to stay well within the limits. These parameters were appropriately named EL, EH, and EW, which as we've seen has been a easy way to find information, these were given the right dimensions. 
<img width="987" height="531" alt="Screenshot 2026-09-28 173201" src="https://github.com/user-attachments/assets/971985f5-0023-4374-9808-21daf0951917" />

**Step 2, Generate a Multiview Drawing**

Below is a image of my Multiview Drawing of the Bracket, I decided to use a pretty big template and I see now that I could have definitely gone a little smaller so that you could see the dimensions and tolerances a lot easier. I started by placing all the views in their respected locations making sure that they are lined up with the other views of the bracket. I then selected a Isometric View and placed it in the upper right of the drawing template like I have done in previous classes and assignments. I selected the dimensioning tool and started selecting the dimensions that I thought we the must useful and meaningful for a engineer to look at to determine certain specs of this design. I made sure to not make a complete mess of where I placed those said dimensions, making sure none cross over and interfere with another. I set the tolerances for the specific dimensions, making sure that they were plus and minus so we can assess the amount of error we have. Lastly, I changed the template to be our UNC Charlotte style with the Title Block information at the bottom right of the drawing letting list some very useful info such as the part name, the date, and material. 
<img width="1238" height="811" alt="Screenshot 2026-09-28 172823 (1)" src="https://github.com/user-attachments/assets/08c41e43-31a5-44f8-b536-4d4886bd2371" />

**Better Image of Title Block**
<img width="941" height="263" alt="Screenshot 2026-09-28 172839 (1)" src="https://github.com/user-attachments/assets/ef798f49-d1fb-490d-9afb-42ddcb986e1a" />

Download My CAD File Here: [a6bracketdesign.prt.zip](https://github.com/user-attachments/files/32775527/a6bracketdesign.prt.zip)

## Decide

**Reflecting:**

**A)**

A tighter three-decimal-place tolerance was used for the width of Feature E to ensure proper alignment and reduce unwanted movement. This was especially important because Feature E is subjected to a moment from the applied load while resting against the rigid T-beam rail, which has a width of 0.550 inches. In comparison, the diameter of the cylindrical pin at Feature A, measuring 0.8 inches, was given a more relaxed tolerance because it is considered a non-critical dimension. The strap only needs to remain securely supported by the pin, so extremely precise sizing is not necessary.

The sliding connections were also accounted for by specifying limits on the key clearance dimensions. The nominal "a" gap was assigned a tolerance of 0.59 +0.00 / −0.10 in, while the larger horizontal clearance was specified as 1.500 +0.000 / −0.001 in. These limits establish the amount of clearance available at the sliding interfaces and ensure that the drawing provides the necessary control over the free-moving fit shown in Figure 1. This approach follows the requirement for nominal dimension "c," where maintaining accurate positioning while limiting excessive play is important for proper function.

**B)**

Feature D is designed with a -0.001" tolerance because it needs to function as a sliding connection with its mating component. This amount of clearance gives the bracket enough freedom to move into position without making the connection excessively loose. The tolerance was selected based on the part's function rather than simply making the dimensions as precise as possible.

Using extremely tight tolerances throughout the entire part would also make the manufacturing process more expensive and time-consuming. A dimension requiring a 0.0001" tolerance would require much more careful machining and inspection than one with a 0.001" tolerance. The machinist would have to make smaller adjustments and remove material more gradually to avoid exceeding the required dimension. By allowing a slightly larger tolerance where the design permits it, the part can still perform properly while being faster and less expensive to manufacture.

## Communicate

This assignment took me 8 hours. 
