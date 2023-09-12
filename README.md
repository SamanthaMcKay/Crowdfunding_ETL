# Crowdfunding_ETL
Project 2

Imported dependencies.
Read the data in from the excel.

Queried the datatypes for each column in the crowdfunding data.

Pull the column names and split the "category & subcategory: column into two separate columns named "category" and "subcategory".
Found and printed the unique values in category and subcategory and stored the values into their respective variables.
Queried the number of unique values in categories and subcategories.

Created numpy arrays for categories and subcategories. 
Concatenated the category identifiers and subcategory identifiers and stored them as variables cat_id and subcat_id.
Created category and subcategory dataframes with their respective ids that were created above.

![image](https://github.com/SamanthaMcKay/Crowdfunding_ETL/assets/132176159/73cb10b8-9210-4783-9e9a-9c70a7864aac)

![image](https://github.com/SamanthaMcKay/Crowdfunding_ETL/assets/132176159/9a7a0ef3-5367-4821-91e8-6eab6b5bf01f)

Exported the category and subcategory dataframes to csvs.

Made a copy of the crowdfunding dataframe and renamed the blurb, launched_at, and deadline columns.
Converted the goal and pledged columns to datatype float and the launch_date and end_date to datetime format.

Merged the category and subcategory dataframes to copied dataframe to incorporate the cat_id and subcat_id columns.
Cleaned the dataframe by removing the staff_pic, spotlight, category & subcategory, category, and subcategory columns.
Exported campaign to a CSV. 

Read in the contacts excel and used the Pandas method to create the contacts dataframe
Converted the contacts list to a dictionary and split the name column into first_name and last_name.
Reordered the columns and exported to a csv.

Used Quick DBD to sketch and ERD.

![image](https://github.com/SamanthaMcKay/Crowdfunding_ETL/assets/132176159/d1d1e16e-62ae-4511-8168-9a7248c67cee)

Used the exported schema to create the crowdfunding_db and tables, imported the four CSVs into their respective tables and queried each with a SELECT * statement to verify they imported correctly and could be queried.

See the Database_verification folder.
