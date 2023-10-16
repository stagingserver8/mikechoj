---
title: Web3 - The Bird's Eye View
description: The Evolution of Asset-Agnostic Financial Infrastructure
date: 2023-08-28 17:51:42
draft: false
tags: ['web3']
---

Web3, crypto, and blockchain often seem like a jumble of interrelated terms. Figuring out what they mean and how they fit together can be confusing—I know it was for me. With this in mind, I've written this post to clarify the foundations for myself and to provide a mental compass that might also be useful for others seeking a primer on the subject

We will kick things off with a whirlwind tour of the history of the internet, explore the basics of how blockchain has introduced a new system for transferring value, and delve into the emergence of new technologies that could potentially serve as the backbone for a new financial system.

A lot to cover, so let's get going!

#1 Internet: A Digital Highway for Data
Let’s take a trip down memory lane and start with the internet in the 1960s.

The internet is like a colossal highway system for data, born from a project called ARPANET. It was an era where computers began to "talk" by sending data packets to each other. This was the dawn of a revolution, a few computers forming a web that would soon envelop the world.

Fast forward to the '80s, and the TCP/IP protocol became the universal language, or a suite of protocols, ensuring seamless communication. It was like the building of bridges and roads, connecting distant towns and villages.

By the '90s, the World Wide Web transformed this data highway into something tangible. Browsers and hyperlinks turned raw data into websites we could view, edit, and explore. It was akin to setting up marketplaces and stores along those roads, each offering something unique.

Today, the essence remains the same. Whether we're streaming movies, competing in esports, or diving into forums, you're essentially a digital nomad navigating a vast landscape of data packets.

As we all know, the impact was almost immediate and profound. Anyone around the world, with a device and an internet connection, could send and receive text, file, image, audio, or video almost instantly. It democratised the access to this information and empowered anyone with an internet connection to take part.

The children of that era were many: email for text and files, communication tools like Skype and Zoom, social media for images and stories, and platforms like YouTube, Amazon, Netflix, and Google for everything from video sharing to shopping.

However, there are cracks behind this ‘centralised’ model that are starting to show. The tools and large databases which facilitate this exchange of information are largely owned by for-profit companies, creating a delicate balance. For social networks, people often trade small pieces of their privacy and control over their data in exchange for access to these tools. With banks, the trade-off may include high fees, less financial control, and the risk of systemic failures that could jeopardise individual assets. In retail, centralised platforms can dictate terms to small sellers, squeezing their margins and collecting valuable consumer data while offering little in return. It's essentially a barter system, where the currency is frequently invisible.

The net seems still positive, but there's a shadow. Most people don't know about any alternatives, so the status quo becomes a heavy anchor.

#2 Bitcoin: The Dawn of Online Money
While the internet allowed for moving data across the digital world, it did not permit money to truly exist or move online.

Now, you might raise an eyebrow and ask: "I have an online bank account, and I can send money. Isn't that moving money on the internet?" Well, not exactly. What about paying for your Spotify subscription with a credit card? Again, not really. The internet moves messages, or instructions, about moving money, not the money itself. When you pay for something online, you're basically sending a request to your bank to transfer funds. It's like sending a letter with instructions rather than handing over cash.

Enter Bitcoin, the first technology to offer a form of ‘money1’ that could be transacted directly between users on the internet, without the need for intermediaries like banks. When someone sends or receives bitcoins, the transaction is added to a ledger called blockchain. To prevent "double spending"—the same bitcoin being spent twice—a network of computers called miners verify, using cryptography, and confirm these transactions so that there is no fraud.

#3 Blockchain: An Accounting System for Online Money
At the heart of Bitcoin lies the blockchain—a big word that simply means a decentralised (not owned by anyone) and transparent ledger.

Instead of one big bank holding all the accounts, the blockchain stores this data in code. To give an example. Let’s say Tom wants to send $10 to Mary using the blockchain. Here is how it works in reality:

Tom inputs Mary’s blockchain address and the amount he wants to send.

Before it's finalised, this transaction needs to be verified. In a blockchain network, various participants (called nodes) check that Tom indeed has $10 to send and that the address he's sending to is valid. Once verified, this transaction is grouped with other verified transactions into a "block."

This block is then added to a "chain" of previous blocks. This is what makes it a "blockchain." The chain serves as a public ledger that's tamper-resistant because changing one block would require changing all subsequent blocks, which is computationally infeasible.

The network then reaches a consensus that the new block is valid (through methods like Proof of Work or Proof of Stake), and then the block is added to the chain.

The network then checks that Tom can do this, puts the transaction in a block, adds that block to a chain of older blocks, and then finalises the $10 transfer (which is of course, nothing more than updating the database entries) from Tom to Mary.

Once the block is added to the chain, Tom's $10 is officially transferred to ary. Both of their new balances are now recorded on the blockchain.

Every transaction, every movement of value, is recorded, verified, and open for inspection viewed by anyone on the blockchain, but it's locked in digital glass, untouchable by rogue hands. However, the identities of Tom and Mary are encrypted for privacy.

It's like a public library where everyone enter, read the books but no one can tear out the pages or scribble in the margins.

Why is this special? Why does it matter?

In essence, I always think of blockchain as a trust mechanism, a technological handshake living on top of the internet that says, "You can count on this”.

Unlike traditional finance, where a few key individuals can control, alter, or hide information, the blockchain's decentralised nature ensures that no single entity has control. As touched on earlier, it operates on a consensus mechanism where multiple parties must agree on the authenticity of a transaction. If something doesn't add up, the network knows it, and the transaction is rejected. But what if we want to build in some rules to this blockchain, for example, allow Tom to send Mary $10 only if a certain event takes place?

And here's where it gets even more exciting: the blockchain has paved the way for something called smart contracts; rules written in code that govern how and when this value can be moved online.

#4 Smart Contracts: Terms of Conditions for Online Transactions
Blockchain technology does two things very well: maintain the supply of an asset, and keep track of ownership. As we saw earlier, it does this by reaching a global consensus of status of the underlying ledger. But it is also the foundation for something called smart contracts.

Think of smart contracts as the legal agreements but with a twist. They are self-executing contracts with the terms and conditions embedded directly into code and with the stamp of trust guaranteed by the blockchain. Unlike traditional contracts, there's no need for lawyers or notaries because smart contracts enforce themselves.

How do they accomplish this? The contracts operate on the blockchain, which is already a trusted and decentralised system. When a smart contract is deployed, it is subject to the same kind of verification as any other transaction. Multiple nodes on the network confirm the contract's code and state changes, creating a consensus that the contract is valid and that its rules should be followed. In essence, the smart contract leverages the blockchain's inherent trust mechanism to gain its own credibility.

Take, for example, a simple smart contract2 resembling a digital piggy bank. You can deposit funds at any time, but withdrawal is only permitted after a specific date. It's a straightforward yet powerful illustration of how smart contracts can govern transactions with precision and trust, all without human intervention.

Sure, you might think to entrust this task to your bank manager, but consider the pitfalls. What if the bank finds itself on shaky financial ground and goes bankrupt? Or what if the manager, despite their best intentions, misplaces your instructions or simply forgets about them? Or your mom comes to the bank manager and asks for the entire piggy bank back. The list of 'what-ifs' could go on and on, and each one represents a potential failure in a system that relies on human intervention.

So to sum up: while blockchain is the trust mechanism, smart contracts are the legal architects, crafting and enforcing the rules that govern transactions within this trust framework without those potential failures.

#5 Token and Standards: Enabling Multi-Asset Blockchains
With the blockchain ledger managing supply and ownership, the only asset that was allowed to benefit from the new rail stack was Bitcoin. Digital tokens and token standards have changed that.

Tokens, serving as digital representations of a particular asset, expanded the capabilities of blockchains to host a wide variety of assets, each with their own rules and functionalities. This is crucial because not all assets are meant to behave the same way, and a one-size-fits-all model like Bitcoin simply won't suffice for all use cases.

Just as a JPEG image is a digital representation of a photograph, a token can be a digital representation of anything that is meant to reliably hold value and reliably be transferred, from a unit of currency to a piece of art or even a share in a company. The key features worth repeating here are the ability to reliably hold of value (supply) and secure, trustworthy change of hands (trading) without intermediaries.

Creating a new digital asset was extremely difficult as it meant you had to build an entirely new blockchain which was a tremendous amount of work. In essence previously, every blockchain was a single-asset ledger. Imagine wanting to develop a new iPhone app, but having to engineer a whole new iPhone just to support it. Each blockchain was essentially a single-asset ledger, severely limiting its versatility.

Enter multi-asset blockchains like Ethereum, which opened the door for an ecosystem allowing diverse digital assets. However, this diversity created a new challenge: how to ensure that these various assets could interact seamlessly with each other and with existing systems.

Recognising this need for consistency across assets, the Ethereum community in 2015 proposed ERC-203, a fungible token standard. This innovation carried substantial benefits. It introduced interoperability, enabling various elements within the ecosystem to "understand each other" and thus streamlining communication and support across an infinite number of tokens. Furthermore, it helped the ecosystem scale by simplifying the creation of new tokens, setting the groundwork for more a a sophisticated and streamlined financial systems and applications.

Returning to our iPhone analogy, consider Ethereum as the App Store of the blockchain world. Just as you can build apps for the iPhone by adhering to the guidelines set by the App Store, standardised token protocols on Ethereum let you create digital assets without having to construct an entirely new blockchain. In other words, you simply follow the established standards, much like app developers adhere to App Store requirements, eliminating the need to reinvent the wheel.

The result was an explosion in the number of digital assets, from around 500 in 2015 to over half a million ERC-20 and 721 standards, representing over 95% of all digital assets in existence today.

#6 Tokens + Token Standards + Smart Contacts = An Asset-Agnostic Financial System
Reflecting on the past decade, it's clear that all the tinkering, experimenting, and ups and downs have given birth to something entirely new—a financial infrastructure native to the internet. True, haven't been any killer applications yet, and the industry faces several headwinds, topics I'll explore in future posts.

However, I think there is a gravitational pull towards blockchains and token standards. Why? Because they all operate in an era of 'asset-agnostic infrastructure.

Consider being an investor in the current system: the US dollar, a company's stock in Riyadh, a gold ETF, a share of a startup bought on AngelList - they all operate on different stacks, and some of them don’t even have any infrastructure to support them at all.

In the new financial infrastructure once an asset becomes a token, it's like being handed a universal passport to this digital financial market. Suddenly, users get considerable flexibility over how they hold an asset, where they trade it, whether and where they leverage it as collateral, and so forth.

#7 DeFi: The Early adopter of asset-agnostic financial infrastructure
The earliest set of use cases of asset-agnostic financial infrastructure is DeFi, or decentralised finance. What exactly is DeFi?

Imagine everything banks and financial institutions do—like saving money, lending, borrowing, or even trading stocks—and now imagine doing it all online peer-to-peer, without any banks or brokers involved. Here is a few things you can do in the DeFi world today:

Lending and Borrowing: Platforms like Compound and Aave allow users to lend and borrow assets directly from one another, setting their own terms without a traditional financial intermediary.

Decentralised Exchanges (DEXs): Uniswap and Sushiswap enable users to trade the token you have borrowed directly with each other, bypassing centralised exchanges, their opening hours and own rules.

Yield Farming: Yearn.Finance introduces innovative ways to earn returns on investments through liquidity provision and staking.

Insurance: You can even use platforms like Nexus Mutual that offering coverage for smart contract risks.

All these capabilities are at your fingertips, accessible within minutes, no matter who you are or where you're located."

Given that DeFi is unregulated, it's often viewed as an experimental sandbox and used by those on the fringes of the financial world. But its potential is immense, and the innovative use cases are only growing. I'll be diving deeper into the universe of DeFi, as well as other standards and use cases such as NFTs, stablecoins etc in future posts, so stay tuned.


Where do we go from here?

I have outlined whatI think is the the groundwork for an evolving financial infrastructure, one where we're already catching early glimpses of applications, such as DeFi coming to life.

From Bitcoin's role in creating online money to Ethereum's multi-asset support; from smart contracts' self-enforcing legal frameworks to token standards like ERC-20, we have established the backdrop for a reliable creation of and movement of digital assets.

But what useful applications can actually be built using this infrastructure? And why haven’t we seen enough use cases already?

While I plan to delve into these challenges and obstacles in future posts, one thing seems to be clear: I can’t help but feel that we may be standing at a cross roads. It's akin to the early days of the internet when we were questioning its value and potential impact (remember this?). Now, with hindsight, we recognise the transformative power of the internet, and we might be on the brink of a similar evolution with Web 3.

Thanks for reading!

Mike

---

Footnotes


Whether Bitcoin is considered money is a subject that has sparked a big debate, one that traverses the realms of economics, law, and philosophy. At its core, the argument revolves around how we define "money" and what it represents in today's rapidly evolving digital world.

2
A smart contract for our Piggy Bank written in Solidity, looks something like this (with comments after //):

contract PiggyBank {

// Store the owner's address (the one who deploys the contract)
    
address public owner;

// Store the unlock date for the piggy bank

    uint256 public unlockDate;

// Set the owner and unlock date at the time of contract deployment

    constructor(uint256 _unlockDate) {
        owner = msg.sender; // Set the owner as the sender of the transaction (deployer)
        unlockDate = _unlockDate; // Set the unlock date (in UNIX timestamp format)
    }

// Deposit function to allow anyone to send funds to the contract
    
function deposit() public payable {

// This function automatically accepts Ether sent to it and adds it to the contract's balance

    }

// Withdraw function to allow the owner to withdraw all funds after the unlock date


    function withdraw() public {
        
// Ensure that only the owner can call the withdrawal

        require(msg.sender == owner, "Only the owner can withdraw");

// Ensure that the current time is greater than or equal to the unlock date

        require(block.timestamp >= unlockDate, "PiggyBank is still locked");       
3
Each smart contact that adheres to the standard must contain those six attributes:

TotalSupply: provides information about the total token supply

BalanceOf: provides account balance of the owner's account

Transfer: executes transfers of a specified number of tokens to a specified address

TransferFrom: executes transfers of a specified number of tokens from a specified address

Approve: allow a spender to withdraw a set number of tokens from a specified account

Allowance: returns a set number of tokens from a spender to the owner
