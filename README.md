# BlockTrivia
Trivia on the Blockchain - get tokens for correctly answering questions. Built on OpenTrivia.

### .env file:

* You need to have a .env file with the following variables:
```
DEFAULT_ADDRESS=the address from where the contract will be created and transactions will be sent (needs ETH, see https://faucet.dimensions.network)
PRIVATE_KEY=private key of the address above
INFURA_ENDPOINT=a ropsten infura endpoint e.g. https://ropsten.infura.io/v3/YOUR-PROJECT-ID
CONTRACT_ADDRESS=the contract address (you set this after you `truffle deploy --network ropsten`)
```

# OpenTrivia
Small multiplayer quiz demo using express and socket.io in the backend and React for the UI. [Click Here](https://opentrivia.herokuapp.com/) to view the live demo. 

### How to use locally:

* Clone the repository and run the following command to download all dependencies.
```
 npm install
```
* Now open a terminal run the following command if you just want to start the server for development.
```
npm run watch
```
Use the following commands if you want to manually build from src to test for production.
```
npm run build:prod or npm run build:dev followed by npm run serve
```
* Open the brower and navigate to http://localhost:3000 for the main screen and point all other devices to http://your_internal_ip:3000 and follow onscreen instructions.

