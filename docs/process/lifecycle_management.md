# Lifecycle Management Process

All ToIP deliverables are governed by the standard three-stage approval process defined by our JDF charter (note that this process is the same for all JDF projects at the Linux Foundation).

This document describes the process for the maturation of [ToIP Deliverables](./work_products.md). Each deliverable, regardless of type, follows the same standard lifecycle.

![lifecycle](../_images/process/lifecycle.png)

## Ideation
An essential part of the contribution process for the ToIP Foundation is the creative process of generating, developing, and communicating new ideas/concepts relative to our mission. Ideation may begin with individual members, it will eventually need to be brought top the attention of one of the WGs. The ideation process is often unstructured and will produce a draft document that can be used for initial discussions with a WG. If the idea is supported by a WG, a Task Force (TF) will be commissioned to formalize the idea into a proposal.

## Process Stages

### Proposed
A proposal reflects the transition of the ideation process into a formalized suggestion for work to be performed by a WG. Based on the [type of deliverable](./work_products.md) being proposed, ideation stakeholders will use a [ToIP Template](./content_templates.md) to develop a deliverable that enters the process with a status of __proposed__.

A proposal is considered a "*work-in-progress*" until it is formally endorsed by the sponsoring WG.

Depending on the type of deliverable, the submission process for a proposal will depend on the preferences and decisions of the contributors.

| Authoring Approach | Publication Category | Contribution Instructions |
| --- | --- | --- |
| Raw File | Basic | [Standard Pull-Request](./contributing_pr.md) |
| Many Files | Basic | [Document Generation](./contributing_basic_doc.md) |
| Many Files | Multi-Modal | [Rich Content Generation](./contributing_multi_docs.md)  |

### Approved
In order for a deliverable to graduate to __approved__ status, it **MUST** be sponsored by a WG. While each WG may have their own lifecycle management process and approval criteria, it is the responsibility of the WG that is sponsoring the deliverable to formally submit a PR against the [deliverables repo](https://github.com/trustoverip/deliverables) that updates the originally proposed deliverable from __proposed__ to __approved__ status.

A WG (or a TF within the WG) incubates the proposed deliverable via whatever process it chooses until it is ready for approval by the WG as a whole. This approval can be via consensus at a meeting of the WG or on the mailing list. In either case, it passes if there are no objections.

If there are objections that cannot be resolved, then a formal vote of the WG is required. In this case the Draft Deliverable must be approved by a supermajority (75%) of the participants.

Once approved, it becomes a Working Group Approved Deliverable. It can stop here if WG members do not feel the need for further advancement.

An `approved` deliverable of the type *specification* may seek further incubation down the standards track if the community has decided to submit the deliverable to a SDO.

![sdo-submission](../_images/process/tss-to-sdo.png)

### Accepted
If a WG seeks Foundation-wide approval, it must submit the deliverable in __accepted__ state to the Executive Director for a vote by the Steering Committee. As with a WG vote, this vote can be by consensus if there are no objections. If there are objections that cannot be resolved, a formal vote requires approval by a supermajority (75%) of the participants.

## Deliverable State Management

The ToIP Steering Committee and Working Groups each perform a role in the [management of state changes](./state_mgmt.md) to ToIP Deliverables. The current status of all deliverables is available under the [Activity Status](../results/proposed.md) section of our [Deliverables Portal](https://trustoverip.github.io/deliverables/).

## Alternative Stages

### Submission to an SDO
Once a TSS becomes reaches the __accepted__ state, the ToIP Steering Committee can vote to submit it to a designated standards body.

### Retirement
If a WG fails to see progress by the stakeholders associated with a deliverable proposal submission, the WG can change the status of the deliverable to __retired__. This action by the WG can be achieved via consensus at a meeting of the WG or on the WG mailing list.  The causes of such a change vary but generally can result from:

1. a decision to withdraw the proposal from community consideration by its authors;
2. a determination that implementation seems permanently stalled
3. an observation that significant refinements require a superseding proposal

If a retired deliverable has been superseded, its `Superseded By` field should contain a link to the newer spec, and the newer spec's `Supersedes` field should contain a link to the older spec. Permalinks are not broken.
