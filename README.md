# Context
YouTube (the world-famous video-sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangnam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

This dataset is a daily record of the top trending YouTube videos.

Note that this dataset is a structurally improved version of this dataset (https://www.kaggle.com/datasets/datasnaek/youtube).

# Content
This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included for the US, GB, DE, CA, and FR regions (USA, Great Britain, Germany, Canada, and France, respectively), with up to 200 listed trending videos per day.

EDIT: Now includes data from RU, MX, KR, JP, and IN regions (Russia, Mexico, South Korea, Japan, and India respectively) over the same time period.

Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.

The data also includes a category_id field, which varies between regions. To retrieve the categories for a specific video, find it in the associated JSON. One such file is included for each of the five regions in the dataset.

For more information on specific columns in the dataset refer to the column metadata (https://www.kaggle.com/datasets/datasnaek/youtube-new/data).

# Introduction

YouTube stands as the world's foremost and most widely used video-sharing platform today. Within its vast content ecosystem, YouTube maintains a dynamic list of trending videos that undergo continuous updates. In this analysis, we employ Python alongside essential libraries like Pandas and Matplotlib to delve into a comprehensive dataset gathered over a span of 205 days. This dataset chronicles the trending videos for each of those days, comprising data on over 40,000 videos that have graced the trending section. Our objective is to extract valuable insights from this dataset, shedding light on the commonalities shared by these trending videos. Such insights can prove invaluable not only for content creators seeking to enhance the visibility and popularity of their YouTube videos but also for anyone interested in understanding the dynamics of YouTube's trending section. For this analysis, we will specifically focus on trending videos within the US context. 

The dataset used for this analysis is sourced from Kaggle and encompasses trending video data from multiple countries, with our examination centered on the US trending video landscape."

# Goals of the Analysis

### We want to answer questions like:

* How many views do our trending videos have? Do most of them have a large number of views? Is having a large number of views required for a video to become trending?
* The same questions above, but applied to likes and comment count instead of views.
* Which video remained the most on the trending-videos list?
* How many trending videos contain a fully-capitalized word in their titles?
* What are the lengths of trending video titles? Is this length related to the video becoming trendy?
* How do views, likes, dislikes, comment count, title length, and other attributes correlate with (relate to) each other? How are they connected?
* What are the most common words in trending video titles?
* Which YouTube channels have the largest number of trending videos?
* Which video category (e.g. Entertainment, Gaming, Comedy, etc.) has the largest number of trending videos?
* When were trending videos published? On which days of the week? at which times of the day?

# Libraries Used

* Pandas ( `pip install pandas` )
* Numpy ( `pip install pandas` )
* Matplotlib ( `pip install matplotlib` )
* Seaborn ( `pip install seaborn` )
* Wordcloud ( `pip install wordcloud` )

#Link Kaggle of dataset: https://www.kaggle.com/datasets/datasnaek/youtube-new
