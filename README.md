# FLYDRIVE V3

A CAD design project shared so people can explore it, make changes, and help it grow as a community.

## Start with the full assembly

Open **[flydrive-assembly.step](hardware/v3/step/assemblies/flydrive-assembly.step)** in Fusion or another CAD tool that supports STEP. This is the proposed V3 complete design exported from `Chassis_Final`. The design includes the top plate, bottom plate, servo holder, coupler, and assembled components, as described by the project maintainer.

This repository currently contains **21 STEP exports**. STEP provides transferable geometry; it does not preserve the original Fusion feature timeline or all assembly relationships. Native Fusion sources and print-ready exports have not yet been supplied.

## Get the files

```sh
git clone https://github.com/SushantNiraula/flydrive.git
cd flydrive
```

You can also use **Code → Download ZIP** on GitHub. Import the complete assembly to explore the design, or open an individual part to work on a change.

## What's included

| Folder | Contents |
| --- | --- |
| [Assemblies](hardware/v3/step/assemblies) | Complete FLYDRIVE, hinge, and pod assemblies |
| [Parts](hardware/v3/step/parts) | Individual project part exports |
| [Alternatives](hardware/v3/step/alternatives) | `chassis-try1`, retained for comparison; its relationship to the proposed assembly needs confirmation |
| [Reference models](hardware/v3/step/reference) | Bearings, motors, propeller, servo, and round servo arm; see attribution notes |

The [file manifest](docs/file-manifest.csv) maps every original filename to its repository path and records its size and SHA-256 checksum. Files were reorganized and renamed without changing their contents.

## Contribute

Fork this repository, create a branch such as `design/servo-holder-clearance`, make your changes, and open a pull request. Include a screenshot, explain the reason for the change, and share updated CAD exports. See [CONTRIBUTING.md](CONTRIBUTING.md).

Design reviews, fit checks, documentation, and build reports are welcome. Start an issue to discuss a change or report a problem.

## Current status and next steps

This is a proposed V3 CAD snapshot. Physical fit, manufacturing settings, operation, and flight performance have not been verified as part of this publication.

- Add native Fusion archives, preserving referenced assemblies where applicable.
- Export the top plate, bottom plate, servo holder, and coupler individually.
- Add a verified bill of materials with quantities and exact selected components.
- Add assembly photos, an assembly guide, and documented test results.
- Confirm reference-model sources and licenses, and the role of `chassis-try1`.
- Add print or fabrication exports once dimensions, materials, and processes are confirmed.

## License and attribution

Original FLYDRIVE project work is shared under **CERN-OHL-S-2.0**; see [LICENSE](LICENSE). Preserve notices and share covered modifications under that license as required by its terms.

Third-party models retain their own rights and are excluded from any claim that the project license grants rights to them. Their provenance and licenses have not been supplied. See [reference-models.md](docs/reference-models.md), including the note about reference geometry embedded in assemblies.

The supplied Fusion listing names **Gopal Sharma** as owner. This repository is maintained through **SushantNiraula**. Ownership metadata alone does not establish authorship of every model.
