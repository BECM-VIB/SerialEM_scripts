# SerialEM_scripts
SerialEM scripts for use of JEOL CryoARM 300 and Gatan K3.
This repository contains all scripts that we use in SerialEM for automated data collection (last tested on SerialEM 3.8)
Detailed explanations are noted at the top or within the script at the specific command to facilitate usage and understanding.

**Parameters.txt**
This file contains all variable parameters that you might want to change depending on your data collection.
Latest version is a tuned for high throughput multi-hole recoding. IS and Astigmatism matrices neeed to be obtained from the IS-vs-Coma calibration in SerialEM.
Vector 1 and 2 neeed to be obtained from the Hole pattern script

**Functions.txt**
This file contains functions that can be (are) called from other scripts in this repository.

**GridAtlas.txt**
This file is automating the collection of a Grid Atlas for a newly inserted sample.

**ShiftXY.txt**
This script is our preferred/most accurate method of aligning CL comp shift and CL comp angle values

**SingleHoleRecord.txt**
This scripts can be used during the screening stage of you data collection. It allows to test the parameters that you want to use in the fully automated collection, while minimizing manual interactions.

**SPA.txt**
MAde wholly redundant with the SPA turbo script.
This script is called for automated data collection in single particle cryoEM.

**SPA-turbo.txt**
This script is called for automated data collection in single particle cryoEM allowing for multi-hole recordings.

**HolePatternDirections.txt**
This script is used to determine the direction and distance of the holes for multi-hole recordings. The result of this script needs to be copied/changed in the parameter.txt file

**BT vs IS (Measure)**
Scripts to measure the coma and stigmation upon image shift either using pre-exposure or making a circular pattern to characterize the microscope
