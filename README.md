# Hey, I’m Jason 👋

I am an avid blockchain developer hacking on a few projects across gaming, DeFi, and NFTs. I am also a CS and Applied Math student at Vanderbilt University (on the side, I like to say 😄).

## Aptos-Move Projects

I am currently focused on building dApps for the Aptos blockchain in Move, a novel smart contract programming language designed for secure digital assets. My current projects include:

### Aptos Arcade

[Aptos Arcade](https://www.aptosarcade.com/) is a web-based gaming platform that uses Aptos NFTs ([Pontem Pirates](https://www.topaz.so/collection/Pontem-Space-Pirates-c46dd298b8), [Aptos Monkeys](https://www.topaz.so/collection/Aptos-Monkeys-f932dcb983), etc.) as characters. Our flagship game, Aptos Arena, is a 2D fighter game similar to Super Smash, where each character has unique stats, skills, and weapons. A preview of the game is available on [Youtube](https://www.youtube.com/watch?v=odlw76LL2i0) and some of its repositories are open-source [here](https://github.com/aptos-arena). 

### Satay Finance

[Satay Finance](https://app.satay.finance/) is an all-in-one DeFi portfolio management tool offering three interconnected products:

1. [Blocks](https://app.satay.finance/blocks)** - composable DeFi primitive operations through trusted third-party protocols
2. [Strategies](https://app.satay.finance/products)** - compositions of Blocks that facilitate multi-protocol yield generation
3. [Vaults](https://app.satay.finance/vaults)** - secure capital pools that optimize allocations to Blocks and Strategies to maximize yield

All of its source code, including the vault architecture, sample strategies, blocks, and partner interfaces are available on the [Satay GitHub organization](https://github.com/satay-protocol).

### Aptostream

[Aptostream](https://www.aptostream.com/) is a continuous payment streamer on Aptos allowing users to send and receive funds in real time. The contracts are deployed on Aptos Testnet, and I am looking to integrate them into Aptos Arcade to facilitate NFT rentals. The repositories are closed source, but the web app is live.

## EVM Projects

Before moving to Aptos, I learned smart contract development by deploying Solidity contracts on Ethereum, Polygon, Avalanche, and Tron.

### Decentralease

I built [Decentralease](https://www.decentra.lease/) as a hackathon project while living in a Coinbase x Polygon hacker house in New York City. We were fortunate to win the hackathon, as well as the Tron Grand Hackathon Season 2! 

Decentralease is an NFT rental platform powered by the [ERC-4907 standard](https://eips.ethereum.org/EIPS/eip-4907), enabling zero-collateral NFT rentals for gaming assets. ERC-4907 is an extension of [ERC-721](https://eips.ethereum.org/EIPS/eip-721) which adds an additional *user* role beyond the standard ******owner****** role, separating ownership and usage rights. This enables the asset owner to assign a user without giving up ownership privileges, standardizing the rental process. The platform unlocks liquidity for NFTs by allowing owners to earn income on their assets while also lowering barriers to entry for new users. The source code for the smart contracts and the dApp are available [here](https://github.com/decentralease).

### Real Vision Bot Portfolio

The [Real Vision Bot Portfolio](https://github.com/hedblock/bot-portfolio) is a collective investment platform allowing holders of the Real Vision Pro Crypto NFT to allocate funds to a set of whitelisted tokens. I built this as a contractor for Real Vision, and it taught me a whole lot about DAO governance and web3 integrations through custom React hooks.

### Vanderbilt Acorns

[Vanderbilt Acorns](http://vanderbiltacorns.com/) is a Proof-of-Concept for a next-generation university community powered by NFTs. A Vanderbilt Acorn is an ERC-721M NFT that grants access to a token-gated ecosystem of integrations with web3 and web2 platforms:

- Vanderbilt Syndicate Investment Club - a collective investment fund where users can deposit USDC and vote on investment decisions, such as buying ETH.
- Vanderbilt Governance Snapshot - a governance platform where Acorn holders can propose and vote on Vanderbilt operational improvements. For instance, “Extend Munchie Mart hours to 2 AM during finals week.”
- Acorns Google Workspace - a shared Google Drive with token-gated sharing access. Some possible applications include research papers, alumni records, and school contact lists.
- Acorns GitHub Workspace - a shared GitHub workspace with token-gated access control. Could be used for open-source community work, job postings
- Vanderbilt Discord - a private communication channel for Acorn holders
