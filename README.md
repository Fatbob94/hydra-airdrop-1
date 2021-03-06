First Hydra Airdrop 
===================

Dear IOP Community, 

Registration for the first Hydra airdrop has opened on Sunday, December 17, 2:00 PM UTC. To give everyone in the community a fair chance to get some Hydra, we are not distributing a fixed amount of Hydra per IOP. 

Instead, we’re running a lottery. 

To take part, you need a valid Ethereum address to receive your Hydra tokens. You can register for the lottery using the tip bot in our official [Telegram Channel](https://t.me/IoPofficial). The command is `/%register YOUR_IOP_ADDRESS YOUR_ETH_ADDRESS SIGNATURE`. In this, `YOUR_IOP_ADDRESS` is the IOP address you want to register and `YOUR_ETH_ADDRESS` is the address you want to receive the Hydra on. `SIGNATURE` is generated by using the *Sign Message* function of your IoP Core wallet. Enter your Ethereum address in the message field, without any other symbols or whitespace. Choose the IOP address you want to register and click *Sign*. Copy the resulting signature into the command for the telegram bot. This is used to verify that you indeed own the IOP address you want to register.

When you register one of your IOP addresses for the lottery, you will be credited 1 ticket for every 2 full IOP in your account when we took the snapshot on Sunday, December 10, 7:00 PM UTC at Block 71417, up to a maximum of 250 tickets per IOP address. 

If you find an address is credited with fewer tickets than expected, please remember that your wallet generates change addresses everytime you send a transaction. Depending on their balance, these addresses might also be eligible. You can get a list of all addresses in your wallet--including change addresses--by running `listaddressgroupings` in the console found in your IOP Core Wallet under *Help->Debug Window->Console*. To find out which of these is eligible for registration, you can compare them against the snapshot data [here](src/data/snapshot.json). 

Registration will be open until Friday, December 22, 2:00 PM UTC. After registration closes, we will update this repository with the full registration data. 

The code for the lottery is already online and can be used by everyone to validate the result. Please be aware that the results of the lottery will only be fixed once registration is complete.
