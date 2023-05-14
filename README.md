### Impermax x Uniswap V2 Core

In order to understand the scope of this project and how it works we suggest the following readings:
- [Impermax x Uniswap V2 Whitepaper](https://www.impermax.finance/_files/ugd/5c39d7_4fe2a5f2b65e44998d4d39c4da98a7b9.pdf "Impermax x Uniswap V2 Whitepaper"): this document explains the scope and the components of this project from a high level perspective.
- [UniswapV2 Whitepaper](https://uniswap.org/whitepaper.pdf "UniswapV2 Whitepaper"): this document explains some design choices made while implementing UniswapV2. Many of those choices have been reused in this project.

### Contracts architecture
![enter image description here](https://i.imgur.com/K2wtH3Y.jpg)

### Testing
Some contracts used for testing exceed the limit of 24000 bytes. In order to test them correctly you need to set `"allowUnlimitedContractSize":"true"` in Ganache settings.
