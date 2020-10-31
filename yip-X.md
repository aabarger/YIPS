---
yip: <to be assigned>
title: <Method for returning $YFI tokens sent to the contract address.>
status: WIP
author: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets): FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) and GitHubUsername (@GitHubUsername)>
discussions-to: https://gov.yearn.finance/t/save-victims-who-mistakenly-sent-to-contract-address/5390/13>

created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
requires (*optional): <YIP number(s)>
implementation (*optional): <Added if YIP passes>
---

<!--You can leave these HTML comments in your merged YIP and delete the visible duplicate text guides, they will not appear and may be helpful to refer to if you edit it again. This is the suggested template for new YIPs. Note that an YIP number will be assigned by an editor. When opening a pull request to submit your YIP, please use an abbreviated title in the filename, `yip-draft_title_abbrev.md`. The title should be 44 characters or less.-->

This is the suggested template for new YIPs. Note that an YIP number will be assigned by an editor. When opening a pull request to submit your YIP, please use an abbreviated title in the filename, `yip-draft_title_abbrev.md`. The title should be 44 characters or less.

## Simple Summary

A way for people who mistakenly sent $YFI tokens to the contract address to retrieve their funds.

## Abstract

Burn tokens sent to the contract address, mint replacements, and send them back to the wallet addresses they were sent from and impliment a line of code that rejects funds attempted to be sent to the contract address.

## Motivation

When Elon Musk set out to create electric cars he knew they'd have to be better than a gas car in everyway. The same goes for DeFi. To see wide adoption of decentralized banking we're going to need it to be better than existing banks in every way. Let's not pride ourselves on how complicated and unforgiving crypto can be. Let's just make it hands down better.

## Specification

Mint replacement tokens, burn tokens trapped in the contract address, return replacement tokens to wallet addresses without affecting tokenomics.

### Overview

Returning funds sent to the contract by minting new one's and burning trapped one's will not change tokenomics of $YFI nor threaten immutable core idealogies. Adding a line of code which rejects funds will prevent further $YFI from being mistakenly sent to the contract address.

### Rationale

Minting new tokens and burning the one's sent to the contract address seems like the logical solution provided there's no way to return the tokens using the contract itself. If that's an option it would be a preferred method. The idea of minting and burning was conceived for the purpose of returning the funds without joepardizing underlying idealogies and the tokenomics of $YFI.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
