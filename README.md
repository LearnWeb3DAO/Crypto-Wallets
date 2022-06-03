# Level 4 - Crypto-Wallets

In this module you will learn about what are Crypto Wallets and how to download one. 🤔

## Introduction
To understand crypto wallets fully, we have to understand some concepts about the blockchain, which will help us in understanding how a wallet aids us. Let's start off.

## What is an address? 🤨

An address is a string of text generated using cryptography to represent your account on the blockchain. This address can be shared publicly with others, and is completely safe to do so. You can send and receive funds from and to your wallet address. Basically, the address is your unique identifier on the blockchain and represents your 'account'. An example of an Ethereum address is: `0x01573Df433484fCBe6325a0c6E051Dc62Ab107D1`.

## What are private keys? 🔐

A private key is the counterpart to an address. Each address has an associated private key. As the name suggests though, this is meant to be kept private and not shared with anyone.

You can think of it like a password, a really strong one, that contains a bunch of letters and numbers that allow you to prove ownership over your address. Anyone who has the private key has access to make transactions from your address i.e. send money from your address to theirs. 

A private key looks something like this: `E9873D79C6D87DC0FB6A5778633389F4453213303DA61F20BD67FC233AA33262`

If you think of your address as a username for your account, the private key is it's password. Therefore sharing your address is okay, but never ever share your private key or someone might steal your funds - and then nothing can be done about it. 

**Caution: Since blockchains are decentralized, there is no 'forgot password' option. If you lose your private key, you lose access to your account. Similarly, if someone steals your private key and steals your funds, you cannot do anything about it. It is VERY important to keep this private key safe.**

For developers, we often use the private key as part of our codebase to perform certain transactions, such as deploying our own smart contracts to the Ethereum network. While you are still learning, we highly suggest you use a separate account entirely for development than you use for storing any sort of funds. Unfortunately, beginner developers often use the same account they have funds on, and accidentally share their codebase publicly - and hackers can see your private key in the codebase and end up stealing funds. Please take that as a tale of caution.

## What is a seed phrase? 👮‍♀️

A seed phrase is like a master password - the password of passwords!

Think of a password manager, something like Lastpass or 1Password. These applications, within them, store your usernames and passwords for other apps securely, and themselves have a password. So, if someone hacks your password manager, they also get access to all accounts stored within it.

A crypto wallet is kind of like a password manager, where you can manage multiple blockchain accounts. If the private key is the password to a single account, the seed phrase is kind of like the master password for that wallet.

When you create a new crypto wallet, you will be presented with a seed phrase you should absolutely securely store and back up. Any new accounts you generate from inside that wallet will all be linked to the seed phrase. That one seed phrase will always generate the same accounts, with the same private keys and addresses for each.

So for example if you created a wallet, and then created 5 accounts within it, your seed phrase manages all 5. If you wanted to switch to a new wallet, you could either import the 5 wallets individually - by using their individual private keys - or just import using the seed phrase, and it would regenerate the same 5 accounts.

An example of a seed phrase is: `dove lumber quote board young robust kit invite plastic regular skull history`

## What is a crypto wallet then? 😛

Crypto wallets are a manager for your accounts, and mainly their private keys. They also allow you to interact with decentralized applications, and allow connecting to a dApp through the wallet, acting as a single sign-on for all applications built on the blockchain. 

At LearnWeb3 as well, you can go into the Dashboard and connect your crypto wallet (after you have set it up), which will let us know what your address is so we can send you some sick NFTs when you graduate from our tracks!

## Setting up a Wallet 🎉

For Ethereum, there are a number of wallet options available. The easiest to get started using, and most developer friendly, are either Metamask or Coinbase Wallet. 

Both are Ethereum crypto wallets that can be installed as browser extensions, or as a mobile apps. You can find the download links below. We suggest downloading any one of them, and setting it up, before proceeding with the track.

- [Download Metamask](https://metamask.io/download.html)
- [Download Coinbase Wallet](https://www.coinbase.com/wallet)

Other alternatives include Trust Wallet, Atomic Wallet, Rainbow Wallet, Frame.sh, etc.
- [Trust Wallet](https://trustwallet.com/)
- [Atomic Wallet](https://atomicwallet.io/)
- [Rainbow Wallet](https://rainbow.me/)
- [Frame.sh](https://frame.sh/)
