# Assignment-2-Data-Cleaning-and-Transformin<img
loaded the file to power query
deleted the blank raws from the "personal ID" column
1) Handling missing values
   found out some missing values in the "Price" column and filled it with median 130
   missing categories are filled by using "if" function by formula
   =if (category ) <> null then (category) else
    if (product name) = " Coffee Maker" then "Kitchen" else
    if (Product name)= "Fitness Tracker" then "Electronics" else "Fashion"
 2) Correcting Inconsistent Data:		
     • Identified  inconsistent text formats present in the "Product Name" column like capitalisation and spaces
        trimmed cleaned and capitalised					
     • Identified the typos Electroni  present in the "Category" column.			
     • Used the find and replace function to standardize the text formats in the "Product Name" column and fixed the typos in the                 "Category" column.								
	3) Removing Duplicates:								
	   • Identified  duplicate rows within the dataset  and removed them .

   Load and close to excel							
	5) Splitting and Merging Data:									
	  • Splited the "Product ID" column into two separate columns for " Manufacturing Date" and "Country Code" by Text to Columns. Removed         unnecessary characters, 								
	  • Merged the "Brand Name" and "Product Name" columns into one column named "Product Brand" using the" &" function								
  5) Number Formatting:							
	• Formated the data type of the "Price" column to currency format by Right clicking to "format cells"	selected Currency					
	• Formated the "Manufacturing Date" column to display dates in the "DD-MM-YYYY " format by Right clicking to "format cells" selected         Time.(created a new column named Manufacturing date by adding Y) and inserted the 2025 year by using the formula (=G9&"2025"))
   6) Conditional Formatting:									
	• Applyed data bar  conditional formatting in the "Price" column given the format colour Red								
	• Created a custom rule for conditional formatting in the "Category" column to highlight cells where the category is "Electronics."	given red format.							

  
    						


						


