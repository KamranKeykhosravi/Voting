# Voting
This is a voting contract in Solidity
When deploying it requires a list of options like ["option1","option2"]
Users can vote using the vote method either by indicating the position of the option (0) or by writing the "option1"
Each user can vote only one time
The contract returns an error if the provided vote is not among the options
