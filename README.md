# W3F Grant Proposal

- **Project Name:** Lootmogul
-  **Team Name:** Lootmogul
- **Payment Address:**  (ERC20 USDT)
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2

## Project Overview :page_facing_up:

### Overview

LootMogul is an influencer-led sports metaverse gaming platform powered by exclusive properties (Lands, Stadium, Arenas, etc.), NFTs, and token rewards for the fans and business community.

There are three key stakeholders in the Lootmogul community:

Sports athletes (influencers) engage with their fans in local stadiums, arenas, playgrounds, etc. through multiplayer blockchain sports games (basketball, football, soccer, baseball, pickleball, etc.) and In-Real-Life (IRL) rewards (Shoes, fitness wear, event ticket & passes, etc.)
Fans enjoy an immersive experience with influencers by playing games with sports athletes' avatars, forming dream teams (ex. Larry Bird playing against Shaq), and competing at a global level.
Land Owners earn revenue from ticket sales, game revenue, NFT revenue, and brand sponsorship.
LootMogul has first mover advantage in this fast-growing $800B industry and has partnered with more than 120 professional athletes from NBA, NFL, MLB, eSports, ICC, etc., and 1.5M+ high-school and college athletes.

LootMogul is expanding the web3 community by bringing web 2 gamers and sports fanatics to the metaverse with a play-to-earn model, real-world perks, experiences, and NFT collections.

LootMogul community - https://www.instagram.com/lootmogul/

Finally, LootMogul's seed round is funded by billion-dollar web 3 crypto companies and web 2 traditional equity venture funds - Harmony, PowerHouse Ventures, BCT, and u2poia with grants from Polygon and Sandbox. Our new investment round is being led by Woodstock, SL2Capital, Animoca Brands, and many others.

### Project Details

![Lootmogul Demo - Build your own metaverse land](https://lootmogul.com/_next/image?url=https%3A%2F%2Fmedia-content.lootmogul.com%2FCreate_Land_2_1440x600_dc8b092056_095d617610.webp&w=3840&q=75)



#### Architecture

![AdMeta Architecture](https://raw.githubusercontent.com/h4n0/gists/master/admeta/admeta_architecture.svg)



#### Technology Stack

- React
- React-native
- Node.js
- 3D Model Design
- Polygon Matic
- Strapi CMS

### Ecosystem Fit



## Team :busts_in_silhouette:

### Team members (In order of joining time)



### Contact

- **Contact Name:** Han Zhao
- **Contact Email:** windzhaohan@gmail.com
- **Website:** https://admeta.network/

### Legal Structure

- **Registered Address:** No legal structure yet.
- **Registered Legal Entity:** No legal structure yet.

### Team's experience

Han and John are core developers as well as project managers at Litentry, and both of them are main developers who implemented the Litentry parachain from scratch. Litentry is an identity aggregation focused company in Polkadot ecosystem, and has got the Web3 Foundation grant since 2019.

Yvonne has more than 8 years experience of digital marketing, and she has a deep understanding and practice of various online marketing and advertising methods. She also initialized this idea of combining advertisement and privacy preserving, to archive the goal of data protection.

Shihao is a full stack developer at Litentry, who contributes a lot in Litentry and Web3Go web apps and backend apps.

Hao is the founder of Web3Go, VP of Litentry, who has a very solid practical experience on both blockchain and data science.

Note: Both [Litentry](https://www.litentry.com/) and [Web3Go](https://github.com/w3f/Grants-Program/blob/master/applications/Web3Go.md) are Web3 granted projects.

### Team Code Repos

- https://github.com/litentry/litentry-parachain
- https://github.com/litentry/litentry-pallets
- https://github.com/web3go-xyz/web3go

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/h4n0 Han Zhao
- https://github.com/Shihao66 Shihao Zhao
- https://github.com/Moehringen Hao Ding

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/zhaohan6
- https://www.linkedin.com/in/shihao-zhao-55752685/
- https://www.linkedin.com/in/hao-ding-msc-pmp-64411193/

## Development Status :open_book:

- https://github.com/AdMetaNetwork/admeta This is the AdMeta Substrate chain implementation. We already started to build the pallets mentioned in Milestone 1 below.
- https://github.com/AdMetaNetwork/admeta-webapp This is our web app repo according to Milestone 1. We already had a single page app with polkadot js API integrated now.
- https://github.com/AdMetaNetwork/admeta-decentraland This is a simple asset built with Decentraland SDK, and currently it's just for a demo purpose.
- https://admeta.network/ We also have the first version of our website.

## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration:** 1 months
- **Full-Time Equivalent (FTE):** 2 FTE
- **Total Costs:** 12,000 USD

### Milestone 1 — Substrate Chain with Impression Ad, Web App


- **Estimated duration:** 6 month
- **FTE:** 2
- **Costs:** 12,000 USD

| Number | Deliverable                 | Specification                                                                                                                                                                                                                                                                                                  |
| -----: | --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|    0a. | License                     | GPLv3                                                                                                                                                                                                                                                                                                          |
|    0b. | Documentation               | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works.                                                                  |
|    0c. | Testing Guide               | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests.                                                                                                                                                              |
|    0d. | Docker                      | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone.                                                                                                                                                                                                  |
|    0e. | Article                     | We will publish an **article**/workshop that explains our advertising workflow as well as technical details.                                                                                                                                                                                                   |
|     1. | Substrate module: ad        | We will create a Substrate module that will allow advertiser to create impression ads, and with council's approval, this ad will be ready to be displayed. If ads are rejected by the council(e.g. illegal or pornographic content), the advertiser's proposal bond will be slashed and collected in treasury. |
|     2. | Substrate module: user mock | We will create a Substrate module that will first store users data on chain, to test and verify our logic. Also, user can update their data, control what data should be used, and these data are used to find the best matching ad for user.                                                                  |
|     3. | Substrate chain             | Module ad and user can be integrated into a substrate node, to enable users access of all approved ads, receive rewards, etc. This chain will integrate treasury, council, democracy and also other essential pallets, to build a full-featured blockchain.                                                    |
|     4. | Web App                     | We will create a web app, to let users easily interact with our substrate node. Users can claim rewards from viewing and clicking ads, and they can also configure their ad preferences and decide if they are willing to view ads or not.                                                                     |

## Future Plans

The next step is to have sensitive data stored in TEE. Also, we will build more ad types, like click ads and acquisition/action ads. Meanwhile, we will implement a Chrome extension to simplify the claim process, and an Ad asset on Decentraland(or other Metaverse platform) to enable land holders to use our ad assets conveniently.

In a long run, we will cooperate and adapt our products with more Metaverse platforms, and also we will develop more creative and interactive ad types.

## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Personal recommendation
