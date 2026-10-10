# customer-call-list-cleaning
My first pandas data cleaning project, messy Excel in, clean CSV out.
# customer-call-list-cleaning

My very first pandas data cleaning project. The result is a cleaned version of the initial Excel file in .csv format.

## Initial issues
The initial data had various issues, namely:
- Duplicate rows
- Inappropriate special characters in the last name column(/, _, .)
- Inconsistent phone numbers(123/643/9775, 876|678|3469)
- Combination of information in one column (address)
- Inconsistent case in columns with yes/no values (Yes/NO)
- Missing values

## Actions performed

The following data cleaning actions were performed:
- Duplicates and unnecessary columns were removed
- The last name column was cleaned
- All phone numbers were standardized to one format (123-456-7890)
- The address was split into the street, state, and ZIP code
- Columns with values Y/N were standardized
- All customers with a Do Not Contact flag were removed, as well as all rows with missing phone numbers



## Attached files
- projectv2.ipynb - the notebook with the code
- Customer Call List.xlsx - the initial data
- cleaned_customer_list.csv - the result of the data cleaning

## How to use
- To use the notebook, upload the excel file to Google Colab and execute the cells from top to bottom.

## Technologies
- The project was created in Python with the Pandas library in Google Colab.

## Credits
- The dataset was taken from Alex The Analyst Pandas series. The cleaning code is mine.
