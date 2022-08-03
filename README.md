# Election Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the voter turnout for each county.
7. Calculate the percentage of votes from each county out of the total count.
8. Determine the county with the highest turnout.

## Resources
- Data Source: [election_results.csv](./Resources/election_results.csv)
- Software: Python 3.7.13, Visual Studio Code, 1.69.2

## Election-Audit Results
The [analysis](./analysis/election_results.txt) of the election show that:
- There were 369,711 votes cast in the election.
- The county results were:
  - Jefferson county received 10.5% of the vote and 38,855 number of votes.
  - Denver county received 82.8% of the vote and 306,055 number of votes.
  - Arapahoe coutny received 6.7% of the vote and 24,801 number of votes.
- The county with the largest voter turnout was:
  - Denver with 82.8% of the vote and 306,055 number of votes.
- The candidate results were:
  - Candidate Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Candidate Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Candidate Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Candidate Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary
Using this python script, any election can be counted as the code uses lists and dictionaries. These mutable data types allow us to count the votes for any reasonable amount of candiates and counties.

Additionally, with some modification more information could be analyzed. Currently the script  is limited to accepting data that is formatted in three columns, but functionality could be added to accept files of varying column counts by searching for the relevant columns using the index() function when reading in the header list. Because of this it is also possible to modify the script to count different information and even calculate more advanced metrics.
