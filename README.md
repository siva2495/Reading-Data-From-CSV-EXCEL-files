# Reading-Data-From-CSV-EXCEL-files
Reading Data From different type of files

Reading Data Files
	So far, we have seen the basic python libraries that commonly used in data science task.  Now the first task is reading different types of files like JSON, TEXT, CSV, EXCEL, etc. In this below work book, we will see how to read these files and what are the different challenges that we facing while reading these files and how to tackle them.
	Pandas is one of the most used library for reading data sets. In this section we are going to use pandas for such a task.
Read more about the pandas here:  https://pandas.pydata.org/pandas-docs/stable/index.html

Reading CSV Files

1.	Reading CSV files

2.	Challenges with reading the CSV file.

	Read the data except the first few rows in the file.

	Read files present in multiple directories.

	Check and delimiter and read file.

	If the dataset is bigger in size, we can read a few rows only.

	If the dataset has large number of columns, read only specific columns

Read the CSV File

About the Data Set: The data set that we are going is use is the Sales Data. It was collected by the data scientists at BigMart for 1559 products across 10 stores in different cities. It contains informations like Item Identifier, Outlet Size, Item MRP, Outlet Location Type, Item Outlet Sales etc.

DATAFRAME

•	DataFrame is a 2-dimensional data structure with columns that can contain different data type.

•	Similar to a spreadsheet or SQL table.

•	It is generally the most commonly used pandas object.

Read the data except the first few rows in the file.

•	You may get an error while reading a CSV file because someone may have added few comments on the top of the file. In pandas we can still read the data set by skipping 
few rows from the top.

•	To deal with the ParseError, open the csv file in the text editor and check if you have some comments on the top.

•	If yes, then count the number of rows to skip.

•	While reading file, pass the parameter skiprows = n (number of rows to skip)

READING FILES FROM MULTIPLE DIRECTORIES

•	When data is present in mutiple directories, Let's see how to read data in this case.

•	Hers, we have split the same dataset year wise into multiple files and stored them into mutliple directories.

•	Use the glob library to list the files in a directory

Read a CSV of a specific Delimeter

•	By default, while reading a CSV file pandas consider the seperator as ,. But if the CSV file has some other seperator or delimiter like [; , \t ] we need to specify 
that.


Reading Excel Files

In this section, we will see how to read excel files using pandas and what are the challenges while reading the excel files and how to tackle them?

Tables of content:

•	Reading Excel Files

•	Challenges with reading the EXCEL file.

	Reading excel files with multiple sheets.

	Comments in top rows.


	Assignment: Read files present in multiple directories.

CHALLENGES WITH READING EXCEL FILES

•	Reading excel files with multiple sheets.

•	Comments in top rows.

•	Read files present in multiple directories.









