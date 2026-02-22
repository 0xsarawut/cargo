# The Cargo Book

![Cargo Logo](images/Cargo-Logo-Small.png)

Cargo is the [Rust] [*package manager*][def-package-manager]. Cargo downloads your Rust [package][def-package]'s
dependencies, compiles your packages, makes distributable packages, and uploads them to
[crates.io], the Rust community’s [*package registry*][def-package-registry]. You can contribute
to this book on [GitHub].

## Sections

**[Getting Started](getting-started/index.md)**

To get started with Cargo, install Cargo (and Rust) and set up your first
[*crate*][def-crate].

**[Cargo Guide](guide/index.md)**

The guide will give you all you need to know about how to use Cargo to develop
Rust packages.

**[Cargo Reference](reference/index.md)**

The reference covers the details of various areas of Cargo.

**[Cargo Commands](commands/index.md)**

The commands will let you interact with Cargo using its command-line interface.

**[Frequently Asked Questions](faq.md)**

**Appendices:**
* [Glossary](appendix/glossary.md)
* [Git Authentication](appendix/git-authentication.md)

**Other Documentation:**
* [Changelog](CHANGELOG.md)
  --- Detailed notes about changes in Cargo in each release.
* [Rust documentation website](https://doc.rust-lang.org/) --- Links to official
  Rust documentation and tools.

[def-crate]:            ./appendix/glossary.md#crate            '"crate" (glossary entry)'
[def-package]:          ./appendix/glossary.md#package          '"package" (glossary entry)'
[def-package-manager]:  ./appendix/glossary.md#package-manager  '"package manager" (glossary entry)'
[def-package-registry]: ./appendix/glossary.md#package-registry '"package registry" (glossary entry)'
[rust]: https://www.rust-lang.org/
[crates.io]: https://crates.io/
[GitHub]: https://github.com/rust-lang/cargo/tree/master/src/doc
> ## Documentation Index
> Fetch the complete documentation index at: https://docs.starknet.io/llms.txt
> Use this file to discover all available pages before exploring further.

# Deploy your first contract guide overview

<Warning>
  If you encounter an issue while following this tutorial, see [Troubleshooting](/build/quickstart/appendix/#troubleshooting).
</Warning>

## Introduction

Welcome to the *Deploy your first contract* guide! 🥇

This comprehensive tutorial will walk you through the entire process of setting up your development environment, creating your first smart contract, and deploying it on Starknet. By the end of this guide, you'll have hands-on experience with the core tools and workflows used by Starknet developers.

## What you'll learn

This guide is structured as a series of interconnected tutorials that build upon each other:

* [Setting up your Starknet development environment](/build/quickstart/environment-setup/)

* [Generating and understanding the `HelloStarknet` contract](/build/quickstart/hellostarknet/)

* [Declaring, deploying, and interacting with the `HelloStarknet` contract locally](/build/quickstart/devnet/)

* [Deploying and interacting with the `HelloStarknet` contract on Starknet Sepolia](/build/quickstart/sepolia/)

* [Recommended next steps after deploying your first contract](/build/quickstart/next-steps/)

## Prerequisites

Before starting this tutorial, you should have:

* Basic familiarity with command-line interfaces
* A computer running macOS, Linux, or Windows with WSL
* An internet connection for downloading tools and interacting with Starknet

No prior experience with Cairo or Starknet is required - this guide is designed for beginners!

## Getting help

If you encounter any issues while following this guide:

1. Check the [troubleshooting section](/build/quickstart/appendix/#troubleshooting) for common problems and solutions
2. Ask for help in the [Starknet Discord community](https://discord.gg/starknet-community)
3. Browse the [Starknet community forum](https://community.starknet.io/) for additional resources
4. 
