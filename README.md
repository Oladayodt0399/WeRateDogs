# WeRateDogs Data Wrangling and Analysis

## Tasks
This project focused on the wrangling of WeRateDogs tweet data and to determine the objectivities of the their rating system and also people reaction to their ratings. Data was gathered from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. Wrangling efforts was documented, plus showcase them through analyses and visualizations.


## Wrangling Effort
The data was gathered from three sources, the main dataset is twitter-archive-enhanced dataset, this can be found [Here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/59a4e958_twitter-archive-enhanced/twitter-archive-enhanced). Second dataset is image prediction dataset that contains the tweet image URL and the predictions [Here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv). The third data which contains **tweet favorite_count** and **retweet_count** was gathered by query WeRateDogs using Tweepy library via Twitter API.

Data assessment was done visually and programmatically and many qualities and tidiness issues were identified and documented. Data cleaning was done programmatically using pandas method and functions. 


## Insight
- **Reaction of WeRateDogs followers to the rating system**: peoples likes/favorite increase a the rating is increasing, there was an indication that people like WeRateDogs rating system.

- The second insight: **top retweeted dogs rating**, this is to **rank WeRateDogs followers retweet by the rating to see the rating categories that was mostly accepted by the followers**. The highest retweeted rating was 13/10 followed by 12/10 and 11/10. The three least rated retweets were 2/10, 11.27/10 and 11.26/10.

- The third insight: **top beloved dog stages out of doggo, pupper, puppo and floofer**. The analysis revealed pupper as the most liked dog with 1,259,041 likes, followed by doggo 1,047,829 likes and puppo 450,614 likes.

- The last insight: **most favorite breed of dogs**. The analysis shows that the most favorite breed of dogs was golden_retriever followed by labrador_retriever and pembroke.
