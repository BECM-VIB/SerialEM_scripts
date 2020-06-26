# SerialEM_scripts
SerialEM scripts for use of JEOL CryoARM 300
This repository contains all scripts that we use in SerialEM for automated data collection (last tested on SerialEM 3.8 beta 11)
Detailed explanations are noted at the top or within the script at the specific command to facilitate usage and understanding.

Parameters.txt
This file contains all variable parameters that you might want to change depending on your data collection.

Fuctions.txt
This file contains functions that can be (are) called from other scripts in this repository.

GridAtlas.txt
This file is automating the collection of a Grid Atlas for a newly inserted sample.

ShiftXY.txt
This script is our preferred/most accurate method of aligning CL comp shift values

SingleHoleRecord.txt
This scripts can be used during the screening stage of you data collection. It allows to test the parameters that you want to use in the fully automated collection, while minimizing manual interactions.

SPA.txt
This script is called for automated data collection in single particle cryoEM.
