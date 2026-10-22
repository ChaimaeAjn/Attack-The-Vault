# Attack The Vault

## Project Overview
This project investigates a power side-channel vulnerability in a password-protected vault using power consumption measurements.

## Attack
The attack exploits differences in power consumption caused by an early-exit password comparison. By collecting and analysing power traces, the vault access password was recovered.

## Countermeasure
A constant-time password comparison is proposed to mitigate the early-exit vulnerability. However, this countermeasure was not implemented or experimentally validated during the project, and constant-time execution alone does not guarantee resistance to power side-channel attacks.

## Report
See [`Write_Up_Projet.pdf`](./Write_Up_Projet.pdf) for the full project report.
