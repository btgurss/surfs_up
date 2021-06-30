# Surfs_up

## Overview
This analysis was done to determine if a surf shop should open up in the state of Hawaii. W. Avy wanted to know the weather patterns of the area to know if his surf and ice cream shop would be sustainable year round.  To do this, I used Pandas and SQLAlchemy to download and anaylze the weather (given to me in a sqlite file).  After the file was imported into Pandas I was able to call the SQLAlchemy functions and methods to organize and query the information that was needed.  W. Avy specifically wanted temperatures from the months of June and December.  I decided to look up the precipitation averages during these months as well.

## Results
Here is my analysis of the obtained results:
- The average temperature is warmer in June than in December.  This average temperature, however, was only different by about 4 degrees Fahrenheit.
- The larger difference in the temperature resides in the minimum amounts.  The June minimum was 64 degrees while the December minimum dropped to 56.  The maximum temperatures were 85 (June) and 83 (December).  I would hypotesize, from this information, that the temperature in June is not very different than the temperature in December.
- The average rainfall amount from June to December was quite a bit different.  June had an average of .13 inches, while December had an average of about .21 inches.

## Summary
I would advise W. Avy that the temperature differences between June and December are not significant enough to deter people from suring and ice cream.  If he thinks warm weather is what is needed for the shop to be successful, than he should invest in the store.  I would, however, let him know to be cautious of rain patterns.  The data tells me that December has almost twice as much rain.  If W. Avy was worried about the rainfall, I would suggest looking back at the data and organizing in a way that shows time of rainfall as well as where most of the rainfall took place.  

