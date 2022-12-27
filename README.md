# EMG-MMG-FES-Force-Proxy


MSc Project – Rishan Patel 

Directory explained
Folder Name	Explained
*Original Files: Original files by Panayotis (previous MSc), original UNO files Nat provided and developed with the board with python interface.
*Active-fes-master-Osuagwu Filters: Osuagwu filters for using Hasomed Rehastim in a fully controlled Simulink file. Inside can find the filter files but I have also populated the right folders with the file separately. 
*Final report images: Images for the dissertation
*Presentations: All presentations I have given over the course of this project

Implementation Folder
*Fatigue Marking: Two subfolders: EMG and MMG. EMG file includes data “emgData”, the other one with “badMMGdata” is with some flawed data which is not useful. Then subfolder RawData gives the pre-processing scripts and putting the data into the right places/variables etc. CollectionScripts are the scripts required to collect that EMG data. Figures.m can provide all figures required for this EMG section.PlayingScript.m can show functions and implementation I would keep track of. ForcerelationshipFind.m is simply looking for that correlation coefficient.
MMG subfolder: FatiguingDataSet.mat which has the data. Data subfolder which is preprocessing. Figures.m for figure production.
Validate Devices: 10Aug22_experimentFiles consists of all the run files to collect data i.e. EMG Arduino files, MMG IMU, python files etc.
Two folders for subject 1 and 2 data pre-processing. 
3 Mat files which are subject1,2 and Merged data for figures.
Figures.m will provide all of the figures.
Outdated Old Data:	Please refer to the logbook file for a track of the data experiments and what problems occurred with each data and device.


All code has been sufficiently commented and explained. 
As all of this data is simply analysis, the running will be in each .m file per folder as outlined above. All Scripts will have been named appropriately and accompany all necessary files/functions/data. 
