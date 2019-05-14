# Kaggle_Music_recommendation
Kaggle_challenge at https://www.kaggle.com/c/kkbox-music-recommendation-challenge

Description/Motivation:

To build a music recommendation system to predict the chances of a user listening to a song repetitively after the first observable listening event within a time window was triggered.

Background:

Musical gatekeepers have been replaced with personalizing algorithms and unlimited streaming services. While the public’s now listening to all kinds of music, algorithms still struggle in key areas. Without enough historical data, how would an algorithm know if listeners will like a new song or a new artist? And, how would it know what songs to recommend brand new users? WSDM has challenged the Kaggle ML community to help solve these problems and build a better music recommendation system. 

Data:

The dataset is from KKBOX, Asia’s leading music streaming service, holding the world’s most comprehensive Asia-Pop music library with over 30 million tracks. KKBOX provides a training data set consists of information of the first observable listening event for each unique user-song pair within a specific time duration. Metadata of each unique user and song pair is also provided.

If there are recurring listening event(s) triggered within a month after the user’s very first observable listening event, its target is marked 1, and 0 otherwise in the training set. The same rule applies to the testing set.

The train and the test data are selected from users listening history in a given time period. The train and test sets are split based on time, and the split of public/private are based on unique user/song pairs.
