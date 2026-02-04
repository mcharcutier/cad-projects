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

*Date of Print: 12/17/2025*

→ The keychain barely fit in my palm; the objective was to make sure that I could easily grasp it within my palm, requiring the design to be smaller.

→ When working on it, the blood splatter came off as sharp, like the tip of an arrow, rather than it looking globular, like a drop of blood. 

→ The outer body of the keychain did not look right. Looking back it, it would have made more sense if the outer body was raised higher than the inside of the keychain. 

→ The sketch was not fully constrained prior to extruding it. 

→ The first print iteration resulted in the bottom layers not lying on top of the bed.

>>Troubleshooting indicated that the bed may not have been completely even or that the z-offset was not properly adjusted with respect to the bed. 

### *v.2.0* 

*Date of Print: 1/5/2026 (white); 1/21/2026 (gray)*

→ The keychain was able to better fit into my palm. 

→ The blood splatter was more globular. 

→ The sketch was fully constrained prior to extruding it with help from the external tutorial. 

>> I also split the keychain into 3 components: Base; Eyes, Mouth; Blood Splatter for an easier method of properly extruding the separate components of the keychain.

>>> Troubleshooting narrowed the issue behind the prints being the z-offset being too close to the bed of the print. Z-offset was increased from -1.380mm → -1.180mm. The top surface flow rate was also edited from 100% → 95%, allowing the layers to properly lie on top of the bed. 

#### *v.2.1*

*Date of Print: 2/2/2026 - 2/3/2026*

→ The loop designated for the keyring in v.2.0 broke as the result of realsitic use conditions. The first one broke while it was resting in my pocket all day, as I was walking around throughout the day. The second one broke as a result of removing the print prematurely off the print bed at elevated temperature - leading to it being structurally weak compared to the rest of the print - followed by then accidently dropping them on the floor. 

→ To resolve this issue, I increased the thickness of the loop by offsetting its sketch on Fusion360. The loop was offsetted by -0.5mm in v.2.0; for this version, the loop is now offsetted -1.2mm from the outer arc of the loop. 

→ 2/2: The significant issue while printing was that the extruder would unknowingly pause mid-print, making an 18 minute print estimate itself to take double the time to complete. The third print was a significant improvement. 

>> Troubleshooting indicated that the issue may be that the filament is too hot to use after staying at 205℃ for too long, so I let the printer rest before I continued printing.

→ 2/3: I aimed to perfect the print before I moved on to other projects. Through tedious trial and error, as well as a lot of stringing and cold pulls, I determined that a Z-offset of -1.050 would be ideal position for the nozzle. I also preheated the filament to 140℃ rather than letting it fully rest before beginning to print the keychain. The result was the smoothest bottom layer that I have ever achieved out of all of my prints. 


## **Manufacturing Notes**

→ Printed in PLA on Neptune 4.

→ Layer fusion at the base of the keychain 

→ Geometry was sound; issue was slicer/material tuning rather than CAD error.

## **Next Steps**

→ Introduce user-defined parameters to control overall size, loop thickness, and base depth to improve parametric flexibility. 
