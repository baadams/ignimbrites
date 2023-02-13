# Ignimbrites
This repository contains the codes used to produce a suite of synthetic landscapes and a condensed version of the model outputs. These codes were written by Byron A. Adams. 

*Directory contents*

sythetic_landscape_data.mat - this is a binary Matlab file that contains the summary metrics used to describe the output landscapes in the publication details below (e.g., channel steepness, range-scale slope, time to steady-state).
  
grow_up.ipynb - is a Jupyter Notebook set up to create landscape evolution models with in Landlab. This notebook allows the user to change boundary conditions and variable and save time slices as the landscape evolves with in a NETCDF file. See headers and comments for more detail.
  
example_landscape.nc - this is a NETCDF file that includes the output data (e.g., topograpy, erosion rate, channel steepness) as a function of space and time with the Landlab grid. Follow this [(link)] to downlaod the file (https://liveuclac-my.sharepoint.com/:u:/g/personal/ucfbbad_ucl_ac_uk/EQk_5D-VfZxBkcn7ycCP_IYBXAr1YF2uXPZHGSn4N6emeg?e=VeY91w)

landlab_analyzer.m - this is a Matlab script that is used to interrogate the NETCDF file and calculate useful matrics. See commented file for more details.
  
# Attribution
If you use or modify these codes and use the results in a publication, please cite the corresponding publication: Adams, B.A., Cooper, F.J., Walsh, C., Cashman, K. (in review). Revealing rock uplift rates from landscapes buried by Earth’s largest volcanic eruptions.

# Error Reporting and Feature Request
If you encounter a bug or have a suggestion for a new feature / improvement the preferred method of communication is to use the 'Issues' function built into GitHub. You can also email Byron [byron.adams 'at' ucl.ac.uk]. If you encounter an issue that you know how to fix and are comfortable with how git works, please feel free to fork the code and submit a pull request with fixes and improvements.
