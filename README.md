# KSK

# codefundoo++
This repository describes the idea and implementation of using Blockchain in elections to make it more secure, transparent and reliable.


# Our main idea of using Blockchain for e-voting is as follows:


First of all, the voter registration process would still have to take place off the grid or the chain. Once a voter registration agency determines that someone is eligible to vote, they would receive a token or key that would allow them to vote precisely once. Any authentic candidate can log in using web-cam and government-issued ID. ECC or Elliptical curve cryptography is used to create these votes. ECC is a form of asymmetric cryptography that uses two public and private key to encrypt and decrypt data. 

During Voter registration, the voter creates two ECC key pairs. The voter reveals their identity to a verifier who certifies the first key pair. Once that's done, the voter registers their second key pair anonymously as belonging to their first pair. Then the voters cast their virtual ballot and sign up on the vote with the private key.

Once the vote is done, anyone can verify whether the signature is valid or not and make sure that none of the votes has been tampered with. All the votes can be verified by using voter's public key to see if they come from a legitimate actor.
During the registration process, after the identity is verified, a smart contract will be executed that will issue a ballot so that he could vote and submit it to the ballot box. The blockchain-based voting system will ensure that the user doesn't vote multiple times.

In a Blockchain-based voting system, when a voter votes, the polling station consults a voter blockchain to ensure the voter hasn't already used up his vote. If the voter's vote is valid, the polling station accepts his vote, and in case the vote is found to be invalid, the vote gets rejected by the polling station thus tackling the problem of multiple votes by a single person. After voting, the vote becomes a transaction and gets stored in Blockchain after encryption. 
Once the vote is cast, it can't be modified because of the innate, immutable characteristics of the Blockchain. The voter can even audit each ballot and confirm if the election results are accurate while retaining the privacy of other voters.
Privacy is maintained.

Well, a 'person's identity is hidden via complex cryptography and represented only by their public address. So, if you were to look up a 'person's transaction history, you will not see "Bob cast his vote to Mr XYZ of ABC party" instead you will see "1MF1bhsFLkBzzz9vpFYEmvwT2TbyCt7NZJ cast his vote to Mr XYZ of ABC party".
The Blockchain is decentralised, distributed public ledger system. Each block of a blockchain is given with a unique string obtained through hashing. Moreover, each block stores the hash of a previous block and hence, it forms a chain.

# Technologies used:
*ECC


*SHA-256

# Link to the dataset

https://data.gov.in/resources/general-election-tamil-nadu-legislative-assembly-constituencies-2011-shb-2012

This Repository was contributed by:

*Kumar Shivam Ranjan

*kartik Rai

*Kavyansh Gangwar
