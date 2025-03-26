MicroLending Move Smart Contract

Description

The MicroLending Move smart contract is a decentralized finance (DeFi) tool designed for micro-lending on the Aptos blockchain. It enables borrowers to request small loans and allows lenders to fund these loan requests securely using AptosCoin (APT). This contract ensures trustless and transparent lending transactions between users.

Vision

The goal of this project is to create an accessible and efficient micro-lending platform that empowers individuals with limited access to traditional financial services. By leveraging blockchain technology, MicroLending aims to facilitate secure, fast, and low-cost peer-to-peer lending without intermediaries.

Future Scope

Loan Repayment Functionality: Introduce a mechanism for borrowers to repay loans.

Interest & Collateral Support: Implement interest rates and optional collateral for risk management.

Loan Approval Mechanism: Add creditworthiness checks and approval processes for loans.

Integration with Wallets & DApps: Enhance usability by integrating with Aptos-compatible wallets and decentralized applications.

Automated Smart Contracts: Implement automated contract execution for repayments and loan closures.

Contract Details

Module Name: MyModule::MicroLending

Functions:

request_loan(borrower: &signer, amount: u64): Allows a user to request a loan.

fund_loan(lender: &signer, borrower: address, amount: u64): Allows lenders to fund requested loans.

Key Structs:

LoanRequest: Stores borrower address, requested loan amount, and funded amount.

Dependencies:

Uses Aptos Framework modules (signer, coin, aptos_coin).

This smart contract lays the foundation for a decentralized micro-lending ecosystem on Aptos. Future improvements will focus on enhancing security, scalability, and accessibility.

Contact Address 

0x92e6453ed7cc076d11bfe520744b91f4fb9d78d626b5010e5b645c36f6bb78a7

Transaction
![image](https://github.com/user-attachments/assets/bdc1570a-4d40-4cbc-aedd-d846badad148)



