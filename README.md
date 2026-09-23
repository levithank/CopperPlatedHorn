#### Copper Plated 3D-Printed Horn

> Replace this title with the name of your project.

### Project Owner

**Name:** Leroy Kang  
**Virginia Tech Email:** kleroy23@vt.edu

### Project Overview

My partner and I previously designed a 7-8 GHz corrugated conical horn. In this phase I will either refine that design or use it as-is, then 3D-print the horn and copper-plate it using electroplating. After plating, I will evaluate its ability to perform circular polarization as well as differentiate LHCP/RHCP with a dipole probe and the oscilloscopes in the AMP Lab. To measure gain, I plan to request access to the anechoic chamber used by Virginia Tech's National Security Institute (NSI) Spectrum Dominance Division. That request depends on showing tangible evidence of the design and working results.

## Project Phases

## Phase 1: Prototype, Measurement Method, and Success Criteria

The AMP Lab oscilloscopes are limited to 3 GHz, which is well below the 7-8 GHz design band. To make the horn measurable with this equipment, the first prototype will be a lower-frequency version of the design, scaled to operate at approximately 1-3 GHz. This lets me verify circular polarization on-site, and the results will support the request for anechoic chamber access. 

The horn transmits a continuous-wave signal from a signal generator. A linear dipole probe placed on boresight in the far field receives it and feeds the oscilloscope. The oscilloscope only receives, so the generator supplies the horn's excitation. From this setup I will measure the horn's axial ratio and handedness.

**Axial ratio.** I will rotate the dipole about the boresight axis in 15° steps, record the received amplitude at each angle, and compute the axial ratio as the ratio of maximum to minimum amplitude, in dB. A perfectly circular wave gives the same amplitude at every angle (0 dB), so a nearly flat response indicates good circular polarization. A deep null 90° from the peak would mean the horn is radiating linear polarization instead. The measurement will be repeated at several frequencies and off-axis angles where feasible.

**RHCP/LCHP** Amplitude alone cannot distinguish right-hand from left-hand circular polarization. To determine handedness, two matched dipoles oriented at 0° and 90° will be connected to two oscilloscope channels. Equal amplitudes confirm circularity, and the sign of the phase difference (+90° or -90°) gives the rotation sense. The dipoles and cables must be matched and kept in identical positions between runs so the measurement reflects the horn and not the setup.

**Success criteria:**
- Axial ratio below about 3 dB at boresight
- RHCP/LHCP differentiation identified from the two-channel phase measurement
- Plated prototype with continuous, uniform copper coverage, including inside the corrugations


# Phase 2: Anechoic chamber access

Once circular polarization is verified, I will request chamber access for gain measurements. The request will be supported by the design documentation, photos of the plated prototype, and the Phase 1 axial ratio and handedness results.

# Phase 3: Final reporting

If chamber access is not granted, the oscilloscope and other bench measurements will serve as the project's primary results. Gain and full pattern characterization will be presented as future work in the final report at the end of the year.



### What I Hope to Learn

- How to design and scale a corrugated conical horn antenna, and how the geometry (aperture, corrugation depth, flare angle) sets its performance
- How 3D printing and copper electroplating can produce RF hardware, including how to get uniform plating inside the corrugations and how surface finish affects loss
- How to measure circular polarization in practice: axial ratio, handedness, and the amplitude and phase relationships between orthogonal probes
- How to control measurement error from cables, baluns, and probe placement, and how to calibrate it out
- How to compare measured results against simulation and explain the differences
- How antenna gain is measured in an anechoic chamber and how to build a case for access to one
- How to document a research project clearly enough for sponsors and future students to continue it

## Design and Implementation

Future documentation of the design of my project as it develops.

## Bill of Materials
Costs are rough estimates and should be replaced with real quotes once the prototype frequency and size are set. Items marked "AMP Lab" are borrowed equipment.

| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Conductive seed layer (conductive copper paint or electroless copper kit) | 1 | $40.00 | TBD |
| Acid copper plating bath (copper sulfate, sulfuric acid, brightener) | 1 | $60.00 | TBD |
| Copper anode (sheet or pipe) | 1 | $30.00 | TBD |
| Plating tank and agitation pump | 1 | $30.00 | TBD |
| PPE and chemical waste containers | 1 | $40.00 | TBD |
| Bench DC power supply | 1 | $0.00 | AMP Lab |

**Estimated Total Cost:** about $520 for core items, about $670 with optional items

## Timeline and Milestones

| Milestone | Target Date | Status |
|---|---|---|
| Project planning and README | Oct 2, 2026 | In Progress |
| Finalize design: pick prototype frequency, confirm how CP is generated, simulate scaled horn | Oct 9, 2026 | Not Started |
| Order materials and run a plating test on a small grooved coupon | Oct 16, 2026 | Not Started |
| 3D-print prototype horn (and polarizer) | Oct 23, 2026 | Not Started |
| Copper-plate and inspect horn | Nov 6, 2026 | Not Started |
| Phase 1 testing: S11, axial ratio, handedness | Nov 20, 2026 | Not Started |
| Submit anechoic chamber access request with results | Nov 23, 2026 | Not Started |
| Perform anechoic chamber testing | Jan-May, 2027 | Not Started |
| Final report and project completion | May 7, 2026 | Not Started |

## Progress Log

WIP



## Project Files

WIP

## Useful Links

WIP

## Project Image

Replace the `hero.png` file in the root of this repository with an image representing your project.

**Keep the filename as `hero.png`.**

This image is used as the project cover image on the AMP Lab website.
