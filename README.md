A comprehensive repository for the characterization and optimization of the H2RG infrared detector, developed as part of a thesis project. This repository includes code for analyzing detector performance under various configurations, identifying bad pixels, evaluating spatial and temporal noise, optimizing spectral resolution windows, and generating meaningful visualizations. The project contributes to the Asgard/NOTT instrument development, focusing on L-band nulling interferometry for exoplanet detection.

This repository contains the following folders and files:

- **`ramp_mode_single_ended/`**  
  Contains data for analyzing ramp mode operations in single-ended configuration.

- **`bad_pixel_noise_characterization.ipynb/`**  
  Includes the script to characterize bad pixels and noise.

- **`cds/`**  
  Data of Correlated Double Sampling (CDS).

- **`sky_code_analysis/`**  
  This folder contains more data from the LBTI code and the corresponding ramp analysis based on several ramps, reads, groups, and coadds. It also includes the script to identify the best window on the detector frame for horizontal and vertical windows.

- **`ramp_mode_check_using_pixel_values.ipynb/`**
  This notebook analyses the signals(read, reset, read) during ramp mode acquisition.  
