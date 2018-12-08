# US_500.csv Metadata

## Information about the US_500.csv file.

This file contains 500 randomly generated US citizens' information.


Data was downloaded December 3, 2018.


The columns in the dataset are in the table below.

Column header | Description
--------------|------------
first_name | first name of citizen
last_name | last name of citizen
company_name | name of citizen's place of employment
address | citizen's home address
city | city the citizen resides in
county | county the citizen resides in
state | state the citizen resides in
zip | zip code
phone1 | primary contact number of citizen
phone2 | secondary contact number of citizen
email | e-mail address of citizen
web | web address of company that employs the citizen


Normalizing the Data: 
I decided to contain all the data from the columns above in one table called "US" simply because there are only 12 and they can easily be combined in one table alone. Columns first_name, last_name, company_name, address, city, county, state, email, and web would be assigned the TEXT data type whereas the zip, phone1, and phone2 would be assigned the INTEGER data type. Since I would contain all the data in one table, I would have no use for primary or foreign keys.
