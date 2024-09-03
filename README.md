# This task we going to clean the country column and parse the data column
## Import and Install the Libraries on Jupyter Notebook
>import numpy as np
>import pandas as pd
>from fuzzywuzzy import process
### Load the data
first five observation
Look all unique values in the 'country' column
Convert the column to lower case
Remove any trailing white spaces
There should be only three separate countries
Eliminate all variations, so that South Africa, UK and US are only three countries

List of standardized country names
Apply the function to the 'country' column
Filter the Dataframe to include only the three countries
Verify the change 

Create a new column called 'days_ago' in the Dataframe that is copy of the 'date_measured' column
Dataframe for demonstration
Convert date_measured to datetime
Get the current date
Calculate the difference in days and create the new column
Verify the new column
