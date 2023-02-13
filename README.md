# lunchBuddiesGenerator

This is an automated matching generator for lunch buddies.

How to use it:
1) Change out the "path" to point to LunchBuds.xlsx in your local directory
2) Change the LunchBuds.xlsx to add all the current eboard members at the top and the rest below
3) Change out the eboards array in line 24

** 
Note that the generation does not guarantee a perfect match each time so there may be runtime errors
In that case, just run it again.
**


Conditions:
1) Eboard should not be matched with another eboard
  => Must add to the list of Eboards in the .py file
2) Should match two people that have been matched previously
  => This is done automatically
