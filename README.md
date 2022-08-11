# Semper

### Brief description

An Advanced Trading Suite with focus on [Cryptocurrencies](https://en.wikipedia.org/wiki/Cryptocurrency) and being developed as a [Free and Open-Source Software (FOSS)](https://en.wikipedia.org/wiki/Free_and_open-source_software). 

It is intended to enable the [trading]([trading](https://en.wikipedia.org/wiki/Trade)) itself, as well as the development of strategies and personalized parameterization. Thus, open source code and free distribution do not preclude the use of proprietary strategies and/or parameters.

Much of the project is being decided and learned during development. That is why many changes are expected, including some radical ones. Where the major version is zero (eg 0.x.x.x), the minimum to release or publish has not yet been reached.

### In-depth description

Cryptocurrencies, also referred to as cryptoassets, are mediums of exchange that make use of blockchain to issue, store and transact funds. A [blockchain](https://en.wikipedia.org/wiki/Blockchain), on the other hand, is a distributed ledger based on cryptography that runs on top of computer networks. Examples of cryptocurrencies are: [Bitcoin (BTC or XBT)](https://en.wikipedia.org/wiki/Bitcoin), [Ethereum (ETH)](https://en.wikipedia.org/wiki/Ethereum) and others, including those classified as [stablecoins](https://en.wikipedia.org/wiki/Stablecoin), which are guaranteed to be redeemed at a pre-established value in units of other assets, such as [Tether (USDT)](https://en.wikipedia.org/wiki/Tether_(cryptocurrency)), pegged to the US Dollar, the [Stasis Euro (EURS)](https://eurs.stasis.net/), pegged to the Euro, among others.

Similar to [brokers](https://en.wikipedia.org/wiki/Broker), [currency exchanges](https://en.wikipedia.org/wiki/Bureau_de_change) and [stock exchanges](https://en.wikipedia.org/wiki/Stock_exchange) in the traditional market, there is in the context of cryptocurrencies what is called Exchange, short for [Digital Currency Exchange (DCE)](https://en.wikipedia.org/wiki/Cryptocurrency_exchange). Entities of this nature are intermediaries that hold the funds and provide depositors with the possibility of trading with other users. When in an advanced stage of development, Semper will carry out assisted manual trading and/or [algorithmic/automated trading](https://en.wikipedia.org/wiki/Automated_trading_system), executing operations to buy and sell assets with a view to profit. This will be possible through integrations with Exchanges, since the vast majority have at least one Application Programming Interface ([API](https://en.wikipedia.org/wiki/API)).

#### Schematic

![Schematic](./docs/schematic.png?raw=true "Schematic")

- **HyperX** will be the module in charge of cryptography, data serialization, connecting to remote APIs and managing connectors for each account
- **Connectors** will be responsible for everything specific to each API or DCE, knowing how to invoke their remote procedures ([wrapper](https://en.wikipedia.org/wiki/Wrapper_library#Cross-language/runtime_interoperability)), build requests and translate responses ([parser](https://en.wikipedia.org/wiki/Parsing#Parser))
- **xLedger** will be the module that will work as a [ledger](https://en.wikipedia.org/wiki/Ledger) and [middleware](https://en.wikipedia.org/wiki/Middleware_(distributed_applications)), making it possible to work with different accounts simultaneously
- **Hazard** will be the module capable of simulating and executing trading strategies, allowing the use of different parameters, in addition to assisting manual trading

### Roadmap and changelog

Check the other branches as there might be work running there. The roadmap is yet to be worked out, so take a look at the schematic above.

#### v0.0.0.0: Repository initialization

Nothing published or released yet!

### License, credits, feedback and donation

[BSD 3-Clause "New" or "Revised" License](./LICENSE.md)  
Developed by [Ezequiel Lage](https://twitter.com/ezlage), Sponsored by [Lageteck](https://lageteck.com)  
Any and all suggestions, criticisms and contributions are welcome!  
Get in touch via Issues, Discussions and Pull Requests  

#### Support this initiative!
BTC: 1Nw2fzDgtXM5X219Q9VtJ7WaSTDPua3oe8  
DASH: XeEuQk3za87DTtNZGkriRXMAJPoMbXNjUA  
LTC: LgMYNhUREb2kgXpBXoybgjtJM7QSNZKs14  
ZEC: t1dtNs9nNphKdLrro3JPzvE2r5E48doboM1  
ERC20*: 0xbc024170e10e097140d4be5c30fd4ed6220cfb57  
\* Any ERC20 token supported by Binance (ETH, USDC, USDT, etc)