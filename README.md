# EZBehavior
Analysis of light-dark choice and sleep / locomotor data from larval zebrafish

Disclaimer: You may encounter "Security Warning" when opening the macro-enabled files in Excel. Just click "Enable Content" so that the Excel VBA codes can be run in your Excel environment.

1. Light-dark choice assay
    
    Step-1: Reuse the Mid_Corrected.xlsm file (version 1.5x), click "Clear" in the "Setting" sheet. Put this file with the raw Excel files - "--.xls" in the same folder.
    
    Step-2: Click "List & Analyze All" button to analyze the raw data files.
    
    Step-3: Once all the raw data files are analyzed, use the Meta-analysis.xlsm file (version 1.3a) to aggregate all the data together.
    
    Step-4: Follow the examples in the Meta-analysis.xlsm to conduct the aggregation.

2. Sleep/locomotor data

    Preparation: Download the zipped example raw Excel files and unzip all the them (n=48 files). Put all the files in the same folder with the v5.63.xlsm file.    

    Step-1: Use the SleepData_Template_v5.63.xlsm to analyze the example sleep raw data files
    
    Step-2: In the Setting sheet, Key in 1)Experiment Name in cell-X13 2)Group names in cells-Y16-Y27 for up to 12 different groups 3)Number of groups in cell-U15.
    
    Step-3: Click the button "List & Analze All" to go over the raw data files. This part may take up to 10 minutes for 24 hours of sleep recording data.
    
    Step-4: Once done, click the buttons "Step-2" and "Step-3" in order.
    
    Step-5: The "Individual" sheet includes the data for how many seconds the fish was active in a given minute bin. Fish in columns and minute bins in rows.
    
    Step-6: The "Distance" sheet includes the distance travelled (mm/minute). Fish in columns and minute bins in rows.
    
    Step-7: The "Shock" sheet includes the xy location of each fish in each of the midnight arousal test trials in the resoultion of each frames.
    
    Step-8: The "Distance Data" sheet includes the distance travelled (in pixels) of the midnight arousal test trials in the resolution of each frames.
    
    Step-9: The "Per Hour Data" sheet includes the distance travelled (in pixels) of the midnight arousal test for each trial.
    
    Step-10: The "Group Data" sheet includes the number of fish responding to each midnight arousal test trials for each groups (groups in coulumns and trials in rows).
    
    Step-11: The "Baseline Data" sheet includes the comparison of each fish moving distance right before the auditory shock and right after the auditory shock.
    
    Step-12: The "FishCount Data" sheet includes the binary data of each fish responding to each of the midnight aoursal test trials (1-responding and 0-not responding).
    
    Step-13: The "GroupCount Data" sheet includes the final aggregated data for the midnight arousal tests and corresponding charts.
    
    Step-14: The "6 Cycles" sheet includes the data for the dark-light transitions in the 1st day afternoon after clicking the button "Analyze It 4."
    
    Step-15: The "Sleep Bouts" sheet includes the sleep data. The rest/sleep detection threshold is modifiable in cell-G2 in this sheet. 
