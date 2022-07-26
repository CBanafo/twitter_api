# Wrangling Twitter's Api

*Real world data as described by most data driven professionals simply implies it rarely comes clean. The project involved in this case comes with three main data sets, the **twitter_archive_enhanced.csv** , **image_predictions.tsv** and an additional data from **twitter’s api** specificaly from a popular dog rating twitter account called WeRateDogs(**@dogs_rates**) which is to be saved in the form of a txt file were used. This wrangling process involved three main steps: Gathering, Assessing and Cleaning of the data. Other phases included storing and exploration of the data as well.*

![WeRateDogs](https://d34zrgnx1tq8w.cloudfront.net/564277/uploads/4cd4a820-9f83-11ec-b6a3-4bf447759056_800_420.png)

## Gathering the Data
*The twitter_archive_enhanced.csv file was presented for the project within the Udacity classroom which was downloaded manually. As is mostly known, this data was in short both dirty and messy and hence required a great deal of skills to get it to the desired format. A link was provided to download the image_predictions .tsv file to be used. This data as well came with its own Issues as well. The final chunk of data was that from the “twitter api”. During this phase, I had to sign up as a developer on twitter’s website to be able to get access to twitters api keys. During the application process, there were some letters and confirmations involved as well. In the course of requesting for the required data from this api however, Issues related to **Rate Limit Reached** was encountered hence had to use the api data provided in the classroom in the form of **tweet_json.txt** as the **api** requested since waiting for the response after the rate limit was reached was taking too long.*

## Accessing the Data
*During this phase of the project, attempts were made to gather all possible Issues within each of the datasets provided. Assessment of the data were group into two main types;**Quality** and **Tidy** issues. Issues related to the quality of the dataset involved issues with completeness which dealt with the wholeness of the data, Validity in terms of having the right info at the right place. It would be worth noting that, a value may be accurate but not valid, Accuracy as in representing the correct values and
Consistency which deals more with how the data conforms with those within the dataset.
There were more than 15 issues discovered with a majority of them being related to the quality of the data. It was also discovered most of the Issues were present within the “twitter_archive_enhanced.csv” file and the “image_predictions.tsv” file.*

## Cleaning the Data
*This phase of the project involved 3 main steps, Defining the steps involved in solving the issue discovered, Codingwhich was laying down the steps defined in the form of codes and Testing the codes to ensure it does what is required of it. Before cleaning the data however, the structural (Tidiness) issues were dealt with first (not an obligation) before the quality Issues as this avoids repetitions in most cases and is mostly recommended as well.*

## Storing the Data
*The cleaned data was saved in the form of a csv file with the name “twitter_archive_master.csv”. A copy of the cleaned data was made to work with for the analysis process as well.*

## Analysis on data
*Insights on the following were generated:*
> * *Most popular dogstages and the ratings associated with them*
> * *Most common likes a tweet is likely to receive*
> * *The relation between the number of likes and the retweet counts for tweets*

![twitter](https://media.kasperskydaily.com/wp-content/uploads/sites/92/2020/02/12095616/twitter-privacy-security-featured.jpg)