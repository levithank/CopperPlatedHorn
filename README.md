# Copper Plated 3D-Printed Horn

> Replace this title with the name of your project.

## Project Owner

**Name:** Leroy Kang  
**Virginia Tech Email:** kleroy23@vt.edu

## Project Overview

## Overview

My partner and I previously designed a 7-8 GHz corrugated conical horn. In this phase I will either refine that design or use it as-is, then 3D-print the horn and copper-plate it using electroplating. After plating, I will evaluate its circular polarization with a dipole probe and the oscilloscopes in the AMP Lab. To measure gain, I plan to request access to the anechoic chamber used by Virginia Tech's National Security Institute (NSI) Spectrum Dominance Division. That request depends on showing tangible evidence of the design and working results.

## Project Phases

# Phase 1: Prototype and circular polarization verification

The AMP Lab oscilloscopes are limited to 3 GHz, so the first prototype will be a version of the horn that operates within that range. I will fabricate and plate it, then measure its circular polarization using the method described below.

# Phase 1 Measurement Method

The horn transmits a continuous-wave signal from a signal generator. A linear dipole probe placed on boresight in the far field receives it and feeds the oscilloscope. The oscilloscope only receives, so the generator supplies the horn's excitation.

# Axial ratio

1. Rotate the dipole about the boresight axis in 15° steps.
2. Record the received amplitude at each angle.
3. Compute the axial ratio as the ratio of maximum to minimum amplitude, in dB.

A perfectly circular wave gives the same amplitude at every angle (0 dB), so a nearly flat response indicates good circular polarization. A deep null 90° from the peak would mean the horn is radiating linear polarization instead. The measurement will be repeated at several frequencies and off-axis angles where feasible.

# Handedness

Amplitude alone cannot distinguish right-hand from left-hand circular polarization. To determine handedness, two matched dipoles oriented at 0° and 90° will be connected to two oscilloscope channels. Equal amplitudes confirm circularity, and the sign of the phase difference (+90° or -90°) gives the rotation sense. The dipoles and cables must be matched and kept in identical positions between runs so the measurement reflects the horn and not the setup.

# Success Criteria

- Axial ratio below about 3 dB at boresight
- Handedness identified from the two-channel phase measurement
- Plated prototype with continuous, uniform copper coverage, including inside the corrugations


# Phase 2: Anechoic chamber access

Once circular polarization is verified, I will request chamber access for gain measurements. The request will be supported by the design documentation, photos of the plated prototype, and the Phase 1 axial ratio and handedness results.

# Phase 3: Final reporting

If chamber access is not granted, the oscilloscope and other bench measurements will serve as the project's primary results. Gain and full pattern characterization will be presented as future work in the final report at the end of the year.



## What I Hope to Learn

## Design and Implementation

Document the design of your project as it develops.

This may include:

- Block diagrams
- Circuit schematics
- PCB designs
- CAD models
- Software architecture
- Hardware selection
- Calculations
- Testing methods

Explain major design decisions and why you made them.

## Bill of Materials

Document the major components and materials used for the project.

| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Component | 1 | $0.00 | Link |

**Estimated Total Cost:** $0.00

## Timeline and Milestones

Outline the major stages of the project and update them as work progresses.

| Milestone | Target Date | Status |
|---|---|---|
| Project planning | Date | Not Started |
| Initial design | Date | Not Started |
| Prototype | Date | Not Started |
| Testing | Date | Not Started |
| Project completion | Date | Not Started |

## Progress Log

Use this section to document meaningful progress throughout the project.

### YYYY-MM-DD

Describe what you worked on, what was completed, any problems you encountered, and what you plan to work on next.

## Project Files

Organize and document important project files in this repository. Depending on the project, this may include:

- Source code
- KiCad files
- Schematics
- PCB layouts
- CAD files
- Datasheets
- Test results
- Documentation

## Useful Links

Add any references, datasheets, documentation, tutorials, or other resources relevant to the project.

## Project Image

Replace the `hero.png` file in the root of this repository with an image representing your project.

**Keep the filename as `hero.png`.**

This image is used as the project cover image on the AMP Lab website.
