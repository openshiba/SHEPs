---
shep: <to be assigned>
title: RENVM Bridge Integration
author: Bbo Harris (@BobHarris1)
discussions-to: none
status: Draft
created: 2021-06-06
---

## Simple Summary

RenVM's RenBridge "enables the simple wrapping of digital assets on different blockchains."(https://bridge.renproject.io/about). 


## Motivation

THis could allow users to take SHIB Coins and put it on the other chains in effect allowing investors on other blockchains to access SHIB Token.

This would allow us access to wraps with with the major Cryptos/protocols, as well as the up-and-coming (e.g. Avalanche... Best crypto protocol i've seen in terms of Speed, throughput and low fees). 

## Specification

How to Request Shiba's inclusion: Submit a Pull Request via this instructions: https://github.com/renproject/multichain#readme

Basic summary of PR instructions: 
1. Add the Asset/Chain
2. Set up a Docker container in the Infra folder, add a file/script to install/run the node
3. Add a private key and public address to access the funds
4. Add a Docker-compose.yaml file to allow the node to boot alongside other nodes in the multichain
5. Add Address, Gas and account API's
6. Run a test
7. Submit the Pull Request

Going Further: Whats not clear is what determining factors they are using for approving PR's.  You see several in the Pull Request section waiting for approval (ONE, BGL, WAVES, etc.).