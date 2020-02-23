# Ramen Ratings

## Context: 

The Ramen Rater is a product review website for the hardcore ramen enthusiast (or "ramenphile"), with over 2500 reviews to date.
This dataset is an export of "The Big List" (of reviews), converted to a CSV format.

## Content:

Each record in the dataset is a single ramen product review. Review numbers are contiguous: more recently reviewed ramen varieties have 
higher numbers. Brand, Variety (the product name), Country, and Style (Cup? Bowl? Tray?) are pretty self-explanatory. Stars indicate the 
ramen quality, as assessed by the reviewer, on a 5-point scale; this is the most important column in the dataset!

## Dropping Top Ten Column:

By using ***missingno*** library vizualizing data frame after loading by using pandas **read_csv()** function by interpreting tha data set 
we can drop the column Top Ten because it atmost contains **NAN** values.

## Checking for NA and Imputting data: 

After dropping Top Ten column checking for na values by using **isnull().sum()** and there are two na values in Style column, so imputting
the null data with style of **Pack** beacause it is most popular style of ramen in this dataset.

