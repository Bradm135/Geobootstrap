# GeoBootstrap

A lightweight, transparent Python workflow demonstrating:
- Experimental variograms
- Variogram model fitting (spherical, exponential)
- Simple kriging
- Spatial block bootstrap uncertainty
- Resource-style calculation using thickness × density (RD)

This project is intended for educational and prototyping use in geoscience and resource-style spatial estimation workflows.

---

## Why this exists

Many geostatistics examples are either too abstract or locked inside black-box tooling.
GeoBootstrap aims to be a readable "glass box" reference you can adapt to your own datasets.

---

## Features

- Omnidirectional experimental variogram calculation
- Spherical and exponential model fitting via non-linear least squares
- Simple kriging using covariance form
- K-means-like spatial block assignment
- Block bootstrap resampling for uncertainty on total in situ estimates
- Polygon masking with consistent contour styling
- Spyder-friendly file dialogs with console fallback

---
## “Start Here” checklist (for your zip)

1. Unzip the folder anywhere (e.g., Desktop).
2. Double-click **run_windows.bat**.
3. When asked for the borehole file, select **sample_boreholes.txt**.
4. When asked for the polygon file, select **sample_polygon.txt**.
5. Confirm the plots appear and the summary prints in the console.
6. Replace the sample files with your own data:

   * Borehole file with headers: **Easting, Northing, Thickness, RD**
   * Polygon file with **x,y** points per line
7. Run **run_windows.bat** again and select your real files.

