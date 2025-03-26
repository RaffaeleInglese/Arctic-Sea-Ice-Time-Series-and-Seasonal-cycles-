# Arctic Sea Ice Analysis and Climatology Calculation

This repository contains scripts for processing and analyzing Arctic sea ice data, specifically focusing on the calculation and visualization of temporal series and climatologies based on NetCDF files.

## **Scripts Overview**

### 1. **Sea Ice Temporal Series Analysis**

This script processes a series of monthly NetCDF files and calculates the mean of two specific sea ice variables (`fswthru` and `congel`) for the Arctic region (latitude ≥ 60°). The results are saved in a new NetCDF file for further analysis.

#### **Functionality**:
- Loads monthly NetCDF files.
- Extracts two variables: solar radiation through ice (`fswthru`) and ice freeze (`congel`).
- Calculates the mean for the Arctic region (latitude ≥ 60°).
- Saves the results in a new NetCDF file.

#### **Example**:
```bash
python sea_ice_temporal_analysis.py
