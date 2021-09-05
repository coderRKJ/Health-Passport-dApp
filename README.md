## Health Passport dApp - A Solana Hackathon Entry

The forked metaplex Project serves as a primer demo to work on our custom NFT minting site for the Health passport dApp that can be deployed on Solana

- **Creating/Minting** non-fungible tokens;
- **Visualizing** NFTs in a unique way to have access to unique priveleges on an upcoming platform

The metaplex code comprised of two core components: an on-chain program, and a self-hosted front-end web3 application.


## Installing

Clone the repo, and run `yarn start` to deploy.

```bash
$ git clone https://github.com/coderRKJ/Health-Passport-dApp.git
$ cd health-passport-dapp
$ cd js
$ yarn install
$ yarn bootstrap
$ yarn start
```


## Community

We have a few channels for contact:

- [GitHub Issues](https://github.com/coderRKJ/Health-Passport-dApp/issues)
- Telegram: @CoderRKJ

# Community Feedback

Collected a few curated feedback from the community, which is updated on the Main folder.

# Protocol

## Non-fungible tokens

The Project's non-fungible-token standard is a part of the Solana Program Library (SPL), which is characterized as a unique token with a fixed supply of 1 and 0 decimals. The examples have followed the ERC-721 standards of Ethereum, however we wish to have plans of having Unique non-transferrable utility that is similar to ERC-1238 standards.

Below are the types of NFTs that can be created using the Metaplex protocol.

### **Master Edition**

A master edition token, when minted, represents both a non-fungible token on Solana and metadata that allows creators to control the provenance of prints created from the master edition.

### **Print**

We have retained the initial feature of the print aspect of the metaplex project.

A **print** represents a copy of an NFT, and is created from a Master Edition. Each print has an edition number associated with it.

Usually, prints are created as a part of an auction that has happened on Metaplex, but they could also be created by the creator manually.

For limited auctions, each print number is awarded based on the bid placement.

### Normal NFT

A normal NFT (like a Master Edition) when minted represents a non-fungible token on Solana and metadata, but lacks rights to print.

An example of a normal NFT would be an artwork that is a one-of-a-kind that, once sold, is no longer within the user's own wallet, but is in the purchaser's wallet.

## Types of NFTs

The project currently allows two type of Health Passport NFTs on offer for every user: 

Level 1 NFT for a specific Unique ID 
Level 2 NFT for a specific Unique ID

The NFTs will create special priveleges that will be visualized on the placeholder website that's shown below

https://arpit119323.invisionapp.com/console/Health-ckt43oh2r013i012obgd89gkr/ckt4m99s00l6w016mee1jfb8w/play

## Demo of the code:

https://youtu.be/kaPkMHTtzAg


### Limited Edition

Initially we wish to have an invitational program for select users who wish to try out our platform.

## Conceptual front ends:

https://www.loom.com/share/86787d693211421b9d1ff0440490ea05?sharedAppSource=personal_library

## Custom NFT Minting:

https://www.loom.com/share/415bb7d4831a45f8b40baacc170019e7?sharedAppSource=personal_library

https://www.loom.com/share/9a11c604014040f39732cf803979867c?sharedAppSource=personal_library


## Level 1 NFT Perks:

https://arpitjain.notion.site/arpitjain/dApp-Wearables-28c071a7ca914df68ebce2d05dbed77c

https://paperpencillabs.notion.site/Covid-19-Products-Vitamins-Supplements-d221809c659f41c3b0dbc21d1a9daf83

https://paperpencillabs.notion.site/Hardware-Wallets-5717aea66d9b458ab63055a757cd9402


## Level 2 NFT perks:

https://paperpencillabs.notion.site/paperpencillabs/Level-2-NFT-Privileges-565515de74e24c3c89153b938a559b1f

## Royalties

We would not explore royalties at the moment, since health-data are sensitive information unique to a person. 

## Storefronts

Upcoming site will give access based on possession of NFTs with the phantom wallet

Please reach out to the Telegram handle if you wish to contribute further to the Project
