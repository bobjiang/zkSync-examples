# zkSync examples

This is examples for zkSync 2.0, `hello greetings` example.
In this example, you need to change 2 points:

1. fill in your private key (ethereum wallet), caution: use the test wallet, not your major wallet.
<File: deploy/deploy.ts>

2. fill in the deployed smart contract address.
<File: src/App.vue>

## How to run this project

```
yarn
yarn hardhat compile
yarn hardhat deploy-zksync
yarn serve
```

# Reference

- https://v2-docs.zksync.io/dev/guide/hello-world.html