# GAAVE

## Problem Statement

There is not enough philanthropy in the world due to the lack of engagement towards donors.

## Solution

A platform where crypto users could deposit their cryptocurrencies to generate yield for a cause. To further drive engagement, soulbound NFTs would be available for claim whenever a user reaches certain milestone when generating yield for a cause.

![claimable-nfts.drawio.svg](https://raw.githubusercontent.com/GigaChadds/.github/main/profile/assets/claimable-nfts.drawio.svg)

## Core Features

### Donors

- Stake cryptocurrencies to generate yield for charity.

```
[Action] User connects his/her metamask
[View] User will be shown the varies campaigns that is open for donations
[Action] User selects a campaign
[View] User will be showned all the APYs with the supported cryptocurrencies
[Action] User selects cryptocurrency to deposit
[View] A modal pops up
[Action] User enters amount of cryptocurrency to deposit and clicks on proceed
[View] Metamask window pops up
[Action] User signs metamask transaction
[View] User sees how much capital is deposited & how much yield was generated so far
```

- Claim NFTs based on yield milestones.

```
[Action] User connects his/her metamask
[View] User will be shown the varies campaigns that is open for donations
[Action] User selects a campaign
[View] User will be shown all of his claimable NFTs based on his/her yield milestones related to the campaign
[Action] User clicks claim NFT button
[View] Metamask window pops up
[Action] User signs metamask transaction, paying only gas fees
[View] User will be able to view his NFT on opensea and on his/her profile
```

- Unstake cryptocurrencies whenever

```
[Action] User connects his/her metamask
[View] User will be shown the varies campaigns that is open for donations
[Action] User selects a campaign
[View] User will be showned all the APYs with the supported cryptocurrencies
[Action] User select cryptocurrencies to unstake
[View] Metamask window pops up
[Action] User signs metamask transaction, paying only gas fees
```

- Claim yield from AAVE's borrowing/lending protocol on behalf of GAAVE

```
[Action] User connects his/her metamask
[View] User will be shown his/her total claimable yield (adds up if it yield was from different cryptocurrencies)
[Action] User clicks on claim yield
[View] User signs metamask transaction
[Action] User sees his/her yield in his metamask wallet
```

### Fundraisers

- Create Campaigns

```
[Action] User connects his/her metamask
[Action] User clicks on create campaign button
[View] User will be shown with a form for campaign creation
[Action] User fills in the campaign details and submits
[View] User will be able to see the campaign in the homepage
```

- Receive Donations from Donors

### DAO

- Vote on Fundraising Campaign
- View Proposed Campaigns
- View Current Campaign progress

## Technical Architecture

## Sponsor Technologies

This project would not have been possible without these wonderful underlying technology:

- Polygon
- IPFS
- AAVE
- The Graph
