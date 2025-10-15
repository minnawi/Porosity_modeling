# Porosity_modeling

## <p align="center"><b>General</b></p>

This repository provides a Papermill-controlled pipeline (scripts 00-08, notebooks A-D) for modeling pore structures in biological tissues from medical images. It includes three post-processing scripts for calculating area, volume, and performing statistical analyses. All codes are python scripts in Jupyter Notebook.



## <p align="center"><b>How To Use The Tool</b></p>

0- Download the [python_codes](minnawi/Porosity_modeling/python_codes/) folder and add your samples to a subdirectory there\
1- run papermil A on all the sample → choose the lower threshold of the pores for each \
2- use the chosen thresholding method for each sample and run papermil B →  choose the upper threshold of the pores \
3- run code 04 for each sample → create the L marks\
4- using the upper and lower thresholds and the L marks, run papermil C → model the pores and clean the STL file\
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NOTE: here check the models manually (number 8 of the craeted files), once accepted, save it as "9-repaired"

5- run papermil D → get the morphological results\
6- run papermil E → get the mechanical properties


<hr style="border:1px solid #ccc;"/>
<br>
<br>
<br>

The [publication_data](minnawi/Porosity_modeling/publication_data/) folder contains all the data from the samples used to publish the journal paper IOD: ********

