# Election_Analysis
Module 3 - Using Python

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete and election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won as it relates to the overall vote count.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio code 1.63.2

## Summary

### There were a total of 369,711 votes cast.

#### Three candidates received votes: 
- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

#### The Candatate received the following number of votes each:
- Charles Casper Stockham: (85,213)
- **Diana DeGette: (272,892)**
- Raymon Anthony Doane: (11,606)

#### The percentage of total votes for each candidate were as follows:
- Charles Casper Stockham: 23.05% 
- **Diana DeGette: 73.81%**
- Raymon Anthony Doane: 3.14% 

### The winner of the election, based on the popular vote, was Diana DeGette. 
### Diana DeGetter Received 272,892 votes, 73.81% of the total vote.

This is all represented in the below image, which is a direct capture of the text file written automatically when running the script.

(![Election_Picture](https://user-images.githubusercontent.com/95391827/149699248-94f6bf4c-86d8-47a2-9107-e9cc51008f30.png)

## Election Audit Summary
Elections audits must be secure, fair, and accurate. The program utilized to produce this report is very accurate. Risk of human error is minimized by taking the raw data and running a program to determine the results of the election. This program can be applicable to any election, and more complex data can even be interpreted with some modifications to the script. Two examples are described below.

### 1. Results by county
As you can see in the results text file, the numbe of votes per county appear in the results. In the script, the for statement that tabulates the votes per candidate could be nested within the loop that counts the numbe of votes in each county. This could be helpful to determine any results that may be surprising or possibly erroneous.

### 2. Votes cast as a percentage of registered voters
With some simple additions to the script initializing the number of registered voters as a value, the data can be leveraged to understand how many votes were cast as a percentage of registered voters. What's more, with a list of census data decribing the number of citizens who are eligible to vote, the script can be leveraged to calculate the percentage of eligible voters who cast a ballot. Using the nesting technique described in "1. Results by county", the script can even be used to show voter turnout by county. Elected officials could use this data to focus on increasing civic participation in the most under-represented counties.
