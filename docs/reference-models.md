# Reference models and provenance

These exports were supplied as part of the CAD folder. Source URLs, authorship, and redistribution licenses were not supplied. The project license does not establish rights to third-party geometry. Confirm applicable permissions before downstream redistribution or reuse.

| File | Supplied identification |
| --- | --- |
| `bearing-6704.step` | BEARING_6704 |
| `bearing-686.step` | BEARING_686 |
| `3052-3-blade-propeller-3-inch.step` | 3052 3-Blade Propeller 3-inch |
| `motor-n20-100rpm.step` | Motor_N20_100rpm |
| `t-motor-f100-2810-kv1350-5-6s-motor.step` | T-Motor F100 2810 KV1350 5-6S Motor |
| `t-motor-v1507-1.5mm.step` | T-Motor V1507 1.5mm |
| `mg996r-v2.step` | mg996R_v2 |
| `mg996-arm-round.step` | mg996_arm_round; treated as a reference pending authorship confirmation |

All files above are in `hardware/v3/step/reference/`. The round arm was originally at the top level; its export header identifies a FreeCAD model, which does not establish its author or license.

Assembly STEP files may also embed reference geometry. Moving standalone references into this directory does not remove embedded geometry. Model labels are not a verified bill of materials; multiple motor models do not establish that all are used in the proposed assembly.
