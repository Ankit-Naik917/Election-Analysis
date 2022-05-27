# Election-Analysis
## Overview of the Project  <br />
### Background <br />
    Provide assistance on performing election audit and developing a script to determine posed questions and use it to automate the audit for other districts in USA.
### Purpose <br />
    The purpose of this analysis is to provide the election audit results to the election commission. By completing the analysis the objective is to get an answer for the points below
    
    Total number of votes casted
    The voter turnout for each county
    The percentage of votes by county and percentage of total votes
    The county with the highest turnout
    A complete list of candidates who received votes
    Total number of votes and percentage each candidate received
    The winner of the election based on popular vote, total votes received and winning percentage.

## Election Audit Results <br />
    
    There were a total of 369,711 votes casted in the congressional elections in 3 counties of Colarado (Jefferson, Denver and Arapahoe).
    Out of the total 369,711 votes, Denver county had largest number of votes casted which was 82.8% (306,055) followed by Jefferson county with 10.5% (38,855) votes and Arapahoe county with 6.7% (24,801) votes.
    The total number of votes received by each candidate is given below
    Candidate                   Total Votes         Votes Percentage
    Diana Degette               272,892             73.8%
    Charles Casper Stockham     85,213              23.0%
    Raymon Anthony Doane        11,606              3.1%
    Based on the analysis, Diana Degette won the populer vote with a total of 272,892 votes which is 73.8% of the total votes.

## Election Audit Summary <br />
	This file can be used for other elections as well. There are couple of things that needs to be kept in mind before using the script
    The path for load the election data file and file to save should be clearly defined.
    Ensure the new file has headers that clearly define the data. In case of no header, the declared variable "header" needs to be removed so that the file is read from the beginning.