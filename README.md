# Address-using-Geocoding-API
"""
									Geocoding Excel Input/Output
									
									#Author : Shivam Parashar
									College: IIT Indore, BTech, CSE
									Contact: 7879423595
									Email  : mailtoageek@gmail.com
									
									Languages used: HTML, JS

"""
**************************************************************************************************************************

User enters the address usign the excel file and using google geocoding API we get the lattitude and longitude of the location and finally gets the base
address of the location. There is a download option as well.


#STEPS TO FOLLOW TO RUN THE SOFTWARE:

Step 1:
	Get your own Google geocoding api key, from google developers website

Step 2:
	Get your own Google geocoding api key, from google developers website and update the Run.html code
	

Step 3:
	Open the file "Run.html" in you browser
	
Step 4:
	Open the file "Run.html" in you browser 
	
Step 5:
	Make sure you have the excel file containg the address. There should be one column named address which can contain multile rows or single 		row.
	
Step 6:
	Click on Upload button and select the address excel file.
	

Step 7:
	Click on choose file button and select the excel file containing the address in column.
	
	
Step 8:
	Click on upload button to upload the file.
	
	
Step 9:
	You can see the formatted address and other location values including latitude and longitude.


Step 10:
	You can click on the "Download Formatted Address in Excel with Latitude and Longitude" to find the latitude, longitude and formatted 		address.




PS: Please note that the third column(formatted address) is intentionally not kept in one cell and left into distinct values so that it'll be easy for the reader to differentiate between the house no.,locality, city, state and country.
 
**********************************************************************************************************************************

# What is CSV-Export
A small javascript library to handle saving JSON data as a CSV/Excel file

There are various fuctionality used:


#The code can be broken into 4 parts:

		1)Upload() function to upload the excel file

		2)Processexcel() to extract/parse the address out of excel file 

		3)Geocode() funtion where the address extracted from the above method is passed and latitude, longitude and 								 formatted address are extracted.

		4)The ectracted data is stored in variable finaladdress and passed into the CSV-Export function which helps 						    to download the excel file.


**********************************************************************************************************************************
