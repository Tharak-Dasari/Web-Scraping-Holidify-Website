# Web-Scraping-Holidify-Website
Check out the Jupyter Notebook here: https://jovian.com/tharakdasari25/indiantourism-web-scraping-project-1
# Scraping 'Holidify' Website To Get Top 100 Indian Tourist Places
![](https://i.imgur.com/nnDuExi.jpg)

Travel planning has always been messy and difficult.*Holidify* is attempting to collect all the information that we will ever need to plan our trip - from when, where, and how, to explore more hidden gems in every destination.*Holidify* is now India's favorite trip planning website as it is the one-stop solution to all our travel planning needs.

Now, through this project, let us get information about the top Indian tourist places from [Holidify-Indian Tourist Places](https://www.holidify.com/country/india/places-to-visit.html?pageNum=0) using *WEB-SCRAPING*.

## Project Overview
Here's an outline of the steps we'll follow:
1. Install Libraries like [Jovian](https://docs.jovian.ai/docs/user-guide/install.html), [Requests](https://www.w3schools.com/python/module_requests.asp) and [BeautifulSoup](https://pypi.org/project/beautifulsoup4/)
2. Download the web page using  *`Requests`*.
3. Parse the HTML Source code of the website using *`BeautifulSoup`*.
4. Extract information like Next Page links, Place Names, the Best time to visit, ratings, etc.
5. Prepare Python lists and dictionaries with the extracted and cleaned information.
6. Create Data Frames with the extracted data
7. Combine and  Save the required information from all pages to CSV files.

## Save the required information to *CSV files.*

A [CSV (Comma Separated Values)](https://www.programiz.com/python-programming/csv#:~:text=To%20write%20to%20a%20CSV,data%20into%20a%20delimited%20string.) format is one of the most simple and common ways to store tabular data. To represent a CSV file, it must be saved with the `.csv`file extension. Let us write a code to convert the information extracted from different pages into  different `CSV Files`

### Save all pages into a MEGA  *CSV* File

Now, we will create appropriate functions to combine the extracted data from all the pages, create a dataframe with it and save it to a single CSV file. This will provide us with all the data from the selected pages in a single file.

## This is how the Mega data looks.
Place Name	 Best Time To Visit  	Ratings	   Link to know more About the Place
0	MANALI	   October to Jun	      4.5/5	     https://www.holidify.com//places/manali
1	LADAKH	   Jun to Sep     	    4.6/5	     https://www.holidify.com//places/ladakh
2	COORG	     October to March	    4.2/5	     https://www.holidify.com//places/coorg

## Summary Of the Project
1. Install required libraries like *Jovian*,*Requests*,*BeautifulSoup*.
2. Download the *Holidify* webpage using `requests.`
3. Save the HTML file of the page into Notebook.
4. Parse the HTML source code using `beautiful soup.`
5. Extract the information of tourist places like place_Name, ratings, etc.
6. Compile extracted information into Python lists and dictionaries.
7. Install and import the `pandas` library.
8. Save the extracted information into a `data frame.`
9. Create `CSV files out of scraped information.
10. Combine data from all pages and create a single `Data Frame` and `CSV` file.
 
