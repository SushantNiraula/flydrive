# Sample bill of materials — FLYDRIVE V3

**Status: planning sample, not a verified purchasing or manufacturing BOM.**

This sample lists existing design components for a cost-conscious build discussion. Quantities come from recursively expanding the assembly relationships in `hardware/v3/step/assemblies/flydrive-assembly.step`. They are CAD occurrence counts, not physical-build verification. A reference filename alone does not confirm a supplier specification.

## Basic purchased components

These are the already represented components to price first. No current prices, suppliers, or claims that they are the cheapest option have been verified.

| Item | CAD identification | Qty per complete assembly | Confirm before purchase |
| --- | --- | ---: | --- |
| N20 geared DC motor | Motor_N20_100rpm | 4 | Rated voltage, 100 rpm at that voltage, gear ratio, shaft dimensions, torque and current; exact vendor/SKU still needed |
| Servo | mg996R_v2 / MG996R | 2 | Exact manufacturer/SKU, supply voltage, torque, current and horn/spline compatibility |
| Bearing | BEARING_6704 | 4 | Full designation, dimensions, shielding/seals and fit; supplier/SKU still needed |
| Bearing | BEARING_686 | 8 | Full designation, dimensions, shielding/seals and fit; supplier/SKU still needed |
| Three-blade propeller | 3052 3-Blade Propeller 3-inch | 4 | Hub/shaft fit, pitch, exact model and required CW/CCW split; do not order four of one rotation by default |
| Round servo horn | mg996_arm_round | 1 | Spline and fastening compatibility; check whether the chosen servo already includes a suitable horn |

Quantities above reflect named component occurrences, excluding nested representations of the same purchased item (for example, the internal `Motor` underneath an N20 motor). The CAD shows two servo occurrences but only one round-horn occurrence; confirm the second servo's linkage/horn requirements.

## Custom parts already represented

These are CAD part counts for planning fabrication. **Material, manufacturing process, infill, tolerances and purchased stock dimensions have not been fixed**, so this sample does not assign PLA, PETG, metal, or sheet thicknesses.

| Part | CAD qty | Export / note |
| --- | ---: | --- |
| Chassis top plate | 1 | Embedded in full assembly; separate export still needed |
| Chassis bottom plate | 1 | Embedded in full assembly; separate export still needed |
| Coupler | 1 | Embedded in full assembly; separate export still needed |
| Hinge shaft | 2 | `step/parts/hinge-shaft.step` |
| Clevis block | 4 | `step/parts/clevis-block.step` |
| Arm | 4 | `step/parts/arm.step`; count the arm component once, not its internal `ARM_V3` representation |
| Pod post | 4 | `step/parts/pod-post.step`; includes nested geometry, not extra purchasable posts |
| BLDC motor plate | 4 | `step/parts/bldc-motor-plate.step` |
| Propeller guard | 4 | `step/parts/propeller-guard.step` |
| N20 15-tooth pinion | 4 | `step/parts/n20-pinion-15t.step`; material and shaft retention still need confirmation |
| Driven rotating hub | 4 | `step/parts/rotating-hub-driven.step`; contains nested hub/45-tooth gear geometry |
| Servo holder | 2 candidate occurrences | Assembly contains `servo-holder` and `servo-holder (1)`; confirm whether both are required before fabrication |

All listed relative export paths are under `hardware/v3/`. The standalone `rotating-hub.step` is available, but its separate manufacturing quantity is not established by a distinct matching occurrence in the main assembly; review it against the driven-hub geometry before adding another line item. Assembly files are not additional fabricated parts.

## Required items outside this basic sample

This sample is deliberately incomplete and has no total build cost.

- **Four T-Motor V1507 1.5mm motor occurrences** are present in the main assembly. The exact winding/KV and electrical specification are not established here. Keep these as a separate propulsion selection/cost decision; no cheaper drop-in replacement is claimed.
- The F100 motor exists as a standalone reference but is not counted as an additional motor in the main assembly.
- Four named M2 locking-screw occurrences are present with the motor models. Confirm whether supplied with the motors; this is not a complete fastener schedule.
- Battery, ESCs, motor drivers, controller, power distribution, wiring, connectors and remaining fasteners have no confirmed selections or complete quantities in the supplied information.

## Turn this into a verified BOM

For each purchased item, add a supplier link, exact part number, confirmed specification, required quantity, unit price, currency and quote date. For custom parts, record material/process and verify the exported part against the assembly. Resolve the servo-holder and linkage questions, then check the complete list against a physical build before changing this document's status to verified.
