# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following task to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.5, Visual Studio Code, 1.62.3

## Summary
The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received "23%" of the vote and "85,213" number of votes.
  - Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
  - Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
- The winner of the election was:
  - Diana DeGette, who received "73.8%" of the vote and "272,892" number of votes.
    
## Challenge Overview

### Purpose

The purpose of this election audit analysis was to determine the winner of a local congressional election in Colorado.

### Results
- How many votes were cast in this congressional election?

A total of 369,711 votes were cast in this congressional election.

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![countyvotes.png](https://github.com/Athenus/Election_Analysis/blob/main/Resources/countyvotes.png)

- Which county had the largest number of votes?

Denver county had the largest number of votes.

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

![candidatevotes.png](https://github.com/Athenus/Election_Analysis/blob/main/Resources/candidatevotes.png)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

The winner of the election was Diana DeGette. She won with 272,892 votes, or 73.8% of the total votes.

# Challenge Summary

With a few modifications, this code can be used for any election. The CSV file for other elections would need to be formatted the same, with "County" being in the second column and "Candidate" being in the third column. The number of candidates or counties should not interfere with the code. The code could be changed to include states instead of counties if the election is on a larger scale by replacing "County" with "State". Likewise, if the election is on a smaller scale, such as a county election, "County" could be replaced by "City".

