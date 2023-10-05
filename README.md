# Context
YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

This dataset is a daily record of the top trending YouTube videos.

Note that this dataset is a structurally improved version of this dataset (https://www.kaggle.com/datasets/datasnaek/youtube).

# Content
This dataset includes several months (and counting) of data on daily trending YouTube videos. Data is included for the US, GB, DE, CA, and FR regions (USA, Great Britain, Germany, Canada, and France, respectively), with up to 200 listed trending videos per day.

EDIT: Now includes data from RU, MX, KR, JP and IN regions (Russia, Mexico, South Korea, Japan and India respectively) over the same time period.

Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.

The data also includes a category_id field, which varies between regions. To retrieve the categories for a specific video, find it in the associated JSON. One such file is included for each of the five regions in the dataset.

For more information on specific columns in the dataset refer to the column metadata (https://www.kaggle.com/datasets/datasnaek/youtube-new/data).

# Introduction

YouTube stands as the world's foremost and most widely used video-sharing platform today. Within its vast content ecosystem, YouTube maintains a dynamic list of trending videos that undergo continuous updates. In this analysis, we employ Python alongside essential libraries like Pandas and Matplotlib to delve into a comprehensive dataset gathered over a span of 205 days. This dataset chronicles the trending videos for each of those days, comprising data on over 37,000 videos that have graced the trending section. Our objective is to extract valuable insights from this dataset, shedding light on the commonalities shared by these trending videos. Such insights can prove invaluable not only for content creators seeking to enhance the visibility and popularity of their YouTube videos but also for anyone interested in understanding the dynamics of YouTube's trending section. For this analysis, we will specifically focus on trending videos within the Indian context. 

The dataset used for this analysis is sourced from Kaggle and encompasses trending video data from multiple countries, with our examination centered on the Indian trending video landscape."

# Goals of the Analysis

### We want to answer questions like:

1. Views Analysis

* What is the average view count of trending videos, and is there a wide variation in view counts among them?
* Are trending videos more likely to have a significantly higher number of views compared to non-trending videos?
* Does a video need a substantial number of views to qualify as a trending video?

2. Likes and Comments Analysis

* How do likes and comment counts vary among trending videos? Are most of them characterized by a large number of likes and comments?
* Is there a correlation between the number of likes and comments on a video and its trending status?
* Can a video with a high number of likes or comments be more likely to trend?

3. Longest Time Trending

* Among trending videos, which video remained on the trending list for the longest duration?
* Is there a notable difference in the time duration that videos spend on the trending list?
4. Capitalized Titles

* How many trending videos have at least one fully-capitalized word in their titles?
* Does having fully-capitalized words in a video's title impact its likelihood to trend?
5. Title Length Analysis

* What is the distribution of title lengths among trending videos, and is there any relationship between title length and trending status?
* Can shorter or longer video titles be associated with a higher likelihood of trending?
6. Correlations between Attributes

* How are views, likes, dislikes, comment count, title length, and other video attributes interrelated? Are there strong correlations or dependencies between them?
* Do certain attributes tend to increase or decrease together, indicating a pattern among trending videos?
7. Common Words in Titles

* What are the most frequently occurring words in the titles of trending videos?
* Are there specific keywords or phrases that are commonly found in the titles of trending content?
8. Top Trending Channels

* Which YouTube channels have the largest number of videos that make it to the trending list?
* Is there a particular set of channels that consistently produce trending content?
9. Category Analysis

* Among various video categories (e.g., Entertainment, Gaming, Comedy), which one has the highest representation in the trending videos?
* Does the category of a video impact its chances of trending on YouTube?
10. Publication Timing Analysis

* When do trending videos tend to be published? Which days of the week and times of the day are most common for video publication?
* Does the timing of video publication have any influence on its potential to become trending?

# Libraries Used

* Pandas ( `pip install pandas` )
* Numpy ( `pip install pandas` )
* Matplotlib ( `pip install matplotlib` )
* Seaborn ( `pip install seaborn` )
* Wordcloud ( `pip install wordcloud` )
