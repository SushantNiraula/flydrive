# FLYDRIVE — Design Archive & Research

FLYDRIVE is an ongoing exploration of a hybrid aerial-ground robot. This repository preserves earlier design work and the research references informing the next design phase.

**Current status:** V3 is a proposed servo-based CAD design. It has not been physically validated. The next architecture has not been selected.

## Repository contents

| Folder | Contents |
| --- | --- |
| `hardware/v3/` | Existing V3 servo-based CAD/STEP archive, including assemblies, parts, alternatives, and reference models |
| `01_PREVIOUS_DESIGNS/V2_WORM_GEAR/` | Available V2 worm-gear and body CAD exports. This is a partial design, not a complete vehicle |
| `01_PREVIOUS_DESIGNS/LINEAR_ACTUATOR/` | Notes on the linear-actuator concept, explored using the Mercury Drone repository as an external reference. No original FLYDRIVE CAD is included |
| `02_RESEARCH_PAPERS/` | Index of six research papers relevant to hybrid aerial-ground and unconventional rotary-wing designs |
| `03_DESIGN_ANALYSIS/` | Short design history and current qualitative design requirements |

## V3 CAD

Start with [the V3 full assembly STEP](hardware/v3/step/assemblies/flydrive-assembly.step). Open it in Fusion 360 or another CAD tool that supports STEP.

The V3 archive contains 21 STEP exports. STEP preserves transferable geometry, but not the original Fusion feature timeline or all native assembly relationships. Physical fit, manufacturing, operation, and flight performance have not been verified.

See the [sample bill of materials](docs/bill-of-materials.md) for a planning reference. It is not an audited purchasing list.

## Earlier design explorations

- **V2 Worm Gear:** only the available gearbox/worm-gear and body CAD exports are included. The design is incomplete; the supplied partial assembly has no arm.
- **Linear Actuator:** the Mercury Drone project was used as an external reference. The FLYDRIVE repository does not contain a corresponding original CAD design.
- **V3 Servo-Based:** see `hardware/v3/` for the existing CAD archive.

See [Design History](03_DESIGN_ANALYSIS/DESIGN_HISTORY.md) for context.

## Research

The six-paper reading list and source links are in [Research References](02_RESEARCH_PAPERS/REFERENCES.md). The papers are external references. No summaries or conclusions have been added yet.

## Design direction

The current qualitative requirements are recorded in [Design Requirements](03_DESIGN_ANALYSIS/DESIGN_REQUIREMENTS.md). They are not measured performance claims or finalized numerical specifications.

No new architecture has been selected. Research and comparison come before another prototype.

## Get the files

```sh
git clone https://github.com/SushantNiraula/flydrive.git
cd flydrive
```

You can also use **Code → Download ZIP** on GitHub.

## Contributing

Design feedback, comparison notes, and documentation improvements are welcome. Open an issue to discuss a change, or see [CONTRIBUTING.md](CONTRIBUTING.md).

## License and attribution

The existing V3 repository work is shared under [CERN-OHL-S-2.0](LICENSE). Third-party reference models may have separate rights and licenses; see [reference-models.md](docs/reference-models.md). Do not assume the repository license grants rights to third-party material.