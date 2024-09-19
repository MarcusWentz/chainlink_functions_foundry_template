# chainlink_functions_foundry_template

## Install Chainlink libraries
```
forge install smartcontractkit/chainlink-brownie-contracts --no-commit
```

## Chainlink Functions Playground

https://functions.chain.link/playground

## Deploy a Functions consumer contract (Remix IDE template)

https://docs.chain.link/chainlink-functions/getting-started#deploy-a-functions-consumer-contract-on-sepolia

## Chainlink Functions Subscriptions

Used to:
```
-point at consumer contracts to receive requests
-fund consumer contract requests with LINK tokens
```

https://functions.chain.link/


## YouTube: Making a Functions Request | Chainlink Tutorial (5 of 5) 

https://www.youtube.com/watch?v=DJny2WlABAE


## Sending a request 

For this example, let the Javascript argument values be:
```javascript
arg[0]=1
```
which looks like this in Solidity:
```solidity
sendRequest(
    <subscriptionId_pointing_at_consumer_contract>,
    ["1"]
)
```

## Deploy and verify contract
```


GettingStartedFunctionsConsumer

```