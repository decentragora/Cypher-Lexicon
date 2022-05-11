---
description: >-
  EIPs are the primary mechanism for proposing improvements to the Ethereum
  network.
---

# 👍 EIPs Ethereum Improvement Proposals

They allow the Ethereum community to come to a consensus about how the network should evolve over time. Anyone can submit an EIP, and all EIPs are logged in the Ethereum Improvement Proposals repository on GitHub.

## EIP Status Terms

Idea - An idea for an EIP that is not yet in development.&#x20;

Draft - The first stage of an EIP in development, where it is formally tracked in the EIP repository.&#x20;

Review - An EIP that is ready for and requesting peer review.&#x20;

Last Call - The final review window for an EIP before moving to FINAL, where an EIP editor will assign Last Call status and set a review end date (`last-call-deadline`), typically 14 days later.&#x20;

Final - This EIP represents the final standard. A Final EIP exists in a state of finality and should only be updated to correct errata and add non-normative clarifications.&#x20;

Stagnant - Any EIP in Draft or Review that is inactive for a period of 6 months or greater is moved to Stagnant. An EIP may be resurrected from this state by Authors or EIP Editors by moving it back to Draft.&#x20;

Withdrawn - The EIP Author(s) have withdrawn the proposed EIP. This state has finality and can no longer be resurrected using this EIP number. If the idea is pursued at a later date, it is considered a new proposal.&#x20;

Living - A special status for EIPs that are designed to be continually updated and not reach a state of finality. This includes most notably EIP-1.

[Source](https://eips.ethereum.org/#:\~:text=Ethereum%20Improvement%20Proposals%20\(EIPs\)%20describe,the%20Ethereum%20Project%20Management%20repository.)📜

## EIP Types

EIPs are separated into a number of types, and each has its own list of EIPs.

#### Standard Track&#x20;

A Standard Track EIP is any change that affects most or all Ethereum implementations, such as a change to the network protocol, a change in block or transaction validity rules, proposed application standards/conventions, or any change or addition that affects the interoperability of applications using Ethereum.

#### [**Core**](https://eips.ethereum.org/core) ****&#x20;

Improvements requiring a consensus fork (e.g. [EIP-5](https://eips.ethereum.org/EIPS/eip-5), [EIP-101](https://eips.ethereum.org/EIPS/eip-101)), as well as changes that are not necessarily consensus critical but may be relevant to “core dev” discussions (for example, the miner/node strategy changes 2, 3, and 4 of [EIP-86](https://eips.ethereum.org/EIPS/eip-86)).

[**Networking**](https://eips.ethereum.org/networking) ****&#x20;

Includes improvements around devp2p ([EIP-8](https://eips.ethereum.org/EIPS/eip-8)) and Light Ethereum Subprotocol, as well as proposed improvements to network protocol specifications of whisper and swarm.

[**Interface**](https://eips.ethereum.org/interface) ****&#x20;

Includes improvements around client API/RPC specifications and standards, and also certain language-level standards like method names ([EIP-6](https://eips.ethereum.org/EIPS/eip-6)) and contract ABIs. The label “interface” aligns with the interfaces repo and discussion should primarily occur in that repository before an EIP is submitted to the EIPs repository.

[**ERC**](https://eips.ethereum.org/erc) ****&#x20;

Application-level standards and conventions, including contract standards such as token standards ([ERC-20](https://eips.ethereum.org/EIPS/eip-20)), name registries ([ERC-137](https://eips.ethereum.org/EIPS/eip-137)), URI schemes ([ERC-681](https://eips.ethereum.org/EIPS/eip-681)), library/package formats ([EIP190](https://eips.ethereum.org/EIPS/eip-190)), and wallet formats ([EIP-85](https://github.com/ethereum/EIPs/issues/85)).

#### [Meta](https://eips.ethereum.org/meta)&#x20;

A meta-EIP is a type of EIP that describes a process or event related to Ethereum or proposes a change to Ethereum's development process. Meta-EIPs are not limited to the Ethereum protocol itself and may suggest an implementation or require community consensus. Examples of meta-EIPs include procedures, guidelines, changes to the decision-making process, and changes to the tools or development environment used in Ethereum.

#### [Informational](https://eips.ethereum.org/informational)&#x20;

This EIP provides general guidelines or information to the Ethereum community but does not propose a new feature. Informational EIPs do not necessarily represent Ethereum community consensus or a recommendation, so users and implementers are free to ignore Informational EIPs or follow their advice.

[Source](https://eips.ethereum.org/#:\~:text=Ethereum%20Improvement%20Proposals%20\(EIPs\)%20describe,the%20Ethereum%20Project%20Management%20repository.)📜
