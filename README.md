# README

## Repository Overview

This repository contains the submission materials for the manuscript titled **"Ancient Anorthositic Complexes: Widespread in Lower Martian Crust"**, intended for publication in 2025. The materials are organized to facilitate review and reproducibility.

## Contents

- **`submission_materials/`**: Includes files prepared for journal submission:
    - `README.md`: This file, describing the repository structure.
    - `cover_letter.pdf`: Cover letter for the submission.
    - `response_to_reviewers.pdf`: Responses to reviewer comments (if applicable).

- **`manuscript/`**: Contains the main manuscript files, including:
    - `argyre_feldspar_paper_v4.tex`: LaTeX source for the manuscript.
    - `figures/`: Directory containing all figures used in the manuscript.
    - `extended_data/`: Directory containing extended data figures and tables.

- **`data/`**: Contains processed data used to generate figures in the study:
    - `crism_mapping_results/`: geopackage files of mapped minerals for each CRISM tile.
    - `crism_mapping_results_as_points/`: collated point file extracted from the individual tile polygons.
    - `dohm_2015_map_unts/`: map units provided by James Dohm from his 2015 paper
    - `hirise_spectral_units`: geopackage files containing ROIs used for HiRISE band ratio plots
    - `previous_plag_points`: point file information for all previously published feldspathic outcrops on Mars
    - `themis_results`: excel files with WAC and CSFM calculations for four THEMIS scenes. 

- **`code/`**: Notebooks used for data analysis and figure generation
    - `get_mean_spectra.ipynb`: plot mean spectra contained in geopackage files in crism_mapping_results
    - `graph_network_analysis.ipynb`: run graph network analysis of CRISM-identified minerals
    - `hirise_band_ratios.ipynb`: create band ratio plots from hirise data
    - `mineral_area_analysis.ipynb`: make plots of mineral area as a function of radial distance from Argyre center
    - `themis_analyses.ipynb`: create THEMIS WAC and CSFM plots

## Usage

1. Clone the repository:
     ```bash
     git clone https://github.com/Michael-S-Phillips/Argyre_feldspar_mapping.git
     ```
2. Navigate to the desired directory to access specific materials.

## License

GPLv3

## Contact

For questions or issues, please contact Michael Phillips at phillipsm@arizona.edu.