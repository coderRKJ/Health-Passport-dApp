<p align="center">
  <a href="https://metaplex.com">
    <img alt="Solana dApp" src="https://imgur.com/GVEr0wi />
  </a>
</p>

The forked metaplex Project serves as a primer demo to work on our custom NFT minting site for the Health passport dApp that can be deployed on Solana

- **Creating/Minting** non-fungible tokens;
- **Starting** a variety of auctions for primary/secondary sales;
- and **Visualizing** NFTs in a standard way across wallets and applications.

Metaplex is comprised of two core components: an on-chain program, and a self-hosted front-end web3 application.

## In Depth Developer's Guide

Details on the architecture can be found here:

https://docs.metaplex.com/

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

# Protocol

## Non-fungible tokens

The Metaplex's non-fungible-token standard is a part of the Solana Program Library (SPL), and can be characterized as a unique token with a fixed supply of 1 and 0 decimals. We extended the basic definition of an NFT on Solana to include additional metadata such as URI as defined in ERC-721 on Ethereum.

Below are the types of NFTs that can be created using the Metaplex protocol.

### **Master Edition**

A master edition token, when minted, represents both a non-fungible token on Solana and metadata that allows creators to control the provenance of prints created from the master edition.

Rights to create prints are tokenized itself, and the owner of the master edition can distribute tokens that allow users to create prints from master editions. Additionally, the creator can set the max supply of the master edition just like a regular mint on Solana, with the main difference being that each print is a numbered edition created from it.

A notable and desirable effect of master editions is that as prints are sold, the artwork will still remain visible in the artist's wallet as a master edition, while the prints appear in the purchaser's wallets.

### **Print**

A **print** represents a copy of an NFT, and is created from a Master Edition. Each print has an edition number associated with it.

Usually, prints are created as a part of an auction that has happened on Metaplex, but they could also be created by the creator manually.

For limited auctions, each print number is awarded based on the bid placement.

Prints can be created during [Open Edition](#open-edition) or [Limited Edition](#limited-edition) auction.

### Normal NFT

A normal NFT (like a Master Edition) when minted represents a non-fungible token on Solana and metadata, but lacks rights to print.

An example of a normal NFT would be an artwork that is a one-of-a-kind that, once sold, is no longer within the artist's own wallet, but is in the purchaser's wallet.

## Types of NFTs

The project currently allows two type of Health Passport NFTs on offer for every user: 

Level 1 NFT for a specific Unique ID 
Level 2 NFT for a specific Unique ID

The NFTs will create special priveleges that will be visualized on the placeholder website that's shown below

https://arpit119323.invisionapp.com/console/Health-ckt43oh2r013i012obgd89gkr/ckt4m99s00l6w016mee1jfb8w/play

### Single Item

We wish to have them as a single item NFT and not without the popular notion of re-sale, however we would encourage users to exchange NFTs to other new users who might like to try out our platform.

### Limited Edition

Initially we wish to have 

### Tiered Auction

A tiered auction can contain a mix of the other three auction types as winning placements. For instance, the first place winner could win a Print of Limited Edition NFT A, while the second-place winner could win Normal NFT, and so on. Additionally, all participants who did not win any place could get a Participation NFT Print from a Master Edition (if the Master Edition had no supply limit).

## Royalties

We would not explore royalties at the moment, since health-data are sensitive information unique to a person. 

## Storefronts

Upcoming site will give access based on possession of NFTs with the phantom wallet
