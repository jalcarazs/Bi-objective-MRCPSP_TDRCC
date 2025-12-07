# Bi-objective MRCPSP with Time-Dependent Resource Costs and Capacities

This repository provides all data and source code required to reproduce the computational results presented in the paper:

**“Multi-Mode Resource-Constrained Project Scheduling Problem with Time-Dependent Resource Costs and Capacities: A Bi-Objective Approach”**,  
submitted to *Expert Systems with Applications*.

---

## Repository contents

### 1. Source code

- **`jMetalExperiments-master.zip`** (available through the Releases section of this repository)

  This archive contains the complete implementation developed for this study, including:
  - The proposed solution encoding,
  - Problem-specific operators,
  - Decoding strategy,
  - Experimental scripts and parameter settings.

  The implementation is based on **jMetal version 5.10**, an open-source Java framework for multi-objective optimization, and extends the official release to meet the specific requirements of the MRCPSP_TDRCC.  
  Further technical details are provided in the `README.rst` file included inside the archive.

---

### 2. Benchmark instances

- **`Bi-objective-MRCPSP_TDRCC_instances.zip`**

  This archive contains all benchmark instances used in the computational study, derived from the original instances in PSPLIB and MMLIB.  
  The instances are organized into the following folders:

  - `calibration set - J20.zip/` – Calibration set of J20 instances
  - `evaluation set - J20.zip` – Evaluation set of J20 instances
  - `evaluation set - MMLIB50.zip` – Evaluation instances from the MMLIB50 benchmark
  - `evaluation set - MMLIB100.zip` – Evaluation instances from the MMLIB100 benchmark

---

### 3. Real-case study data

- **`bridge_construction.dat`**

  This file contains the data for the *Highway Bridge Construction Project* used as a real-world case study.  
  The corresponding problem description and results are reported in the **Supplementary Material (Section C)**.

---

## Reproducibility

The combination of the provided source code, benchmark instances, and real-case data enables full reproducibility of all computational experiments reported in the paper.

---

## Contact

For any questions regarding the code or data, please contact the authors through the GitHub repository.
