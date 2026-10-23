# Sub-6 GHz UWB MIMO Antenna

A student antenna-design project for Ansys® Electronics Desktop / HFSS. The supplied project header identifies **Electronics Desktop Student 2025.2**.

## Open the design

Download [`single_element_and_MIMO.aedt`](single_element_and_MIMO.aedt) using GitHub’s **Download raw file** button, then open it in a compatible licensed Ansys Electronics Desktop installation. No extraction is needed.

A lossless [`ZIP backup`](single_element_and_MIMO.aedt.zip) is also available; it contains the exact same reviewed public project file, not an original working archive. Both copies retain the reviewed sanitized design bytes. The project contains single-element and MIMO design definitions, geometry, material assignments, excitations, analysis setups, and report definitions.

Solver result files are deliberately not included. Existing report definitions may need a fresh solve before they show data. Compatibility and reopening have not been tested in Ansys during this preparation.

## Public-copy cleanup

- Retained the core project and its reference block byte-for-byte.
- Removed the separate appended project-preview block containing cached JPEG thumbnails. No geometry, circuit, material, excitation, or solver setup was edited.
- Excluded saved solver results, field and mesh databases, locks, semaphores, caches, original ZIPs, and historical preservation packages.
- A focused text scan did not find personal filesystem paths, usernames, hostnames, credentials, or externally imported source files in the retained project. This is not a guarantee that every possible privacy issue has been identified.

The source archives remain preserved separately and are not part of this public copy. Avoid adding generated result folders or machine-specific files after opening the project; `.gitignore` covers common outputs.

## Dependencies, rights, and status

The design requires an appropriate local Ansys installation and license. The [official Electronics Desktop Student page](https://www.ansys.com/academic/students/ansys-electronics-desktop-student) describes educational-use restrictions, and [Ansys Academic Usage](https://www.ansys.com/legal/terms-and-conditions/academic-usage) provides related academic terms. These sources are not a blanket clearance of every third-party or institutional right in a project.

This repository does not distribute Ansys software, documentation, license keys, or a commercial materials database. Standard air/vacuum material parameters and the supplied project-local material definition remain part of the model. No open-source license has been assigned to material the project author has not explicitly licensed.

**No solver run or independent performance validation was performed during cleanup.** The project title is not a verified claim about bandwidth, gain, efficiency, matching, or MIMO performance. Verify the design, assumptions, applicable permissions, and results before relying on them.
