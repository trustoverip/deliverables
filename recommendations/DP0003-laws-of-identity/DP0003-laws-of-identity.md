# DP0003: Laws of Identity
- Authors: [Darrell O'Donnell](darrell.odonnell@continuumloop.com), [Victor Syntez](victorsyntez@gmail.com), [Chris Buchanan](cjb@mitre.org)
- Deliverable Type: *Recommendation - Design Principle*
- Status: [PROPOSED](https://trustoverip.github.io/deliverables/process/lifecycle_management/#proposed)
- Since: 2020-10-21
- Status Note: Draft
- Supersedes: N/A
- Start Date: 2020-10-21
- Tags: (see ../../../tags.md)


## Summary

The **Seven Laws of Identity** were [published by Kim Cameron, Architect of Identity at the Microsoft Corporation](https://www.identityblog.com/stories/2005/05/13/TheLawsOfIdentity.pdf) in 2005. This document serves to recognize this work as a collection of design principles for a unifying identity metasystem that provides an identity layer for the Internet.

## Motivation

The _Laws of Identity_ as defined by Kim Cameron et.al. remains a foundational document in defining an identity system for the Internet.  _The Laws of Identity_ posit that, because the Internet itself is a metasystem comprised of competing protocols and interoperability standards without a centralized mechanism of control or enforcement, any identity system that intends to service the needs of the Internet must itself be a metasystem.  Any monolithic identity system will either lack the span-of-control or the proper context to properly service the users needs.  _The Laws of Identity_ provide the reasoning for a decentralized identity metasystem which in turn creates the need for a Trust over IP Foundation to provide one coherent and principled approach to defining the competing protocols and interoperability standards required to realize the universal metasystem for identity envisioned by Cameron.

## Approach

Since Laws of Identity are indicative vice prescriptive, this document, by mapping each Law of Identity to each Layer of the Trust Over IP Technology stack, is intended to guide design decisions rather than prescribe them.  This is not to say they may be dismissed entirely, but that there is a necessary flexibility of application within the incredibly complex and diverse identity ecosystem. This mapping will inform the members of Trust Over IP Governance and Ecosystem Working Groups in their daily work of creating frameworks, policies, etc.  Additionally, there are portions of the decentralized identity ecosystem which were not anticipated in 2005 by the authors of _The Laws of Identity_ which are treated as caveats within this guide to reinforce their inclusion within the Trust Over IP process.

## Outcome

It is important for users and technologists to understand that the ideas and goals of the Trust over IP Foundation are not new ideas.  These concepts have a strong pedigree that goes back to the origins of the internet.  The Laws of Identity show that any universal identity system must necessarily be a metasystem and user centric, but User Centric Identity fell flat because it depended on governance structures and technologies that could not hope to achieve the levels of security and transparency required for the universal identity metasystem to be realized.  However, the advent of Distributed Ledger Technology (DLT) has finally made it possible for a universal identity metasystem to be established.  By acknowledging adherence to the line of thought by which we have arrived at the present moment, we sweep away the objections of immaturity and novel approaches and refocus on the important work of __*connecting people while also respecting their individuality of person, time, place, and context.*__

## Scope

This document serves to provide an opportunity to discuss how laws of identity **MUST** or **SHOULD**, or **MAY**  be applicable on every layer of TOIP Technology Stack.

In many standards track documents words **MUST**, **SHOULD**, and **MAY** are used to signify the requirements in the specification.  This matrix use these words according to IETF [RFC2119](https://www.rfc-editor.org/rfc/rfc2119).

## Trust Over IP Stack Layers Descriptions
The first two layers of the ToIP stack are designed to provide **technical trust** — the assurance that one machine can establish a secure, private connection with another machine. Layers Three and Four are where **human trust** is established and maintained.

![](https://i.imgur.com/PnZb0EW.jpg)

**TL4:** **Application Ecosystem**. Layer Four is the application layer—the layer where humans interact with applications in order to engage in trusted interactions that serve a specific business, legal, or social purpose.

**TL3:** **Data Exchange Protocols**. Layer 3 is where issuers, holders, and verifiers exchange credentials and proofs using credential exchange protocols that run on top of DID Comm.

**TL2:** **DIDComm Peer to Peer Protocol**. Layer Two is about the branches—the digital wallets and digital agents needed to form secure, private peer-to-peer connections using either public DIDs (from Layer One) or peer DIDs.

**TL1:** **Public Utilities**. Layer One is about the strong cryptographic roots of technical trust. ToIP Layer One utilities can be implemented using any technology that can provide the necessary trust assurances, e.g., blockchains (of any kind), distributed ledgers, decentralized file systems, distributed hash tables, and so on.

```
Briefly describe the scope of this document – how it presents the architecture of this particular enabler.  Include an explanation of how this architecture relates to Organization Name activity.  If it adds clarity, also describe what is not in the scope of this architecture.  DELETE THIS COMMENT
```

## Design Goals

We believe that matrix presentation will simplify the road to creation various governance frameworks, policies, requirements, etc. This matrix will provide easily consumable format of relationship between Laws of Identity and TOIP Technological Stack Layers.

```
What are the goals that makes this collection of principles unique?
DELETE THIS COMMENT
```

## List of Principles
![ext-image](https://camo.githubusercontent.com/12ed1f186cab49f66f62bc804eadf082c18ce749/68747470733a2f2f7777772e6964656e74697479626c6f672e636f6d2f77702d636f6e74656e742f696d616765732f323030392f30362f375f4c6177735f6f665f4964656e746974792e6a7067)

### 1. User Control and Consent
Digital identity systems must only reveal information identifying a user with the user's consent.
| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** ||
| :---: | :---: | :---: | :---: |:---:|
||||| TL4 |
||||| TL3 |
||||| TL2 |
||||| TL1 |
### 2. Limited Disclosure for Limited Use
The solution which discloses the least identifying information and best limits its use is the most stable, long-term solution.
| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** ||
| :---: | :---: | :---: | :---: |:---:|
||||| TL4 |
||||| TL3 |
||||| TL2 |
||||| TL1 |
### 3. The Law of Fewest Parties
Digital identity systems must limit disclosure of identifying information to parties having a necessary and justifiable place in a given identity relationship.
| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** ||
| :---: | :---: | :---: | :---: |:---:|
||||| TL4 |
||||| TL3 |
||||| TL2 |
||||| TL1 |
### 4. Directed Identity
A universal identity metasystem must support both "omnidirectional" identifiers for use by public entities and "unidirectional" identifiers for private entities, thus facilitating discovery while preventing unnecessary release of correlation handles.
| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** ||
| :---: | :---: | :---: | :---: |:---:|
||||| TL4 |
||||| TL3 |
||||| TL2 |
||||| TL1 |
### 5. Pluralism of Operators and Technologies
A universal identity metasystem must channel and enable the interworking of multiple identity technologies run by multiple identity providers.
| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** ||
| :---: | :---: | :---: | :---: |:---:|
||||| TL4 |
||||| TL3 |
||||| TL2 |
||||| TL1 |
### 6. Human Integration
A unifying identity metasystem must define the human user as a component integrated through protected and unambiguous human-machine communications.
| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** ||
| :---: | :---: | :---: | :---: |:---:|
||||| TL4 |
||||| TL3 |
||||| TL2 |
||||| TL1 |
### 7. Consistent Experience Across Contexts
A unifying identity metasystem must provide a simple consistent experience while enabling separation of contexts through multiple operators and technologies.
| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** ||
| :---: | :---: | :---: | :---: |:---:|
||||| TL4 |
||||| TL3 |
||||| TL2 |
||||| TL1 |

## Synopsis
Please refer to the [original article](http://www.identityblog.com/stories/2005/05/13/TheLawsOfIdentity.html) by the author for a complete synopsis about each principle.

## Relevance

```
Explain the positioning of each principle against the overarching goals of this proposal.  How / where would they be used (example Use cases or industry sectors).
DELETE THIS COMMENT
```

## Trade-offs
It's clear that creating any matrix will always result in border situation when there is no clear choice between **MUST**, **SHOULD**, and **MAY**. This shouldn't stop us from thinking about situation when there is a clear answer and therefore a direct relation between Laws of Identity and TOIP Technological Stack Layers.
We also understand that by creating such a matrix we might shift focus from overall fundamental picture to more detailed way of looking on governance and ecosystem frameworks.
```
Provide an assessment of the ramifications of including and/or excluding each principle in a solution.
DELETE THIS COMMENT
```
