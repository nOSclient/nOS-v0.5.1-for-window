# nOS-v0.5.1-for-window
What's New?

Added ability to perform multiple test invokes in nOS API.
Updated token balance fetches to reduce number of RPC requests.
Updated block polling frequency to reduce number of RPC requests.
Updated account holdings to sort tokens.
Updated account holdings to localize token amounts.
Fixed NEO RPC node selection when calculating block height.
Fixed primary holding icon positioning in account breakdown chart.
SHA256 Checksums:

Windows: 7c18b1b341f84a0459ee3b65202c61bbd48fda0be8531ab1f1166d7999b97ffe

macOS: a74da31981d5a0cee35e935f11954013441893c8e9607ca8aa2ec473824c164d

Linux (AppImage): 1be89b4dbd16b9dd83f9bb0613eede2255bd8e77b318a8875778eb95acc42c6c

Linux (snap): ce4168481eabc3a52a7a4ffca658232ed9a4da6a0a5799f5e9ed2ca7a47d130c


nOS
             

nOS is a NEO-powered virtual operating system that serves as the gateway to the Blockchain-powered Smart Economy.

The nOS Client (Developer MVP Release) allows for the development of Decentralized Applications that interact with Smart Contracts in the back-end.

Getting Started with nOS
The standalone client installers can be found here. To build manually, the client can be cloned from GitHub and run using the development steps below.

Commands
# Cloning from Github
git clone https://github.com/nos/client.git

# Install dependencies and launch the nOS client
# This is used to start developing on the nOS client
yarn install && yarn start

# Testing command
yarn test

# Testing with debug (repl) command
yarn test:debug

# Distribution command
yarn dist
Getting started with nOS Development
Need some help with building nOS dApps? Check out our dedicated documentation website containing useful info for the following topics:

nOS Client API Documentation
Create nOS dApp Usage
nOS Local Setup and usage
Contribution Guidelines
Future resources:

Tutorials
List of known bugs
List of coming features
Contribute to this repository
We welcome contributions to the code base. If you are interested in becoming a contributor, please read the contributing guide that covers the following:

Reporting bugs
Suggesting enhancements
Code contribution guidelines
There is a specific channel called develop on Discord to discuss development.

Contribute by building a dApp on nOS
Check out the documentation of the Create nOS dApp CLI tool to get going quickly.

Resources:

Create nOS dApp repository
Create nOS dApp example (NeoBlog implementation)
nOS Client API Documentation
Releasing
Windows & Linux
We use CircleCI to automatically create builds based upon git tags.

Create a tag, e.g. 1.0.0. a. git tag -a 1.0.0 b. git push origin 1.0.0
Wait for deploy_win64 and deploy_linux jobs to finish on CircleCI.
Open "Artifacts" tab & download executable files.
macOS
Create the distributable, i.e. yarn dist.
Locate executable file dist/nOS-1.0.0.dmg.
