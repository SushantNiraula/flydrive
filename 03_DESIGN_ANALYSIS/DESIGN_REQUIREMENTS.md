# FLYDRIVE — Basic Design Requirements

**Status:** Working requirements for research and concept comparison. These are goals, not validated performance, finalized specifications, or a selected architecture.

## Mission

Develop a compact hybrid robot that can fly and move over suitable ground, with a deliberate transition between modes. Ground mode should extend mission capability while protecting safe, controllable flight.

## Requirements to guide concept selection

1. Support controlled flight and controlled ground locomotion.
2. Explain how the robot changes modes, what actuates it, and how it locks or stays stable.
3. Keep transformation hardware from making the vehicle too heavy, unstable, difficult to control, or inefficient to fly.
4. Design ground movement for intended surfaces and obstacles; smooth indoor floors are the initial reference.
5. Minimize added mass, volume, parts, wiring, and failure points.
6. Measure flight and ground endurance separately; ground movement should offer a mission benefit.
7. Avoid jamming, loosening, uncontrolled deployment, propeller contact, and unsafe linkage or servo loads.
8. Investigate lower noise; do not claim an improvement without measurement.
9. Keep mechanisms accessible and document wiring and assembly.
10. Compare complete system cost, including actuators, drivers, power conversion, linkages, mounts, fasteners, and frame changes.

## Values to set before architecture selection

Current project facts do not establish numerical targets. Define and justify maximum takeoff mass/dimensions, minimum flight time and payload, ground speed/distance/surface/obstacles, transition time and cycle life, noise test method and limit, allowable actuator mass/power/current, BOM cost ceiling and sourcing region, and verification thresholds.

Do not present estimates or simulation as measured results. Label evidence REAL, SIM, or DESIGN as appropriate.

## Decision status

No new architecture is selected. Linear actuators, worm gears, and servo mechanisms remain prior explorations or external references for comparison.