# Miniproject_4

Hi. This project was a hard one for me. Dirty data is a pain to work with, but anyway, here it is.

## Description:
This time, the data has the following structure:

- recorded for each user who made purchases, every day
- for each date, there is a separate folder, inside it – folders for each user
- inside each folder, there is a file data.csv, where the data is stored 

Schematically, it looks like this:


<img width="400" alt="image" src="https://github.com/Horiz0nT/Miniproject_4/assets/123100055/1cdad4b2-5b7c-416a-a8b3-957473ddf2f1">


For example, on December 30th, three customers made purchases, and on the 31st – two (folders 2020-12-30 and 2020-12-31 respectively). Since the customer FirstName_LastName1 bought goods on both days, there is a folder for him in the folder for each of these dates. For other customers – one each.

## Tasks:

- Collect all the data from the "data" folder into a single dataframe, having the following columns: columns from the files themselves (product_id, quantity), as well as the username (name), and the date of these purchases (date), corresponding to the name of the folder where the user's folder is located.
- Find out which user bought the most products. If there are several, list the names in alphabetical order, separated by a comma and a space.
- Find the top 10 products by the number of units sold over time and create a bar plot. How many units of the product with product_id==56 were sold?
- Visualize sales by days.
- How many users have purchased any product more than once (repeatedly)? A repeat will be considered as the purchase of a product with the same product_id, made on different days.
