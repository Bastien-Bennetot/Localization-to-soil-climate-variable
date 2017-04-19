# Localization-to-soil-climate-variable
## Purpose
This is a pipeline to go from a table with localization (latitude and longitude) to soil and climatic parameter from different database. 
## Procedure
Following step :
1) You have to download all pipeline using this link https://drive.google.com/file/d/0B5wacU_YrTNhbEJZczByM1BuYkU/view?usp=sharing.
2) Unzip pipeline.zip somewhere on your computer

Please read  Pipeline_to_add_variable_from_database.pdf. It contains all informations in details. Step are summarize there:
3) edit Pipeline_to_add_variable_from_database.rmd with rstudio
4) Change setwd command in the rmd file to your path. Operation described in pdf
5) Install packages in rstudio by using install.packages command or tools>install packages
6) Get you data table formatted as explained in the pdf
7) Run the .rmd with rstudio by clicking on knit.
8) You have your processed data in processed_data.csv
