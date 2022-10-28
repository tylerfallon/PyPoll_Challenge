# PyPoll_Challenge

## Overview and Purpose

The purpose of this election audit analysis is analyze a .csv file of raw election data and analyze it in order to provide statistics such as the election winner, total votes cast, votes cast by county, turnout, and more. 

## Election-Audit Results

![ElectionResults](https://github.com/tylerfallon/PyPoll_Challenge/blob/main/Resources/election_results.png?raw=true)

This screenshot shows our analysis of the election data, which has been summarized in a .txt document (election_results.txt). Here is a full analysis of the results:

* There were 369,711 votes cast in total during this congressional election

* By county- Jefferson County cast 38,855 votes (10.5% of total), Denver County cast 306,055 votes (82.8% of total), and Arapahoe County cast 24,801 votes (6.7% of total)

* Denver was the county with the largest number of votes. 

* For candidates- Charles Casper Stockham received 85,213 votes (23.0% of total), Diana DeGette received 272,892 votes (73.8% of total), and Raymon Anthony Doane received 11,606 votes (3.1%  of total)

* Winner: Diana DeGette won the election with 272,892 votes and 73.8% of the total votes. 

## Election-Audit Summary

Since the data is extracted and rewritten to a .txt document, this script can be modified and adapted to be used for any election in the future. Because we used a for loop to loop through the counties and candidates, this loop will be able to be applied to an entirely new set of data in the future. With a new set of data, the file_to_load variable can be modified to use a new .csv file with new election data. Variables can be modified if needed in the script as well to account for any new data present in the .csv as well. Lastly, this script could be used in a future local election by replacing "counties" with "districts" throughout the script, allowing us to analyze the turnout and vote numbers in each voting district. 
