# Mechanical-datasets

This repository contains mechanical datasets used in the paper "Highly-Accurate Machine Fault Diagnosis Using 
Deep Transfer Learning". All the data are the original vibration signals acquired by sensors.

Bearing dataset is from Case Western Reserve University bearing data center 
(http://csegroups.case.edu/bearingdatacenter/pages/welcome-case-western-reserve-university-bearing-data-center-website). 
For the names of the data files, for example 'B007_0', the first letter represents fault position, 
next three numbers represent fault diameters (0.007, 0.014, 0.021 inches) and the last number represents bearing loads(0,1,2,3).
There are three kinds of fault positions here, B-bearing rolling element, IR-inner raceway, OR-outer raceway. 
Data we used are all from fan end which is marked as 'FE' in the data files.

Gearbox dataset is from Southeast University, China. These data are collected from Drivetrain Dynamic Simulator.
This dataset contains 2 subdatasets, including bearing data and gear data, which are both acquired on Drivetrain Dynamics Simulator (DDS).
There are two kinds of working conditions with rotating speed - load configuration set to be 20-0 and 30-2. 
Within each file, there are 8rows of signals which represent: 1-motor vibration, 2,3,4-vibration of planetary gearbox in three directions: x, y, and z, 5-motor torque, 6,7,8-vibration of parallel gear box in three directions: x, y, and z. Signals of rows 2,3,4 are all effective.
