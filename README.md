# NFT-minting
## To whitelist your address follow the below steps:
Go to [Goerli Testnet](https://goerli.etherscan.io/) and search up this contract address: 0x4B274e77b551D60ffE3595DDA5B3eF3B40fA5B77
1) Go to the Read Contract tab and click on numAddressesWhitelisted - it should currently be set to 0 as nobody has joined the whitelist yet.
2) Now, go to the Write Contract tab and first click on Connect to Web3 - this will prompt you to connect your wallet to Etherscan. Once you have connected a wallet, click on addAddressToWhitelist and then click on Write.

3) This should pop open your wallet to confirm a transaction. Confirm the transaction, and then wait for it to go through. You can click on View your transaction on Etherscan to check it's status.

4) Once the transaction is successful, go back to the Read Contract tab, refresh, and click on numAddressesWhitelisted, The number should Increase by 1.
