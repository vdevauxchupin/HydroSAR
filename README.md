# WORKFLOW
## First, on <https://search.asf.alaska.edu> create some SLC jobs and wait a bit so they can finish
## Start working with notebooks 1 to 4
- 1: download the RTC files and DEMs from your Vertex job
- 2: subset those files to your area of interest
- 3: use their combined DEMs to create a HAND for your AOI
- 4: create water masks from your RTCs and the HAND
- 5: run FIER.ipynb to analyze the water-masks or the RTCs in preparation for the ML algorithm and forecast


# HydroSAR
## About the HydroSAR Project
HydroSAR is a project funded by the NASA Applied Sciences Program focused on the development of algorithms for the monitoring of hydrological hazards using data from Synthetic Aperture Radar (SAR) sensors. Algorithms are being developed for the following SAR-derived products:
- **RTC30:** Time series of Radiometrically Terrain Corrected (RTC) SAR images provided at 30 m resolution.
- **RTC30-Color:** RGB compositions of from dual-pol (VV/VH) Sentinel-1 SAR RTC image products provided at 30 m resolution.
- **CCD30:** Change detection products relative to the first image of an event subscription (30 m resolution).
- **HYDRO30:** Surface water extent maps per Sentinel-1 SAR image acquisition (30 m resolution).
- **AG100:** Agriculture extent maps derived by statistical analyses of RTC30 time series stacks (provided at 1 ha resolution).
- **AG30-IN:** Maps of inundated agriculture (1 ha resolution).

## The HydroSAR Team
HydroSAR includes an interdisciplinary team from the following universities and NASA Centers:
- University of Alaska Fairbanks (UAF; project lead); Fairbanks, AK
- NASA Alaska Satellite Facility (ASF) Distributed Active Archive Center; Fairbanks, AK
- NASA Marshall Space Flight Center (MSFC); Huntsville, AL
- University of Alabama, Huntsville (UAH); Huntsville, AL
- NASA Goddard Space Flight Center (GSFC); Greenbelt, MD
- Jet Propulsion Laboratory (JPL); Pasadena, CA
