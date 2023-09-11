# Fundle

Fundle is a Quadratic Funding Platform that is powered by a Lossless Pool generated from DeFi fixed yields. Beyond the traditional direct transfers, donors have the option give without losing anything by simply depositing funds to the protocol for an amount of time. They will get back 100% of their funds risk-free, meanwhile NPOs get to keep the yields (distributed quadratically) to support their causes.

This unique platform solves the problem for many people who are interested to help but come across common hurdles, like:

1. **Decision fatigue from having to evaluate and pick from hundreds of NPOs**: Fundle offers direct deposits to the quadratic pool which automatically allocates to causes that the public care about the most
2. **Needing to do research and verify that the recipient is indeed a legitimate beneficiary**: All the beneficiaries listed on Fundle have been evaluated and accredited by a central authority before they get to be part of the protocol
3. **Transparency of donation distribution**: How the donations will be distributed is already programmed in a smart contract and the status can be monitored in real-time through Fundle
4. **Finding more economically efficient options for donating**: Choosing to spend a budget on even the most deserving charity can be a pain in these challenging times, so Fundle offers a lossless donation option where donors can get back all the money they deposited and still make a huge impact.

## Table of Contents
- [Introduction][#a-quadratic-fundraising-platform-powered-by-risk-free-yields]
- [How Fundle Works](#how-fundle-works)
- [Technologies Used](#technologies-used)
- [Future Developments](#future-developments)
- [Deployed Contract Addresses](#deployed-contract-addresses)

## A Quadratic Fundraising Platform Powered by Risk Free Yields

Bringing fundraising to the blockchain offers advantages that cannot be found anywhere else. For organizations, fundraising through a completely transparent platform can boost their credibility and streamline the disbursement process for them. And for donors, they can find incredibly efficient systems to maximize the impact of even the smallest contributions. 

Fundle is taking on the huge challenge of building a credible fundraising platform that opens possibilities for lossless donations. Through fixed yield, people who are economically conscious can contribute by just parking their funds in the platform. **And because it is risk-free, it can radically lower the barrier for anyone who would like to help worthy causes.**

Aside from that, users can directly donate to the matching pool where their contributions will affect how the quadratic pool from fixed yields is distributed among NPOs.

Only the accredited AA wallets can be listed in the donation pool, so while the donation process is convenient, it is also official. The flow of funds is also fully transparent and cannot be tampered with, so it will be open for anyone to monitor. 

## How Fundle Works

The user journey for NPOs:

1. A central authority accredits an NPO before getting listed on Fundle
2. Accredited NPO generates a special wallet to be listed and receive funds on Fundle
3. After a funding round, all direct donations as well as the matching funds from the quadratic pool will be distributed to the NPO

The user journey for Donors:

1. Donors can donate in three ways. (1) They can park their DAI in the protocol and the yield it generates becomes their donation, (2) They can directly donate their DAI to a project of their choice, and (3) They can send their donation to the quadratic pool and it will match the direct donations sent to each NPO.
2. If they choose to park their DAI and generate a lossless donation, they will be prompted to pick which fixed yield strategy to use for their funds
3. They can withdraw their deposits anytime, while the generated yields will go to Fundle's quadratic pool
3. Donations that go to the quadratic pool will be distributed according to how many people directly donated to a project and how much they donated. This ensures that the funds go to organizations that people deem most deserving

## Technologies Used

- **Quadratic Funding Mechanism**: Fundle used a quadratic pool that takes in direct donations and yield-generated donations, and then it distributes them to match the individual donations made to each NPO

- **Pendle’s PT sUSDC**: Pendle’s fixed yield on fUSDC made the lossless donation pool possible. This is the technology that enables the protocol to generate risk-free yields for the quadratic pool

- **DAI and sDAI**: The user can also have the option to generate fixed yield from their funds through MakerDAO and SparkProtocol's DAI and sDAI

- **Axelar**: Interchain donations were made possible because of Axelar message and token passing from Mantle and Linea to Goerli 

- **Mantle**: We have deployed Donation Relayer contracts on Mantle for user who chose the network's hyperscale performance, data availability, and robust security

- **Linea**: We also deployed a contract that accepts donations from Linea for users who chose the network for its seamless integration with Metamask

- **Nouns Artwork**: We used Nouns’ assets to create a colorful UI theme that fosters optimism

## Future Developments

We are planning to make Fundle a holistic platform for fundraising and we already have a few ideas on how we would like to improve on the MVP. To mention some:

- A gamified way to incentivize users to recurringly donate to their chosen charity
- An AA wallet factory to enable the central authority to generate special purpose-bound wallets for beneficiaries
- A token-gated page where NPOs can communicate to their respective donors and boost engagement and transparency
- Integrating attestations to NPO wallets for donor feedback and suggestions

## Deployed Contract Addresses

