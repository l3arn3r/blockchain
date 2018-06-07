# blockchain

Block.java 
Stores the block data structure.

BlockHandler.java
ByteArrayWrapper.java 
Use BlockChain.java to process a newly received block, create a new block, or process a newly received transaction.
A utility file which creates a wrapper for byte arrays such that it could be used as a key in hash functions. (See TransactionPool.java)

Transaction.java 
This is similar to Transaction.java except for introducing functionality to create a coinbase transaction. Take a look at Block.java
constructor to see how a coinbase transaction is created.

TransactionPool.java 
Implements a pool of transactions, required when creating a new block.
