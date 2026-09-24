PROCESS PLANNING AND SIMULATION OF A TRANSMISSION SHAFT MANUFACTURING PLANT USING DELMIA


1. AIM

To develop the process plan and simulate the plant layout for the batch production of a transmission shaft using CNC and NC machining operations, and to create a virtual manufacturing environment using DELMIA for studying material flow, machine arrangement, material handling, productivity, and workplace safety.


2. OBJECTIVES

1. To study the manufacturing process of a transmission shaft.
2. To select suitable material and manufacturing operations.
3. To prepare a suitable process sequence for batch production.
4. To identify the machines, equipment, storage areas, and inspection facilities required.
5. To estimate the approximate manufacturing cycle time.
6. To simulate the plant layout using DELMIA Plant Layout Design.
7. To study the material flow between different manufacturing stations.
8. To analyze unnecessary material movement and handling.
9. To incorporate safety fencing and operator working areas in the virtual plant.
10. To visualize the complete manufacturing plant in a 3D simulation environment.


3. INTRODUCTION

A transmission shaft is a rotating mechanical component used to transmit torque and rotary motion from one component to another. Transmission shafts are widely used in automobiles, industrial machinery, gearboxes, pumps, and other power-transmission systems.

For batch production, CNC and NC machining are suitable because they provide good dimensional accuracy, repeatability, and productivity.

In this work, a virtual manufacturing plant for transmission shafts is considered. The complete manufacturing system consists of raw material storage, material cutting, CNC turning, NC machining, drilling or tapping, finishing, deburring, inspection, and finished-product storage.

The plant layout is simulated using DELMIA Plant Layout Design. The simulation includes machines, conveyors, storage racks, inspection areas, operator areas, and safety fencing to represent a practical manufacturing environment.

The DELMIA simulation helps in visualizing the arrangement of manufacturing resources and studying the movement of material through the proposed production system before physical implementation.


4. PRODUCT DESCRIPTION

Product: Transmission Shaft

Function: Transmits torque and rotary motion

Applications: Automotive and industrial machinery

Production Type: Batch Production

Manufacturing Method: CNC Turning and NC Machining

Material: EN8 / AISI 1040 Steel

Raw Material Form: Hot-rolled round bar


5. MATERIAL SELECTION

Material Selected: EN8 / AISI 1040 Steel

EN8 steel is selected for the transmission shaft because it provides a suitable combination of strength, toughness, machinability, and wear resistance. It is also suitable for machining operations such as turning and drilling.

Raw Material Form: Hot-rolled round bar


6. PROCESS PLANNING

The transmission shaft is manufactured using a sequence of machining and finishing operations.

PROCESS FLOW:

Raw Material Storage
        ↓
Material Cutting – Band Saw
        ↓
Facing and Centering – CNC Turning Centre
        ↓
Rough Turning
        ↓
Step and Profile Turning
        ↓
Grooving and Chamfering
        ↓
Drilling / Tapping – If Required
        ↓
Finish Turning
        ↓
Deburring
        ↓
Inspection
        ↓
Finished Goods Storage


7. MANUFACTURING OPERATIONS


7.1 RAW MATERIAL STORAGE

The hot-rolled EN8 round bars are received and stored in the designated raw-material storage area.

The storage area is positioned near the material-cutting station to reduce unnecessary material movement.


7.2 MATERIAL CUTTING

The raw material is cut into the required lengths using a band saw machine.

Purpose:

• To obtain blanks of suitable length.
• To prepare the material for CNC machining.
• To reduce material wastage.

Machine Used: Band Saw Machine


7.3 FACING AND CENTERING

The cut blank is transferred to the CNC turning centre. Facing is carried out to obtain a flat reference surface. Centering may be performed to establish the required reference for subsequent machining operations.

Machine Used: CNC Turning Centre


7.4 ROUGH TURNING

The outer diameter of the shaft blank is reduced to the required approximate dimensions. Rough turning removes excess material while maintaining sufficient allowance for finishing.

Machine Used: CNC Turning Centre


7.5 STEP AND PROFILE TURNING

Different shaft diameters and profiles are produced according to the component design.

This operation produces:

• Steps
• Shoulders
• Different diameters
• Required shaft profile

Machine Used: CNC Turning Centre


7.6 GROOVING AND CHAMFERING

Grooves are produced at the specified locations. Chamfering is carried out to remove sharp edges and provide smooth transitions between surfaces.

Machine Used: CNC Turning Centre / NC Machine


7.7 DRILLING AND TAPPING

If the shaft design requires holes or threaded features, drilling and tapping operations are performed.

Machine Used: NC / Conventional Machine


7.8 FINISH TURNING

Finish turning is carried out to achieve the required diameter, length, dimensional accuracy, and surface finish.

In this process plan, grinding is not considered. The required dimensional accuracy and surface finish are achieved through suitable finish-turning operations.

Machine Used: CNC Turning Centre


7.9 DEBURRING

After machining, burrs and sharp edges are removed manually or using suitable deburring tools.

Deburring improves component safety, surface quality, and handling safety.


7.10 INSPECTION

The finished shaft is transferred to the inspection area. The component is checked for dimensional accuracy and manufacturing quality before being transferred to the finished-goods storage area.


8. MACHINES AND EQUIPMENT REQUIRED

1. Band Saw Machine – Cutting raw material
2. CNC Turning Centre – Facing, rough turning, profile turning and finish turning
3. NC / Conventional Machine – Drilling and tapping
4. Deburring Station – Removal of burrs and sharp edges
5. Inspection Table – Dimensional inspection
6. Vernier Caliper – Measurement of dimensions
7. Micrometer – Accurate diameter measurement
8. Dial Gauge – Runout and alignment inspection
9. Conveyor – Material and component movement
10. Storage Rack – Raw and finished material storage
11. Safety Fence – Machine and operator safety


9. TIME ESTIMATION

Operation                         Approximate Time

Raw Material Cutting             4 min
Facing and Turning               35 min
Drilling / Tapping               6 min
Deburring and Inspection         9 min

Total Cycle Time                 54 min/component

Therefore, the approximate total cycle time for one transmission shaft is 54 minutes per component.

Note: The above values are approximate planning values and may vary depending on shaft dimensions, machine capacity, cutting parameters, tooling, batch size, and operator handling time.


10. QUALITY CONTROL

Quality inspection is carried out at the inspection station after machining.

Inspection Instruments:

• Vernier Caliper
• Outside Micrometer
• Dial Gauge
• Surface-finish checking equipment, where required

Parameters Checked:

1. Shaft diameter
2. Overall length
3. Step dimensions
4. Groove dimensions
5. Concentricity and runout
6. Surface condition
7. Chamfer dimensions
8. Visual defects

Only components satisfying the specified dimensional and quality requirements are transferred to the finished-goods storage area.


11. PLANT LAYOUT SIMULATION

The plant layout is simulated according to the sequence of manufacturing operations.

The major areas considered in the simulation are:

1. Raw Material Storage Area
2. Cutting Area
3. CNC Machining Area
4. NC Machining Area
5. Conveyor System
6. Deburring Area
7. Inspection Area
8. Finished Goods Storage Area
9. Safety Fencing


12. DESCRIPTION OF SIMULATED PLANT LAYOUT


12.1 RAW MATERIAL STORAGE AREA

The raw material storage area is represented in the DELMIA simulation for storing incoming EN8 round bars before processing.


12.2 CUTTING AREA

The band saw machine is positioned near the raw material storage area in the virtual plant to reduce material transportation distance.


12.3 CNC MACHINING AREA

The CNC turning centre is positioned after the cutting station because the major machining operations are performed on the cut blanks.


12.4 NC MACHINING AREA

The NC/conventional machine is provided for secondary operations such as drilling and tapping, wherever required.


12.5 CONVEYOR SYSTEM

A conveyor system is represented in the DELMIA simulation for controlled movement of components between manufacturing stations and to reduce manual material handling.


12.6 INSPECTION AREA

The inspection area consists of an inspection table and measuring instruments such as vernier calipers, micrometers, and dial gauges.


12.7 FINISHED GOODS STORAGE

The finished-goods storage area is represented in the simulated plant for storing inspected and accepted transmission shafts before dispatch.


12.8 SAFETY FENCING

Safety fencing is incorporated into the virtual plant layout around the machine and manufacturing areas to separate operators from hazardous machine zones and to improve workplace safety.


13. MATERIAL FLOW

The simulated material flow is:

Raw Material Storage
        ↓
Band Saw Cutting
        ↓
CNC Turning Centre
        ↓
NC Machining
        ↓
Deburring
        ↓
Inspection
        ↓
Finished Goods Storage

The simulated arrangement provides a logical forward flow of material and helps in studying unnecessary backtracking and material handling.


14. DELMIA PLANT LAYOUT SIMULATION

The plant layout is simulated using DELMIA Plant Layout Design.

The following elements are represented in the DELMIA simulation:

• Manufacturing machines
• CNC Turning Centre
• NC / Conventional Machine
• Conveyor System
• Storage Racks
• Inspection Table
• Operator Areas
• Safety Fencing
• Material Handling Areas
• Raw Material Storage
• Finished Goods Storage

The layout is represented as a 3D virtual manufacturing environment, allowing the arrangement of machines, equipment, safety zones, storage areas, and material-flow paths to be visualized and studied before actual plant implementation.


15. DELMIA SIMULATION

The developed DELMIA simulation represents the proposed transmission shaft manufacturing facility.

The machine arrangement, safety fencing, conveyor system, storage racks, and inspection area are positioned in the virtual environment to represent a practical batch-production system.

The simulation provides a 3D visualization of the proposed manufacturing facility and helps in understanding the arrangement and movement of resources within the plant.

Figure 1: 3D Simulation of Transmission Shaft Manufacturing Plant Using DELMIA

[INSERT DELMIA SIMULATION IMAGE HERE]


16. SAFETY CONSIDERATIONS

The following safety measures are incorporated into the simulated plant layout:

1. Safety fencing around hazardous machine areas.
2. Adequate space for operator movement.
3. Proper separation between machines and walkways.
4. Controlled material movement.
5. Proper storage of raw materials.
6. Removal of sharp edges and burrs.
7. Clear access to inspection and maintenance areas.
8. Safe positioning of conveyors and storage racks.


17. ADVANTAGES OF THE DELMIA SIMULATION

1. Provides a 3D visualization of the manufacturing plant.
2. Helps in understanding the arrangement of machines and equipment.
3. Enables visualization of material flow.
4. Helps identify unnecessary material movement.
5. Provides better understanding of space utilization.
6. Allows safety fencing and operator areas to be represented.
7. Helps in studying the manufacturing system before physical implementation.
8. Improves understanding of the relationship between machines, storage, conveyors, and inspection areas.
9. Supports planning of an organized manufacturing environment.
10. Provides a virtual representation of the proposed batch-production system.


18. RESULT

The process plan and 3D plant layout simulation for batch production of transmission shafts were successfully developed using DELMIA.

The manufacturing sequence was established from raw-material cutting through CNC turning, secondary machining, deburring, inspection, and finished-product storage.

A virtual manufacturing environment was created using DELMIA Plant Layout Design, incorporating machines, conveyors, storage racks, inspection facilities, operator areas, and safety fencing.

The simulation successfully represents the proposed manufacturing system and provides a clear visualization of material flow, machine arrangement, and plant organization.


19. CONCLUSION

The transmission shaft manufacturing process was successfully planned and simulated using suitable CNC and NC machining operations. EN8 / AISI 1040 steel was selected as the raw material based on its strength, machinability, and suitability for shaft manufacturing.

The proposed process sequence consists of cutting, facing, rough turning, step and profile turning, grooving, chamfering, drilling/tapping, finish turning, deburring, and inspection.

The DELMIA Plant Layout Design was used to create a 3D virtual simulation of the manufacturing facility. The simulation represents the arrangement of machines, material-handling systems, storage areas, inspection facilities, operator areas, and safety zones.

The developed simulation provides a clear visualization of the proposed manufacturing system and helps in studying material flow, machine arrangement, space utilization, and workplace safety before actual plant implementation.


20. OVERALL PROCESS FLOW

RAW MATERIAL STORAGE
        ↓
BAND SAW CUTTING
        ↓
CNC FACING AND CENTERING
        ↓
ROUGH TURNING
        ↓
STEP / PROFILE TURNING
        ↓
GROOVING AND CHAMFERING
        ↓
DRILLING / TAPPING
        ↓
FINISH TURNING
        ↓
DEBURRING
        ↓
INSPECTION
        ↓
FINISHED GOODS STORAGE


Figure 1: DELMIA 3D Simulation of Transmission Shaft Manufacturing Plant


[INSERT DELMIA SIMULATION IMAGE HERE]


FINAL CONCLUSION

The CNC-based process planning and DELMIA-based 3D simulation provide a virtual representation of the transmission shaft manufacturing system. The simulated plant layout demonstrates the arrangement of machines, material flow, storage facilities, inspection areas, conveyors, and safety fencing, providing a better understanding of the proposed manufacturing process before physical implementation.
<img width="1600" height="749" alt="657766401-a60791cd-1ca1-4aee-82de-3261011e4bde" src="https://github.com/user-attachments/assets/d08c07e9-2437-4168-82e1-09e15d5982d0" />


Conclusion : 
The CNC-based process planning and well-organized plant layout ensure efficient production of transmission shafts with consistent quality, reduced cycle time, and improved safety.
