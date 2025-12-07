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


