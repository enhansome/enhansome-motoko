# Awesome Motoko with stars

> An awesome list of Motoko code and resources curated by the community.

> The [Motoko programming language](https://smartcontracts.org/docs/language-guide/motoko.html) is a new, modern and type safe language for developers who want to build the next generation of distributed applications to run on the [Internet Computer](https://dfinity.org) blockchain network.

## Contents

* [Applications](#applications)
  * [Canister tools](#canister-tools)
  * [Cryptocurrencies](#cryptocurrencies)
  * [Decentralized Finance](#decentralized-finance)
  * [Games](#games)
  * [Mining Platform](#mining-platform)
  * [Realestate](#realestate)
  * [Social](#social)
  * [Storage](#storage)
  * [Utilities](#utilities)
  * [Video](#video)
* [Development tools](#development-tools)
  * [Build system](#build-system)
  * [IDEs](#ides)
  * [Testing](#testing)
* [Libraries](#libraries)
  * [Algorithms](#algorithms)
  * [Cryptography](#cryptography)
  * [Data structures](#data-structures)
  * [Encoding](#encoding)
  * [Graphics](#graphics)
  * [Logging](#logging)
  * [Misc](#misc)
  * [Payment](#payment)
  * [Storage](#storage-1)
  * [Templates](#templates)
  * [Text processing](#text-processing)
  * [Web Programming](#web-programming)
* [Registries](#registries)
* [Resources](#resources)
* [Contribute](#contribute)
* [License](#license)

## Applications

Fully functional smart contract.

### Canister tools

* [ic-blackhole](https://github.com/ninegua/ic-blackhole) ⭐ 54 | 🐛 3 | 🌐 Nix | 📅 2025-01-05 - Once a canister sets its only controller to a black hole, it becomes immutable.
* [Canister Tip Jar](https://github.com/ninegua/tipjar) ⭐ 51 | 🐛 4 | 🌐 Motoko | 📅 2026-07-03 - Donate cycles to your favorite canisters on the Internet Computer and keep them live and healthy.
* [motoko\_top\_up\_canister](https://github.com/ORIGYN-SA/motoko_top_up_canister) ⚠️ Archived - Implementation of a canister called periodically by a Node.js service; that top-up automatically user-defined canisters with cycles.
* [candid-spaces](https://github.com/matthewhammer/candid-spaces) ⭐ 15 | 🐛 4 | 🌐 Modelica | 📅 2021-06-30 - A general-purpose candid data lake for canisters' data on the IC.
* [iCAN](https://github.com/PrimLabs/iCAN) ⭐ 15 | 🐛 3 | 🌐 Motoko | 📅 2022-08-15 - A Canister Management Platform, which helps you create canisters in random subnet and manage canisters status efficiently and conveniently.

### Cryptocurrencies

* [ic-token](https://github.com/rocklabs-io/ic-token) ⭐ 85 | 🐛 1 | 🌐 Rust | 📅 2022-05-25 - An ERC-20 style token standard implements for Motoko.
* [extendable-token](https://github.com/Toniq-Labs/extendable-token) ⭐ 82 | 🐛 15 | 🌐 Motoko | 📅 2023-03-23 - This token standard provides a ERC1155/multi-token-like approach with extensions that can add additional functionality based on the purpose of the token.
* [ic-nft](https://github.com/rocklabs-io/ic-nft) ⭐ 45 | 🐛 1 | 🌐 Motoko | 📅 2022-05-30 - A NFT standard implementation for the Internet Computer, the interfaces mainly follow the ERC721 standard.
* [extendable token standard](https://github.com/aviate-labs/ext.std) ⭐ 12 | 🐛 3 | 🌐 Motoko | 📅 2022-03-23 - Extendable Token Standard.
* [icrc7\_motoko](https://github.com/noku-team/icrc7_motoko) ⭐ 2 | 🐛 0 | 🌐 Motoko | 📅 2023-08-22 - An ICRC-7 standard implementation in Motoko.
* [Appic](https://github.com/Appic-Solutions/Auto_Investment) ⭐ 1 | 🐛 0 | 🌐 Motoko | 📅 2024-06-08 - A canister for automatically buying and selling tokens at specific times or intervals.
* [icrc1-token-canister](https://github.com/sonicdex/icrc-1-public/) ⭐ 1 | 🐛 0 | 🌐 Motoko | 📅 2024-05-10 - Implementation of ICRC1 token canister
* [token faucet](https://github.com/rocklabs-io/token-faucet) ⭐ 1 | 🐛 0 | 🌐 Modelica | 📅 2021-11-12 - A token faucet for [ic-token](https://github.com/rocklabs-io/ic-toke).
* [icrc30-mo](https://github.com/PanIndustrial-Org/icrc30.mo) - A Class+ ICRC-30 Library for providing Approve/TransferFrom to ICRC-7 NFT Canisters.
* [icrc3-mo](https://github.com/PanIndustrial-Org/icrc3.mo) - A Class+ ICRC-3 Library for adding transaction logs and archives to your canister.
* [icrc7-mo](https://github.com/PanIndustrial-Org/icrc7.mo) - A Class+ ICRC-7 Library for building NFT Canisters.
* [icrc-nft-mo](https://github.com/PanIndustrial-Org/icrc_nft.mo) - A Sample NFT combining icrc7-mo, icrc30-mo, icrc3-mo.
* [motoko-token](https://github.com/enzoh/motoko-token) - This package implements a simple ERC-20 style token.
* [non-fungible-token](https://github.com/DepartureLabsIC/non-fungible-token) - The goal for this project is to develop a non-fungible token standard which leverages the unique properties of the IC and enables builders to create entire experiences from a single contract.

### Decentralized Finance

* [BrownFi](https://github.com/BrownFi/BrownFi-AMM-ICP) ⭐ 0 | 🐛 2 | 🌐 Motoko | 📅 2026-06-04 - Simple AMM Dex with high Capital Effifiency

### Games

* [reversi](https://github.com/ninegua/reversi) ⭐ 71 | 🐛 11 | 🌐 JavaScript | 📅 2023-03-14 - Multiplayer Reversi Game on Internet Computer.
* [superheroes](https://github.com/enzoh/superheroes) ⭐ 28 | 🐛 1 | 🌐 JavaScript | 📅 2020-09-01 - A simple example that demonstrates how to build a CRUD application on the Internet Computer using Motoko and React.
* [revo](https://github.com/DepartureLabsIC/revo) ⭐ 1 | 🐛 0 | 🌐 Modelica | 📅 2021-10-27 - A drawing game on Internet Computer.

### Mining Platform

* [loka](https://github.com/lokaverse/loka_canister) ⭐ 0 | 🐛 0 | 🌐 Motoko | 📅 2023-12-05 - Trustless Non-Custodial Bitcoin Mining Platform built on IC

### Realestate

* [ber](https://github.com/orgs/assets-tokenization/repositories) - Blockchain estate register with IC

### Social

* [LinkedUp](https://github.com/dfinity/linkedup) ⭐ 151 | 🐛 34 | 🌐 JavaScript | 📅 2026-04-09 - An open professional network on Internet Computer.
* [Formyfi](https://github.com/Talentum-id/formify) ⭐ 4 | 🐛 0 | 🌐 Vue | 📅 2025-07-24 - Decentralized & fully on-chain Q\&A Forms.
* [Anti-Korrupt](https://github.com/kezzyNgotho/Hackathon202409AI) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2025-01-09 - Expand your knowledge on corruption using AI and blockchain.
* [Spark](https://github.com/johnxiaohe/ICP-Spark) ⭐ 0 | 🐛 0 | 🌐 Motoko | 📅 2024-09-11 - An ICP-based full-chain document collaborative editing management and knowledge sharing platform.

### Storage

* [motoko-cdn](https://github.com/gabrielnic/motoko-cdn) ⭐ 39 | 🐛 2 | 🌐 TypeScript | 📅 2022-06-07 - A simple storage auto-scaling solution across multiple canisters. Ie: mini-bigmap.
* [motoko-bucket](https://github.com/PrimLabs/Bucket) ⭐ 30 | 🐛 1 | 🌐 Motoko | 📅 2022-10-10 - A K-V Database lib that uses stable memory to store data.
* [motoko-ICSP](https://github.com/PrimLabs/ICSP) ⭐ 20 | 🐛 0 | 🌐 Motoko | 📅 2022-06-13 - Internet Computer Storage Protocol. This lib supports many features, such as auto-scale storage, HTTP Redirect, cycle monitor and top up self automatically.
* [motoko-document-db](https://github.com/DepartureLabsIC/motoko-document-db) ⭐ 5 | 🐛 1 | 🌐 Modelica | 📅 2021-11-13
* [motoko-dht](https://github.com/enzoh/motoko-dht) ⭐ 4 | 🐛 0 | 🌐 Modelica | 📅 2020-06-01 - This canister implements a distributed hash table.

### Utilities

* [motoko-certified-http](https://github.com/nomeata/motoko-certified-http) ⭐ 18 | 🐛 0 | 🌐 Modelica | 📅 2021-09-15 - A motoko canister that does HTTP asset certification.
* [cleansheets](https://github.com/matthewhammer/cleansheets) ⭐ 12 | 🐛 0 | 🌐 Modelica | 📅 2020-03-12 - A spreadsheet-like application for the Internet Computer, written in Motoko.
* [IC Payroll](https://github.com/cosmasken/ic-payroll) ⭐ 8 | 🐛 1 | 🌐 Vue | 📅 2025-04-16 - Human Resource and Payroll App hosted fully on-chain on the internet Computer. Users can hold and send ckbtc and other icrc2 compliant tokens .Allows user to send a single payment or bulk payment. Vue/Tailwindcss Frontend with Motoko Backend.
* [relay](https://github.com/DepartureLabsIC/relay) ⭐ 4 | 🐛 0 | 🌐 Modelica | 📅 2021-10-21 - Managed events infrastructure by Departure Labs.
* [SecureGuard Escrow](https://github.com/bix-tech/secure-guard-escrow) - Revolutionizing secure transactions with a blockchain-based escrow platform , ensuring safe exchanges of high-value goods and services with immutable smart contracts.

### Video

* [cancan](https://github.com/dfinity/cancan) ⭐ 337 | 🐛 33 | 🌐 TypeScript | 📅 2026-04-09 - A scalable video-sharing service.

## Development tools

### Build system

* [dfx](https://github.com/dfinity/sdk/tree/master/src/dfx) ⭐ 204 | 🐛 70 | 🌐 Rust | 📅 2026-07-28 - The DFINITY command-line execution environment (dfx) is the primary tool for creating, deploying, and managing the dapps you develop for the Internet Computer blockchain.
* [Vessel package manager](https://github.com/dfinity/vessel) ⚠️ Archived - Add and manage packages, libraries, and dependencies for your Motoko programs.

### IDEs

* [motoko-playground](https://github.com/dfinity/motoko-playground) ⭐ 65 | 🐛 25 | 🌐 TypeScript | 📅 2026-04-08 - A playground for the Internet Computer's native Motoko language.
* [IntelliJ IDEA Motoko support](https://github.com/ununhexium/idea-motoko-plugin) ⭐ 0 | 🐛 1 | 🌐 Lex | 📅 2023-07-05 - Adds support for the Motoko language from Dfinity.
* [Blocks](https://blocks-editor.github.io/blocks/) - An open source visual Motoko smart contract editor.
* [Visual Studio Code](https://code.visualstudio.com/)
  * [Motoko](https://marketplace.visualstudio.com/items?itemName=dfinity-foundation.vscode-motoko) - Motoko language support maintained by official.

### Testing

* [motoko-matchers](https://github.com/kritzcreek/motoko-matchers) ⭐ 28 | 🐛 0 | 🌐 Motoko | 📅 2025-09-11 - Composable assertions for unit testing.
  * [ic101](https://github.com/kritzcreek/ic101) ⭐ 3 | 🐛 0 | 🌐 Modelica | 📅 2021-02-11 - This repository demonstrates how to use the matchers library to unit test canisters on the Internet Computer.
* [ic-mini-terminal](https://github.com/matthewhammer/ic-mini-terminal) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2022-12-27 - Minimal keyboard input (⌨) and graphical output (📺) for programs on the Internet Computer.
* [motoko-bigtest](https://github.com/matthewhammer/motoko-bigtest) ⭐ 12 | 🐛 2 | 🌐 Modelica | 📅 2020-09-15 - Long-running tests as/for IC services, via a Motoko-based DSL.
* [motoko-color](https://github.com/ByronBecker/motoko-color) ⭐ 8 | 🐛 0 | 🌐 Motoko | 📅 2022-06-08 - A Motoko library for rendering color schemes and graphics to the terminal, based on the ANSI ASCII standard.

## Libraries

### Algorithms

* [motoko-qr](https://github.com/enzoh/motoko-qr) ⭐ 21 | 🐛 2 | 🌐 Modelica | 📅 2021-05-21 - A QR-code generator for the Motoko programming language.
* [chronosphere](https://github.com/enzoh/chronosphere) ⭐ 14 | 🐛 1 | 🌐 Modelica | 📅 2021-02-08 - A time library for the Motoko programming language.
* [motoko-adapton](https://github.com/matthewhammer/motoko-adapton) ⭐ 6 | 🐛 2 | 🌐 Modelica | 📅 2021-12-27 - Dynamic dependence graph and memoization techniques in Motoko.
* [mo-parsec](https://github.com/crusso/mo-parsec) ⭐ 6 | 🐛 0 | 🌐 Modelica | 📅 2021-04-09 - A [Parsec](https://hackage.haskell.org/package/parsec)-based parser combinator library for Motoko.
* [Parser Combinators](https://github.com/aviate-labs/parser-combinators.mo) ⭐ 4 | 🐛 1 | 🌐 Motoko | 📅 2024-02-09 - Based on Monadic Parser Combinators by Graham Hutton and Erik Meijer.
* [Sorted](https://github.com/aviate-labs/sorted.mo) ⭐ 4 | 🐛 0 | 🌐 Motoko | 📅 2022-12-16 - Data structures in which each element is sorted in numerical, alphabetical, or some other order.
* [motoko-scc](https://github.com/nomeata/motoko-scc) ⭐ 1 | 🐛 0 | 🌐 Motoko | 📅 2022-01-03 - A Strongly Connected Component library for Motoko.
* [motoko-splay](https://github.com/chenyan2002/motoko-splay) ⭐ 1 | 🐛 0 | 🌐 Motoko | 📅 2023-05-30 - The splaying algorithm for Motoko.

### Cryptography

* [motoko-bitcoin](https://github.com/tgalal/motoko-bitcoin) ⭐ 20 | 🐛 1 | 🌐 Modelica | 📅 2023-02-14 - Bitcoin-related libraries (Base58, RIPMED160, HMAC).
* [motoko-sha](https://github.com/enzoh/motoko-sha) ⭐ 16 | 🐛 3 | 🌐 Modelica | 📅 2021-12-30 - This package implements secure hash algorithms for the Motoko programming language.
* [ecdsa-motoko](https://github.com/herumi/ecdsa-motoko) ⭐ 15 | 🐛 1 | 🌐 Motoko | 📅 2023-07-19 - ECDSA for Motoko.
* [motoko-SHA](https://github.com/aviate-labs/crypto.mo) ⭐ 10 | 🐛 2 | 🌐 Motoko | 📅 2023-03-15 - SHA224 and SHA256 hash algorithms as defined in FIPS 180-4.
* [evm-txs](https://github.com/av1ctor/evm-txs.mo) ⭐ 9 | 🐛 0 | 🌐 Motoko | 📅 2023-07-19 - EVM transactions creation, encoding, and decoding library in pure Motoko.
* [motoko-sha224](https://github.com/flyq/motoko-sha224) ⭐ 5 | 🐛 0 | 🌐 Motoko | 📅 2023-12-23 - A Sha224 implements for Motoko.
* [rand](https://github.com/aviate-labs/rand.mo) ⭐ 5 | 🐛 1 | 🌐 Motoko | 📅 2022-12-16 - Pseudo Random Number Generators.
* [motoko-CRC32](https://github.com/aviate-labs/hash.mo) ⭐ 2 | 🐛 0 | 🌐 Modelica | 📅 2023-03-14 - Implements the 32-bit cyclic redundancy check, or CRC-32, checksum.
* [motoko-sha2](https://github.com/timohanke/motoko-sha2) ⭐ 2 | 🐛 0 | 🌐 Motoko | 📅 2022-01-15 - All hash functions from the SHA2 family (sha224, sha256, sha512-224, sha512-256, sha384, sha512).
* [libsecp256k1.mo](https://github.com/av1ctor/libsecp256k1.mo) ⭐ 1 | 🐛 2 | 🌐 Motoko | 📅 2023-05-02 - Motoko port of libsecp256k1.
* [ecdsa\_poc](https://github.com/flyq/ecdsa_poc) ⭐ 0 | 🐛 0 | 🌐 Motoko | 📅 2023-12-25 - Prototype implementation of ECDSA, only for learning.
* [motoko-crc](https://github.com/enzoh/motoko-crc) - This package implements cyclic redundancy checks for the Motoko programming language.

### Data structures

* [motoko-base](https://github.com/dfinity/motoko-base) ⚠️ Archived - The Motoko base library, commonly used data structures and algorithms, maintained by the official.
* [motoko-crud](https://github.com/matthewhammer/motoko-crud) ⭐ 26 | 🐛 9 | 🌐 Modelica | 📅 2021-05-13 - A framework for constructing CRUD services in Motoko for the Internet Computer.
* [motoko-MerkleTree](https://github.com/nomeata/motoko-merkle-tree) ⭐ 21 | 🐛 4 | 🌐 Nix | 📅 2025-08-18 - A simple merkle tree data structure for Motoko. It provides a key-value store, where both keys and values are of type Blob.
* [motoko-bigsearch](https://github.com/matthewhammer/motoko-sequence/blob/2b7b429224/service/BigSearch.mo) ⭐ 15 | 🐛 2 | 🌐 Motoko | 📅 2023-04-17 - A search service in Motoko, inspired by indexing and search systems like Apache Lucene.
* [motoko-sequence](https://github.com/matthewhammer/motoko-sequence) ⭐ 15 | 🐛 2 | 🌐 Motoko | 📅 2023-04-17 - Cache-friendly, persistent sequential data for Motoko.
* [Stable HashMaps](https://github.com/canscale/StableHashMap) ⭐ 15 | 🐛 1 | 🌐 Motoko | 📅 2022-05-18 - Functional & Class-Based (Heap-based) stable Hashmaps in Motoko.
* [Principal](https://github.com/aviate-labs/principal.mo) ⭐ 13 | 🐛 0 | 🌐 Motoko | 📅 2022-12-16 - Provides a wrapper around the [base principal module](https://github.com/dfinity/motoko-base/blob/master/src/Principal.mo) ⚠️ Archived.
* [Stable Buffers](https://github.com/canscale/StableBuffer) ⭐ 13 | 🐛 3 | 🌐 Motoko | 📅 2023-11-10 - Stable (Heap-based) Buffers in Motoko.
* [MotokoStableBTree](https://github.com/sardariuss/MotokoStableBTree) ⭐ 11 | 🐛 3 | 🌐 Motoko | 📅 2023-10-06 – Stable Memory Based BTree.
* [motoko-BiMap](https://github.com/aviate-labs/bimap.mo) ⭐ 7 | 🐛 0 | 🌐 Motoko | 📅 2022-12-16 - A bimap (or "bidirectional map") is a map that preserves the uniqueness of its values as well as that of its keys.
* [Stable BTree Map](https://github.com/canscale/StableHeapBTreeMap) ⭐ 5 | 🐛 1 | 🌐 Motoko | 📅 2024-01-01 - Stable (Heap-based) BTreeMaps in Motoko.
* [array](https://github.com/aviate-labs/array.mo) ⭐ 4 | 🐛 0 | 🌐 Motoko | 📅 2022-12-15 - Extended Array Package for Motoko.
* [motoko\_datetime](https://github.com/edjcase/motoko_datetime) ⭐ 4 | 🐛 5 | 🌐 Motoko | 📅 2025-09-06 - Datetime library. Support for UTC, local timezones, locales and basic datetime operations/structures
* [Stable Red-Black Trees](https://github.com/canscale/StableRBTree) ⭐ 3 | 🐛 2 | 🌐 Motoko | 📅 2023-08-15 - (Heap-based) Stable Red-Black Trees in Motoko.
* [Stable LinkedList](https://github.com/canscale/LinkedList) ⭐ 2 | 🐛 0 | 🌐 Motoko | 📅 2022-04-08 - (Heap-based) Stable, mutable singly & doubly linked lists in Motoko.
* [motoko-Queue](https://github.com/aviate-labs/queue.mo) ⭐ 1 | 🐛 0 | 🌐 Motoko | 📅 2022-12-16 - A collection of elements that are maintained in a sequence, a FIFO Queue.
* [motoko-text-map](https://github.com/kritzcreek/motoko-text-map) ⭐ 1 | 🐛 0 | 🌐 Modelica | 📅 2021-04-11 - A Motoko Hashmap that fixes its key type to Text.
* [mutable-queue.mo](https://github.com/ninegua/mutable-queue.mo) ⭐ 1 | 🐛 0 | 🌐 Motoko | 📅 2026-06-21 - Motoko module of a mutable queue data structure.
* [Stable Data Struct](https://github.com/aviate-labs/stable.mo) ⭐ 1 | 🐛 0 | 🌐 Motoko | 📅 2022-12-16 - Stable (Heap-based) Hashmap implements.
* [motoko-StableMap](https://github.com/mix-labs/StableMap) - Stable Map for the Motoko.

### Encoding

* [Account.mo](https://github.com/dfinity/ICRC-1/blob/main/ref/Account.mo) ⭐ 90 | 🐛 32 | 🌐 Rust | 📅 2026-05-11 – ICRC1 Account En/Decoding
* [motoko-UUID](https://github.com/aviate-labs/uuid.mo) ⭐ 20 | 🐛 2 | 🌐 Motoko | 📅 2022-12-16 - Generation of UUIDs based on RFC 4122.
* [json package](https://github.com/aviate-labs/json.mo) ⭐ 19 | 🐛 6 | 🌐 Motoko | 📅 2024-02-09 - JSON for Motoko.
* [motoko-Encode](https://github.com/aviate-labs/encoding.mo) ⭐ 11 | 🐛 0 | 🌐 Motoko | 📅 2022-12-15 - Base32, Hex and Binary Library for the Motoko.
* [motoko\_candid](https://github.com/edjcase/motoko_candid) ⭐ 9 | 🐛 0 | 🌐 Motoko | 📅 2025-12-09 - CANDID encoding/decoding library
* [motoko\_cbor](https://github.com/edjcase/motoko_cbor) ⭐ 6 | 🐛 0 | 🌐 Motoko | 📅 2025-09-06 - CBOR encoding/decoding library
* [motoko-base32](https://github.com/flyq/motoko-base32) ⭐ 4 | 🐛 1 | 🌐 Motoko | 📅 2023-12-23 - Base32 coding/decoding for Motoko.
* [motoko-json](https://github.com/kritzcreek/motoko-json) ⭐ 4 | 🐛 1 | 🌐 Modelica | 📅 2020-04-14 - Json parser in Motoko.
* [motoko\_xml](https://github.com/edjcase/motoko_xml) ⭐ 2 | 🐛 0 | 🌐 Motoko | 📅 2025-09-06 - XML encoding/decoding library
* [lexicographic-encoding](https://github.com/canscale/lexicographic-encoding) ⭐ 1 | 🐛 2 | 🌐 TypeScript | 📅 2022-10-02 - Lexicographic (string sortable) integer encoding in Motoko.
* [motoko-hex](https://github.com/enzoh/motoko-hex) - This package implements hexadecimal encoding and decoding routines for the Motoko programming language.

### Graphics

* [motoko-graph](https://github.com/matthewhammer/motoko-graph) ⭐ 17 | 🐛 1 | 🌐 Modelica | 📅 2021-12-19 - Graphical data models for Motoko.
* [motoko-SVG Generator](https://github.com/aviate-labs/svg.mo) ⭐ 8 | 🐛 1 | 🌐 Motoko | 📅 2022-12-16 - A SVG generator for the Motoko.
* [motoko-redraw](https://github.com/matthewhammer/motoko-redraw) ⚠️ Archived - 2D graphics and layout algorithms for Motoko.

### Logging

* [ic-logger](https://github.com/ninegua/ic-logger) ⭐ 20 | 🐛 1 | 🌐 Motoko | 📅 2026-06-21 - Motoko library to help create an append-only logger actor.
* [motoko-pretty](https://github.com/kritzcreek/motoko-pretty) ⭐ 4 | 🐛 0 | 🌐 Modelica | 📅 2021-05-15 - A pretty printer library for Motoko.

### Misc

* [Gitcoin Passport Client](https://github.com/vporton/passport-client-dfinity) ⭐ 1 | 🐛 8 | 🌐 Motoko | 📅 2026-01-24 - A sample app to securely copy Gitcoin Passport scores to ICP databases.

### Payment

* [IC-PayPortal](https://github.com/Expeera/IC-PayPortal/tree/phase-3) ⭐ 0 | 🐛 3 | 🌐 Motoko | 📅 2024-08-25 - Module for Motoko is a library that provides developers with a set of functions for managing fiat payments (Stripe, PayPal) on the Internet Computer Protocol (ICP).

### Storage

* [Bucket](https://github.com/PrimLabs/Bucket) ⭐ 30 | 🐛 1 | 🌐 Motoko | 📅 2022-10-10 - A data bucket library that use stable memory to store files bytes and assist developers to build http response.
* [Asset Storage](https://github.com/aviate-labs/asset-storage.mo) ⭐ 20 | 🐛 2 | 🌐 Motoko | 📅 2022-01-13 - Interface of the Asset Storage Canister.
* [A site about Motoko databases and related software](https://internet-computer.vporton.name)
* [motoko-GraphQL](https://github.com/aviate-labs/graphql.mo) - GraphQL is a query language designed to build client applications and system for describing their data requirements and interactions.

### Templates

* [motoko-library-template](https://github.com/kritzcreek/motoko-library-template) ⭐ 31 | 🐛 0 | 🌐 Modelica | 📅 2021-05-27 - A template for creating Motoko libraries.

### Text processing

* [motoko-regex](https://github.com/kritzcreek/motoko-regex) ⭐ 7 | 🐛 0 | 🌐 Modelica | 📅 2021-03-09 - Simple regex matching for Motoko Text.
* [Format](https://github.com/aviate-labs/fmt.mo) ⭐ 1 | 🐛 0 | 🌐 Motoko | 📅 2022-12-16 - Implements conversions to and from textual representations of basic data types.
* [motoko-regex-engine](https://github.com/demali-876/motoko_regex_engine) ⭐ 1 | 🐛 1 | 🌐 Motoko | 📅 2025-05-07- A library for native pattern matching on the Internet Computer.

### Web Programming

* [Http Request Parser](https://github.com/tomijaga/http-parser.mo) ⚠️ Archived - A http request parser for parsing url, search query, headers and form data.

## Registries

A registry allows you to publish your Rust libraries as crate packages, to share them with others publicly and privately.

* [Vessel Package Set](https://github.com/dfinity/vessel-package-set) ⚠️ Archived - The official package-set for Motoko libraries to use with vessel.
* [Package Set](https://github.com/aviate-labs/package-set) ⭐ 11 | 🐛 1 | 🌐 Dhall | 📅 2022-12-19 - Aviate-labs package-set for Motoko libraries to use with vessel.
* [io package](https://github.com/aviate-labs/io.mo) ⭐ 3 | 🐛 0 | 🌐 Motoko | 📅 2022-12-15 - Basic Interfaces for I/O Primitives.
* [MOPS](https://j4mwm-bqaaa-aaaam-qajbq-cai.ic0.app/) - A package manager for Motoko with on-chain package registry.

## Resources

* Learning
  * [AgorApp](https://agorapp.dev/course/learn-motoko) - AgorApp is an online interactive coding platform that provides courses and coding challenges on all-things-web3 engineering and Internet Computer development.
  * [DFINITY Education](https://github.com/orgs/DFINITY-Education/) - Lessons about blockchain, cryptocurrencies and protocol of Internet Computer.
  * [Introducing the Internet Computer](https://smartcontracts.org/docs/introduction/welcome.html) - A comprehensive series of documents that introduce Internet Computer.
  * [Mastering Motoko Book](https://github.com/niklabh/motokobook) ⭐ 2 | 🐛 1 | 🌐 HTML | 📅 2026-06-21 - The Definitive Guide to Decentralized Application Engineering on the Internet Computer
  * [Motoko Bootcamp](https://github.com/motoko-bootcamp/education) - Lectures and resources from the Motoko Bootcamp.
  * [motoko by example](https://github.com/dfinity/examples/tree/master/motoko) ⭐ 613 | 🐛 23 | 🌐 Rust | 📅 2026-08-27 - An officially maintained collection of short Motoko examples.
  * [The Motoko Programming Language Book](https://web3.motoko-book.dev/) - A guide for writing Web3 Software on the Internet Computer.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
