# INSC590-OSF-DoctorWho

This Reproducible README.txt was generated on 20200410 by Hannah Gunderman, Rhiannon Williams, and Kyle Welch

----------------------------------------
GENERAL INFORMATION
----------------------------------------

1. Title of Dataset:  Using Focus Groups to Assess Doctor Who's Impact on Empathy and Geopolitical Awareness

2. Author Information

Author Contact Information  
    Name: Hannah Gunderman  
    Institution: Carnegie Mellon University  
    Address: 5000 Forbes Avenue, Pittsburgh, Pennsylvania, USA, 15213  
    Email: hgunderm@andrew.cmu.edu  
    Phone Number: 865-973-9543  


Author Contact Information  
    Name: Rhiannon Williams  
    Institution: University of Tennessee-Knoxville  
    Address: 1345 Circle Park Drive, Knoxville, Tennessee, USA, 37916  
    Email: rwill167@vols.utk.edu  

Author Contact Information   
    Name: Kyle Welch  
    Institution: University of Tennessee-Knoxville  
    Address: 1345 Circle Park Drive, Knoxville, Tennessee, USA, 37916  
    Email: kwelch17@vols.utk.edu  

---------------------------------------
DATA & FILE OVERVIEW
---------------------------------------

Directory of Files:

   A. Filename:  2017_Likert_DW_focusgroups_Dislikers.csv
   
      Short description:  This CSV file contains the data provided by participants in the Dislikers focus group taking a Likert scale pre- and post- viewing of the Doctor Who episode. 


   B. Filename:  2017_Likert_DW_focusgroups_Nonviewers.csv   
   
      Short description:  This CSV file contains the data provided by participants in the Nonviewers focus group taking a Likert scale pre- and post- viewing of the Doctor Who episode.     


        
   C. Filename:  2017_Likert_DW_focusgroups_Whovians.csv  
   
      Short description: This CSV file contains the data provided by participants in the Whovians focus group taking a Likert scale pre- and post- viewing of the Doctor Who episode. 


Additional Notes on File Relationships, Context, or Content:  The data contained in these three CSVs are *simulated* values from the actual data taken during these focus groups. The three focus groups were divided across three specific populations: Whovians 
(those who consider themselves strong fans of the show), Non-Viewers (those who had never previously seen the show), and Dislikers (those who have seen the show, and disliked it). The data were collected under IRB approval from the University of 
Tennessee-Knoxville. Because the IRB approval did not include data sharing, the data held in the linked GitHub repository are simulated to visually display the kind of data collected; however, the simulated data bears no resemblance to the original data in terms 
of numerical values, and includes no identifying information.

File Naming Convention: yearofdatacollection_datacollectioninstrument_theme_datacollectionmethod_groupname.csv  


----------------------------------------------------------------------------------------------------------
DATA DESCRIPTION FOR: 2017_Likert_DW_focusgroups_Dislikers.csv
----------------------------------------------------------------------------------------------------------

1. Number of variables: 4


2. Number of cases/rows: 67


3. Missing data codes: The dataset has no missing data, but in the case of missing codes, the dataset would use "999" to denote missing data. 

4. Variable List

    A. Name: User  
	
       Description: Denotes the numeric ID representing each individual participant in the focus group. Allowable values are whole numbers only, 1-6.   

    B. Name: Question  
	
       Description: Denotes the question on the Likert scale the participant has answered. Allowable values are alphanumeric, Q1 - Q11, and correspond to the questions listed in the file "likert_questions_DW.png" in the GitHub repo.  
					
	C. Name: Pre
	
       Description: Denotes the Likert option chosen by the focus group participant for each question prior to viewing the Doctor Who episode. Allowable values are whole numbers only, 1-5. 
					
	 D. Name: Post
	 
       Description: Denotes the Likert option chosen by the focus group participant for each question after viewing the Doctor Who episode. Allowable values are whole numbers only, 1-5. 
					
--------------------------------------------------------------------------------------------------------------
DATA DESCRIPTION FOR: 2017_Likert_DW_focusgroups_Nonviewers.csv 
--------------------------------------------------------------------------------------------------------------

1. Number of variables: 4


2. Number of cases/rows: 67


3. Missing data codes: The dataset has no missing data, but in the case of missing codes, the dataset would use "999" to denote missing data. 


4. Variable List

    A. Name: User
	
       Description: Denotes the numeric ID representing each individual participant in the focus group. Allowable values are whole numbers only, 1-6. 

    B. Name: Question
	
       Description: Denotes the question on the Likert scale the participant has answered. Allowable values are alphanumeric, Q1 - Q11, and correspond to the questions listed in the file "likert_questions_DW.png" in the GitHub repo. 
					
	C. Name: Pre
	
       Description: Denotes the Likert option chosen by the focus group participant for each question prior to viewing the Doctor Who episode. Allowable values are whole numbers only, 1-5. 
					
	D. Name: Post
	
       Description: Denotes the Likert option chosen by the focus group participant for each question after viewing the Doctor Who episode. Allowable values are whole numbers only, 1-5. 
					
------------------------------------------------------------------------------------------------------------
DATA DESCRIPTION FOR: 2017_Likert_DW_focusgroups_Whovians.csv  
------------------------------------------------------------------------------------------------------------

1. Number of variables: 4 


2. Number of cases/rows: 67


3. Missing data codes: The dataset has no missing data, but in the case of missing codes, the dataset would use "999" to denote missing data. 


4. Variable List

    A. Name: User
	
       Description: Denotes the numeric ID representing each individual participant in the focus group. Allowable values are whole numbers only, 1-6. 

    B. Name: Question
	
       Description: Denotes the question on the Likert scale the participant has answered. Allowable values are alphanumeric, Q1 - Q11, and correspond to the questions listed in the file "likert_questions_DW.png" in the GitHub repo. 
					
	C. Name: Pre
	
       Description: Denotes the Likert option chosen by the focus group participant for each question prior to viewing the Doctor Who episode. Allowable values are whole numbers only, 1-5. 
					
	D. Name: Post
	
       Description: Denotes the Likert option chosen by the focus group participant for each question after viewing the Doctor Who episode. Allowable values are whole numbers only, 1-5. 

-------------------------------------------------------
METHODOLOGICAL INFORMATION
-------------------------------------------------------

1. Software-specific information:

Name: Microsoft Excel
Version: 2016 
System Requirements: Windows or macOS
Open Source? (Y/N):  N

Additional Notes: The data were initially entered into Microsoft Excel and can be input into Excel. However, for stability and access, the files have been saved in CSV format and can be viewed and analyzed across all operating systems, including Linux. 


2. Equipment-specific information:

Manufacturer: Dell 
Model: Inspiron 3847

Additional Notes: The data were entered, cleaned, and formatted on this Dell computer. 


3. Date of data collection: 20170601 - 20170801

--------------------------------------------------
NOTES ON REPRODUCIBILITY 
--------------------------------------------------

While it would be virtually impossible to recreate these data exactly as shown in the datasets, using the methodology listed in the "DW_focusgroups_manuscript.pdf" file found in the GitHub repository will allow this research to be reproduced with values dependent on those taking part in the focus groups. 

