# Velocitemperature

Velocitemperature is an open-source web application helping users to better understand the present-day subsurface temperature profiles in 2D and 3D sense. The application converts interval velocities corresponding to each shot point based on the method in Ryan & Shalev’s paper published in 2014.

By importing your interval velocity data and static temperature data from the wells, you can;

•	Filter the nearest point data coordinate to the wells,  

•	Calibrate velocity derived temperatures with well temperatures by controlling 2 constants,

•	Display the full temperature profile on crossplots with time and depth domains,

•	Create 2D temperature maps for every 500 ms. as timeslices,

•	Generate a temperature cube and examine your point data in a 3D sense,

•	Download any graphs, maps and/or cubes as a .png file to implement them for presentations, reports and scientific papers,

•	Export the data as an excel file to import it into interpretation softwares and reflect temperature cubes on seismic sections to reveal the temperature profiles and detect meaningful anomalies. 

The outcomes can be used for both hydrocarbon and geothermal exploration projects.

Any contributions or suggestions are welcomed.

## Data Import

The application requires two different excel files including seismic velocities and well data. Depth data for seismic velocities is also needed for well calibration. 
For both, special column names should be used as following:

**Velocity Data**

Velocity Data column names: "X", "Y", "T", "V" and "TVD_m"

X: Coordinate X

Y: Coordinate Y

T: Time (miliseconds)

V: Interval velocities (m/s)

TVD_m: True Vertical Depth (meters)

**Well Data**

Well Data column names: "TVD_m", "T"

TVD_m: True Vertical Depth (meters)

T: Temperatures
