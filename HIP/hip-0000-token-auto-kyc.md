---
hip: <HIP number (this is determined by the HIP editor)>
title: Auto Token KYC with Auto 
author: @wensheng, @gregscullard
working-group: a list of the technical and business stakeholders' name(s) and/or username(s), or name(s) and email(s).
type: Standards Track
category: Service
needs-council-approval: Yes
status: Draft
created: 2021-11-23
discussions-to: https://github.com/hashgraph/hedera-improvement-proposal/discussions/239
updated: 2021-11-23
requires: <HIP number(s)>
replaces: <HIP number(s)>
superseded-by: <HIP number(s)>
---

## Abstract

This hip introduces automatic token KYC with token auto association.

## Motivation

Hedera previously approved and finalized [opt-in token auto association](https://hips.hedera.com/hip/hip-23).  It simplified the flow of a user acquiring a token.  However currently KYC is still required  for a user to receive a token.  The current process make certain token activities suck as airdrop impossible.

## Rationale

When a user has slots available for auto association and an auto association is transacted, KYC should be automatically granted.

## User stories

1. As a game operator, I want to give custumes or loots as NFTs to my users so that when they log into the game, they can receive NFTs and start wearing or using them immediately so they can have a better game experience.
Provide a list of "user stories" to express how this feature, functionality, improvement, or tool will be used by the end user. Template for user story: “As (user persona), I want (to perform this action) so that (I can accomplish this goal).”
  
## Specification

The technical specification should describe the syntax and semantics of any new features. The specification should be detailed enough to allow competing, interoperable implementations for at least the current Hedera ecosystem.

## Backwards Compatibility

All HIPs that introduce backward incompatibilities must include a section describing these incompatibilities and their severity. The HIP must explain how the author proposes to deal with these incompatibilities. HIP submissions without a sufficient backward compatibility treatise may be rejected outright.

## Security Implications

If there are security concerns in relation to the HIP, those concerns should be explicitly addressed to make sure reviewers of the HIP are aware of them.

## How to Teach This

For a HIP that adds new functionality or changes interface behaviors, it is helpful to include a section on how to teach users, new and experienced, how to apply the HIP to their work.

## Reference Implementation

The reference implementation must be complete before any HIP is given the status of “Final”. The final implementation must include test code and documentation.

## Rejected Ideas

Throughout the discussion of a HIP, various ideas will be proposed which are not accepted. Those rejected ideas should be recorded along with the reasoning as to why they were rejected. This both helps record the thought process behind the final version of the HIP as well as preventing people from bringing up the same rejected idea again in subsequent discussions.

In a way, this section can be thought of as a breakout section of the Rationale section that focuses specifically on why certain ideas were not ultimately pursued.

## Open Issues

While a HIP is in draft, ideas can come up which warrant further discussion. Those ideas should be recorded so people know that they are being thought about but do not have a concrete resolution. This helps make sure all issues required for the HIP to be ready for consideration are complete and reduces people duplicating prior discussions.

## References

A collections of URLs used as references through the HIP.

## Copyright/license

This document is licensed under the Apache License, Version 2.0 -- see [LICENSE](../LICENSE) or (https://www.apache.org/licenses/LICENSE-2.0)
