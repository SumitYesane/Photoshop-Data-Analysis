Analysis of Photography studio data

Problem: 
To find the appropriate customers age group which attract the business and find monthly growth of the business as well as by analysis acquiring new things this will help for growth of business.
Solution: 
Creating a product in which the user can drag and drop the excel file   and at the backend it will be filtered and analysis is done, the analysis will be shown on the user window. Where it can be easily analyzed by non-skilled people also, to understand the growth of business.
Goal: 
On a single click the user will get the required analysis of the data, to implement and acquire new things to grow more.


Front End (User Interface)
Buttons: 
Two buttons will be provided when user upload file it will display sample data and then the show analysis button will appear 
    1) Enter your file: Here user can drag and drop excel file up to limit 200mb
    2) Show Analysis: After click the analysis of the data in very clear manner will be shown
Result Section: 
In this section all the data is divided in number forms to get more knowledge about the customer rate. 
1)	Total customer: 
It will display how many customers approached. 
2)	Unique customer: 
It will display how many unique customers approached. 
3)	Total modelling: 
It will display how many customers approached for modelling photographs.
4)	Total wedding:
It will display how many customers approached for the wedding.
5)	Total Xerox/Print: 
It will display how many customers approached for Xerox/Print.
6)	Total Karizma album: 
It will display how many customers approached for Karizma album.
7)	Total Id Photo: 
It will display how many customers approached for Id Photo.
8)	Total Earning: 
It will display total earnings month wise.



Analysis Section:
In this area all the analysis will be displayed in graphs for better understanding. By using various graphs going to show the below listed content by using appropriate graphs.
    1) Monthly growth:
    2) Male vs female customer rate:
    3) Growth of female and male:
    4) Divide by age group:
    5) Divide by type of model:
    6) Growth rate for every type:

Types in photography
   1) Modelling (M)
   2) Wedding (W)
   3) Xerox/Print (X)
   4) Id Photo (ID)
   5) Karizma album (WKA)
Back end (Coding part): 

Three files we are going to create 

  app.py: 
This file contains and receives all the data which will be shown on the user interface

  preprocessor.py:
  
This file contain user data in which  processing takes place then renaming the column name, dividing the data and creating new columns and return the processed data to app.py
 
 helper.py: 
  
This file contains all the analysis part in which we are going to code for Analysis section and result section and at last all the processed data will return to app.py
