# FLYDRIVE — Design Archive & Research

FLYDRIVE is an ongoing exploration of a hybrid aerial-ground robot. This repository keeps prior design work, current research references, and the basic requirements guiding the next design phase in one place.

**Current status:** The servo-based V3 is an unvalidated CAD design. V2 worm-gear files are partial. Linear-actuator work is an external-reference exploration. No new architecture or prototype has been selected.

## Repository contents

| Folder | Contents |
| --- | --- |
| `01_PREVIOUS_DESIGNS/` | V2 worm gear, V3 servo-based CAD and components, and linear-actuator notes |
| `02_RESEARCH_PAPERS/REFERENCES.md` | One index with all six DOI/source links and concise lessons from each paper |
| `03_DESIGN_ANALYSIS/` | Design history, basic requirements, reference classes, and approach/cost comparison |
| `docs/bill-of-materials.md` | CAD-derived V3 component counts and what remains to verify |

## Previous designs

- **V2 Worm Gear:** available gearbox/worm-gear and body CAD exports; incomplete, with no arm in the supplied partial assembly.
- **V3 Servo-Based:** the 21 STEP exports, including assembly, candidate parts, servo/motor/propeller/bearing reference geometry, and alternatives, are under [V3 Servo-Based](01_PREVIOUS_DESIGNS/V3_SERVO_BASED/). The sample BOM is based on CAD occurrences and has not been checked against a physical build.
- **Linear Actuator:** earlier exploration referencing the [Mercury Transforming Drone](https://github.com/tobieapb/mercury-transforming-drone/tree/main) and other external examples; no original FLYDRIVE actuator CAD is included.

The [reference classification](03_DESIGN_ANALYSIS/REFERENCE_CLASSIFICATION.md) retains the supplied Servo Based, Linear Actuator Based, and Just Drone groups. These are research examples, not adopted designs.

## V3 CAD

Start with the [V3 full assembly STEP](01_PREVIOUS_DESIGNS/V3_SERVO_BASED/step/assemblies/flydrive-assembly.step). STEP files carry transferable geometry, but not the original Fusion feature timeline or all native assembly relationships. Physical fit, fabrication, operation, and flight performance have not been verified.

See the [sample BOM](docs/bill-of-materials.md) for CAD occurrence counts, and the [design and cost comparison](03_DESIGN_ANALYSIS/DESIGN_COMPARISON.md) for dated retail examples. Neither is a verified purchase list or total build cost.

## Research

All six paper citations and reading notes are in the single [Research References](02_RESEARCH_PAPERS/REFERENCES.md) index. It links to DOI and arXiv landing pages; PDF copies are not mirrored here.

## Design requirements

The [basic requirements](03_DESIGN_ANALYSIS/DESIGN_REQUIREMENTS.md) cover hybrid modes, transition, flight viability, ground use, mass, endurance, reliability, safety, maintainability, acoustics, and transparent cost. Numerical targets still need to be set before selecting an architecture.

## Get the files

```sh
git clone https://github.com/SushantNiraula/flydrive.git
cd flydrive
```

You can also use **Code → Download ZIP** on GitHub.

## Contributing

Design feedback, comparison notes, and documentation improvements are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License and attribution

The original project work is shared under [CERN-OHL-S-2.0](LICENSE). Third-party reference models may have separate rights and licenses; see [reference-models.md](docs/reference-models.md). Do not assume the project license grants rights to third-party material.
