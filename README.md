# railchain-ticketing
RailChain is a full-stack decentralized application that models a railway ticket booking system using blockchain. It includes Solidity smart contracts (ERC-721 tickets), Hardhat development &amp; tests, a React front end for wallet-based booking, and optional off-chain indexing for search and analytics.

# RailChain — Decentralized Railway Ticket Booking

[![Build Status](https://img.shields.io/github/actions/workflow/status/<your-username>/railchain-ticketing/ci.yml?branch=main)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
[![Test Coverage](https://img.shields.io/badge/coverage-—%25-lightgrey)]()

## Overview
RailChain is a demo-grade decentralized railway ticket booking system. It demonstrates how blockchain can be used to mint, transfer and verify immutable tickets (implemented as ERC-721 tokens), with a simple React dApp for users to search trains, connect a wallet and book tickets on testnets/local Hardhat network.

This repository is intended as a resume/project showcase: it contains smart contracts, unit tests, deployment scripts, a frontend demo, and documentation.

## Features
- ERC-721 NFT tickets representing seat reservations
- Smart contract functions: add train, book ticket, cancel ticket, transfer ticket
- Hardhat test suite for core contract flows
- React dApp (ethers.js + MetaMask) to demo booking flow
- Scripts to deploy to local network and public testnets (Sepolia / Goerli)
- Optional Express indexer for off-chain search & metadata caching

## Tech stack
- Solidity (contracts)
- Hardhat (development & tests)
- Ethers.js + MetaMask (frontend wallet interactions)
- React (frontend)
- Node.js + Express (optional backend)
- PostgreSQL / MongoDB (optional off-chain storage)

## Quickstart (local)
1. Clone repo:
   ```bash
   git clone git@github.com:<your-username>/railchain-ticketing.git
   cd railchain-ticketing

