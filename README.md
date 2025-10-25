# TRACKING HYDROTHERMAL DIFFUSE FLOW WITH MULTIBEAM SONAR: INSIGHTS FROM COVIS (2019–2023)
Master of Operational Oceanography Thesis

This repository contains Python code that analyzes multi-beam sonar data collected by the Cabled Observatory Vent Imaging Sonar (COVIS) system located at the ASHES hydrothermal vent field. The primary dataset, available in the `heat_flux_results.zip` archive, was initially processed using MATLAB to extract heat flux density and fractional area data from diffuse hydrothermal flows for the period from 2019 to 2023. The provided Jupyter Notebook processes this data to create time series plots, heat flux density visualizations, and statistical summaries. An `environment.yml` file is included to recreate the exact Python environment used for this analysis.

The overall purpose of this repository is sharing code used to analyze and visualize diffuse hydrothermal flow using COVIS data. The findings demonstrate the time-series details of heat flux density at the ASHES vent field, highlight seasonal and episodic changes, and lay the groundwork for correlating these patterns with environmental drivers such as volcanic activity or seismic conditions. By providing both the processed datasets and the Python code, this repository aims to support reproducibility and future extensions of the study by other researchers.

## Repository Structure
- `heat_flux_results.zip`: Contains MATLAB-processed heat flux density data (.mat files) for 2019-2023.
- `MOO_Thesis_2025_Final`: Jupyter Notebook that reads, processes, analyzes, and plots the heat flux data.
- `environment.yml`: YAML file listing Python package dependencies needed to run the notebook.

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/Jay-sei/research.git
cd research
```

2. Set up the Python environment:

```bash
conda env create -f environment.yml
conda activate covis-analysis
```

3. Unzip the `heat_flux_results.zip` file in the repository directory.

4. Open and run `MOO_Thesis_2025_Final` in Jupyter Lab or Jupyter Notebook.

## Requirements

- Anaconda or Miniconda
- Python 3.9+
- Jupyter Notebook or Jupyter Lab
