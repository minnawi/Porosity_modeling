# Porosity_modeling

## <p align="center"><b>General</b></p>

This repository provides a Papermill-controlled pipeline (scripts 00-08, notebooks A-D) for modeling pore structures in biological tissues from medical images. It includes three post-processing scripts for calculating area, volume, and performing statistical analyses.

## <p align="center"><b>Steps to take</b></p>

1- run papermil A on all the sample → choose the lower threshold of the pores for each \
2- use the chosen thresholding method for each sample and run papermil B →  choose the upper threshold of the pores \
3- run code 04 for each sample → create the L marks\
4- using the upper and lower thresholds and the L marks, run papermil C → model the pores and clean the STL file\
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:orange;">NOTE: here check the models manually (number 8 of the craeted files), once accepted, save it as "9-repaired"</span></p>

5- run papermil D → get the morphological results\
6- run papermil E → get the mechanical properties


