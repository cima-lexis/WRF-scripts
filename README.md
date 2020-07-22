# WRF-scripts
A set of bash scripts to simplify execution of WRF on HPC servers

## run-no-da.sh
This scripts prepare and execute a WRF simulation without data assimilation. 
Expects as argument three environment variable
 - WRF-INPUT: path of a directory that contains namelist, boundary and initial conditions as produced by WPS
 - WRF-OUPUT: path of a directory where AUX and WRFOUT are saved
 - WRF-BIN: path of a directory that contains WRF binaries and runtime files
 - WRF-WORKDIR: directory that the WRF simulation uses as working directory

## run-da.sh
This scripts prepare and execute a WRF simulation that performs data assimilation of radar and weather stations data. 
Expects as argument three environment variable
 - WRF-INPUT: path of a directory that contains namelist, boundary and initial conditions as produced by WPS
 - WRF-OUPUT: path of a directory where AUX and WRFOUT are saved
 - WRF-BIN: path of a directory that contains WRF binaries and runtime files
 - WRF-RADARS: path of a directory that contains radar data to assimilate
 - WRF-STATIONS: path of a directory that contains radar data to assimilate
 - WRF-WORKDIR: directory that the WRF simulation uses as working directory

 
