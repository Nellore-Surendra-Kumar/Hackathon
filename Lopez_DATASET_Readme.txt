This README.txt file was generated on 2021-10-28 by Brenda Lopez Reyna



GENERAL INFORMATION

1. Title of Dataset: NCST real world brake activity of heavy-duty vehicles data

2. Author Information
	A. Principal Investigator Contact Information
		Name: Heejung Jung
		Institution: University of California Riverside
		Address: 
		Email: heejung@engr.ucr.edu

	B. Associate or Co-investigator Contact Information
		Name: Kent Johnson
		Institution: University of California Riverside
		Address: 
		Email: kjohnson@cert.ucr.edu

	C. Alternate Contact Information
		Name: Brenda Lopez Reyna
		Institution: University of Califronia Riverside	
		Address: 
		Email: lopezbe@ucr.edu

3. Date of data collection (single date, range, approximate date): 2021/03/15 - 2021/03/16

4. Geographic location of data collection: Riverside, CA and Victorville, CA


DATA & FILE OVERVIEW

1. File List: 

DATAXX.CSV (where XX ranged from 23 to 43) - Files numbered from 23 to 35 pertain to chassis dynamometer tests while 36 to 43 pertain to on-road driving tests.

Logger_Notes.pdf - Information on which files were used for warm up tests, troubleshooting, and cycle or on-road testing.

1C15XXXX.CSV - HEM logger files XXXX corresponds to file 2217 for the CBD cycle warm up test, 2229 for the CBDx3 cycles, and 2305 for the UDDSx3 cycles.

20200215XX_YYYY.csv- HDCD files YYYY corresponds to file 1905 CBD cycle warm up test, 2217 CBD cycle warm up test, 2229 CBDx3 test, and 2305 UDDSx3 test.

20200315_HangLog.pdf - Information on the HCDC dynamometer tests.

1C16XXXX.CSV - XXXX corresponds to file 1614 for the local Riverside route, and 1734 for the Riverside to Victorville route.

UCR_of_College_of_Engineering-Center_for.pdf - Information for the on-road tests.



METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 


2. Methods for processing the data: all CVS files are raw data from the brake logger, HEM logger, and HDCD


3. Instrument- or software-specific information needed to interpret the data: N/A


4. Standards and calibration information, if appropriate: Time synchronized to NIST US official time



DATA-SPECIFIC INFORMATION FOR: DATAXX.CSV

1. Number of variables: 5

2. Number of cases/rows: 

3. Variable List: 

Time - hh:mm:ss (refer to Logger_Notes.pdf to synchronize start time and stop time)
T - Cold Junction Temp (refer to Logger_Notes.pdf as T and CJC labels are switched on all raw data files)
CJC - Brake Temperature (oC)
PV - Pressure voltage (Volts)
PSI - Brake fluid pressure (PSI)


