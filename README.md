# Election Analysis

## Overview of Election Audit

A Colorado Board of Elections employee has requested information to complete an
election audit of a recent local congressional election.
* Calculate the total number of votes cast.
* Get a complete list of candidates who received votes.
* Calculate the total number of votes each candidate received.
* Calculate the percentage of votes each candidate won.
* Determine the winner of the election based on popular vote.

Following the initial results delivery, the election commission requested
additional data to complete the audit to include:
* Voter turnout for each County
* The percentage of votes for each county out of the total count
* The county with the highest turnout

## Resources
* Data Source: election_results.csv
* Software: Python 3.8.3, Atom 1.50.0

## Election Audit Results
The analysis of the election shows that:
* There were 369,711 votes cast in the election.
### Candidate Results
* The candidates were:
    * Charles Casper Stockham
    * Diana DeGette
    * Raymon Anthony Doane
* The candidate results were:
    * Charles Casper Stockham received 23.0% of the vote or 85,213 votes.
    * Diana DeGette received 73.8% of the vote or 272,892 votes.
    * Raymon Anthony Doane received 3.1% of the vote or 11,606 votes.
* The winner of the election was:
    * Diana DeGette, who received 73.8% of the votes or 272,892 votes.

### County Results:
* The County results were:
    * Jefferson: 10.5% or 38,855 votes
    * Denver: 82.8% or 306,055 votes
    * Arapahoe: 6.7% or 24,801 votes
* County with the largest voter turnout:
    * Denver with 306,055 votes

## Election Audit Summary
This script can streamline the process of conducting an election audit by
automating the process of reading in the data and calculating the metrics.
This script can also be applied to any election including congressional elections,
senatorial districts and local elections.

Ways to modify the script include:
1. Make use of functions to open and write to file text files to simplify code
2. Make the script interactive with input function so users can specify the location of the dataset
3. Use list and dictionary comprehension to improve readability of script.
