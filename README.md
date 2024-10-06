Name: Tanishq Satote
Company: CODTECH IT SOLUTIONS
ID: CT08DS8502
Domain: Blockchain
Duration: Sept 25 - Oct 25, 2024
Mentor: Neela Santhosh







Project Overview: Decentralized Voting Smart Contract

Introduction
This project implements a decentralized voting system using a Solidity smart contract deployed on the Ethereum blockchain. The primary goal is to create a transparent, secure, and efficient electoral process that enhances trust in democratic practices.

Key Features:-

* Candidate Registration
Candidates can register by providing their name, party affiliation, age (must be 18 or older), and gender.
Each candidate is assigned a unique ID and can register until a maximum limit is reached.

* Voter Registration
Eligible voters can register by providing their name, age (must be 18 or older), and gender.
Each voter is assigned a unique ID and can register only once to prevent duplicate entries.

* Voting Mechanism
Voters can cast their votes for registered candidates during a specified voting period.
Each voter can vote only once, ensuring the integrity of the voting process.

* Voting Period Management
The election commissioner can define the voting start and end times, ensuring that the voting process is time-bound.
The system prevents voting before the start time or after the end time.

* Election Results
The election commissioner can announce the winner after the voting period ends by counting the votes for each candidate.
The winning candidate is the one with the highest vote count.

* Emergency Protocols
The election commissioner has the authority to stop voting in case of emergencies, providing a safeguard against potential issues.

* Transparency
All voter and candidate details are stored on the blockchain, ensuring transparency and preventing tampering.
The voting status can be checked by anyone, providing clarity on the electoral process.

* Technical Implementation
Smart Contract Language: Solidity (version ^0.8.26).

* Blockchain Platform: Ethereum.

Data Structures:-

- Voter: Struct to store voter details (name, age, ID, gender, vote status, address).
- Candidate: Struct to store candidate details (name, party, age, gender, ID, address, votes).
- Mappings: Used to track registered voters and candidates.
- Enums
- VotingStatus: Indicates the status of the voting process (NotStarted, InProgress, Ended).
- Gender: Enumerates gender options (NotSpecified, Male, Female, Other).
  
Security Features:-

- Modifiers: Used to restrict access to certain functions (e.g., onlyCommissioner, isVotingOver).
- Require Statements: Ensures that all conditions (age eligibility, registration status, etc.) are met before executing functions.
  
Use Cases:- 

- Election Commission: Can manage the entire electoral process, ensuring fair practices.
- Candidates: Can participate in elections and represent their parties.
- Voters: Can exercise their voting rights in a secure and anonymous manner.
- 
Conclusion
This decentralized voting smart contract serves as a robust framework for conducting elections on the blockchain. It aims to enhance the democratic process by providing a transparent, secure, and efficient voting mechanism, minimizing the risks associated with traditional voting systems.

