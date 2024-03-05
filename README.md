# reweightingtools
python library to simulate via openmmtools extension with Girsanov path reweighting and to analyse with a reweighted MSM of deeptime
# How to set up the reweighting software?
1. download existing software with reweighting modification 
   a) go to github https://github.com/anyschaefer 
   b) clone the modified openmmtools, deeptime package by 
   	- copying the "HTTPS clone URL" link that appears after selecting the code icon and 
   	- run git clone [url] in the directory you want to download it to
2. create new environment (RWGHTSoftware) with conda create -n RWGHTSoftware python=3.11 and install
   conda install -c anaconda matplotlib
   conda install -c anaconda spyder
   pip insatll .  # in cloned deeptime path within deeptime folder
   pip insatll .  # in cloned openmmtools path within openmmtools folder
   conda install -c conda-forge openmm 
   conda install -c conda-forge mdtraj 
   conda install -c conda-forge netcdf4 
   conda install -c conda-forge mpiplus 
   conda install -c omnia pymbar 
   conda install -c numba numba
3. create scripts for simulation and analysis with Girsanov reweighting or use the setup and templates in reweightingtools
