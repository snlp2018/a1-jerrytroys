# SNLP Assignment 1

This project made use of the tweepy library to interface with the twitter API. The tweets were obtained by creating a stream seeded by keywords (the keywords being the ten most frequent Thai words). Given the Thai languages lack of similarity to other languages this already seemed to function well for harvesting only Thai tweets, but as an extra measure the program also filtered for only tweets where twitter had already tagged the language as Thai. The number of tweets too short to be recorded was extremely small, about 0.015%. 
