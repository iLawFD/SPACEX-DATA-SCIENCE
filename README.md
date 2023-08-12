# SPACEX-DATA-SCIENCE

This is my solution for the final project of the Data science IBM certification

This project has gone thorugh 4 phases:
# 1- Data collecting:
- In this phase, i made a get request to the SPACEX API and then stored the response.json as our data frame. After that i did some data cleaning, dealing with missing values and filtering  
# 2- Data wrangling:
- Because some columns do no have to the actual value of the column but rather the adress or part of the URL of that spcecifc info, we have to do some Data wrangling. Since this is a little advanced we were provided with functions that do the data wrangling and we just have to use them. Also in this phase we created the Class column, which indicated how successful the misson was. 
# 3- Data visualisation:
 In this phase, i tried to find hidden info & patterns  in the Data. My findings were:
  - all launhces at the site of KSC LC 39A with GridFins had a sucess rate of 100 %. This implies that KSC LC 39A should be the main laucnh site for SPACEX and all launhces should be equiped with grid fins.
  -  the Payload mass is faily corrlated with the sucess rate of the mission. This implies that increasing the mass can be benfical.
