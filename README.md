# Do Certain Unique Factors Impact a Country’s Education Rank/Test Score?

# Guide to replication

To replicate all results presented in the paper, execute the file EconProject.R which is contained in the main directory.

# Data 
* The data that I collected is under RealEcon2000.csv and RealEcon2010.csv
* The dependent variable will be an average of the reading, math and science scores on the PISA test. Observations and test scores for Year 2000 will be from the PISA 2000:Overview of the Study Design, Method and Results written by Stanat · Artelt · Baumert · Klieme · Neubrand · Prenzel · Schiefele · Schneider · Schümer · Tillmann · Weiß, and Organization for Economic Co-operation and Development (OECD). Observations and test scores for Year 2010 will be from the 2009 PISA test scores.
  * All the test scores for each testing period can be found here: http://www.oecd.org/pisa/data/
* This paper will include 8 independent variables and each will include 30 observations from 2000 and 2010. Included: 
  * Enrollment rate of both sexes as a percentage from the Data World Bank
  * Education Index which is a number between 0 and 1 which accounts for the mean years of schooling in a country as percentage of the expected years of schooling for an individual from Human Development Report
  * School Expenditure as percentage of GDP from the Data World Bank
  * Unemployment Rate as a percentage from the Data World Bank
  * Health expenditure per capita in USD from the Data World Bank
  * Ratio of pupils to teacher from United Nations Educational, Scientific and Cultural Organization
  * Prison population rate in per hundred thousand of the national population from World Prison Brief
  * Gross domestic saving as a percentage of GDP from the Data World Bank.

* The variable names are labeled differently for computational analysis. 
 * For Year 2000, x is the average PISA scores
   * x1 is Enrollment Rate, x2 is Education Index, x3 is School Expenditure as a percentage of GDP, x4 is Unemployment Rate, x5 is Health Expenditure per Capita, x6 is Pupil to Teacher Ratio, x7 Prison Population Rate, x8 is Gross Domestic Savings. 
* For Year 2010, x0 is the average PISA scores
  * x11 is Enrollment Rate, x21 is Education Index, x31 is School Expenditure as a percentage of GDP, x41 is Unemployment Rate, x51 is Health Expenditure per Capita, x61 is Pupil to Teacher Ratio, x71 Prison Population Rate, x81 is Gross Domestic Savings.
 

# Software Required 
Work was done with R Studio and the following packages used are in the EconProject.R file and below:
* readr
* stargazer
* lmtest
* car
