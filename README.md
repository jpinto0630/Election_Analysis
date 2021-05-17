# Election_Analysis

# Project Overview
Seth and Tom are employees of the Colorado board of Election, they have asked us to complete an audit of a recent election. The project initially had the following 5 items which were to be included in our audit:
- Determine the total number of votes cast
- Formulate a complete list of candidates who received votes
- Determine the total number of votes each candidate received
- Determine the percentage of votes each candidate won
- The winner of the election based on popular vote

It was then modified to include the following three items: 
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout	

## Resources
- Software: Python 3.9.5, Visual Studio Code 
- Data Source: election_results.csv  

## Results
We have created an analysis in Python to analyze the election_results.csv data Seth and Tom provided, below are the results of our analysis. Note that the analysis was conducted to specifically address the items Seth and Tom requested as listed in the results section above, and a txt file was formulated to include some of the information below. 

- How many votes were cast in this congressional election?

```Total Votes: 369,711```
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
The following output from our script is formatted as (County): (percentage of votes received) (total number of votes received)
```
Jefferson: 10.5%  (38,855)
Denver: 82.8%  (306,055)
Arapahoe: 6.7%  (24,801)
```

- Which county had the largest number of votes?

```Largest County Turnout: Denver```

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
The following output from our script is formatted as (Candidate): (percentage of votes received) (total number of votes received)
```
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)
```
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
The following output from our script addresses this:
```
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%
```

## Election-Audit Summary:

The script utilized is a versatile script that with some refactoring could be used to conduct analysis of differing elections. Our variables, lists, and dictionaries used at the start of the script could be changed to encompass other election types. Here are some examples of how the code could be changes. 
```
#Create a precinct list and precinct votes dictionary.
precinct _namelist = []
precinct _voting = {}
```

```
# Track the winning political party, vote count and percentage
winning_party = ""
winning_party_count = 0
winning_party_percentage = 0

```
