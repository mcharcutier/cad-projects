# **Joint Mechanism V.1**

## **Overview**

This project aims to design a rotational joint mechanism inspired by an anglepoise lamp, allowing controlled 360° equatorial motion while maintaining positional stability without permanent locking features.

## **Goals**

→ Allows 360° equatorial base rotation.

→ Maintains arm stability without ratcheting or locking features.

→ Minimizes gravitational droop.

→ Avoids permanent deformation under expected loads.


## **Success Criteria**

→ The mechanism must hold its position at any angle between 0° and 90°
without external support.

→ Printed pivot holes must be within ±0.2 - ±0.5 mm of the intended diameter.

→ All components must assemble using only the printed parts and washers,
with no post-processing required.

→ Printed links must withstand normal handling and full articulation
without cracking or layer separation.

→ Washer seats must maintain flat contact surfaces that prevent
lateral play during joint rotation.

## **Process**

### **Conceptual Understanding**
For this project, I chose to reference and anglepoise lamp joint mechanism, especially with the joint and the base of the system. The base allows the joint to move 360° equatorially. 

The joint utilizes a spring mechanism to balance the torque against gravity. Gravitational torque changes with angle, making the arms want to droop. By balancing the torque induced by gravity, the arm "floats," preventing sudden jerks, making the relative position of the joint mechanism stable regardless of the angle. 

While printing the components, I ran out of my regular filament, requiring me to learn to work with matte PLA, which is known for being more brittle and requires a higher temperature than regular PLA to properly utilize it. 

### **Printer Calibration Setup**
→ For regular PLA, it should feel as if the nozzle is lightly brushing the paper. 

→ For Matte PLA, the Z-offset should be lower to compensate for the filament's higher viscosity and ensuring that it sticks.
 
### **Main Takeaways**
→ Keep the COM closer to the base to prevent the joint from tipping over. 

→ Torque = mass x gravitational force x radius. It's important to reduce the torque induced by gravity. Some methods to reduce include:

>> Making the forearm shorter.
>> 
>> Making the forearm lighter.
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
→ Matte PLA works better at 215℃, compared to 205℃ for most regular PLA. 

→ The Z-offset for Matte PLA needs to be closer to the nozzle, as first-layer bed adhesion can prove to be difficult with Matte PLA. 

→ FDM printing typically produces undersized holes due to material shrinkage.

→ Additional clearance was included in pivot holes to compensate for this behavior.

→ Washer recesses were designed to provide flat bearing surfaces and reduce plastic-on-plastic wear.

→ Joint tolerances were selected to balance two competing requirements:

> smooth articulation.
   
> sufficient friction to resist gravitational torque.
  
## **Testing and Observations**

### **V.0.0** 
→ Incorrect offset caused poor first-layer adhesion. 

→ Full Assembly Print:
>  Exceeds build plate dimensions
> 
> ~400g of filament, ~12 hours to complete printing
> 
> Potential fusing of surfaces if clearance is insufficient. 
> 
> Would need to reprint the entire assembly if an iteration is unsuccessful.

→ Component - Based Printing:
> Will fit on the bed (excluding the Body-Base 2 due to the legs. The height can be reduced for it to properly print within the bounds of the printer.
>
> Will require more filament, but shorter print duration
>
> Can print replacement components if damaged or ineffective to the design intent.

### **Clearance Dimensions**:

→ Standing Arm - Leg Peg:
> Peg ⌀ = 12mm
> 
> Peg Hole ⌀ = 12.2mm
> 
> Washer Seat Inner ⌀ Offset from Peg Hole = 0.2mm
> 
> Washer Seat Outer ⌀ = 24.60mm
> 
>> Improved rotational clearance, taking into account of PLA tolerance of ± 0.02mm.

→ Joint - Peg:
> Peg ⌀ = 9.90mm
>
> Hole ⌀ = 10.30mm
> 
> Hole Offset from Inner Washer Seat = 0.2mm
> 
> Washer Seat Outer ⌀ = 20.70mm
>
> Clearance added to account for FDM hole shrinkage and dimensional variation.
> 
>> Designed clearance: ~0.2–0.4 mm.

## **Manufacturing Notes**
→ Pivot holes designed with +0.6 mm clearance to compensate for FDM hole shrinkage. 
> Clearance validated through test prints.

→ Washer recesses included to maintain flat bearing surfaces and reduce friction
between rotating components.
> Recess depth: 0.2 mm.

→ Initial prints failed due to inadequate Z-offset calibration,
leading to poor first-layer adhesion. 
> Issue resolved through bed cleaning and offset adjustment.

## **Lessons Learned**
→ Proper Z - offset for general FDM use. It should feel as if the nozzle is lightly brushing the paper; not pressing nor scratching it. 
> Soft resistance, paper moves slowly, nozzle doesn't catch/tear it. 

## **Next Steps**
→ Print and assemble the first full iteration of the joint. 


→ Explore taking the joint to the next level. 
> Next iteration should involve electronics, involve calculations stemming from conceptual understanding (torque, forward kinematics).
> 
→ Iterate using Python API to streamline assembly process. 
