# PoW Chains

Proof of Work (PoW) chains use a competitive validation method to confirm transactions and add new blocks to the blockchain. The validation method involves difficult math problem to verify digital transactions.&#x20;

This problem is called a client puzzle. [**Hashcash**](https://en.wikipedia.org/wiki/Hashcash), first proposed in 1997 by [**Adam Back**](https://en.wikipedia.org/wiki/Adam\_Back). Hashcash **** paved the way for blockchains utilizing a proof-of-work function.

In order to create a new hash, a miner must solve the puzzle. The first miner to hit the lowest target nonce '**solves**' the problem. This miner creates the new block by hashing together the most recent block with the newest one— _the miner who solves the block receives a reward in the form of newly '**minted**' coins._

Proof-of-work is the mechanism that allows a blockchain to reach consensus. \
\
Consensus allows a blockchain to keep track of things like account balances and transaction order. This prevents coins from getting '**double spent**' and ensures that a proof-of-work chain is incredibly difficult to attack or manipulate.

To attack a PoW chain, attackers need to control 51% or more of the network power. This allows miners to collude with greater power than the remainder. (49%)&#x20;

The '**attackers**' force a change by adjusting the chain. The other miners can fight back which will result in a hardfork of the chain.&#x20;

{% hint style="warning" %}
_A hardfork occurs when the consensus is violated_&#x20;
{% endhint %}

Two groups of miners want to continue the history of their '**version**' by enforcing the new consensus. A different consensus may occur when heavily contested code changes or software updates fundamentally change the functionality of the chain.
