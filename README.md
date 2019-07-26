# Vote Recording & Counting in Blockchain based voting system
Currently with EVMs, we have to wait days before all the EVMs are collected to respective central points and then manually each of the EVM individually has to be connected to the main computer and then votes are counted, resulting in a very expensive process both in terms of money and time.

Using Blockchain, we will be able to count the votes very quickly(within muinutes) of finishing the elections with the added transparency as well.

## A basic blockchain voting system
Our project is mainly concerned with the counting of votes, but we here sketch the outline of how we garner the rest of the system looks like.

The basic voting system either will record the votes through a local node or even a mobile device for each individual.Each of the vote is recorded as a transaction in the blockchain underneath. All the votes/transactions registered finally by the blockchain have been verified and are valid. The blockchain is public meaning anyone can join as a node and verify the legitimacy of the network and database by applying the transactions.

#### Consensus Algorithm: 
Our solution will be taking proof-of-stake as the consensus algorithm, which we found during our research to be more suiting for voting system.

## Problem Statement: 
Through research, we created a problem statement for ourselves to try and solve during the course of the hackathon, if given a chance.

+ The model on how to record votes against each constituency/political-party.
+ Count the total vote based transactions in the blockchain (The algorithm has to be very scalable and error free).
+ Since the blockchain is avaible to everyone, we have to restrict the access of counting during the election period itself as this can influence the decision of the public yet to vote.
+ We also have to generate reports based on each constituency, representative, party etc.
+ The final report should be the number of seats won by the party only.
