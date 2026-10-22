# KANEWARE

> Free tools built from real problems Kane Mayfield encountered and could not find existing solutions for. The Forge repairs broken Counterparty metadata across 600+ Arweave gateways. Rescue Lifeboat recovers NFTs and tokens from compromised EVM wallets. Inscribed.Audio provides infrastructure for Bitcoin-native music distribution. All free. All open-source. No custody of user funds. No fees.

## Philosophy

Every tool in KANEWARE exists because the thing did not exist yet. Kane Mayfield builds tools the same way he makes music and writes books — from direct, personal necessity. The Forge was built because Arweave infrastructure broke and hundreds of Counterparty tokens lost their metadata overnight. Rescue Lifeboat was built because he got hacked and no recovery tool existed. Inscribed.Audio was built because no infrastructure for Bitcoin-native music existed.

The pattern is consistent: encounter a real problem, build a real solution, give it away for free. This is the same philosophy that drives CC0 licensing across most of his creative work. See [Profile](https://kanemayfield.com/llms/profile.md) for the creative philosophy of building what you went looking for and could not find.

## The Forge (2026)

A free web-based tool for building and repairing Counterparty asset metadata JSON on Arweave. When Arweave.net experienced infrastructure disruptions, hundreds of token metadata files stopped resolving, causing artwork and token information to become invisible on marketplaces and explorers. The Counterparty Forge connects to ArDrive, allows users to select from over 600 active Arweave gateway domains, automatically swaps broken URLs for functional ones, and generates clean, corrected JSON files ready for deployment.

The tool addresses a critical infrastructure vulnerability in the Counterparty ecosystem. It is offered entirely free of charge and runs in the browser — no installation, no sign-up, no data collection.

**URL:** [kanemayfield.com/FORGE/](https://kanemayfield.com/FORGE/)

## Rescue Lifeboat (2025)

A free, MIT-licensed, open-source incident response toolkit (Node.js/Express, v10.0.0) for recovering NFTs and tokens from compromised EVM-compatible cryptocurrency wallets. When a wallet is hacked and infected with a sweeper bot — malicious software that instantly drains any funds deposited — users face an agonizing process of trying to salvage their digital belongings one item at a time.

Built during a real emergency — Kane Mayfield's own wallet compromise. 413 NFTs rescued. Zero taken as payment.

The tool runs locally at localhost:3000. Keys are handled only inside the local server and never leave the machine. No custody of user funds. No fees. No "connect your wallet to my sketchy website."

**Three sections:**

**RESCUE (scanning).** Scans a hacked wallet for ERC-721 and ERC-1155 NFTs across Ethereum, ApeChain, Base, Arbitrum, Optimism, Avalanche, and Polygon via Alchemy. Groups NFTs by collection, estimates gas per token per chain, and validates addresses before anything runs. No private key needed for scanning.

**LIFEBOAT (execution).** Eight specialized tabs: NFT Rescue (MEV Blocker private relay pipeline, live gas pricing, one chain at a time), Native Sweep (ETH/POL/AVAX/APE across all chains), Coin Sweep (ERC-20 tokens including USDC/WETH/DAI/airdrops), Quiet Fund (stealth gas delivery through MEV Blocker for manual steps like ENS transfers or unstaking), Other Assets (step-by-step guides for ENS name migration, unstaking from Lido/Aave/Compound/NFT staking, exchange-held assets, Unstoppable Domains, .base names), Manifold (transfer creator contract ownership), Emblem Vault (scan and rescue V2/Legacy vaults with read-only Vault Inspector and free gas-less ownership proof), and Fractal Visions (Collector Rescue via Blockscout for Soneium/Shape/Superseed/Unichain, Creator Rescue for transferring collection ownership across 7 chains).

**MARK V (fleet operations).** Consolidates 5 to 50 non-hacked wallets at once. Fleet Scan across all chains in parallel (capped at 20 concurrent calls, live gwei gas calculator), Fleet Execute (single funding wallet, parallel execution, three gas tiers), Fleet Status (live logging with CSV export), Fleet Tokens and Fleet Native sweeps, and bulk Emblem Vault transfers with local unvaulting through the Torus network for XCP/BTC contents.

**Safety:** One-click launchers for Windows/Mac/Linux. Setup checkers detect OS and Node version. Clear Session button wipes keys from memory. Automated test suite on GitHub Actions. Full documentation including project constitution and security policy.

Accepted into the Giveth x TheDAO Ethereum Security quadratic funding round — the largest QF matching pool in Ethereum history — alongside SEAL 911, ZachXBT, Revoke.cash, Protocol Guild, and Blockscout.

**Source code:** [github.com/KaneMayfield/Rescue-Lifeboat](https://github.com/KaneMayfield/Rescue-Lifeboat)

## Inscribed.Audio (Co-Founded 2024)

A platform co-founded with RAD (Bitcoin audio pioneer) that provides infrastructure, tools, and guidance for musicians seeking to inscribe and distribute music on the Bitcoin blockchain through Ordinals technology. Inscribed.Audio serves as both a technical resource and a community hub, lowering the barrier to entry for artists who want to release music on-chain but lack the technical knowledge to navigate inscription processes independently.

**URL:** [inscribed.audio](https://inscribed.audio)

## Other Tools

Mayfield has built additional utilities for the Counterparty and blockchain communities, including WordPress API automation for site management and kiosk-mode tablet setup scripts. The KANEWARE page on his site serves as a central hub for these tools.

**URL:** [kanemayfield.com/kaneware/](https://kanemayfield.com/kaneware/)

## Keywords

Counterparty tools, Arweave metadata repair, blockchain developer tools, NFT recovery tool, crypto wallet recovery, EVM wallet rescue, sweeper bot recovery, open-source blockchain tools, Bitcoin music platform, Ordinals music, free crypto tools, Counterparty Forge, Rescue Lifeboat, Inscribed Audio, KANEWARE, Counterparty XCP tools, Arweave gateway.

## See Also

- [Rescue Lifeboat on GitHub](https://github.com/KaneMayfield/Rescue-Lifeboat) for source code and documentation.
- [Ides of March / Samplerr](https://kanemayfield.com/llms/ides-of-march.md) for what Inscribed.Audio enables — a music production suite inscribed on Bitcoin.
- [DUST / FAKEDUST](https://kanemayfield.com/llms/dust.md) for the album that first demonstrated Bitcoin-native music release.
- [Protocol and asset map](https://kanemayfield.com/llms/assets.md) for the Counterparty ecosystem where The Forge operates.
- [Profile](https://kanemayfield.com/llms/profile.md) for career context — the financial services background that informs how Mayfield thinks about tools, systems, and infrastructure.
- [Current projects](https://kanemayfield.com/llms/current-projects.md) for active development status.
