# Additional files for Final Project for GEOM 2007 - Analysis of Red-Light and Speed Cameras in Ottawa
## Data
I don't know if I have the right to share the data without a proper license so if you'd like to use the scripts please download the data from Open Ottawa. The datasets used for are detailed below.
### Script Data
- [Speed Camera Data (2022)](https://open.ottawa.ca/datasets/ottawa::automated-speed-enforcement-camera-violations-2022/about)
  - Named "speed_cams.zip" in the script
  - Any year should be useable, unless format is changed in future years.
- [Collision Data (2017-2022)](https://open.ottawa.ca/datasets/ottawa::traffic-collision-data/about)
  - Named "Traffic_Collision_Data.zip" in the script.
  - Only this file has been tested, modifications may be needed for future or past data
### Other Data Used In Project
- [Red-Light Cameras](https://open.ottawa.ca/datasets/ottawa::red-light-camera-violations-2022/about)
- [Centrelines](https://open.ottawa.ca/datasets/ottawa::road-centrelines/about)
## Instructions
To run collisions_per_year_cams.ipynb use a code editor compatible with jupyter notebook kernels, also geopandas must be installed in the environment before use.
Ensure that an outputs folder has been created in the directory the script is in, as well as necessary inputs as shown in the Script Data Portion
## Tables
Tables are the modified tables exported from ArcGIS Pro based on the shapefiles found on Open Ottawa which calculate revenue of fines.

Speed Fines are set as $50 (assumption of 10km over limit with $5.00 per km)

Red-Light Fines are $325 per City of Ottawa (2022)
## Other
Any questions can be directed to me via email: nevanopp@cmail.carleton.ca do not hesitate to reach out.

This is free to use for anything without permission, just don't copy it for an assignment.

