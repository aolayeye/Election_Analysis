# Election_Analysis
## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local
congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.1, Visual Studio Code, 1.56.0

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane
#### The candidate results were:
- Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
- Diana DeGette received 73.8% of the vote and 272,892 number of votes.
- Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
#### The winner of the election was:
- Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Overview of Election Audit
### This section provides insight into the the purpose of this election audit analysis.
The purpose of this analysis is to audit the tabulated results for a US congressional precinct in Colorado. This analysis will provide data on the following:
  - The voter turnout for each county
  - The percentage of votes from each county out of the total count
  - The county with the highest turnout
Working from the data source: election_results.csv file, this analysis utilized for loops and conditional statements with membership and logical operators to find the requested results. Then, printed the results to the command line and saved them to an election_results.txt file.

#### Control Flow
1. Add our dependenies
2. Add variables to load and save our source and target files respectively
3. Initialize a total votes counter variable
4. Create empty lists to hold each county and each candidate
5. Create empty dictionary to hold candidate votes and county votes
6. Declare variables to track the winning candidate, vote count and percentage
7. Declare variables to track the largest county and county voter turnout.
8. Using the csv.reader method, read the source file and convert it into a list of dictionaries to fetch candidate name, county name, and vote count for candiatate and county
9. Open the target file and save the election results
10. Write a for loop to get the count from the county dictionary.
11. Calculate the percentage of votes for the county
12. Print the county results to the terminal and save to the target text file.
13. Write an if statement to determine the winning county and get its vote count.
14. Print the county with the largest turnout to the terminal and save to the target text file.
15. Using csv's write method, save the final candidate vote count to the text file.
16. Using an if statement, determine winning vote count, winning percentage, and candidate.
### Election-Audit Results
  - There were 369,711 votes cast in this congressional election
##### Candidate Results
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes won the election
##### County Results
  - The county with the largest turnout was Denver
  - Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

![Largest_County_Turnout](https://user-images.githubusercontent.com/67847583/117727317-7b3d3700-b1ad-11eb-8bf3-d120a2a240b7.png)


### Election-Audit Summary
  - In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
