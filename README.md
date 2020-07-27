## **Blockchain Section** 

## Custom testnet Blockchain specifications 

## Initiate puperneth to generate genesis block 
### Name of the testnet "bush" using POA as shown in the below screenshoot
![](https://github.com/MishraSubash/Blockchain/blob/master/images/Part1.png)


### Below is the bunch of steps to generate necessary dependencies using address from MyCrypto wallet using chain ID 1234
![](https://github.com/MishraSubash/Blockchain/blob/master/images/part2.png)

### More Screenshot for genesis configuration where we can see steps for creation a bush.json file
![](https://github.com/MishraSubash/Blockchain/blob/master/images/part3.png)

### Creating Nodes (node1 and node2). this screenshot also shows the public address of the key and the path for the secret key.
![](https://github.com/MishraSubash/Blockchain/blob/master/images/part4.png)

### Initialization of nodes using genesis block.
![](https://github.com/MishraSubash/Blockchain/blob/master/images/part5.png)

### Please find below output of the the first node into mining mode with the following command ./geth --datadir node1 --mine --minerthreads 1
![](https://github.com/MishraSubash/Blockchain/blob/master/images/part6.png)

### After Opening a new git bash. Please find below output of the the second node into mining mode with the following command ./geth --datadir node2 --port 30304 --rpc --bootnodes enode://7e9529e2475cdcd047c722e898964f52e694718b1b5e64238f46fc5838e7944a3ebb2e7b713aef0254b6d09e65a5ee26c4fa13f04585409a5b60b1938594d485@127.0.0.1:30303
![](https://github.com/MishraSubash/Blockchain/blob/master/images/part7.png)

## **Crypto Wallet Section** 
### Opening the Crypto wallet to configure the testnet.
![](https://github.com/MishraSubash/Blockchain/blob/master/images/testnet1.png)
### Please find below screenshot of the custom network using same parameters that we use on gitbash. http://127.0.0.1:8545 chain id 333 name banknet, we can see that it is prefunded with ETH.

![](https://github.com/MishraSubash/Blockchain/blob/master/images/bush%20eth%20dashboard.png)


### Transfer Confirmation page 
![](https://github.com/MishraSubash/Blockchain/blob/master/images/confirmtransc.png)

### Checking status page after transfer confirmation 
![](https://github.com/MishraSubash/Blockchain/blob/master/images/check%20status.png)

### Transaction success page
![](https://github.com/MishraSubash/Blockchain/blob/master/images/success%20page.png)

## **Conclusion**

- We were able to use Puppeth, to generate your genesis block
- We were able to use Geth, command-line tool, to create keys, initialize nodes, and connect the nodes together.
- We use configure our network using The Clique Proof of Authority algorithm


