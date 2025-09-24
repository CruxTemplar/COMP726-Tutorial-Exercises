# COMP726-Tutorial-Exercises
A selection of 10 questions taken from the various lab activities to test our ability and understanding in COMP726 (Blockchains and Cryptocurrencies). Each of the 10 questions will be divided into 3 separate files and named 'Exercise ##'. Such questions are as follows:

### Exercise 1: Questions 1 to 3
Mining difficulty is not only represented by leading zeroes (powers of 16) but by a value (hex number) that is recalculated every 2016 blocks (in Bitcoin). Write a script demonstrating simplified proof-of-work, using 

  *'if hash < target: block_found = True'*

  and run your simplified proof-of-work in two different difficulties.

Write a script to modify the difficulty every time a block is found faster than expected (increase difficulty) and readjusts if a block is found slower than expected (decrease difficulty).

Can you have a proof of work blockchain with a realtime difficulty adjustment? What are some of the advantages of this setup? Limitations?

### Exercise 2: Questions 4 to 6
Using remix, modify the Storage.sol contract to store and retrieve a text variable: yourName. How much gas does this use, how does this compare to storing an integer?

Where is a deployed contract stored in Ethereum? Comment on the different gas costs for a) deploying a contract, b) calling a function, and c) storing an address.

Above, where it says STORAGE AT 0X...., what does this mean? Are there differences between someone's Ethereum Address and where your contract is stored?

### Exercise 3: Questions 7 to 10
What are some examples of fungible tokens compared to non-fungible tokens that you use that are not blockchain related (Tutorial 9)?

How much gas did you pay to deploy your contract? What are some implications of the gas auction fees model (Tutorial 9)?

Change the metadata and mint another NFT (Tutorial 10).

Write a script to generate a new random NFT every time mint is called (Tutorial 10).
