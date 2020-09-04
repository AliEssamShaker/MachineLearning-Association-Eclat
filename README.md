# MachineLearning-Association-Eclat

Association Rule Learning Eclat intuition:-

Unlike in the Apriori algorithm, the Eclat algorithm only has a Support.

E.g  movie recommendation:     Support(M) =  #user watchlists containing M/#user watchlists

Since we are only looking at Support it does not make since to look at one movie by itself. The M here stands for a set of movies, and using the Support(M) we are looking at how frequently does a set of items occur.

How the Eclat algorithm work:

Step 1) Set a minimum support.
Step 2) Take all the subsets in transactions having higher support than minimum support.
Step 3) Sort these subsets by decreasing support. (Having the best results at the top).

Therefore, in short, the Eclat is pretty much Apriori without the Confidence and the lift factors.

