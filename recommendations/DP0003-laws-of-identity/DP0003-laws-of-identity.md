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

[__The Laws of Identity__](https://www.identityblog.com/stories/2005/05/13/TheLawsOfIdentity.pdf) were published by Kim Cameron, Architect of Identity at the Microsoft Corporation, in 2005. This document serves to recognize this work as a foundational collection of design principles for a unifying identity metasystem that provides an identity layer for the Internet.  The seven laws outline the properties with which any identity solution must be imbued to meet the hyperdynamic needs of the entire internet.  Cameron's seven laws predated the nascent technologies and standards with which we now seek to realize his prescient declaration.  While we regard these laws as incomplete (in that more laws must certainly exist regarding [dependent identity](./dependent-id.md)), they have no less efficacy in their context.  We must therefore  stand "on the shoulders of giants" as we make the evolutionary leap to decentralized identity by applying __*The Laws of Identity*__ to our contemporary efforts of building the universal identity metasystem as prescribed by its progenitors.

## Motivation

The __*The Laws of Identity*__ as defined by Kim Cameron et.al. remains a foundational document in defining an identity system for the Internet.  __*The Laws of Identity*__ posit that, because the Internet itself is a metasystem comprised of competing protocols and interoperability standards without a centralized mechanism of control or enforcement, any identity system that intends to service the needs of the Internet must likewise be a metasystem.  Any monolithic identity system will either lack the span-of-control or the proper context to properly service global needs.  We seek to provide guardrails for future technologies to support the universal vice the monolithic.

Additionally, while __*The Laws of Identity*__ illuminate the path to a universal identity metasystem, those of us who seek to realize this vision are immediately confronted with the global consequences of having ignored these laws for over a decade due to ignorance, arrogance, greed, or necessity. The status quo for digital identity, as Cameron warned, is experiencing "a wake of reinforcing side-effects that [will] eventually undermine all resulting technology."  By focusing on authentication, we have required the ever increasing accumulation of data which, because it is used for authentication, is imbued with value beyond its natural state.  This accumulated data attracts those who would exploit its value and, once the data is exploited, the only cure for the resulting vulnerability is to accumulate more data thus restarting the cycle. This accumulation to expoitation cycle _is_ the reinforcing side effect of authentication.  

To break this cycle, authentication must be decentralized, and verification must become the predominant trust mechanism.  Of course this has always been the way of identity systems.  Authenticate at the edge, then verify once authenticated.  However, by creating a universal identity system, authentication is pushed off of the internet entirely.  Instead it becomes the domain of the agents and devices which represent our presence on the internet.  In so doing, the accumulation cycle can be broken and sanity restored.  However, a new problem is created: 

_**How do we trust the verifiable credentials presented to us?**_ 

Enter the Trust over IP Foundation. Concieved in order to solve this question, the Trust over IP Foundation seeks to enable the universal identity metasystem by solving the biggest question that faces the digital identity ecosystem in accordance with __*The Laws of Identity*__.

## Approach

Since __*The Laws of Identity*__ are indicative vice prescriptive, this document, by mapping each law to each Layer of the Trust Over IP Technology stack, is intended to guide design decisions rather than prescribe them.  This is not to say they may be dismissed entirely, but that there is a necessary flexibility of application within the incredibly complex and diverse identity ecosystem. This mapping will inform the members of Trust Over IP Governance and Ecosystem Working Groups in their daily work of creating frameworks, policies, etc.  Additionally, there are portions of the decentralized identity ecosystem which were not anticipated in 2005 by the authors of __*The Laws of Identity*__ which are treated as caveats within this guide to reinforce their inclusion within the Trust Over IP process.

In the provided matrixes, the terms **MUST**, **SHOULD**, and **MAY** will indicate whether or not documented adherence procedures are required in accordance with IETF [RFC2119](https://www.rfc-editor.org/rfc/rfc2119).  Additionally, caveats will be noted for certain issues for which documented adherence is waived (such as subject consent in guardianship contexts) when it is otherwise required.

## Outcome

It is important for users and technologists to understand that the ideas and goals of the Trust over IP Foundation are not new ideas.  These concepts have a strong pedigree that goes back to the origins of the internet.  The Laws of Identity show that any universal identity system must necessarily be a metasystem and user centric. However, [__*User Centric Identity*__](https://itlaw.wikia.org/wiki/National_Strategy_for_Trusted_Identities_in_Cyberspace:_Creating_Options_for_Enhanced_Online_Security_and_Privacy) fell flat, even after its incorporation into the United States National Strategy, because it depended on governance structures and technologies that could not hope to achieve the levels of transparency required for the universal identity metasystem to be realized.  However, the advent of Distributed Ledger Technology (DLT) has provided the next step to.  By acknowledging adherence to the line of thought by which we have arrived at the present moment, we sweep away the objections of immaturity and novel approaches and refocus on the important work of __*connecting people while also respecting their individuality of person, time, place, and context.*__

## Scope

The scope of this document is intended to be a reference for Trust over IP Foundation documents that establish frameworks or policy overlays to the Trust over IP Governance and Technical Stacks.

## Trust Over IP Stack Layers Descriptions

The first two layers of the ToIP stack are designed to provide **technical trust** — the assurance that one machine can establish a secure, private connection with another machine. Layers Three and Four are where **human trust** is established and maintained.

![](https://i.imgur.com/PnZb0EW.jpg) 

```
move image to github to ensure compatibility with corporate firewalls.
DELETE THIS COMMENT
```

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

### Law 1: User Control and Consent
Digital identity systems must only reveal information identifying a user with the user's consent.

|| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** |
|:---:|:---:|:---:|:---:|:---:|
|TL4|X*|||
|TL3|X*|||
|TL2||X*||
|TL1||X*||

\* The first caveat to the Laws of Identity is the application of user consent in cases of [dependent identity](./dependent-id.md).  If your solution includes the capability to enable proxy use of a digital identity, please see the linked document for further guidance.

### Law 2: Minimal Disclosure for a Constrained Use
The solution which discloses the least amount o identifying information and best limits its use is the most stable long-term solution.

|| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** |
|---|---|---|---|---|
|TL4|X|||
|TL3|X|||
|TL2|X|||
|TL1|X|||

### Law 3: Justifiable Parties
Digital identity systems must limit disclosure of identifying information to parties having a necessary and justifiable place in a given identity relationship.

|| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** |
|---|---|---|---|---|
|TL4|X|||
|TL3|X|||
|TL2|X|||
|TL1|X|||

### Law 4: Directed Identity
A universal identity metasystem must support both "omnidirectional" identifiers for use by public entities and "unidirectional" identifiers for private entities, thus facilitating discovery while preventing unnecessary release of correlation handles.

|| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** |
|---|---|---|---|---|
|TL4|X*|||
|TL3|X*|||
|TL2|X|||
|TL1|X|||

\* The second caveat is that no indivudual system must support both omnidirectional and directed identity.  However, no underlying technologies should prevent the existance of both types.

### Law 5: Pluralism of Operators and Technologies
A universal identity metasystem must channel and enable the interworking of multiple identity technologies run by multiple identity providers.

|| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** |
|---|---|---|---|---|
|TL4|||X|
|TL3||X||
|TL2|X|||
|TL1|X|||

The overall system must allow as many participants as possible.  However, individual credentials and applications do not need to interoperate with others.  Some credentials may be application specific as long as the user is aware that they are non-compliant.

### Law 6: Human Integration
A unifying identity metasystem must define the human user as a component integrated through protected and unambiguous human-machine communications.

|| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** |
|---|---|---|---|---|
|TL4|X||||
|TL3|||X||
|TL2|||X||
|TL1||||X|

Applications in this ecosystem must include users in identity decisions and recognize they right of the individual to change their preferences at any time.

```
We need to define acceptable ToIP Ceremonies.
DELETE THIS COMMENT
```

### Law 7: Consistent Experience Across Contexts
A unifying identity metasystem must provide a simple consistent experience while enabling separation of contexts through multiple operators and technologies.

|| **MUST** | **SHOULD** | **MAY** | **NOT Applicable** |
|---|---|---|---|---|
|TL4||X*||
|TL3|X*|||
|TL2|X*|||
|TL1|X*|||

\* While this law may appear to be focust on User eXperience (UX), a deeper reading of the paper will show that law seven implies coherence among member systems to the extent that UX is impacted.  In other words, the user **_must have the ability to exercise seperation of contexts through multiple operators and technologies_**.  Therefore, any operator or technology must be interoperable to multiple layers above, below, or adjacent to it within the Trust over IP Stack.

## Synopsis

Please refer to the [original article](http://www.identityblog.com/stories/2005/05/13/TheLawsOfIdentity.html) by the author for a complete synopsis about each principle.

## Relevance

```
Explain the positioning of each principle against the overarching goals of this proposal.  How / where would they be used (example Use cases or industry sectors).
DELETE THIS COMMENT
```

As Cameron (et.al) point out in _The Laws of Identity_, failure to adhere to the seven laws "create[s] a wake of reinforcing side-effects that eventually undermine all resulting technology."  In other words, divergence from the seven laws will result in bifercation of the technology which can only serve to degrade and dilute the digital trust ecosystem.  There is plenty of room for competition and innovation within the Seven Laws, but outside of them lay the reinforcing side-effects that form the status quo and provides for the exploitation of billions of people.  As we venture into areas which the seven laws do not cover such as [dependent identity](./dependent-id.md), we must do so with great trepidation and purity of purpose; for our responsibility is to recodify the fabric of the future digital society.

## Trade-offs
It's clear that creating any matrix will always result in border situation when there is no clear choice between **MUST**, **SHOULD**, and **MAY**. This shouldn't stop us from thinking about situation when there is a clear answer and therefore a direct relation between Laws of Identity and TOIP Technological Stack Layers.
We also understand that by creating such a matrix we might shift focus from overall fundamental picture to more detailed way of looking on governance and ecosystem frameworks.

```
Provide an assessment of the ramifications of including and/or excluding each principle in a solution
DELETE THIS COMMENT
```
 