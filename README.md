# EX.No.-2.2 CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date : 15/10/2026

## AIM: 

To create a 3Dmodel from the given isometric drawing using fusion 360 tool. 

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## Procedure:
1. Open the CAD software and create a "New Part File** (prt or.sldprt).

2. Set the unit system to "MMGS** (Millimeter, Gram, Second).

**Step 2: Modeling the Base Plate**

1. Select the **Top Plane** and create a new sketch.

2. Draw two circles of diameter spaced 56mm apart horizontally along the center axis.

3. Draw concentric arcs of radius R18mm around each circle center.

4. Connect the outer arcs with tangent lines to complete the slot-like base boundary.
5. Extrude the sketch upwards using **Extrude Boss/Base** with a height/depth of **8𝑚𝑚**.
<img width="753" height="471" alt="{80859294-5513-450E-A68B-33BEB7529EDC}" src="https://github.com/user-attachments/assets/c3082196-6714-4d5c-93bd-0d108d87c8f6" />

**Step 3: Modeling the Vertical Block**

1. Select the top surface of the base plate (or the **Front/Right Plane**) to create the central vertical support profile.

2. Sketch a rectangle with a width of **40mm**, thickness of **10mm**, and height of ** 32mm** rising above the top surface of the base.

3. Apply **Extrude Boss/Base** to create the solid vertical block.

<img width="757" height="358" alt="{875837CF-9616-4EC5-B738-6532D2DAB049}" src="https://github.com/user-attachments/assets/3bad69a0-6712-4a5e-8ba5-1fe718dc4496" />

**Step 4: Creating the Triangular Support Rib (Stiffener)**

1. Select the symmetry plane (e.g., **Right Plane** or mid-plane passing through the center of the part).

2. Draw a right-angled triangle sketch connecting the top rear edge of the vertical block to the top face of the base plate.

3. Use the **Rib Feature** (or **Extrude Mid-Plane**) with a specified thickness of **12mm**

<img width="761" height="368" alt="{506FCE28-7553-44B6-A6F9-234E9CD6F72E}" src="https://github.com/user-attachments/assets/791d22a2-7bfe-48d7-a8ec-3b0613cd7dda" />

**Step 5: Modeling the Upper Cantilever Arm**

1. Select the front face of the vertical block.

2. Create a sketch extending forward horizontally:

* Extension length = **32mm**

*Height/Thickness = **10mm**

*Width = **40mm** (matching the vertical block width)

3. Extrude the sketch to create the horizontal cantilever portion.

**Step 6: Modeling the Upper Cylindrical Boss & Center Hole**

1. Select the top surface of the upper cantilever arm or a parallel plane.

2. Draw a circle of diameter centered at the front end of the arm

3. Extrude this sketch upwards by **10mm**.

4. Select the top face of the new cylinder, sketch a concentric circle of diameter **$\varnothing20\text{ mm}$**.

5. Apply **Extruded Cut** with the condition **Through All** to create the central hole.
<img width="755" height="403" alt="image" src="https://github.com/user-attachments/assets/7b2c1e8f-a28a-462c-aad6-d8c9426cf395" />

**Step 7: Final Inspection & File Saving**

1. Inspect the feature tree to ensure proper parent-child relations and fully constrained sketches.

2. Check all dimensions against the drawing.

3. Apply appearance/material (e.g., Magenta/Purple color as seen in the source image) if required.

4. Save the file as 'Mechanical_Bracket.SLDPRT' (or corresponding extension).

Output:

<img width="760" height="515" alt="{D08E41ED-60C5-4260-804A-6DD8A24620B1}" src="https://github.com/user-attachments/assets/9391b392-d593-4161-879c-44099026633a" /> 

<img width="723" height="526" alt="{39504DB9-7F4A-49BB-914E-D17CCDCEE62D}" src="https://github.com/user-attachments/assets/0df61673-d178-4f77-82cf-ccb1c19b44fe" />

## RESULT: 
Thus, the 3D model is created from given isometric drawing.


