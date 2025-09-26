ZenSwap will fetch token logos from this repo by default using the following pattern:

```ts
const getTokenLogoURL = (address: string) =>
  `https://raw.githubusercontent.com/zenchain-protocol/zenswap-assets/main/assets/${address}/logo.png`;
```
