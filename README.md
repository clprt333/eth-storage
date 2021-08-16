# eth-storage

use ganache (might need ganache-cli)
check truffle-config.js, make sure it corresponds to the ganache network

Creation:
In commandline:
npm install -g windows-build-tools
npm install in directory
npm run start
go to localhost:3000

In commandline:
npm install -g truffle
powershell -ep bypass
truffle migrate --reset
truffle console
dstorage = await DStorage.deployed()
dstorage
name = await dstorage.name()
name
.exit

truffle migrate --reset (used after any changes, deploys again)
truffle test
npm run start


refresh localhost, connect wallet after editing components/app.js
ipfs url example returned https://ipfs.io/ipfs/QmeNmxD1DG2A8W9QqPJndhcGgijvNztZNejB9F6YbEhSZx
