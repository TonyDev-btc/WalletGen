# WalletGen
# WalletGen

WalletGen is a program for generating crypto wallets such as Bitcoin and EVM (ETH, BNB, MATIC, e.t.c), 
as well as searching for forgotten/lost wallets with an existing balance. 

<p align="left">
    <img src="/assets/menu.png" />
</p>

## Description

WalletGen is written in c++ and has an open source code for everyone. The speed of generating wallets exceeds the speed of programs written in python several times and depends more on your graphics card. \
For generating EVM wallet (ETH, BNB, MATIC, e.t.c) keccak256 is used. Bitcoin wallet is generated by Segwit format under Bech32.

## Features

 - generate one Bitcoin wallet.
 - generate one EVM wallet (ETH, BNB, MATIC e.t.c)
 - start searching for Bitoin wallets with balance
 - start searching for EVM wallets with balance

![video gif](/assets/walletgen.gif)

# Searching crypto wallets
You can run a search for 2 types of crypto wallets with balance. 
To start searching for bitcoin wallets, press key 3 in the menu or run start_search_btc.bat. 
To start searching for EVM wallets (Ethereum, BNB, etc.), press the 4 key in the menu or run start_search_evm.bat. \
The speed of searching for wallets depends on your hardware, primarily your video card. Also, depending on your hardware, to increase the chance of finding a wallet with a balance, you can run multiple copies of the program, about 1 to 4, or more if you have a powerful video card.

## My Find
I also managed to find 2 Bitcoin wallets with balance. 
the first was with 0.000032 bitcoin and the second was with 0.528 bitcoin (3800$ at the time of finding). 
link to the wallet: https://mempool.space/ru/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay.

<p align="left">
    <img src="/assets/found_wallet.png" />
</p>


## Download
 - [Windows x64](../../releases)

## Build

Open the project (WalletGen.sln) with Visual Studio or use another compiler, install the required dependencies and build the project.

### Download vcpkg and libssl

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.ba
> .\vcpkg\vcpkg integrate instal
> .\vcpkg\vcpkg install openssl:x64-windows
```

## Run from cmd

 - start WalletGen.exe (start without parameters)
 - start WalletGen.exe gen-btc <number> (generate the required number of bitcoin wallets)
 - start WalletGen.exe gen-evm/gen-eth <number> (generate the required number of EVM wallets)
 - start WalletGen.exe search-btc (start search for bitcoin wallets with balance)
 - start WalletGen.exe search-evm/search-eth (start search for EVM wallets with balance)

## Disclaimer
The program is created for educational purposes only. The developer is not responsible for any actions with found wallets using this program.

## Author Support
I would sincerely welcome your support. If you have found a forgotten or lost wallet using this program, I hope you will share a small part of your find.
my crypto wallets: \
Bitcoin: bc1qm2hla5zg735uqpgjtp3va4djqhh9zd8derzrwx \
EVM (ETH, BNB, MATIC, e.t.c): 0x8BCa04cA3e65fa7ECE2314e02149F6Ef4F3A0060 \
Litecoin: ltc1qa4ermet8czres4aunf33zwe35sk6peq6tg6cc8 \
USDT TRC20: TFu3ydp1tSDhCtrHNsVSVxriVGhHvVzUu9