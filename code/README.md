All custom code goes into this directory. All scripts should be written such
that they can be executed from the root of the dataset, and are only using
relative paths for portability.

GenUGDGTSV.m: To generate tsv files in the BIDS directory for UGDG, use GenUGDGTSV.m. 
This code extracts the information needed to generate three column  files for UGDG. 
The code requires the logs from the istart directory to work. 
Clone istart from https://github.com/DVS-lab/istart on the root of the data set to # run. 
