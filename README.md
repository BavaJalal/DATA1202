# YOUTUBE CHANNEL ANALYSIS
# Short Description
This Python script inserts the data into a MySQL database, analyzes YouTube channel data from a dataset, and determines the distribution of channel types from the top 1000 records.
# Getting Started
# Prerequisites
Make sure you have installed the following: 
- Anaconda
- Jupiter Notebook
- MYSQL Workbench
# insatalling 
 First, we imported required libraries
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/75513b6d-6ebb-4a60-952a-31e7e1f96768)
Now we are all set to do the youtube channel analysis
you can downlaod the dataset from here: https://github.com/BavaJalal/DATA1202/edit/main/README.md
# Running the analysis
Loaded the original dataset
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/f275139f-fbfb-4b01-948d-5bdbc85194e8)
Created a function to calculate the distribution of channeltypes from the top 1000 records 
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/6b2436c2-aa3a-4ba1-91de-81bb884807ab)
Calculating the distribution of channeltypes from the top 1000 records by calling the function
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/a1108ce4-ed39-47cc-8b9f-08c8cabb553c)
Print statements to display the results
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/20bf177c-08e7-463e-a6cb-c258853c9bf3)
# Breakdown of Tests
Calculating the distribution of channeltypes from the top 1000 records as percentage 
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/eac38c43-ae5f-4184-9f47-4b40177dcb11)
Print statements to display the results
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/659d150b-2f05-45f1-a34f-f67867bef8c4)
Calculating the distribution of channeltypes from the top 1000 records without removing null values 
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/3c695e43-bae7-40d3-9535-a8595355130b)
Print statements to display the results
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/a60d94de-6c89-421d-a73f-d5b5757928b9)
Loading the top 1000 records into a new csv file
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/f9aafd34-3484-4a4e-ac29-660dd30b5289)
Checking if the new csv file is created
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/1d77acfd-1335-46a1-8d8b-eea1f2638699)
Creating engine to connect to MySQL
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/cc3f1e93-0787-43a2-ace5-e9bc1d9f64be)
Loading the top 1000 records into new table in the database
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/823a15f2-9967-4e1f-9f3b-fbbbbd49e4f8)
Using select statement to load data from newly created table
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/5ec8f60d-8529-4ada-b4b8-b91e01d155ee)
Displaying the top 10 records from the new table
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/644b7788-02eb-4d13-898c-e6a9616e3d5b)
Finding if newly created table has expected number of rows
![image](https://github.com/BavaJalal/DATA1202/assets/151898946/af31c4fe-fcae-46e5-ad34-c1beb2c84ba6)
# Deployment
Make sure you have a MySQL database setup before deploying this script, and adjust the script's connection parameters. To load the data into the database, run the script after that.
# Author
Bava Jalal


























