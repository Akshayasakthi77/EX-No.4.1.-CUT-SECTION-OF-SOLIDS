# EX No.4.1. CUT SECTION OF SOLIDS
## DATE:22/10/2026
NAME:AKSHAYA S
Reference number: 26018325

## AIM
To create the solid model from given drawing and section the solid model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3.16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
Step 1: Create the Base Flange

* Start a Sketch: Click Create Sketch and select the Front (XZ) Plane (or any vertical plane).
* Draw Circles:
	• Draw a center circle at the origin with a diameter of 50 mm (or two R15 mm arcs at the ends).
	• Place two points vertically aligned with the origin—one 35 mm above and one 35 mm below (70 mm total spacing).
	• Draw two 30 mm diameter (R15 mm) outer circles and two 12 mm diameter inner holes centered on those two points.
* Connect Tangents: Use the Line tool to connect the outer edges of the 50 mm center circle to the top and bottom R15 mm circles. Apply Tangent constraints to all four contact points.
* Extrude: Finish the sketch, select the flange profile (excluding the two 12 mm holes), and Extrude it forward by 10 mm.

![image](https://user-images.githubusercontent.com/113594316/198825274-c6a8d3ee-fb19-4641-b915-8d2e000c40a8.png)

Step 2: Extrude the Cylindrical Boss

* New Sketch: Select the front face of the 10 mm flange and click Create Sketch.
* Draw Boss Circle: Draw a circle centered at the origin with a diameter of 50 mm.
* Extrude: Finish the sketch and Extrude this circle forward by 28 mm (Join operation). The total thickness from the back face to the front of the boss is now 38 mm.


![image](https://user-images.githubusercontent.com/113594316/198825282-0d3de4b8-b6d9-446a-ae2a-461955057399.png)

Step 3: Add the Counterbored Center Hole

* Activate Hole Tool: Go to Create > Hole (or press H).
* Select Placement: Click the front flat face of the 50 mm boss and snap the center point to the origin.
* Set Hole Parameters:
	• Extents: All (cuts completely through the 38 mm body).
	• Hole Type: Counterbore.
	• Counterbore Diameter: 30 mm.
	• Counterbore Depth: 6 mm.
	• Hole Diameter: 20 mm.
* Click OK to cut the hole.

![image](https://user-images.githubusercontent.com/113594316/198825314-b90f6aba-da26-4f0d-8d61-a03e8ad0d765.png)

Step 4: Add the Top Oil/Pin Hole (Ø6 mm)

* Create Tangent Plane: Go to Construct > Tangent Plane, click the outer cylindrical surface of the 50 mm boss, and set the angle so the plane sits horizontally on top (0°).
* Sketch the Hole Center: Click Create Sketch on this new tangent plane. Place a Point aligned with the vertical center axis, dimensioned 12 mm back from the front face of the boss.
* Cut the Hole: Finish the sketch and use the Hole tool (or Extrude Cut) with a diameter of 6 mm, cutting downward until it breaks into the 20 mm inner bore (To Object -> inner bore wall).

![image](https://user-images.githubusercontent.com/113594316/198825328-205fac21-1322-4d67-894b-6fd92e454e26.png)

## INPUT:

<img width="1600" height="900" alt="WhatsApp Image 2026-11-17 at 9 27 04 PM" src="https://github.com/user-attachments/assets/a6f930d5-efe1-49db-a745-7ba58b372a5b" />


## OUTPUT:
<img width="1600" height="900" alt="WhatsApp Image 2026-11-17 at 9 27 03 PM" src="https://github.com/user-attachments/assets/47f55fe8-a574-485c-acaf-e185f32064fd" />


## RESULT:

Thus, the cut section for solid model is created.

