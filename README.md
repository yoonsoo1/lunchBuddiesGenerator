# Lunch Buddies Generator
This is an automatic generator to create random matches between a group of members in an organization.

## What is it used for?
This was used to generate random matches for weekly lunch buddies for a school's social organization. \
\
It can be used to generate weekly coffee chats, lunch buddies, or even speed dates! 

## Methodolgy
I used a modified version of the Gale-Shapley matching algorithm to generate a random pair for each week's lunch buddies.

## How to use it:
1) Change out the "path" to point to LunchBuds.xlsx in your local directory 
2) Change the LunchBuds.xlsx to add all the current eboard members at the top and the rest below 
3) Change out the eboards array in line 24 

## Conditions:
1) Eboard should not be matched with another eboard
  => Must specify the list of current Eboards in the lunchBuds.py file
2) Should not match two people that have been matched previously
  => This is done automatically

## Note
** \
Note that the generation does not guarantee a perfect match each time so there may be runtime errors \
In that case, just run it again. \
** 

