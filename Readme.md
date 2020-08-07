# About the project:
# this project is about the review gathered from the amazon site using webscrapping,beautiful soup which is the html parser. 1.gathered the reviews,stars,and name using scrapping. 2.using the pandas library made a data frame. 3.did the sentimental analysis found the polarity and subjectivity. 4.added to the data frame. 5.did the data visualization and found out the conclusion
# 3.SCRAPPING THROUGH THE AMAZON SITE
# Here we are scrapping the reviews of each customer who has given the reviews on the amazon site and appending it into the list using the for loop.
# Polarity:-polarity of the given text data tells us the how positive the statement is .it varies from -1 to 1,
# LESS THAN '0' POLARITY DENOTES NEGATIVE STATEMENT.
# MORE THAN '0' POLARITY DENOTES POSITIVE STATEMENT.
# '0' DENOTES THE NEUTRAL STATEMENT
# SUBJECTIVITY:- the quality of being based on or influenced by personal feelings, tastes, or opinions.
# 6.now a function score is made in which it returns the negative when polarity less than 0 ,neutral whrn polarity=0
# and positive when more than 0
# create a function to add a column in dataframe that is satisaction in which when star<3 then "not satisfied". when star=3 then "partially satisfied" and when star>3 then "Full satisfaction".
# from the above report we got into the conclusion that most of the customers have given positive reviews.
# so it is recomended to buy the phone
