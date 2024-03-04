#****************************************** 
#**          Module 4 Challenge          **
#** last edited by Justin Bein, 03/03/24 **
#**                                      **
#****************************************** 

#********************************************************************* 
#** In this assignment, I'll create and manipulate Pandas DataFrames**
#** to analyze school and standardized test data.                   **
#**                                                                 **
# * The scenario: I'm the new Chief Data Scientist for my city's    **
#** school district. In this capacity, I'll be helping the school   **
#** board and mayor make strategic decisions regarding future school**
#** budget and priorities. As a first task, I've been asekd to      **
#** analyze the district-wise standardized test reults. I'll be     **
#** given access to every student's math and reading scores, as well**
#** as various information on the schools they attend. My task is to**
#** aggregate the data to showcase obvious trends in school per-    **
#** peformance.                                                     **
#**                                                                 **
#** My anlaysis will begin with summarize the district's metrics:   **
#** (1) total number of unique schools; (2) total students;         **
#** (3) total budget; (4) avg math score; (5) avg. reading score;   **
#** (6) % passing math; (7) % passing reading; and                  **
#** (8) % passing overall.                                          **
#**                                                                 ** 
#** My analysis will then shift to the individual schools. I'll     **
#** provide the following metrics for each school: (1) name;        **
#** (2) school type (district or charter); (3) total students;      **
#** (4) total budget; (5) per student budget; (6) avg. math score;  **
#** (7) avg. reading score; (8) % passing math,                     **
#** (9) % passing reading; and (10) % passing overall.              **
#**                                                                 **
#** Lastly, I'll explore the math and reading scores by grade and   **
#** the scores by school spending.                                  **
#*********************************************************************

#*********************************************************************
#**                           Source Data                           **
#** The source data for this challenging is contained within two    **
#** files:                                                          ** 
#**                                                                 **
#** schools_complete.csv (15 rows and 5 columns + a header row)     **
#** students_complete.csv (39,170 rows and 3 columns + a header row)**
#*********************************************************************
