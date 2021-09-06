# Election_Analysis

## Project Overview
A Colorado Board of Election employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Geat a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentagge of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.7, Visual Studio Code, 1.38.1

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Chales Casper Stockham
  - Diana Degette
  - Raymon Anthony Doane
- The candidate results were:
  - Chales Casper Stockham received 23.0% of the vote and 85,213 votes
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- The winner of the election was:
  - Diana DeGette: 73.8% (272,892)

## Overview of Election Audit
* This election audit has been commissioned by the Colorodo Board of Elections to develop automations in the tabulation of votes for future local, congressional, and senatorial elections. 

## Election-Audit Results

* How many votes were cast in this congressional election? - 369,711 votes were cast. 
* 
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)
  
* Which county had the largest number of votes? - Denver had the largest number of votes. 
* 
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  * Charles Casper Stockham: 23.0% (85,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606)
  
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  * Diana DeGette: 73.8% (272,892)

## Election-Audit Summary
This script was able to analyis and create a document showing the winner, vote count, and percentage of votes for over 370,000 voters in this election. Future applications would be able to quickly and reliably tabulate smaller elecitons in the thousands or state wide elections in the millions. 
  * To use for future elections, the variables, lists, and dictionaries referencing the county coloumn would need to be adjusted. This could reference districts for state senetorial elections or congressional districts for state wide elections. 
  * Additionally political party is an important category and should be added. This one chategory is important for public funding, presdential ballots, and popularity analysis. 
