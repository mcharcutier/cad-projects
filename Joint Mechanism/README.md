# **Joint Mechanism V.1**

## **Overview**

This project aims to design a rotational joint mechanism inspired by an anglepoise lamp, allowing controlled 360° equatorial motion while maintaining positional stability without permanent locking features.

## **Goals**

→ Allows 360° equatorial base rotation.

→ Maintains arm stability without ratcheting or locking features.

→ Minimizes gravitational droop.

→ Avoids permanent deformation under expected loads.

## **Success Criteria**

→ Designed friction joint to maintain angular position of both stnading arm and forearm under load. 

→ Identified frictional torque as the primary holding mechanism, eliminating need for springs

→ Printed pivot holes must be within ±0.2 mm of the intended diameter.

→ All components must assemble using only the printed parts and washers,
with no post-processing required.
>> 4/16: That was the initial success criteria; now preload fastening system includes metal M12 fasteners. 

→ Printed links must withstand normal handling and full articulation
without cracking or layer separation.

→ Washer seats must maintain flat contact surfaces that prevent
lateral play during joint rotation.

## **Process**

### **Conceptual Understanding**
For this project, I chose to reference and anglepoise lamp joint mechanism, especially with the joint and the base of the system. The base allows the joint to move 360° equatorially. 

The anglepoint lamp joint typically utilizes a spring mechanism to balance the torque against gravity. Gravitational torque changes with angle, making the arms want to droop. By balancing the torque induced by gravity with friction, the arm "floats," preventing sudden jerks, making the relative position of the joint mechanism stable regardless of the angle. 
 
### **Main Takeaways**
→ Keep the COM closer to the base to prevent the joint from tipping over. 

→ Torque = mass x gravitational force x radius. It's important to reduce the torque induced by gravity. Some methods to reduce include:

>> Make the forearm shorter.
>> 
>> Make the forearm lighter.
>> 
>> Centralize the mass near the radius.
>> 
>> Add mass to the base to prevent tipping.
>> 
>> Keep the hardware near the joints.
>> 
>> Include a defined friction choice to introduce the frictional torque necessary to counter the torque induced by gravity.

### **Expected Assembly Steps**
1. Insert pivot pins into base joints.
   
2. Place washers in recessed seats.
   
3. Attach forearm link.
   
4. Secure rotating components.

## **Engineering Considerations**

→ FDM printing typically produces undersized holes due to material shrinkage.

→ Additional clearance was included in pivot holes to compensate for this behavior.

→ Washer recesses were designed to provide flat bearing surfaces and reduce plastic-on-plastic wear.

→ Joint tolerances were selected to balance two competing requirements:

> smooth articulation.
   
> sufficient friction to resist gravitational torque.
  
## **Testing and Observations**

### **V.1.0** 
→ Incorrect offset caused poor first-layer adhesion. 

→ Printed bolts as fasteners. 

→ No washer recesses.

[Full Assembly Print:]
>  Exceeds build plate dimensions
> 
> ~400g of filament, ~12 hours to complete printing
> 
> Potential fusing of surfaces if clearance is insufficient. 
> 
> Would need to reprint the entire assembly if an iteration is unsuccessful.

[Component - Based Printing:]
> Will fit on the bed (excluding the Body-Base 2 due to the legs. The height can be reduced for it to properly print within the bounds of the printer.
>
> Will require more filament, but shorter print duration
>
> Can print replacement components if damaged or ineffective to the design intent.

### **Clearance Dimensions**:

→ Standing Arm - Leg Peg:

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

→ Joint - Peg:

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

OBSERVATIONS:
• Full Print Assembly:

[Insert Image here]

→ Printed PLA bolts deformed at thread geometry prior to establishing measurable preload.

→ The base is heavy enough to hold the joint system without it collapsing. 

→ Fastener material identified as limiting variable — a metal preload fastening system required to establish sufficient clamping force at friction interface. 

→ Friction interface was not loaded -> frictional torque capacity could not be measured. Can be fixed with a preload fastening system to connect the surfaces closer together. 

### **V.2.0** 
• Full Print Assembly:

[Insert Image here]

• Gravitational Torque Values:

| Arm Component  | Length (mm) | Gravitational Torque Values ( N × m) | 
| ------------- | --------- | ------------------------| 
| Black Arm  | 220 mm  | .65 - 1.08 N × m| 
| Forearm  |  185 mm  | .045 - .081 N × m | 

→ Gravitational torque of black arm exceeded friction torque capacity by approximately 7–20x — black arm identified as beyond design load of PLA friction interface.

→ Replaced printed fasteners with M12 fastening system, which includes bolts, washers, and nuts for a more effective preload within the joint system. 

→ Black arm could not hold itself up with the current fastener system. Conducted torque analysis using the black arm as the primary articulating element rather than using the base. 

→ Calculated a frictional torque between .05 - .15 N × m at the test load. The frictional torque value is within capacity of the gravitational torque at the joint.

→ Washer system was designed for M10 fastening system but used M12 -> fundamental load mismatch. 


## **Manufacturing Notes**
→ Pivot holes designed with ±0.2 mm radial clearance to compensate for FDM hole shrinkage. 
> Clearance validated through test prints.

→ Washer recesses included to maintain flat bearing surfaces and reduce friction
between rotating components.
> Recess depth: 0.2 mm.

→ Initial prints failed due to inadequate Z-offset calibration,
leading to poor first-layer adhesion. 
> Issue resolved through bed cleaning and offset adjustment.

### **Printer Calibration Setup**
→ For regular PLA, it should feel as if the nozzle is lightly brushing the paper. 

→ For Matte PLA, the Z-offset should be lower to compensate for the filament's higher viscosity and ensuring that it sticks.

## **Lessons Learned**
→ Proper Z - offset for general FDM use. It should feel as if the nozzle is lightly brushing the paper; not pressing nor scratching it. 
> Soft resistance, paper moves slowly, nozzle doesn't catch/tear it. 

## **Next Steps**
→ Print and assemble the first full iteration of the joint. 

→ Evaluate articulation smoothness and positional stability.

→ Measure whether friction is sufficient to resist gravitational torque.

Future iterations can explore:

→ spring-assisted balancing

→ improved joint tolerances

→ electronically actuated motion
