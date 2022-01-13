# Election_Analysis

## Overview of Election Audit
We are auditing the tabulated results for a US Congressional precinct in Colorado for the Colorado Board of Elections employee, Tom. The election commission wants the voter turnout for each county, the percentage of votes from each county, and te county with the highest turnout.

## Election-Audit Results
<img width="309" alt="image" src="https://user-images.githubusercontent.com/58046234/149229788-dc553e60-91ce-4c33-96d1-cb57ac7b1edc.png">

- There was a total of 369,711 votes casted in this congressional election.
- Breakdown of the number of votes and the percentage of total votes  in the precinct:
-- Charles Casper Stockham received 23.0% of the votes and a total of 85,213 votes.
-- Diana DeGette received 73.8% of the votes and a total of 272,892 votes.
-- Raymon Anthony Doane received 3.1% of the votes and a total of 11,606 votes.
- Denver county had the largest number of votes.
- Breakdown of the number of votes and the percentage of the total votes each candidate received:
-- Jefferson received 10.5% of the voters and a total of 38,855 voters.
-- Denver received 82.8% of the voters and a total of 306,055 voters.
-- Arapahoe received 6.7% of the voters and a total of 24,801 voters.
- Diana DeGette won the election with 272,892 votes, 73.8% percentage of the total votes?

## Election-Audit Summary

This election script can easily be used with some modifications for any election. If there is an election with their reults on a .csv file with the Ballot ID number with the county and candidate they voted for, the employee can put the file in the Resources folder and in the script, change the file names in the code. If you look at the image below, on line 9 with the syntax underlined in pink, you can chnage this syntax with the new .csv file name. On line 11 with the syntax underlined in yellow, you can change that .txt file with a differnet name so that you can get a diffrent file with the new results based on the new file.

<img width="416" alt="image" src="https://user-images.githubusercontent.com/58046234/149243394-1eebd6ca-a308-4e3a-a070-7aa9c1b6f486.png">

We can also modify the script to find other things other than the county election results, such as city election results. We can also use the script to see the voter turnout not based on county, but based on ethncity or age or for how long they were a resident, you would just need to chage the second column of your csv file to the breakdown you would want. By doing so, we can can a breakdown of which ethnicty voted for which canidate the most and this can also help the candidates know which are of their election campign they need to work on. 
