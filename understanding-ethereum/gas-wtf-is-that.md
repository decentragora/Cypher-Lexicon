# ⛽ Gas? Wtf is that?

"Gas" refers to the fee, required to complete a transaction/execute a smart contract over the Ethereum network. Measured in smaller units of Ether called Gwei, where "1 Gwei" is equal to "0.000000001 Ether"/ "1000000000 Gwei" is equal to "1 Ether", refer to this [table](./#ethereum-conversion-table). Gas is used to allocate the computational effort required to execute specific operations on the Ethereum network. Since each Ethereum transaction requires computational resources to execute, each transaction requires a fee.

## How are Gas fees calculated?&#x20;

The price of Gas is determined by basic supply & demand between the network miners/validators. These miners/validators can set thresholds for Gas fees, if a transaction does not meet the requirements it will not be processed. We can use (Gwei limit \* Gas price) to calculate an estimation for "Gas Fees"

Simply "Gas Fees" will be measured by how many steps are taken inside the transaction; Gewi limit. The smallest fee would be to send Ether to another address as it has the least amount of steps required, a Gwei limit of 21000gwei. Executing/deploying contracts will have a higher Gwei limit due to there being more steps.
