# nosql-challenge
Instructions
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.
An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis.

First, I imported the libraries, such as PyMongo, pandas, and Pretty Print, for the Jupyter Notebook setup and data analysis. -With the above process, I created an environment for working with the 'uk_food' MongoDB database and the 'establishments' collection within my Jupyter notebook, allowing me to perform data analysis or manipulation tasks as needed.
Database and Jupyter Notebook Setup
Then, I imported the data provided, in the establishments.json file from my Terminal and named the database and the collection respectively as 'uk_food' and 'establishments'.
Using the query tool establishments in Dover area were deleted.
Rating value and geo location information was converted into integer for further calculations
Following questions were answered
(i) Which establishments have a hygiene score equal to 20?
(ii) Which establishments in London have a RatingValue greater than or equal to 4?
(iii) What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
(iv) How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.