# Election Analysis

## Election Audit Project Overview
A Colorado Board of Elections employee recently gave me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a list of the counties where votes were cast.
3. Calculate the total number of votes, and the percentage of votes for each county.
4. Determine which county had the largest voter turnout.
5. Get a complete list of candidates who received votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

### Resources
+ Data Source: election_results.csv
+ Software: Python 3.6.1, Visual Studio Code, 1.38.1

### Election Summary
The analysis of the election shows that:
+ There were 369,711 votes cast in the election.

The counties where votes were counted:
+ Arapahoe
+ Denver
+ Jefferson

The county results were:
+ Arapahoe County received 6.7% of the vote and 24,801 votes.
+ Denver County received 82.8% of the vote and 306,055 votes.
+ Jefferson County received 10.5% of the vote and 38,855 votes.

The county with the largest voter turnout:
+ Denver, which received 82.8% of the vote and 306,055 votes.
 
The candidates were:
+ Charles Casper Stockham
+ Diana DeGette
+ Raymon Anthony Doane  

The candidate results were:
+ Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
+ Diane DeGette received 73.8% of the vote and 272,892 votes.
+ Raymon Anthony Doane received 3.1% of the vote and 11,606 votes. 
 
The winner of the election was:
+ Diana DeGette, who received 73.8% of the vote and 272,892 votes.

![image](https://user-images.githubusercontent.com/113741694/212165958-1f0d26c6-1e32-43ec-a48b-3e4a5668a75b.png)
  
 ## Election Audit Summary
 + This script would be useful to analyze future elections because none of the variables are state or city specific.  As long as the CSV files are formatted the same way (ballot ID, county, candidate) this script can be used.  In the event that the formatting is a little different, an experienced analyst could easily modify this code to extract the relevant information.
 + This script could be modified to include the breakdown of the election results by indidvidual counties.  This information would enable the Board of Elections to see which parts of a county has low voter turnout so that voter registration drives can be focused on those areas.
 
 
 
