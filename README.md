## Install
* Install truffle with **npm install -g truffle**
* Metamask is needed to pay the gas fee (with a local Blockchain) of the transactions: [Metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en)
* Dependency Ganache is needed to have a local in memory Blockchain: [Ganache](http://truffleframework.com/ganache)
* Run **npm install** command on the project root

## Start truffle configuration
Run **truffle build** command (this will generate a build folder in the root of the project)
Run **truffle migrate** command
Run **truffle migrate --reset** command to refresh (you need to run this every time you do a modification on the contracts or migrations)

## Start web on local
Run **npm run dev** command

## Run tests
truffle test
