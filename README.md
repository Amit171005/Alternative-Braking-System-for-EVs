# Alternative-Braking-System-for-EVs
Externally Clamped Hydraulic Drum Brake for Electric Two-Wheelers
Team CADillac designed a friction brake for Indian commuter electric two-wheelers that pairs a cast-iron drum with hydraulic actuation. Two curved shoes grip the outside of the rotating drum. The design explores whether this arrangement can keep the drum affordable, expose its friction surface to cooling air and compensate for lining wear automatically.

Project status: Concept design, CAD assembly, analytical sizing and component-level ANSYS simulations completed for ME322 Machine Design at IIT Guwahati. Prototype and vehicle testing are future work.
How the brake works
1. Apply. The rider squeezes a 5:1 hand lever connected to a 14 mm master cylinder. Hydraulic pressure travels through the brake hose to a wheel cylinder with two opposed 22 mm pistons.
2. Clamp. The pistons move apart and drive a mirrored scissor linkage. The links pull two lined shoes inward against the drum. Friction slows the wheel, and the stationary backing plate transfers the reaction torque into the vehicle.
3. Release and adjust. Return springs pull the shoes clear when the rider releases the lever. As the linings wear, a ratchet-and-pawl mechanism is designed to take up excess travel while preserving running clearance.
Design point
The team sized the front brake for a 300 kg loaded vehicle travelling at 80 km/h. A target stop of 40.7 m gives a constant deceleration of 6.07 m/s². Assuming the front tyre supplies 75% of the braking force and the wheel has a 0.30 m rolling radius, the required front-wheel torque is 300 × 6.07 × 0.75 × 0.30 ≈ 410 N·m.
Quantity	Value	Basis
Normal load per shoe	7.32 kN	Two shoes, assumed lining friction coefficient of 0.35 and nominal friction radius of 80 mm
Required force per slave piston	1.83 kN	Nominal linkage force multiplication of 4:1
Ideal hand-lever effort	154 N	50 bar line pressure, 14 mm master bore and 5:1 hand lever
Front-brake energy per stop	55.6 kJ	75% of the vehicle’s translational kinetic energy
Estimated cost per wheel	₹4,500	Itemised bill of materials including small-batch manufacturing and assembly


Structural analysis and validation
The ANSYS static model reported approximately 115 MPa peak equivalent stress near the shoe attachment lug and 0.15 mm maximum shoe displacement. The linkage drawing specifies a 15 mm arm, while the bill of materials specifies a 4 mm stamped arm. The arm material and section should be reconciled before applying the simulation results to a prototype.

The first bench test would measure hub torque and hand-lever travel against hydraulic line pressure. The specified 155 mm drum diameter gives a 77.5 mm outer radius. At that radius, the ideal linkage model predicts about 412 N·m at 50 bar, leaving little margin over the 410 N·m target. Recording travel as well as torque would show whether the linkage delivers the required clamp force within the rider’s available lever stroke. Subsequent tests would assess repeated-stop fade, wet braking and adjuster operation as the linings wear.
Project documents
- [Project report (PDF)](ME322_Project_Report_TeamCADillac-2.pdf) — assembly drawings, sizing calculations, structural analysis, thermal estimates and itemised costs.
- [Design presentation (PowerPoint)](CADillac.pptx) — exploded CAD views, linkage geometry and simulation contours.
Team CADillac · Amit Kumar, Arnav Kshirsagar and Anumula Bharath Kumar
Department of Mechanical Engineering, Indian Institute of Technology Guwahati · 2025–26
