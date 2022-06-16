# PROPER

**P**ython for **R**econstruction **O**f **P**RIM **E**xperimental **R**esults

Software companion to the **PRIM**

---

## Project Description

### What is this?
* Research project, data analysis, & visualization
* Companion software to PRIM
* Use for 3D reconstruction and meshing of objects captured with a PRIM


### How does this work?
* python3, data (available upon request), and libraries included in `headers.py`
* Run scripts in project folder in order
* Data includes a video and corresponding spreadsheet of mechanical data

### What is the goal?
* Geometrical-Material-Mechanical analysis of objects captured with a PRIM

### How is this organized?
1. Imports handled in `headers.py`
1. Functions are in `elib.py`
1. A project folder is used for each data set e.g. `beaumont`
1. Project folder structure:
    * `_data`
        * `raw` - raw PRIM data
        * `interm` - intermediate data storage for machine use
        * `output` - for human use, validation, logging, etc.
    1. `init` - collect and organize data
    1. `reconstruction` - data processing
    1. `transform` - surface transforms
    1. `graph` - 3D rendering and plotting
    1. `viz` - visualization: plots, renders, etc.
1. `_snapshots` weekly local backup non-data files & show modified files
        
### License
* See `LICENSE.md` -- free to copy, use, modify, etc.

### Questions/requests
* Contact broemere

### Cite
v0.1-alpha release 

[![DOI](https://zenodo.org/badge/499912165.svg)](https://zenodo.org/badge/latestdoi/499912165)

