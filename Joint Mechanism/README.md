# **Joint Mechanism V.1**

## **Overview**

This project aims to design a rotational joint mechanism inspired by an anglepoise lamp, allowing controlled 360° equatorial motion while maintaining positional stability without permanent locking features.

__Skills & Tools:__

• Autodesk Fusion (Parametric modeling, assembly, tolerancing)

• FDM Fabrication (Elegoo Neptune 4, PLA Manufacturing)

• Gravitational & Frictional Torque Analysis

• Preload Fastening Systems

## **Design Requirements**

• 360° equatorial rotation at the base

• Passive positional stability without ratcheting or locking features.

• Resistance to gravitational droop

• No permanent deformation under expected operating loads. 

## **Success Criteria**

•Friction-based joint designed to maintain angular position of both the standing arm and forearm under load, eliminating the need for spring-assisted balancing.

• Pivot hole diameters held to a tolerance of ±0.2 mm of nominal dimension.
Full assembly achieved using only printed components and washers; no post-processing required.

> **Updated (4/16)**: Preload fastening system revised to incorporate metal M12 fasteners.

• Printed links must withstand normal handling and full articulation range without cracking or layer separation.

• Washer seats must maintain flat, perpendicular contact surfaces to prevent lateral play during joint rotation.

## **Process**

### **Conceptual Understanding**
This design references the anglepoise lamp joint architecture, particularly its base rotation and arm balancing mechanisms. 

The anglepoint lamp joint conventionally utilizes spring tension to counter the gravitational torque, which varies with arm angle, allowing the arm to remain stable at any position. This design utilizes a preloaded friction interface to resist gravitational torque, elimintating springs while maintaining positional stability. 
 
### **Key Design Principles Derived From Reference**
• Keep the COM closer to the base to prevent tipping.

• Torque (𝝉 = m × g × r) must be minimized through geometry and mass distribution. Strategies include:

> • Shortening forearm length
>
> • Reducing forearm mass
> 
> • Centralizing component mass near the joint axis
>
> • Adding ballast to the base
> 
> • Locating the hardware near the joints.
>
> • Include a defined friction choice to introduce the frictional torque necessary to counter the gravitational torque

## **Engineering Considerations**

• **FDM Behavior:** Undersized holes due to material shrinkage during cooling process. Additional clearance was included in pivot holes to compensate for this behavior.

• **Bearing Surface Design:** Washer recesses were designed to provide flat bearing surfaces and reduce plastic-on-plastic wear.

• **Joint Tolerance Philosophy:** Joint tolerances were selected to balance:

> smooth articulation.
   
> sufficient friction to resist gravitational torque.

### **Clearance Specifications**:

• Standing Arm - Leg Peg:

<img width="1315" height="790" alt="image" src="https://github.com/user-attachments/assets/67ec5d37-97ff-4482-a7c6-0423dcfa725c" />

> Peg ⌀ = 12mm
> 
> Peg Hole ⌀ = 12.2mm

<img width="1315" height="790" alt="image" src="https://github.com/user-attachments/assets/14d953ab-88aa-4436-b601-700759946800" />

> Washer Seat Inner ⌀ Offset from Peg Hole = 0.2mm
> 
> Washer Seat Outer ⌀ = 24.60mm
> 
>> Improved rotational clearance, taking into account of FDM variational clearance (~ ±0.1 - ±0.3mm)

• Joint - Peg:

<img width="992" height="776" alt="image" src="https://github.com/user-attachments/assets/884ff8f1-c4e4-438f-a903-0b9176cb893b" />

> Peg ⌀ = 9.90mm
>
> Hole ⌀ = 10.30mm
>
> Hole Offset from Inner Washer Seat = 0.2mm
> 
> Washer Seat Outer ⌀ = 20.70mm
>
>> Clearance added to account for FDM hole shrinkage and dimensional variation.
> 
>> Designed clearance: ~ ±0.2mm radial clearance.
  
## **Testing and Observations**

### **V.1.0** 

[Insert Image here]

• Incorrect offset caused poor first-layer adhesion. 

• Printed PLA bolts deformed at thread geometry prior to establishing any measurable preload — fastener material identified as the primary limiting variable.

• Friction interface was never loaded; frictional torque capacity could not be evaluated.

__Print Strategy Evaluation:__

__Full Assembly Print:__
>  Exceeds build plate dimensions
> 
> ~400g of filament, ~12 hours to complete printing
> 
> Potential fusing of surfaces if clearance is insufficient. 
> 
> Would need to reprint the entire assembly if an iteration is unsuccessful.

__Component - Based Printing:__
> Will fit on the bed (excluding the Body-Base 2 due to the legs. The height can be reduced for it to properly print within the bounds of the printer.
>
> Will require more filament, but shorter print duration
>
> Can print replacement components if damaged or ineffective to the design intent.

### **V.2.0** 
• __Full Print Assembly__:

[Insert Image here]

• __Gravitational Torque Values & Analysis:__

| Arm Component  | Length (mm) | Gravitational Torque Values ( N × m) | 
| ------------- | --------- | ------------------------| 
| Black Arm  | 220 mm  | .65 - 1.08 N × m| 
| Forearm  |  185 mm  | .045 - .081 N × m | 

• Gravitational torque of black arm exceeded friction torque capacity by approximately 7–20x — black arm identified as beyond design load of PLA friction interface.

• Replaced printed fasteners with M12 fastening system (bolts, washers, and nuts) for  sufficient clamping force at the friction interface.

• Black arm could not hold itself up with the current fastener system. Conducted torque analysis using the black arm as the primary articulating element rather than using the base. 

• Calculated a frictional torque between .05 - .15 N × m at the test load. The frictional torque value is within capacity of the gravitational torque at the joint.

• __Note:__ Washer system was designed for M10 fastening system but used M12 -> fundamental load mismatch that must be resolved in future iterations. 
> Identified clearance gap within fastener stack → insufficient contact pressure at friction interface. Introduced PLA filament shim to take up slack and introduce controlled preload. 

## **Manufacturing Notes**
• Pivot holes designed with ±0.2 mm radial clearance to compensate for FDM hole shrinkage. 
> Clearance validated through test prints.

• Washer recesses included to maintain flat bearing surfaces and reduce friction
between rotating components.
> Recess depth: 1.0 mm.

• Initial prints failed due to inadequate Z-offset calibration,
leading to poor first-layer adhesion. 
> Issue resolved through bed cleaning and offset adjustment. 

## **Lessons Learned**
• Printed polymer fasteners are insufficient to generate preload in friction-based joint systems under meaningful gravitational loads. Metal fasteners are required.

• Hardware sizing must be matched to printed geometry from the outset; a washer-fastener mismatch (M10 seat, M12 bolt) introduces unintended load distribution and should be treated as a design error.

## **Next Steps**
• Evaluate articulation smoothness and positional stability.

• Measure whether friction is sufficient to resist gravitational torque.

__Future Iterations:__
• Redesign washer seats to match M12 fastener geometry.

• Investigate spring-assisted balancing to expand load capacity

• Refine joint tolerances based on assembled test data.

• Explore electronically actuated motion as a long-term development path. 
