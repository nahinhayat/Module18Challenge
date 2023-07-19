Module 18 Challenge

Description:

In this challenge a blockchain was created with a hashing function that allows somebody to hypothetically record their transactions on a ledger when they send currency to other users. This blockchain was then run on Streamlit for demonstration. 

Details:

The ledger consists of multiple classes for different purposes it begins with a class that stores the record of the sender's username, the reciever's username, and the amount that is being sent:

![screenshot1]()

The next class creates the blocks for the chain, this has an attribute that uses the record data from the Record class and also a function to create a hash for the block:

![screenshot2]()

The final class chains the blocks together and contains functions that create a proof of work with a difficulty of having four zeroes to begin the winning hash, add the block to the chain, and validate if the new block has the correct hash:

![screenshot3]()

The ledger and user interface was tested by running a Streamlit application and storing mined blocks. The blockchain validation process was also tested:

![block contents]()

![pychain ledger valid]()

Author: Nahin Hayat https://www.linkedin.com/in/nahinhayat/