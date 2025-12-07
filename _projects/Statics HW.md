---
layout: project
title: Statics HW
description: Assignment
technologies: [Goodnotes, Calculator]
image: /assets/images/statics5.jpg
---
Step 1
Problem: Design a system to hold the max weight and least mass
Constraints: Must use 3 pins and limted to a 150cm by 150 cm box
Freedom: Must choose a linear actuator that performs under these constraints in real world situations

1b) I drew a system that has 3 pins, on at A connecting the linear actuator to the ground. Next, connecting the actuator bar to the lever bar. Lastyly, pinning the lever bar to the ground. I used the integrated servo actuator which has an extension length of 50cm and max of 36 kN of force.
Using an height of 30 cm which can be calucated using geometry, we can find the angle phi by inverse tan. Once phi is solved then theta can be solved for considering sum of angles. Then L can be solved for using height/sin theta. Finally we can find By using moment around C which is 60kN which translates to max weight the system can raise to max height of 30 cm. 

<img src="{{ '/assets/images/Calculations.jpg' | relative_url }}" width="500">

This image shows the calculations done in Step 1 for Homework 5.


 Step 2

  2a) Now considering the beam is no longer rigid like in Step 1, we must find the maximum deflection in your beam.
  Assumptions: phi= 36.87
               theta= 53.13
               w= 60 kN
               thickness = 2cm
               A= 2cm x 2 cm for the beam
Now using the appendix we can use the formula Delta L= FL^3/ 3EI to find the deflection of the beam. 
By using these assumptions we calculate the I value using bh^3/12. The force is found by weight times sin theta.
As you see in the image, the max deflection is 105.46 mm which makes sense in regard to the assumptions of this set up.

2b) Now we are redesigning the beam's cross section/ material in order for its vertical deflection to be below 2% of its length and is the most mass-efficient possible.

First we calculate how much the deflection is which is L times 0.02 which equals 0.0075m
Then we must change the I value to accomodate cross sectional changes. Alos the material property should change to be more stiff as 
0.0075 is a very small amount when it can deflect 0.105m max. I chose a high modulus carbon fiber material which has a youngs modulus
of 800 GPa. Also, I changed the base to be 0.022m and height to be 0.03m. The image below shows the calculations for step 2 and the drawing changes.




