# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote. 
6. The voter turnout for each county
7. The percentage of votes from each county out of the total county
8. The county with the highest turnout

## Resources
  - Data Source: election_results.csv
  - Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The county vote breakdown:
  - Jefferson: 38,855, 10.5%
  - Denver: 306,055, 82.8%
  - Arapohoe: 24,801, 6.7%
- The candidates were:
    - Candidate Charles Casper Stockham
    - Candidate Diane DeGette
    - Candidate Raymon Anthony Doane
 - The candidate results were:
    - Candidate Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Candidate Diane DeGette received 73.8% of the vote and 272,892 number of votes.
    - Candidate Raymon Anthony Doane recieved 3.1% of the vote and 11,606 number of votes.
 - The winner of the election was:
    - Diane DeGette, who received 73.8% of the vote and 272,892 number of votes.

![Election_Audits_Results](https://user-images.githubusercontent.com/86331812/134776044-cd50c131-5e83-415b-a6d6-85bd9c04143f.png)

## Election Audit Summary
The script gives the election commission a quick and easy way to evaluate a recent election.  The script uses a .csv file to feed it the data to analyze.  The election commission can use this code by just changing out the the .csv file that is feeding it. That means it can be used for more then just the 3 counties that are listed. 
It can also be modified to show the "loser" as well.  It can be modified to show the number of votes in each county that any of the candidates received. 
