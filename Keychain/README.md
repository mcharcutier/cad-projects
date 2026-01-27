# **Keychain Model**

## **Overview**
The aim of this project was to develop and print a functional keychain prototype that explores the utilization of components and fully constraining sketches. 

## **Goal**
Design a keychain accessory that is fully constrained, printed with minimal stringing, and all of the layers are completely rested on top of the bed of the printer. 

## **Success Criteria**
→ The loop of the keychain must be able to fit standard keyrings.

→ The keychain must be able to withstand normal handling without the layers separating. 

→ The keychain must be able to comfortably rest in one hand, with its overall dimensions constrainted to fit within the standard adult palm without heavily restricting finger movement.

## **Process**
For my keychain, I referenced the image below for its simplicity and for my interest in the graphic novel "*<ins>Watchmen</ins>*."

![The Comedian's Badge](https://static.wikia.nocookie.net/headhuntersholosuite/images/1/1f/Comedian%27s_button.jpg/revision/latest?cb=20200827152035)

*After I worked on v.1.0, I referenced an external video so that I could better understand how to utilize constraints before I begin extruding my sketches.*

- [Fusion 360 Tutorial for Absolute Beginners - Lars Christensen](https://www.youtube.com/watch?v=A5bc9c3S12g)

## **Notes**

### *v.1.0*

→ The keychain barely fit in my palm; the objective was to make sure that I could easily grasp it within my palm, requiring the design to be smaller.

→ When working on it, the blood splatter came off as sharp, like the tip of an arrow, rather than it looking globular, like a drop of blood. 

→ The outer body of the keychain did not look right. Looking back it, it would have made more sense if the outer body was raised higher than the inside of the keychain. 

→ The sketch was not fully constrained prior to extruding it. 

→ The first print iteration resulted in the bottom layers not lying on top of the bed.

>>Troubleshooting indicated that the bed may not have been completely even or that the z-offset was not properly adjusted with respect to the bed. 

### *v.2.0*

→ The keychain was able to better fit into my palm. 

→ The blood splatter was more globular. 

→ The sketch was fully constrained prior to extruding it with help from the external tutorial. 

>> I also split the keychain into 3 components: Base; Eyes, Mouth; Blood Splatter for an easier method of properly extruding the separate components of the keychain.

→ Troubleshooting narrowed the issue behind the prints being the z-offset being too close to the bed of the print. Z-offset was increased from -1.380mm → -1.180mm. The top surface flow rate was also edited from 100% → 95%, allowing the layers to properly lie on top of the bed. 

## **Manufacturing Notes**

→ Printed in PLA on Neptune 4.

→ Layer fusion at the base of the keychain 

→ Geometry was sound; issue was slicer/material tuning rather than CAD error.

## **Next Steps**

→ Introduce user-defined parameters to control overall size, loop thickness, and base depth to improve parametric flexibility. 

→ Explore strength and failure awareness through applying twisting force, pulling force, and simulated pocket movement. 

>> Look for layer separation, deformation at loop, cracks near sharp transitions. 
