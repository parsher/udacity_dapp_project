
# StarNotary Token Dapp

Hi! I'm an udacity student. I developed StarNotary Token Token Dapp from Udacity's boilerPlate codes [git](https://github.com/udacity/nd1309-work-code/tree/master/Course_Identity_And_Smart_Contracts). Also this project is based on openzepplin-solidity, truffle. And this Dapp follows ERC-721.

You can use some of features on the simple web application too.
  
# Token Description
Token Name : Star Notary Token  
Token Symbol : SNT  
To notarize and exchange stars, developed this Dapp.

# Token Features

# createStar
parameter : name, token id  
make a star token.

# putStarUpForSale
parameter: token id, price  
make a star price for sale.

# buyStar
parameter: token id  
buy a star on the price.
  
# lookUptokenIdToStarInfo
parameter: token id  
search the name of the star.

# exchangeStars
parameter: token id 1, token id 2  
exchange token id 1 with token id 2.

# transferStar
parameter: address, token id  
transfer the star to the address.

# Install & Run

1. Please install truffle(v5) and metamask in chrome.

2. Please join Infura and change an infuraKey variable in truffle-config.js file.

3. Type the command in the command line prompt.
```
cd app
npm install
npm run dev
```
```
npm install
truffle develop
compile
migrate --reset
test
```
* npm install --global windows-build-tools
(First of all, in Window OS, using this command on PowerShell as administrator mode.)

4. Before run the test, please change a mnemonic in .secret file.

* For the test, the infuraKey and the mnemonic are set. 

# License

For the boiler plate codes and other library in this project, please check the original sources' code license.

Others are under MIT License.