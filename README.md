# Data-Science-Project
## Movie Release
### Overview
Your team has been hired by a media company that wants to understand the discussions currently happening around the film “(insert a recently-released movie that your team selected here)”. They have indicated that they are especially concerned with the favorability of the audience response. Specifically, they want to know:
1. The salient topics discussed around their film and what each topic primarily concerns
2. Relative engagement with those topics
3. How positive/negative the response to the movie has been

You will conduct this analysis and submit a report discussing your findings.

### Analysis Details

Your analysis will draw on Twitter posts (tweets). To inform your analysis, you should collect 1,000 tweets within a 3 day window. You should set filters such that all 1,000 posts have a very high likelihood of being related to the movie AND all are in English (ensure that the language field is set to “en”... this isn’t exact, but it gets close). You can filter by hashtags or words when collecting Twitter data. You can choose the exact words, as long as they are related to the context that we mentioned before.

Each tweet in your collection should be unique – meaning that you shouldn’t include an identical tweet or retweet twice.
To develop your topics, conduct an open coding on 200 tweets (approach the exercise requiring each tweet to belong to exactly one topic). You should aim for between 3-8 topics in total.

Once your topics have been designed, manually annotate the entire set of the 1,000 tweets in your dataset. During this annotation, also code them for positive/neutral/negative sentiment. While double annotation would usually be used, for this project (given time constraints), use single annotation.
Characterize your topics by computing the 10 words in each category with the highest tf-idf scores (to compute inverse document frequency, use all 1,000 posts that you originally collected.
