ZenSwap will fetch token logos from this repo by default, unless another URL is provided in the token list.

A token logo should be placed in `assets/<token-address>/logo.png`.

The logo will be fetched in ZenSwap using the following url:
```ts
const getTokenLogoURL = (address: string) =>
  `https://raw.githubusercontent.com/zenchain-protocol/zenswap-assets/main/assets/${address}/logo.png`;
```

The token address is case sensitive and should be the checksummed address.