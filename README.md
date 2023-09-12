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
Cleaned the dataframe by removing the staff_pic, spotlight, category & subcategory
