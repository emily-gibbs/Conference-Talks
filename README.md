Resources related to talks that I have given at meetups, conferences, etc. 

## *The Developer and the Data Scientist*

## *Entity Resolution – A ML Approach for When df.drop_duplicates() Isn’t Enough*

This talk was given to the St. Louis ML and Data Science Meetup.

**Description**:

If you take a pandas tutorial, you might think that all of your duplicate data problems can always be fixed with a quick call to df.drop_duplicates(). However, in real-world datasets the data has often come from a wide range of disparate sources and can contain multiple references to the same entity which are not quite the same. A typo here, a different way of writing an address there, and it can quickly become a nightmare to deduplicate. Sure, you can try to create rules to catch some of the most common differences, but the magnitude of variations is often beyond the reach of rules alone. Fortunately, a rules-based approach is not your only option… 
In this presentation we will walk through:
•	The importance of entity resolution (ER) and some of its applications and challenges
•	An overview of common steps involved in the ER process
•	A deep-dive into a real-world example utilizing the helpful RecordLinkage Python library

