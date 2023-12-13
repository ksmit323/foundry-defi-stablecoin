# Decentralized Stable Coin System

## Overview

Decentralized stablecoin system designed with minimalism in mind, aiming to maintain a 1:1 peg with the US Dollar. Key features include exogenous collateral, a dollar peg, and algorithmic stability. It draws inspiration from DAI but no governance, no fees structure implemented, and backing by WETH and WBTC.

## Key Properties

- **Exogenous Collateral:** DSCEngine employs exogenous collateral.
- **Dollar Pegged:** The system maintains a 1 token to $1 peg.
- **Algorithmically Stable:** Self-regulating system that adapts to market conditions,

## Comparison to DAI

This implementation shares similarities with DAI but key differences are:
- **No Governance:** Unlike DAI, DSCEngine operates without a governance structure.
- **No Fees:** DSCEngine doesn't implement any fee structure mechanics.
- **Limited Collateral:** The stablecoin is backed exclusively by WETH and WBTC.

## Overcollateralization

For robustness and risk mitigation, DSCEngine mandates that the system is always overcollateralized. At no point should the total value of collateral be less than the USD value of all DSCEngine tokens.

## Core Functionality

The DSCEngine contract serves as the core of the system, encompassing the following functionalities:

- **Mining and Redeeming:** Handles the logic for mining and redeeming DSC tokens.
- **Collateral Management:** Manages the depositing and withdrawing of collateral, ensuring the system's stability.

## Acknowledgments

DSCEngine is loosely based on the MakerDAO DSS (DAI) system. 
This implementation follows the tutorial taught by Patrick Collins.
