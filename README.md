# 3DMorph
3DMorph is a MATLAB-based script that analyzes microglia morphology from 3D data. Outputs include cell and territorial volume, branch length, and number of branch and end points.

CGK fork
-----------
The main change of this fork is the use of updated versions of:
- [skeleton3D-matlab](https://github.com/phi-max/skeleton3d-matlab)
- [skel2graph3d](https://github.com/phi-max/skel2graph3d-matlab)


Description
-----------

3DMorph imports .tif or .lsm stacks (3 dimensional images) and processes cell morphologies. 
To begin, run the program and select 'Interactive Mode'. Choose your file (must be in Current Folder or add path first), input xy and z scale, and channel information. 
From here, GUI windows are implemented with individual explanations. Follow the instructions, using image feedback to determine accuracy of data processing. 
Once complete, a Parameters file will be saved to the MATLAB Current Folder. This file can then be used to batch process files with no user input. 

Control and ExCell images are provided as test samples. 

For more information,troubleshooting tips, and to cite, please refer to [paper]. 


### Matlab dependencies:
- MATLAB >= 2018a
- Image Processing Toolbox
- Statistics and Machine Learning Toolbox
- Parallel Computing Toolbox
- MATLAB Parallel Server
- Polyspace Bug Finder

------------------------------------------------------------

Forked from original code written by Elisa M York
Packaged May 2018

This package comes with no warranty of any kind. Permission is
granted to use the material for noncommercial and research purposes. Please cite "3DMorph automatic analysis of microglial morphology in 3 dimensions from ex vivo and in vivo imaging". 

------------------------------------------------------------
