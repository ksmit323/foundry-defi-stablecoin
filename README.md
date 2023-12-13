# DSCEngine: Decentralized Stable Coin System

## Overview

DSCEngine is a decentralized stablecoin system designed with minimalism in mind, aiming to maintain a 1:1 peg with the US Dollar. Key features include exogenous collateral, a dollar peg, and algorithmic stability. It draws inspiration from DAI but stands out with no governance, no fees, and sole backing by WETH and WBTC.

## Key Properties

- **Exogenous Collateral:** DSCEngine employs exogenous collateral, ensuring a robust and secure backing for its stablecoin.
- **Dollar Pegged:** The system maintains a 1 token to $1 peg, providing stability and predictability for users.
- **Algorithmically Stable:** Leveraging algorithms, DSCEngine achieves stability without the need for governance or fees.

## Comparison to DAI

DSCEngine shares similarities with DAI but distinguishes itself through its unique features:
- **No Governance:** Unlike DAI, DSCEngine operates without a governance structure, empowering users without the need for decision-making protocols.
- **No Fees:** DSCEngine eliminates fees, offering a cost-effective solution for stablecoin transactions.
- **Limited Collateral:** The stablecoin is backed exclusively by WETH and WBTC, emphasizing simplicity and security.

## Overcollateralization

Ensuring robustness and risk mitigation, DSCEngine mandates that the system is always overcollateralized. At no point should the total value of collateral be less than the USD value of all DSCEngine tokens.

## Core Functionality

This contract serves as the core of the DSCEngine system, encompassing the following functionalities:

- **Mining and Redeeming:** Handles the logic for mining and redeeming DSCEngine tokens.
- **Collateral Management:** Manages the depositing and withdrawing of collateral, ensuring the system's stability.

## Acknowledgments

DSCEngine is loosely based on the MakerDAO DSS (DAI) system. 
This implementation follows the tutorial taught by Patrick Collins.
