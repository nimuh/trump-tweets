# Twitter on Trump
Twitter has become one of the largest social media platforms and has millions have people using it on a daily basis. One of these users is our current president, Donald Trump. Given the degree to which the POTUS makes use of this platform it can make one wonder what other users are saying about him. This project aims to explore a sample of tweets to understand what people are saying about Trump.

## Tweets By Location
The first portion of this project looked at what people were saying depending on their location. The tweets are filtered to contain only users from the United States. All tweets are then grouped by state and each state is given its own topic model. With a topic model for each state the topics discussed in each group of tweets is extracted by looking at the highest weighted words contributing to a topic. For example, Indiana (IN) consisted of topics containing words such as 'lyin donnie' and 'fecal matter' while Michigan (MI) consisted of words like 'lofty lib' and 'lib goofs'. Thus, it seems that twitter users from Indiana may be more against Trump while users from Michigan may be more for Trump. 

## Types of Users
The second portion of this project aims to try to understand who the users are that sent tweets to Trump. The data pulled from Twitter comes with a feature that contains user information. The unique users are determined and then each of these user's twitter bios are clustered and then visualized in two dimensions by using t-SNE. Given the high variability in words users use for twitter bios, the clusters were not very informative or did it display any clear 'user types'.

## Conclusion
The results of this exploration provided some insight into twitter user opinions on Trump, but there are some issues. One, the data consisted of approximately 40K tweets from U.S. users containing Trump's twitter handle and this was the only filter used. The reason for the limited sample size was the limited calls that could be made to the Twitter API and the fact that not all users that criticize Trump put his handle in the tweet. Two, not all states were represented equally. Some states consisted of a few tweets while other states consisted of hundreds of tweets, which results in not having a sufficient amount of samples to represent the overall opinion of twitter users for each state. Thus, to better improve results would mean to consistently pull tweets using more complex filters and to have more samples representing each state.
