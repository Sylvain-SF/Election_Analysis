# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
 - Data Source: election_results.csv
 - Software: Python 3.6.1, Visual Studio Code 1.38.1

 ## Overview of Election Audit
 
In this audit, we analysed the total votes casted, then the numbers of votes by county as well as the numbers of votes by candidate. 
We also find out the largest county turnout and to finish the winner of the elections.

- There was 369,711 votes casted in this election.
- County votes and percentages:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- Largest County Turnout: Denver
- Candidate votes and percentages:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- The winner is Diana DeGette with a winning vote count of 272,892 (73.8%).

 ## Election Audit Summary 
 
This script is flexible for any elections as long as the dataset come into a csv format with the same headers.<br>
It can be modified to work with similar format like tsv.
With minor adjustment it could analyse cities or states elections.


 