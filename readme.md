# (TMDB Dataset Exploration)
## by (Abdelrahman Ragab)


## Dataset

> I used the 2015 TNDB Movies Dataset from Kaggle 

>it has 5106 after cleaning Movies in this dataset With 21 featuers

>most of the featuers are numeric exactly 11 and 10 are categorical.

>the data types are 6 integers , 4 floats , 1 date , 10 Strings.

>For the Cleaning part first of all i changed the data types of for columns to integers to make them easier to work with I aslo removed the nulls and removed the duplicated valus aslo I removed the negtive revenue values



## Summary of Findings

>I wanted to discover the budget and revenue and if there was a relation btwwen them so:

>1- check for the budget in a normal Histgram and a log scale Hist and found out the budget range.Ifound out that there there is a Range for the budget on from 10M to 100M.

>2- check for the revenue in a normal Histgram and a log scale Histgram and found out the revenue range.I found out that the revenue range btween 100B to 1B.

>I wanted two know what year has the most movies also what is the standerd runtime so:

> 1- I made a count plot for the release year to know what is the Most year that had movies into it.I found out that the year was 2011.

> 2- I made a count plot to Know what is the most commen runtime for the movies.I found out that the most was 90 min and 120 min.

>I wanted to check for outlires in revenue to make the plots more noraml so I made a box plot to remove the outliers from the revenue.I found out there were outliers from above 1.5B.

>I wanted to discover what are the most geners getting revenue so I made a bar plot for the top 10 geners geting mony in the dataset. I found out that Action and Adventure have the most revenue of all time

>I wanted to check the Correlation for the bivriante plots so I made a PairGrid to check the Correlation btween the featuers in more visual way. I found out that the featurs of intrest have the most corroelation.

>I wanted to check the change in budget and revenue so I made a 2 varibles box plot to know the revenue and budget for each year and get the max.I found out that there increasd to much.

>I wanted to see the ralation btween varibels like vote_count and popularity and release year so I made 4 scatter plots to check the Correlation btween variables.I found out that there is a postive relation btween them

>10-I wanted to here to check the change of budegt with revnue and popularity and vote_cout throw out the years so I made 2 point plots to check the relation btween three variables.I found out that from the year 2010 that budget and revenue increasd alot

>11- I  Wanted to know the relation btween runtime and votes throw out the years so I made a Implot to check the relation btween three variables.I found out that it does not affect that much.

## Key Insights for Presentation

> The presentaion is about the Revenue and Budegt and How to understand them in the Movies industry from many points of view.
> I added here 4 explanatory plots a budget histgram , a revenue histgram , a scatter plot btween budget and reveunu and a Implot btween budget and revenue and realse_year 