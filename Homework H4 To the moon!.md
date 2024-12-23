x) -The introduction of the paper of Bitcoin: A Peer-to-Peer Electronic Cash System discusses the current limitations of Internet commerce, which relies on financial institutions with trusted parties that process electronic payment methods. The system does work, 
    but it has several weaknesses, such as the need for dispute mediation, which is increasing transaction costs, limiting small transactions, and preventing non-reversible payments. Also, fraud is a big concern, with merchants requiring excessive 
    customer info and accepting a certain level of fraud as inevitable. Physical currency avoids this kind of issue but has no equivalent exists for online payments. The solution would be to use electronic payment based on cryptographic proof, rather than trust.
    With this kind of system it would be possible to enable direct transactions between persons without a third party. This would also prevent transaction reversals, and protect the sellers from possible fraud, while offering a safeguard for the buyers also. 

  -The transaction section of the paper of Bitcoin: A Peer-to-Peer Electronic Cash System describes the electronic coin to be defined as a series of digital signatures. Each owner transfers the coin to the next person by signing a hash of the previous 
   transaction along with the public key of the next owner, adding them to the selected coin. The owner who has paid can verify the signatures to confirm the chain of ownership of the coin. The problem with the electronic coin system is that the owner cannot verify 
   if an owner has double-spent the coin. A solution to this is to use a trusted central authority, or minting, that checks the transactions for possible double-spending. After each transaction, the coin must be returned to the mint for a new one to be issued for
   them, and only these coins directly from the mint can be trusted. However, this solution relies strongly on the mint, similar to a bank, and makes the entire system vulnerable to minting control. To solve this without a trusted party, there needs to be 
   a system where the transactions are publicly announced, and participants agree on the order in which they were received. This will ensure that the payer can verify that the majority of nodes agreed upon on the first transaction, and then prevent double-spending 
   attempts and removes the needed central authority.

  -The timestamp server section paper of Bitcoin: A Peer-to-Peer Electronic Cash System is offering a solution to the timestamp server, that works by creating a hash of a block of data to be timestamped and then is widely published by the hash. This provides data that 
   existed at that time. Each timestamp includes the previous one in its hash, creating a chain, where each of the new timestamps strengthens the validity of the previous ones.
 
  -The proof-of-work of the paper of Bitcoin: A Peer-to-Peer Electronic Cash System is a distributed timestamp server on a peer-to-peer basis, the solution uses a proof-of-work system, similar to Adam Back's Hashcash, instead of relying on newspaper or Usenet posts. 
   The proof-of-work involves finding a value of, when hashed also (with SHA-256), produces a hash starting with several zero bits. The work required growing exponentially with the number of zero bits, and it can be verified by executing a single hash. For the 
   timestamp network, the proof-of-work is implemented by incrementing a nonce in the block until the hash meets the required criteria. Once the work is done, the block cannot be altered without redoing the work, and as new blocks are added, the work to change a 
   previous block becomes progressively harder. Proof-of-work also helps solving the problem of majority decision-making by ensuring that the majority is based on CPU power (one-CPU-one-vote), not IP addresses, which can be manipulated. The longest chain, requiring 
   the most proof-of-work, represents the majority decision. If honest nodes control the majority of CPU power, their chain will grow fastest. An attacker trying to alter past blocks would need to redo the proof-of-work for all subsequent blocks and surpass the 
   work of honest nodes, making such an attack increasingly unlikely. To adjust for changes in hardware speed and varying node participation, the difficulty of the proof-of-work is adjusted based on a moving average that targets a fixed number of blocks per 
   hour. If blocks are generated too quickly, the difficulty is going to increase.
  
  -The network section of the paper of Bitcoin: A Peer-to-Peer Electronic Cash System explains the process for running the network as follows: 
  1. New transactions are broadcast to all nodes.
  2. Each node collects transactions into a block.
  3. Nodes work to find a difficult proof-of-work for their block.
  4. Once a node finds a proof-of-work, it broadcasts the block to all other nodes.
  5. Nodes accept the block only if all transactions are valid and not previously spent. They then begin working on the next block, using the accepted block’s hash as the previous one.
   Nodes always consider the longest chain to be the correct node and continue to extend it. If two nodes broadcast different versions of the next block at the same time, then the nodes will work on the first one they received but store the other branch. The tie is
   broken when a longer chain is found, and nodes will switch to the longer one. Transaction and block broadcasts are robust to message loss. As long as transactions reach many nodes, they will eventually be included in a block. If a node misses a 
   block, it can request it upon receiving the next block.

  -The incentive section of the paper of Bitcoin: A Peer-to-Peer Electronic Cash System explains the first transaction in each block that is special, creating a new coin for the block's creator. This serves as an incentive for nodes to support the network 
   and provides a way to distribute coins since there is no central authority. The process is similar to gold mining, where resources (CPU time and electricity) are expended to add new coins to the mixture. The incentive can also come from transaction fees. If the 
   output value of a transaction is less than its input, the difference becomes a fee that contributes to the block’s reward. Eventually, as the total supply of coins grows, the incentive can shift entirely to transaction fees, eliminating the inflation. 
   This incentive structure encourages nodes to remain honest. If an attacker gains more CPU power than all honest nodes combined, they would need to choose between using that power to create new coins (by following the rules) or to defraud the system. 
   Following the rules is always more profitable, as it allows the attacker to earn more coins than others, making dishonesty less attractive.


  Source: https://git.dhimmel.com/bitcoin-whitepaper/


a) I created a wallet using Electrum. I had to save the seed to a location where only I have access to. Photos saved here: https://imgur.com/a/8QiZKpD 

b) I used Testnet demo to receive fake BTC from a testnet Bitcoin faucet. Photos saved here: https://imgur.com/a/8QiZKpD 

c) I sent a random amount of BTC to another wallet that has the last two digits as 73. Photos saved here: https://imgur.com/a/8QiZKpD 

d) I sent bitcoin back to a Testnet Bitcoin Faucet wallet. Photos saved here: https://imgur.com/a/8QiZKpD 

e) I went to  BTC block scanning site to analyse a BTC block. The Bitcoin block height measures how many blocks have preceded it on the Bitcoin protocol. The status indicates if the chain has received the BTC. The time stamp shows the date and time when the BTC was
   received. The size describes the size of the BTC block in kilobytes. The virtual size describes the virtual size of the BTC in virtual kilobytes. The weight unit discribes the size of all the transactions in teh same block. The version describes the number of the 
   BTC protocol being used. The Merkle root describes how much the 32-byte field contains a 256-bit hash of the root of the Merkle tree of all the transactions in the current block. The bits describes the 4-byte field contains the target difficulty of the current 
   Bitcoin block which determines how difficult the target hash will be to find. The difficulty shows the version level of the difficoulty of the block. And the nonce shows that 4-byte field contains a 32-bit number that a miner must alter in order to correctly 
   solve the computational puzzle for the current block. Photos saved here: https://imgur.com/a/8QiZKpD 


   Source: https://www.gemini.com/cryptopedia/what-is-block-in-blockchain-bitcoin-block-size#section-bitcoin-block-headers-and-mining


f) Watched the video about Rogecoin: https://www.youtube.com/watch?v=GUs5y9leCyA

    - I agree with the video that most of the Crypto currencies out there are pretty much worthless and people only are trading them because of the hype that the price could go up, but mostlikely won't.
    - I think that most people should do more resarch before investing their life savings into a new Crypto coin and analyse the market history, before investing thousands of Euros in the new Crypto coins.



