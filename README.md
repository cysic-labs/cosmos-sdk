# cosmos-sdk

## Introduction

Brief overview of what Cosmos SDK is and its purpose.
Explanation of its modular and interoperable design.

## Tools and Frameworks
The Cosmos ecosystem is vast. Awesome Cosmos is a community-curated list of notable frameworks, modules and tools.

### Inter-Blockchain Communication (IBC)

The IBC module for the Cosmos SDK has its own [cosmos/ibc-go repository](https://github.com/cosmos/ibc-go). Go there to build and integrate with the IBC module.

### Version Matrix

The version matrix below shows which versions of the Cosmos SDK, modules and libraries are compatible with each other.

#### Core Dependencies

Core dependencies are the core libraries that an application may depend on.
Core dependencies not mentioned here as compatible across all maintained SDK versions.

| Cosmos SDK | cosmossdk.io/core | cosmossdk.io/api | cosmossdk.io/x/tx |
| ---------- | ----------------- | ---------------- | ----------------- |
| 0.52.z     | 1.y.z             | 0.8.z            | 1.y.z             |
| 0.50.z     | 0.11.z            | 0.7.z            | 0.13.z            |
| 0.47.z     | 0.5.z             | 0.3.z            | N/A               |

#### Module Dependencies

Module Dependencies are the modules that an application may depend on and which version of the Cosmos SDK they are compatible with.

> Note: The version table only goes back to 0.50.x, as modules started to become modular with 0.50.z.
> X signals that the module was not spun out into its own go.mod file.
> N/A signals that the module was not available in the Cosmos SDK at that time.

| Cosmos SDK                  | 0.50.z | 0.52.z |
| --------------------------- | ------ | ------ |
| cosmossdk.io/x/accounts     | N/A    | 0.2.z  |
| cosmossdk.io/x/bank         | X      | 0.2.z  |
| cosmossdk.io/x/circuit      | 0.1.z  | 0.2.z  |
| cosmossdk.io/x/consensus    | X      | 0.2.z  |
| cosmossdk.io/x/distribution | X      | 0.2.z  |
| cosmossdk.io/x/epochs       | N/A    | 0.2.z  |
| cosmossdk.io/x/evidence     | 0.1.z  | 0.2.z  |
| cosmossdk.io/x/feegrant     | 0.1.z  | 0.2.z  |
| cosmossdk.io/x/gov          | X      | 0.2.z  |
| cosmossdk.io/x/group        | X      | 0.2.z  |
| cosmossdk.io/x/mint         | X      | 0.2.z  |
| cosmossdk.io/x/nft          | 0.1.z  | 0.2.z  |
| cosmossdk.io/x/protocolpool | N/A    | 0.2.z  |
| cosmossdk.io/x/slashing     | X      | 0.2.z  |
| cosmossdk.io/x/staking      | X      | 0.2.z  |
| cosmossdk.io/x/upgrade      | 0.1.z  | 0.2.z  |

## Getting Started

Prerequisites (e.g., Go programming language, dependencies).
Installation instructions.
Setting up a new project using the SDK.

## Quick Start Guide

Step-by-step instructions to create and run a basic blockchain application.
Sample commands to initialize, build, and start the application.

## Architecture

Overview of the SDK’s architecture (modules, ABCI, etc.).
Explanation of the role of the Cosmos Hub and zones.

## Modules

List of commonly used modules (e.g., staking, governance).
Instructions on how to implement or customize modules.

## Inter-Blockchain Communication (IBC)

Introduction to IBC and its significance in the Cosmos ecosystem.
Basic setup for enabling IBC between blockchains.
Documentation and Resources

Links to official documentation, tutorials, and community resources.
GitHub repository links for accessing the codebase.

##Contributing

Guidelines for contributing to the Cosmos SDK project.
Code of conduct and community standards.
