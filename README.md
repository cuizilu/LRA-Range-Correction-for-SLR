# LRA-Range-Correction-for-SLR
# Low Earth Orbit Satellite LRA Range Correction Models

This repository provides **range correction models** for **Laser Retroreflector Arrays (LRAs)** mounted on Low Earth Orbit (LEO) satellites. The corrections account for dependencies on **incidence azimuth**, **elevation angle**, and **laser wavelength**.

---

## 📘 Overview

Three types of LRA geometries are included:

1. **Tetrahedral LRA**
   - **Satellites:** GRACE-C, GRACE-D, SWARM-A, SWARM-B, SWARM-C
   - **Description:** Four-cube tetrahedral configuration

2. **Hemisphere LRA with 7 Cubes**
   - **Satellites:** JASON series, Sentinel-3A, Sentinel-3B
   - **Description:** Hemispherical base with 7 corner cubes

3. **Hemisphere LRA with 9 Cubes**
   - **Satellites:** Sentinel-6A
   - **Description:** Hemispherical base with 9 corner cubes

For each configuration, **range corrections (in millimeters)** are tabulated as functions of:
- **Incidence azimuth angle** (0°–360°)
- **Elevation angle** (0°–90°)
- **Laser wavelength** (e.g., 532 nm, 1064 nm)

These corrections improve the accuracy of Satellite Laser Ranging (SLR) measurements.

---

## 🛠️ Usage

Typical usage scenarios:
- Interpolate corrections for specific incidence angles and wavelengths.
- Apply corrections to raw SLR measurements.
- Visualize correction surfaces across azimuth and elevation.

**Example workflow:**
1. Load the appropriate correction table.
2. Interpolate the correction value.
3. Subtract or add this correction to the measured range.

---

## 📝 License

This dataset and associated documentation are licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

**You are free to:**
- **Share** – copy and redistribute the material in any medium or format.
- **Adapt** – remix, transform, and build upon the material for any purpose, even commercially.

**Under the following terms:**
- **Attribution** – You must give appropriate credit, provide a link to the license, and indicate if changes were made.

**Full license text:**  
[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

---

## ✉️ Contact

For questions, contributions, or collaboration inquiries, please open an issue or contact the repository maintainer.
