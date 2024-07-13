# Whitelist Gated Token Sale

Solana program made in Rust using the Anchor framework, for the 2024 Superteam Talent Olympics

## Program Architecture
<img width="2167" alt="architecture" src="https://github.com/user-attachments/assets/06189cfd-819a-4d3f-a132-dc7f4b179c4a">

This program allows to sell SPL tokens to whitelisted users, at a fixed price, with a purchase limit.

## Installation and Usage

Install Anchor CLI and other packages required (https://www.anchor-lang.com/docs/installation).

The program can then be deployed using `anchor deploy`.
Tests cases in the tests/ folder can be ran using `anchor test` (with the `--skip-local-validator` option if you already run a local solana validator)