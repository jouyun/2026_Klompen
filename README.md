# 2026_Klompen

Series of scripts for processing planula stage nematostella co-localization using Pearson's coefficient in ncol1, ncol4, and ncol5.

A-ProcessImaris.ipynb - Turns .ims into .tif

B-segment\_single\_object.ipynb - Uses sam2 to find the boundary of the animal in 3D with a manually drawn seed rectangle

C-StellaPearsons.ipynb - Uses a distance transform from the mask to filter out the crap on the surface of the animal, as well as adjust the z-attenuation using an exponential before loosely segmenting out the cells with a threshold.  For the first two weighted otsus were used for setting thresholds, but eventually no simple threshold system worked reliably and values hard-coded. 
