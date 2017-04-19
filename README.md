# Localization-to-soil-climate-variable
## Purpose
This is a pipeline to go from a table with localization (latitude and longitude) to soil and climatic parameter from different database. 
## Step
Please read  Pipeline_to_add_variable_from_database.pdf.

Following step :
1) You have to download all github file. Please don't change folder. Put it somewhere on your computer
2)Download and unzip in pipeline/database this file: https://drive.google.com/file/d/0B5wacU_YrTNhVGRGTUN4Rmg2ZVk/view?usp=sharing
unzip the .zip in pipeline/database. 
2) edit Pipeline_to_add_variable_from_database.rmd with rstudio
3) Change setwd command in the rmd file to your path. Operation described in pdf
4) Install packages in rstudio by using install.packages command or tools>install packages
5) Get you data table formatted as explained in the pdf
6) Run the .rmd with rstudio by clicking on knit.
7) You have your processed data in processed_data.csv
