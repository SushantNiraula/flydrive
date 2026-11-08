# Design Approach and Cost Comparison

**Status:** Early screening only. This is not a purchasing BOM, quote, or architecture decision. Retail prices are snapshots; the actuator options below are not mechanically equivalent.

## What the current CAD tells us

The V3 servo-based CAD archive has two MG996R servo occurrences in its main assembly. The reference BOM also lists four N20 gearmotors and four 3-inch propellers. These are CAD counts, not confirmation of a physical build or final component suitability.

## Nepal retail examples

Prices checked 8 November 2026. Prices may change and may exclude delivery, tax, import costs, or accessories.

| Example | Public listing | Price | Limits |
| --- | --- | ---: | --- |
| MG996R hobby servo | [RoboNepal listing](https://robonepal.com/product/mg996r-servo) | NPR 835 each | Proxy only; the V3 label does not confirm this exact manufacturer/SKU. |
| Two MG996R servos | Same listing × 2 | NPR 1,670 | Matches two V3 CAD occurrences, before horns, brackets, power supply, and linkage. |
| Four MG996R servos | Same listing × 4 | NPR 3,340 | Illustrative proxy for a four-servo layout; actual servo models may differ. |
| 12 V, 200 mm linear actuator | [Daraz listing from RoboNepal](https://www.daraz.com.np/products/linear-actuator-12v-200mm1-pcs-i143287030.html) | NPR 9,349 each | No ratings and no warranty shown in listing. Does not establish suitability for FLYDRIVE. |

This listed actuator costs about 2.8 times the illustrative four-servo proxy and 5.6 times the two-servo proxy. This compares unit prices only. A fair comparison needs stroke, force, speed, mass, duty cycle, geometry, current draw, driver, limit sensing, and quantities. Those requirements have not been set.

A [separate Nepal listing](https://robonepal.com/product/pull-linear-actuator) has a 12 V, 10 mm push-pull solenoid at NPR 783, but that short-stroke lock actuator is not comparable to a 200 mm transformation actuator and is not used as the actuator estimate.

## Qualitative trade-offs

| Approach | Potential advantages | Main questions |
| --- | --- | --- |
| Servo-based | Compact rotary actuation; potentially inexpensive for small mechanisms; simple position commands. | Holding torque under shock, backlash, peak current, linkage loads, locking, servo count/type, and actual load suitability. |
| Linear actuator | Direct push-pull travel; may simplify long translation motion. | Size/mass, speed, stroke, force, current, driver, limit sensing, mounts, and locking. |
| Worm gear | Can provide high reduction and may resist back-driving depending on geometry/friction. | Efficiency, backlash, friction, lubrication, tolerances, input motor, mounting loads; available V2 CAD is incomplete. |

## Costing method before a decision

Compare complete systems at equal required load and travel. Include actuators, motors, drivers, controllers, power conversion, wiring, sensors, linkages/gears, mounts, fasteners, fabricated material, shipping, and spares. Record exact SKU, quantity, currency, supplier, stock, and quote date. Do not call an approach cheaper based on actuator unit price alone.