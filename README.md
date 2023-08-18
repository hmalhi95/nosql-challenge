# NoSQL Challenge

## Database and Jupyter Notebook Set Up
I imported the data provided in the establishments.json file from Terminal and named the database uk_food and the collection establishments.

## Update the Database
- I wrote a Python script in the notebook to update the database with a new halal restaurant- "Penang Flavours" that just openned in Greenwich and modfiy its Business Type ID, this allowed for this restaurant to be included in the analysis
- I also used the Python script to remove any restaurants in Dover from the database
- Lastly, I used the script to update some number values that were stored as strings and change them to integers/decimals

## Exploratory Analysis
- I was able to identify establishments that have a hygiene score equal to 20
- I was able to identify establishments in London that have a RatingValue greater than or equal to 4
- I was able to identify the top 5 establishments with a RatingValue of 5 that were nearest to the new restaurant that was added, "Penang Flavours" - - I also sorted them by lowest hygiene scores
- Lastly, I identified the establishments in each Local Authority area that had a hygiene score of 0 - I sorted the results from highest to lowest
