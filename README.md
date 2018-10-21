# basicBlockChainImplementaion
Straight Outta Siraj Raval's Tutorials XD

I'll try to explain to you the concept of blockchain as simple as possible.

It is nothing but a linked list of a user defined data type generically called a block. Hence BlockChain.
Every block has a number and that number along with certain other attributes of the block are being put into a hash function to generate a code. This code goes into the hash function to generate the code for the next block and so on.

Why is it called Safe?
The hash code is not an ordinary 4-digit number but a very complex multiple digit code which exponentially decreases the chances of cracking the code by brute force and then while you edit one block, it consequently changes the code of the other resulting in constant changing of the code. It takes humangous computing power to crack such codes by brute force and hence people call it safe to use block chain and as you can see Bitcoins use it. And a lot of other Technologies would use it in future as well.
