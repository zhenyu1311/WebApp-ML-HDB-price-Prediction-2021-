You can use this web app to predict HDB prices. Data is updated as of 2021. This is previously hosted on Heroku but Heroku no longer offers free hosting services. So you have to run the app locally by running the manage.py file. 

For floor numbers, only increments of 3 floor. Eg. "01-03" ,"04-06" ,"07-09"...will work but "02-04" will not work. 
Location names are also case sensitive, following hdb1720.csv. EG. you should input ANG MO KIO AVE 3 , not Ang mo kio ave 3.


Sourced from singstat.gov


Note: 


       1. Ensure you follow the entry format of the app. For example, the floor format is XX to XX, you have to input '04 to 06' , it will not work if you input, say '4 to 06' or '4 to 6'. 

      2. It is case-sensitive. For example, you should input REDHILL, but reDHilL will not work. 
      
      3. Only data that exist in the data files can be predicted, no extrapolation predictions are available. for example, highest floor in data is 45, but if you predict the pricing for a house with 60 floors, the app will bug out.
