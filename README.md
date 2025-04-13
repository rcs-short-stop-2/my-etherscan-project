# Etherscan API Utility Scripts

## Description

This repository contains a collection of scripts and examples for interacting with the [Etherscan API](https://docs.etherscan.io/). It's used to fetch various blockchain data points like account balances, transaction details, contract information, token data, and more.

## Purpose

To provide reusable tools and `curl` command examples for querying Etherscan, primarily for analysis, monitoring, or integration tasks.

## Setup

This project is designed to be used with [GitHub Codespaces](https://github.com/features/codespaces).

1.  Launch a Codespace from this repository.
2.  The required tools (`curl`, `git`, `node`, `npm`, `nano`) should be available in the default Codespace environment. If any are missing, install them using:
    ```bash
    sudo apt update && sudo apt install curl nodejs npm nano -y
    ```
3.  **API Key:** You need an Etherscan API key. **Do not commit your API key directly into the repository!** It's recommended to store it securely, for example, using Codespaces secrets or environment variables.

## Usage

### Environment Variable Setup (Recommended)

Before running scripts, set your API key as an environment variable in the Codespace terminal:

```bash
export ETHERSCAN_API_KEY="YOUR_API_KEY_HERE"
