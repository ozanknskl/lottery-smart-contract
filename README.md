# lottery-smart-contract

One lottery runs for a period of 40000 blocks. A new lottery round starts right after the previous one is completed. Lottery tickets are offered in three forms:
- A full ticket which costs 8 finneys,
- A half ticket which costs 4 finneys,
- A quarter ticket which costs 2 finneys.

Three unique winners will be selected by computing random numbers that determine each winner.Three random numbers are to be supplied by the ticker purchasers.

The stages of each lottery round are scheduled as follows:

a) Ticket purchase and random number submission stage : blocks 0..19999.

b) Random number reveal stage : blocks 20000…39999. Note that if previously submitted random numbers are not submitted correctly in the reveal stage, the chance of winning is lost. Also, no ticket refund is made.

Anyone having a Metamask account is able to use the interface to interact with Lottery smart contract.
You should first download the Metamask plugin and run it on Brave browser. 

1-)After you download the code, while in the same directory you should type "npm install express" to be able to run the server. 

2-)Run the server by "node myserver.js"

3-)Go to the web page "http://localhost:8081/lottery.html" while you have the Metamask plugin on your Brave browser. You can connect to Ropsten Test Network from Metamask and try to buy some tickets. 


