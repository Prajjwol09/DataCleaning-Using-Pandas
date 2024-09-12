Data Cleaning Project Using Pandas

This project demonstrates how to clean and preprocess a customer call list dataset using Python and the Pandas library. The primary focus is on preparing the data for analysis by removing unnecessary values, standardizing formats, handling missing values, and ensuring consistency throughout the dataset.

Project Overview:

The dataset contains customer information such as phone numbers, addresses, and preferences regarding communication. The cleaning process involves:

Stripping unwanted characters from the last names.

Cleaning and reformatting phone numbers to a standard xxx-xxx-xxxx format.

Splitting the address into separate columns (street name, state, and zip code).

Standardizing responses for customer preferences.

Handling missing values by either filling them with empty strings or dropping records.

Removing duplicates and irrelevant columns.

Steps Performed:

Importing Required Libraries:

Used pandas for data manipulation.

Loading Data:

The dataset is loaded from an Excel file.

Cleaning Last Names:

Stripped special characters (123./_) from last names using str.strip().

Cleaning and Formatting Phone Numbers:

Removed all non-alphanumeric characters from the phone number column.

Reformatted the cleaned phone numbers to the format xxx-xxx-xxxx.

Handled cases where phone numbers were missing.

Splitting the Address Column:

Split the full address into separate columns for Street Name, State, and Zip Code.

Standardizing Customer Preferences:

Converted the values in the Paying Customer and Do Not Contact columns to 'Y' (Yes) and 'N' (No).

Handling Missing Data:

Replaced missing values (NaN) with empty strings.

Removed rows where important fields, such as Phone Number, were missing.

Removing Duplicates:

Identified and removed duplicate records.

Dropping Unnecessary Columns:

Removed irrelevant columns, such as Address and Not Useful Column.

Final Dataset:

Reset the index and ensured the cleaned dataset is ready for further analysis or export.

Prerequisites

Python 

Pandas library
