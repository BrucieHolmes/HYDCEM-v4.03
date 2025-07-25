***************************************
*		                      * 
* HOW TO INSTALL AND USE HYDCEM v4.03 *
*		                      *
***************************************

THESE INSTRCTIONS ARE FOR MS WINDOWS USERS

----------------------------------------------------------------------
ACCESSING THE SOFTWARE - COMPLETE ALL STEPS BEFORE RUNNING AN ANALYSIS
----------------------------------------------------------------------
1.1 Install PHREEQC into the C:/ drive from the link below.
https://www.hydrochemistry.eu/ph3/phreeqc3.Installer.exe
Installing PHREEQC will allow the user to view the input file created after each analysis
Notepad++ will be installed on your PC
 
1.2 Download IPhreeqC (Windows COM 32-bit) from the website below
https://water.usgs.gov/water-resources/software/PHREEQC/IPhreeqcCOM-3.7.3-15968-win32.msi
IPhreeqc is needed to couple C# with PHREEQC

1.33 Open GitHub using the link below
https://github.com/BrucieHolmes/HYDCEMv4.0_Executable

1.4 Download the GitHub Repository by opening <Code> (green button) and clicking 'Download to Zip'.

1.5 Open the downloaded GitHub folder, Double-click on 'setup.exe' and Install the software.
The HYDCEM application will be installed as a program (HYDCEMv4_WinPrototype) on your PC.
If you receive a 'Windows protected your PC' warning, select 'More info' and 'Run Anyway'.

1.6 Copy the 'DataHYDCEM' folder from the GiTHub downloaded directly to your C:\ drive.
This folder contains files the software needs to run

1.7 Copy the cemdata18.dat file located in the 'DataHYDCEM' folder above and paste into C:\phreeqc\database folder (created after installing PHREEQC).
This is the default file location for the cemdata18 thermodynamic database required to run the analysis

-----------------------------------------------------------------------------
HOW TO UNDERTAKE AN ANALYSIS - YOU MUST COMPLETE ALL STEPS TO RUN AN ANALYSIS
-----------------------------------------------------------------------------
2.1 Starting from the left of the front end, select the analysis type (only one a time can be selected)

2.2. Input the oxide proportions of the cement/CSC
   2.1 If undertaking seawater, sulfate or a quaternary/LC3 analysis, input the required information.
   2.2 If undertaking a fly-ash or slag analysis, input the oxide proportions of the SCM.

2.3 Input the w/c ratio (0.5, 0.65, etc), temperature (in degrees C) and cement Blaine fineness (in m2/kg).

2.4 Select which output(s) and format(s) is required (graphical or tabular (Excel spreadsheet)).

2.5 The file location for the database and saving the output where set up in Steps 1.1, 1.6 and 1.7 above.

2.6 Click RUN to start the analysis.
The PHREEQC Input file and spreadsheet (if selected) will be saved in the 'DataHYDCEM' folder.
Provided all necessary inputs are correct, the analysis will begin.

------------------------------
FEEDBACK
------------------------------
Please provide any constructive feedback to Dr Niall Holmes (niall.holmes@tudublin.ie) so the software can continue to be improved.
