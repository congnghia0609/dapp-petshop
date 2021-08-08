# dapp-petshop
dapp-petshop is an example DApp PetShop on Ethereum blockchain  

## Quick start

### Run and test local
**1. Download and start [Ganache](http://truffleframework.com/ganache)**
```bash
sudo chmod a+x ganache-2.5.4-linux-x86_64.AppImage
./ganache-2.5.4-linux-x86_64.AppImage

##==> choose QuickStart
##==> ganache run on port 7545
```

**2. Compiling and migrating the smart contract**
```bash
## Compilation
truffle compile

## Migration
truffle migrate
```

**3. Testing the smart contract using Solidity**
```bash
# Running the tests
truffle test
```

**4. Start lite-server**
```bash
## Start the local web server:
npm run dev

##==>Open on browser: http://localhost:3000/
```

**5. Installing and configuring MetaMask on browser**  
- Now we need to connect MetaMask to the blockchain created by Ganache.  
- Click the menu that shows "Main Network" and select Custom RPC.  
- In the box titled "New Network" enter `http://127.0.0.1:7545`, in the box titled "Chain ID" enter 1337 (Default Chain ID for Ganache) and click Save.  
- A MetaMask pop-up should appear requesting your approval to allow Pet Shop to connect to your MetaMask wallet. Without explicit approval, you will be unable to interact with the dapp. Click Connect.  


