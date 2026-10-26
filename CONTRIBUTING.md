# Contributing to FLYDRIVE

Help improve the design, document a build, check component fit, or explain something that is missing.

## Make a change

1. Fork the repository to your account and clone your fork.
2. Create a focused branch, for example `git switch -c design/hinge-clearance`.
3. Edit the relevant part or assembly in your CAD tool. Keep the existing main assembly as the starting point for compatible changes.
4. Export updated STEP files. Include native editable sources when available, and describe the tool/version used. Do not label a mesh as an editable source.
5. Include before/after screenshots and describe dimensions, clearances, materials, or interfaces affected. State what you actually checked and what remains untested.
6. Commit, push the branch to your fork, and open a pull request targeting `main` here.

Keep unrelated experiments in separate branches. Maintainers review pull requests before merging them.

## File conventions

Use lowercase hyphenated filenames. V3 files live under `hardware/v3/`; omit repeated `_V3` suffixes and avoid names such as `final`. Put complete or subsystem assemblies in `step/assemblies`, individual project parts in `step/parts`, and comparison designs in `step/alternatives`.

Preserve an original-to-new name mapping when renaming. Update `docs/file-manifest.csv` with current sizes and SHA-256 checksums when CAD files change; add new rows for new exports. Do not make cosmetic edits to STEP contents or change internal component names without checking assembly references.

## Rights and reference geometry

Only contribute material you have permission to share. Original covered contributions use CERN-OHL-S-2.0. Preserve existing attribution. Identify third-party geometry and provide its source and license separately; do not relicense it as your own work.

## Helpful reports

Include the filename, CAD tool/version, screenshots, expected behavior, observed behavior, and steps to reproduce. For a physical build, include manufacturing process, material, measured dimensions, and test conditions. Distinguish proposed improvements from tested results.
