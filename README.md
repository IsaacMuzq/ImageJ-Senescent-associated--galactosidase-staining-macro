This is an ImageJ macro to automatically determine the intensity of your Senescent associated galactosidase staining pictures.
Two sets of pictures must be prepared, sa-staining pictures and corresponding DAPI pictures, each saved under their own folder separately. 
Open sa-staining macro in ImageJ in "Macros-RUN", then choose the folder that contains the sa-staining pictures, then the ImageJ will determine the staining intensity by color thresholding the positive area and measure its intensity.
Color thresholding parameters can be optimized for precision, but must be kept the same in experiment group and control group.
Once finished sa-staining macro, open the count macro.
Choose the folder containing the DAPI files, the ImageJ will count the cell number.
The relative SA-staining index is the SA-staining intensity divided by the cell number of each view.
