---
description: Official company, product, industry and engineering documentation.
---

# Utopeon Documentation

This knowledge library is open source. Anyone can fork [the repository](https://github.com/utopeon/docs) and submit a pull request with new information or improvements to existing pages. Help us educate newcomers not only about Utopeon but also about [blockchain](decentralization/blockchains.md), [cryptocurrencies](decentralization/cryptocurrencies.md), [NFTs](decentralization/non-fungible-tokens-nfts.md), [Web3](decentralization/wallets.md), and [play-to-earn video gaming](introduction/welcome/mission.md#\_2e).&#x20;

The Utopeon GitHub is partially public: [https://github.com/utopeon](https://github.com/utopeon). Being open and transparent is important. Some work will be made open source so other engineers can contribute.&#x20;

[GitHub discussions](https://github.com/orgs/utopeon/discussions) are used for technical support, product questions, ideas/suggestions and so much more.&#x20;

Thank you so much for reading and contributing! Your support is greatly appreciated. A big warm welcome to all the new community members! :hugging:

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Changes will be deployed to production automatically after pushing to the `main` branch.  

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
