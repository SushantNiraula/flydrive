# FLYDRIVE Research References

This is the single index for the six papers, their DOI/source links, and the lessons to carry into FLYDRIVE research. They describe external robots and studies, not FLYDRIVE results.

## 1. BAXTER — Bi-modal Aerial-Terrestrial Hybrid Vehicle for Long-endurance Versatile Mobility

Choi et al., 2021 preprint. [DOI: 10.48550/arXiv.2102.02942](https://doi.org/10.48550/arXiv.2102.02942) · [arXiv record](https://arxiv.org/abs/2102.02942)

**Understand:** The design combines aerial and terrestrial modes with an M-Suspension and decoupled transmission. The authors report flight testing for robustness and endurance and propose a transition intended to reduce impact impulses.

**For FLYDRIVE:** Mode transition, landing impact, endurance, and transmission need to be considered together. BAXTER’s mechanisms and performance belong to that platform.

## 2. Roller-Quadrotor — A Novel Hybrid Terrestrial/Aerial Quadrotor with Unicycle-Driven and Rotor-Assisted Turning

Zheng et al., IROS 2023. [DOI: 10.1109/IROS55552.2023.10341703](https://doi.org/10.1109/IROS55552.2023.10341703) · [arXiv preprint](https://arxiv.org/abs/2303.00668)

**Understand:** A unicycle-driven ground mechanism is paired with rotor-assisted turning. The authors report experimental validation and longer operating time/range in ground mode than flight mode for their tested platform.

**For FLYDRIVE:** Ground locomotion may extend mission range, but the drive and turning method add hardware/control requirements. Reported ratios are specific to the robot and tests.

## 3. Design and Control of a Reconfigurable Robot with Rolling and Flying Locomotion

Chang et al., *Actuators*, 2024. [DOI: 10.3390/act13010027](https://doi.org/10.3390/act13010027)

**Understand:** Presents an umbrella-style retracting airframe, kinematic/dynamic modeling, and controller comparisons. The paper reports simulation results; improving the prototype and verifying control on hardware are future work.

**For FLYDRIVE:** Separate simulation from physical validation. A reconfigurable mechanism still needs prototype tests before performance claims.

## 4. Design and Experimental Validation of HyTAQ, a Hybrid Terrestrial and Aerial Quadrotor

Kalantari and Spenko, ICRA 2013. [DOI: 10.1109/ICRA.2013.6631208](https://doi.org/10.1109/ICRA.2013.6631208)

**Understand:** HyTAQ uses a protective rolling cage around a quadrotor so the rotor system supports both flight and rolling locomotion. The work includes experimental validation.

**For FLYDRIVE:** Reusing flight actuation for ground movement could limit separate drive hardware, while the cage adds size and mass. Measure those trade-offs.

## 5. Quadrolltor — A Reconfigurable Quadrotor With Controlled Rolling and Turning

Jia et al., *IEEE Robotics and Automation Letters*, 2023. [DOI: 10.1109/LRA.2023.3279624](https://doi.org/10.1109/LRA.2023.3279624)

**Understand:** Passively reconfigurable joints couple body attitude to a rolling cage. The paper reports controlled rolling/turning experiments and a low-speed operating-range improvement for its platform.

**For FLYDRIVE:** Passive mechanisms may reduce dedicated actuators, but need careful joint, stability, and control design. The reported 15-fold range extension is platform- and condition-specific.

## 6. Beyond Conventional Drones: A Review of Unconventional Rotary-Wing UAV Design

Li, *Drones*, 2025. [DOI: 10.3390/drones9050323](https://doi.org/10.3390/drones9050323)

**Understand:** Reviews unconventional rotary-wing UAVs across tilted/tiltable propellers, expanded structures, morphing multirotors, and other aerodynamic concepts, with challenges and research directions.

**For FLYDRIVE:** Use the review as a map of design classes, then consult primary papers. A survey does not establish which architecture fits FLYDRIVE.

## Use

These concise notes do not replace reading the papers. Check methods, assumptions, limitations, and licensing before reusing figures or other material. Supplied PDFs are not mirrored here; use DOI/arXiv links for publisher or repository access. No architecture is selected by this reading list.