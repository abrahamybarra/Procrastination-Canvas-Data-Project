# Procrastination-Canvas-Data-Project
 
CODE

01_Data_Cleaning: This file creates new columns in the dataset corresponding to the different proposed procrastination indices as well as additional "helper columns" used in calculating those indices. Indices are calculated both per-assignment and per-student as is applicable.

02_Feature_Engineering: This file creates new columns in the dataset corresponding to the different proposed procrastination indices as well as additional "helper columns" used in calculating those indices. Indices are calculated both per-assignment and per-student as is applicable.

03_Simple_Regression: Performs regression analyses (including linear mixed models) to test whether various procrastination indices predict course outcomes 


04_Descriptive_Stats: 



DATA

raw_data: contains 1) the data pulled from Canvas by OIT:
		psyc_students_report_split_v2: contains assignment submission data across all sections
		sid_key_v2: contains student id's of all students

	raw_data also contains 2) secondary data pulled directly from Canvas by us (in the "Additional Canvas Datasets" folder), containing grades as well as late/missing assignment submissions

clean_data: contains the assignment submission data after cleaning and separated by class section

final_data: contains the assignment submission data after procrastination indices have been added by 02_Feature_Engineering

