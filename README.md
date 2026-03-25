## Crypto Trading Foundry

A complete Automated Market Maker (AMM) implementation built with Foundry, featuring token pair contracts, pair factory, and routing logic with comprehensive test coverage.

### Project status
- ✅ Token pair interface and implementation (`TokenPair.sol`, `ITokenPair.sol`)
- ✅ Pair factory contract (`PairFactory.sol`, `IPairFactory.sol`)
- ✅ AMM router contract (`AMMRouter.sol`, `IAMMRouter.sol`)
- ✅ AMM library utilities (`AMMLibrary.sol`)
- ✅ Comprehensive Foundry test suite with ERC20 mocks
- ✅ Full integration tests for all components

### Prerequisites
- [Foundry](https://book.getfoundry.sh/getting-started/installation)
- Node.js (only needed for tooling in `package.json`; contracts/tests run via Foundry)


### Install & build
```bash
forge install
forge build


### Test
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```
