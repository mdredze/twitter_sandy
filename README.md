twitter_sandy
=============

This is the Hurricane Sandy Twitter dataset. Details on the dataset can be found in the following paper.

Haoyu Wang, Eduard Hovy, Mark Dredze. The Hurricane Sandy Twitter Corpus. AAAI Workshop on the World Wide Web and Public Health Intelligence, 2015.

Please use this citation if you use the dataset.

File Format
==========
Due to Twitter's terms of service, we can only release the tweet ids.

Each line of the data contains three fields separated by <tab>. The first field is the ID of the tweet, the second field is the time stamp of the tweet, and the third field indicates whether the tweet contains word "sandy". The original tweets can be obtained by using the search API from Twitter to fire up queries according to the ID of the tweet. The fields can be used to filter tweets ahead of time, e.g. only pull tweets that contain the word "sandy."
