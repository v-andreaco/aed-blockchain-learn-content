# Exercise: Install Truffle

## About Truffle

Truffle is the most popular development framework for Ethereum. It can easily be installed with the help of the node package manager.

With Truffle, you get:

- Built-in smart contract compilation, linking, deployment and binary management.
- Automated contract testing for rapid development.
Scriptable, extensible deployment & migrations framework.
- Network management for deploying to any number of public & private networks.
- Package management with EthPM & NPM, using the ERC190 standard.
- Interactive console for direct contract communication.
Configurable build pipeline with support for tight integration.
- External script runner that executes scripts within a Truffle environment.

## Confirm that Node.js is installed

Truffle requires that you have Node.js v8.9.4 or greater. With Node.js, you automatically get the Node package manager, referred to as npm, installed on your computer.

To check if you have Node.js installed, run this command in your terminal:

`node -v`

To confirm that you have npm installed you can run this command in your terminal:

`npm -v`

## Install Truffle

From your terminal, you can install Truffle with the help of npm. Type:

`npm install -g truffle`

To confirm truffle is installed, type:

`truffle`

That will show the version installed and present the list of commands available to use Truffle with:

```solidity
$ truffle
Truffle v5.1.7 - a development framework for Ethereum

Usage: truffle <command> [options]

Commands:
  build     Execute build pipeline (if configuration present)
  compile   Compile contract source files
  config    Set user-level configuration options
  console   Run a console with contract abstractions and commands available
  create    Helper to create new contracts, migrations and tests
  debug     Interactively debug any transaction on the blockchain (experimental)
  deploy    (alias for migrate)
  develop   Open a console with a local development blockchain
  exec      Execute a JS module within this Truffle environment
  help      List all commands or provide information about a specific command
  init      Initialize new and empty Ethereum project
  install   Install a package from the Ethereum Package Registry
  migrate   Run migrations to deploy contracts
  networks  Show addresses for deployed contracts on each network
  obtain    Fetch and cache a specified compiler
  opcode    Print the compiled opcodes for a given contract
  publish   Publish a package to the Ethereum Package Registry
  run       Run a third-party command
  test      Run JavaScript and Solidity tests
  unbox     Download a Truffle Box, a pre-built Truffle project
  version   Show version number and exit
  watch     Watch filesystem for changes and rebuild the project automatically

See more at http://truffleframework.com/docs
```