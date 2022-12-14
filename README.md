#                   Amazon_Keywords 

![](https://github.com/Alexandria-Ransom/Amazon_Keywords/blob/main/amazonman.gif)



# Project Description | Project Preface: Amazon Keywords-Search Terms | Author: Alexandria Ransom

This project will be taking 18 keywords that you can type into the amazon search bar at amazon.com and perform analysis on trends and patterns amongst product categories. These 18 keywords represent physical products that can be purchased from their website. From there, I will be evaluating the search results products pages under that key term via junglescout data. For each keyword, I will be collecting  my own data on each term via third party app junglescout. After, typing in each keyword via amazon searchbar, click on the junglescout app to pull on data for that keyword that showcases around 15 attributes for the individual keyword. Here is a photograph example below on this exactly on how each word was collected:

Hands on visual example: "bellydance wings" is the keyword in this photo. The orange square is the third party app junglescout that collects data (holds around 15 attributes) for the search pages under this keyword.

![junglescout](https://github.com/Alexandria-Ransom/Amazon_Keywords/blob/Version1.1/gifs/photos/junglescout.png)







## Version 1
- V1 Version 1.1 - Data Wrangling, Pre-processing, & Cleaning in Python. In this version, I will take all the 18 csvs of tabular data collected per each keyword and combine them into one large csv file. After, I will conduct indepth cleaning through the pandas library. This version essentially wrangles the data and gets the data in proper format. This version fills in missing values, cleans column names, uses stat tests to help preprocess skewed numerical data. 
- V2 Version 1.1 - Extracting Insights and Identifying database patterns via SQL queries - simple analysis in SQLite3 python library
  In version V2, I use SQL queries to discover and extract insights amongst product 22 categories from the cleaned csv file from v1. This helps reveals underlying structure of the dataset. The goal is to do a simple analysis for each category by itself to look how the column is behaving on its own.(This will be independent analysis on amazon product categories in looking at categoreies by eacg singley. )  
- V3 Version 1.1 - Data Visualization in Tableau
  After extracting insights amongst each category, I will take it a step further by visualizing the data in Tableau. These visuals reveal and maginify the trends explored on graphs. The visuals help form interactive dashbards to gain even more insights and perspective across all categories. 

## Version 2 
- Version 2.2 V1 Automation 
- Version 2.2 V2 Machine Learning Algothrims: Predicting all numerical columns
- Version 2.2 V3 Building an app to predict single, binary, and multiclassers. 
## Broad Why of this project | Who will this project add the most value and be a asset to? 
This project will help amazon sellers in their product research stage in finding na product that is lucrative and can help them achieve their overall goal to sell and private label. This project would help save FBA sellers time in product search by automating data visualizations and data analysis for the sellers to make decisions faster. 



## Dataset Background-Link: [DatasetLink](https://github.com/Alexandria-Ransom/Amazon_Keywords/blob/Version1.1/ecom_search_keywords.csv)



### Tabular Data Attributes: For each keyword the attritube we will using to analyze each search term is 
* Product Name: The individual name under the keyword of the product 
* Brand: Individual Product brand for the keyword
* Monthly Sales: 30 unit sales estimate
* Price: Current buy box Price  
* Daily Sales: Daily unit sales estimate  
* Monthly Revenue: 30 day gross revenue (price x monthly sales)
* Date First Available: A date for listings based on when they were launched on Amazon. Established products, such as from five years ago, will be harder to compete with than a product that just launched last year.
* Net: Payout to sellers after subtracting amazon sellers fba fees
* Rating Number: number of product ratings for this listing
* Rating: average review star rating of #'s 1-5... This helps you find products that sell well but may have room for improvement ??? all information you can take advantage of.
* Fees: These are estimated FBA fees--> a flat fee per unit, based on the size and weight of the product
* Product Rank: Best sellers rank in teh parent category. The lower the number, the better the Best Seller rank ?????? and the higher the sales on Amazon. If you want to filter out slow-moving products, add a maximum sales rank.the number that represents the popularity in a main category or sub category. To get a good product rank, the product must have great sellers rank. The closer to 1 is a considered the best. A ranking closer to 1M is a worst ranking.
* Category: Amazon product category the listing fell under
* Asin: Product Asin Number (Amazon Standard Identification Number)
* Link : The link to view the individual product
## **18 Keywords Used:**


* bathbombs 
* bellydance wings 
* coin scarf
* cotton balls 
* eco friendly pencils
* faux mink eyelashes
* glitter
* led lights
* led lights for bedroom
* makeup applicators 
* makeup blender sponge 
* makeup brush set 
* makeup sponge 
* pencil case 
* qtips 
* sheet protectors 
* vegan lipstick 
* vegan mascara

![](https://github.com/Alexandria-Ransom/Amazon_Keywords/blob/main/giphy.gif)

# Obtaining Data 
In this repo, you will see a folder called data/final_combined_csv/. Click this folder to obtain the data. There are different options to use this data interactively with thsi notebook. You will see  a folder called 18csvs_individual_zip. This is a zipfolder that holds the 18 seperate csvs for every keyword. You have the option to download this zip and run the jupyter notebook code. Second Option: You will a second folder called individual_csvs. This folder is the same csvs from the above zipfile, but just not held in a zip file, that way they can be accessible one by one. Open this folder, download individual csvs one by one. 

*The final folder ecom_search_keywords, is a file that can be downloaded after you walkd through this project with the jupyter notebook. This is a csv with of the 18 csvs combined as oone single csv.


# Gifs Folder 

The gifs folder holds all of the interactive gifs in this repo that can be downloaded for fun to follow along with.


# Version 1.1 Folder

After obtaining the data, first open the v1 folder. The v1 folder stands for Version 1.1.1 v1. Here in v1, you will be looking at a notebook of data wrangling, cleaning and analysis in pandas in python. v1 folder you will find the notebook keywords_ecom.ipynb to follow along. Download keywords_ecom.ipynb and run each cell.
