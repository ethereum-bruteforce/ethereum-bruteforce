# Ethereum Brute Force: Unlocking the Power of WalletGen

Need a powerful tool for **Ethereum brute force**? **WalletGen** is a leading-edge, open-source solution designed to help you generate, test, and potentially recover your lost or inaccessible Ethereum (ETH) and other EVM-compatible wallets. This tool allows you to perform brute-force seed phrase testing and is optimized for speed.

<!--
Meta description:
Looking for a powerful Ethereum brute force tool? WalletGen is the fast, open-source solution. Test seed phrases, generate wallets, and potentially recover your Ethereum.
-->

## Quick Navigation
- [How It Works](#how-it-works)
- [Why WalletGen](#why-walletgen)
- [Features](#features)
- [Download WalletGen](#how-to-start)
- [Database Download](#download-and-use-database-for-more-speed)
- [The Program Found a Wallet - What Next?](#the-program-found-a-wallet--whats-next)
- [Recovery Your Bitcoin Wallet](#recovery-your-bitcoin-wallet)
- [My Finds](#my-finds)
- [FAQ](#-frequently-asked-questions-faq)
- [Build Instructions](#building-the-project)
- [Donate](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="Ethereum bruteforce" title="WalletGen Ethereum Brute Force Tool" height="460" src="/default/visual.webp" />
</p>

⚠️ **Disclaimer**: WalletGen is a research and educational tool. It is not intended for unauthorized access or malicious activity. Use it responsibly and only with wallets you own or have permission to access.

## How It Works

WalletGen generates wallets, including Ethereum wallets, using the [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki) standard, and the [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing algorithm for EVM-based chains such as Ethereum.

The software checks generated Ethereum addresses against known address databases or checks balances in real-time via public blockchain explorers. This systematic approach allows for the identification of potentially valuable wallets.

Wallet Gen is built in C++ and open-source, offering transparency and community collaboration. Wallet Gen is designed for faster wallet generation compared to Python-based alternatives, taking advantage of your CPU & GPU.

##  Why WalletGen?

If you're looking for an efficient **Ethereum brute force** tool, choose **WalletGen**. Written in C++ and optimized for multi-threaded CPU and GPU usage, it provides performance that is up to **10x faster** than many similar tools. Whether you’re exploring lost wallets, validating key spaces, or working to recover your own, WalletGen delivers the speed and reliability you need.

## Features

-   **Ethereum Wallet Generation:** Supports creating Ethereum wallets.
-   **Brute-Force Search:** Use brute-force techniques to find existing wallets with balances on the Ethereum network.
-   **Algorithm Support:** Designed for EVM wallets with Keccak256 algorithm.
-   **Database Integration:** Download and use databases to improve search speed.
-   **High Speed Operation:** Fully uses CPU and GPU for best performance.
-   **Bitcoin Wallet Recovery:** The program also allows for Bitcoin wallet recovery by seed phrase (mnemonic phrase).

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="Ethereum bruteforce demo" title="WalletGen Ethereum Brute Force Demo" src="/default/simple.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="Ethereum bruteforce on Linux" title="WalletGen Ethereum Brute Force on Linux" src="/default/recent.webp" />
</p>

# How to start

## Windows 
- Download [Release](../../releases) 
- Unpack anywhere
- Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget 
or download [Release for Linux](../../releases) 





## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** allows you to use brute-force methods for finding crypto wallets with balances.

### For Bitcoin (BTC) wallets:

*   Select option 3 in the menu or run start_search_btc.bat to search Bitcoin wallets via the internet. This will take longer, as it uses real-time balance checks.
*   Select option 6 to search Bitcoin wallets using the database.  This offers a faster method by comparing generated wallets against a pre-existing database of known addresses.

### For EVM wallets (Ethereum, BNB, MATIC, etc.):

*   Select option 5 or run start_search_evm.bat to search for EVM wallets via the internet. This will check balances in real-time.
*   Select option 6 to search EVM wallets using the database. This is the faster approach, comparing generated wallets against a database of addresses known to hold balances.

### Speed Considerations:

*   The speed of the search depends on your hardware, particularly the GPU. To maximize speed, run multiple program instances (1 to 4).

## The Program Found a Wallet — What’s Next?

When the program finds a wallet with a balance:
*   The search stops immediately.
*   Wallet details are shown in the console.
*   This data is saved in the ``found_wallets.txt`` file.

### How to Access the Funds?
1.  Import the **mnemonic seed phrase** from the located wallet into a compatible crypto wallet.
2.  You can then transfer the funds to your own wallet.

## Recovery Your Bitcoin Wallet

WalletGen can recover your Bitcoin wallet using the seed phrase (mnemonic phrase). The program supports entering a complete seed phrase, as well as searching for missing words.

### Process Description

#### Search for missing words:

If your seed phrase is incomplete, use * as a placeholder.

#### Entering a complete seed-phrase:

Enter the full 12-word seed.

![recovery](/default/shell.webp)

### Important recommendations

*   Seed-phrase must contain exactly 12 words.
*   Use only the * symbol to search for missing words.
*   Searching for missing words may take time.
*   Successful recovery stops the program and saves data.

## My Finds

![mywallet](/default/slate.webp)

I’ve recovered two BTC wallets with a balance. The first had 0.000032 BTC, the second contained 0.0528 BTC (roughly $4800 at the time of discovery).
Here’s the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/default/analyze.webp" />
</p>

### New Find 4/9/2025

After a week of non-stop wallet searching, I finally found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is my 4th and biggest find of all time.

![image](/default/details.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/default/aspect.webp)

## Building the Project

1. Open the project file (`CryptoWalletGen.sln`) in Visual Studio or any compatible C++ compiler.
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
You can download the WalletGen given on the [release download page](../../releases) 

### ❓ Where can I download a database of known addresses with balance?
You can download the current database given on the [release   page](../../releases) 

### ❓ Can WalletGen help me recover a lost Bitcoin wallet?
Yes. WalletGen uses brute-force seed generation and a known-address database to help users potentially **recover lost Bitcoin wallets**.

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

If you find a wallet with a balance, please consider donating a small portion as a thank you. This motivates me to keep working on the program!

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)