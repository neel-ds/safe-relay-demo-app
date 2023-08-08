# safe relay examples

Simple Safe-relay repo calling Counter on Base Goerli "0x763D37aB388C5cdd2Fb0849d6275802F959fbF30"



### Setup Instructions

Please copy the .env.example --> and add the PK, Alchemy Key and Gelato SponsorKey. Reference for Gelato SponsorKey [here](https://docs.gelato.network/developer-services/relay/payment-and-fees/1balance-and-relay)

Example of using Gelato relay with the the Safe sdk. In this example you can relay transactions through any Safe controlled by the signer passing the Safe address

- Using 1Balance

Code can be found [here](src/safeRelay.ts)

```
yarn safeRelay
```
