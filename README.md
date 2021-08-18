# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local 
congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7

## Summary
The analysis of the election show that:
-There were 369,711 votes cast in the election
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham recieved 23.0% of the vote and "" number of votes.
    - Diana DeGette recieved 73.8% of the vote and 272.892 number of votes.
    - Raymon Anthony Doane recieved 3.1% of the vote and "" number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Challenge Overview
The Colorado Board of Elections wanted the following additional data for the election audit of the recent local congressional election:

1. Calculate the amount of votes and total percent of votes per county in the election (Jefferson County, Dever County, and Arapahoe County).
2. Calculate which of the 3 counties had the largest turnout.
3. Determine the amount of votes and total percentage of votes for each candidate in the election 
   (Charles Casper Stockham, Diana DeGette, Raymon Anthony Doane).
4. Determine which candidate won the election, the winner's vote count, and the percentage of votes for the winner.

## Challenge Summary
### Election Audit Results
1. The total number of votes for the election was determined to be 369,711 votes. The following are the votes broken down by county:
    - Jefferson: 0.1% (38,855 votes)
    - Denver: 0.8% (306,055 votes)
    - Arapahoe: 0.1% (24,801 votes)
2. According to the results above in 1., it is determined that Denver County had the highest voter turnout with 306,055 voters.
3. The total number of votes for the election was determined to be 369,711 votes. The following are the votes broken down by candidate:
    - Charles Casper Stockham: 23.0% (85,213 votes)
    - Diana DeGette: 73.8 (272,892 votes)
    - Raymon Anthony Doane: 3.1% (11,606 votes)
4. According to the results in 3., the winner of the election was Diana DeGette with a total vote count of 272,892, which was 73.8% of
   the total votes.

### Election Audit Summary
The python code used can be used for any election needed by altering the code. One way this can be done is by simply changing the .csv file
to have the same information used in this .csv file for any other election no matter the size since it utilized a for loop based on the total
number of votes. Also, this code can be changed slightly to allow it to utilize a vast amount of .csv files with election data. The .csv file path
will need to be changed and slight code changes will likely be needed depending on the format of the new .csv file.
