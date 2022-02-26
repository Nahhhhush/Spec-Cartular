# Spec-Cartular
A basic API project to gather car data information from a website.

There are 2 python files which are included in this project.

1. Cardata.py - This file contains a python script for the fetching the information from the URL list provided. This file contains all the User defined functions with the main code.

2. URL list.py - In this file the list of URL are provided and has been set into a for loop to hit the URL from the localhost.

Requirements :- 
1) Python with libraries like Flask, Json, Pymongo, lxml, traceback, pandas.
2) MongoDB and MongoDB Compass(Optional)

Execution :- 
1) After installing all the requirements on the machine, Open a command prompt/terminal in the same directory where you have stored the files.
2) Run Cardata.py with command "python Cardata.py".
3) After successfully starting the localserver, Open another command prompt/terminal and run the URL list file with the command "python URL list.py"
4) It will gather data from every url and preprocess it and store that data directly into MongoDB.
5) After Injection, Open MongoDB Compass/ Use command propmt to start mongoDB server and use the data for analysis.

Thank you.
