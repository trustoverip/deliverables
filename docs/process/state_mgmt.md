All ToIP deliverables are governed by the standard three-stage approval process defined by our JDF charter (note that this process is the same for all JDF projects at the Linux Foundation).

Our [Lifecycle Management Process](./lifecycle_management.md) describes the process for the maturation of [ToIP Deliverables](./work_products.md). Each deliverable, regardless of type, follows the same standard lifecycle.

![lifecycle](../_images/process/lifecycle.png)

## Governance

The ToIP Steering Committee and Working Groups each perform a role in the management of state changes to ToIP Deliverables. The current status of all deliverables is available under the [Activity Status](../results/proposed.md) section of our [Deliverables Portal](https://trustoverip.github.io/deliverables/).

| Deliverable State | Governing Body  | Instructions |
| --- | --- | --- |
| Proposed | Working Group | [Submit a Proposal]('./lifecycle_management.md#proposed') |
| Approved | Working Group | [Working Group Approved Deliverable](#working-group-approved-deliverable) |
| Accepted | Steering Committee | [Foundation-wide Approved Deliverable](#foundation-wide-approved-deliverable) |

## Instructions

### Working Group Approved Deliverable

1. Work through the incubation process defined by the WG that is sponsoring your deliverable.
2. Once the sponsoring WG agrees to graduate the deliverable from `proposed` to `approved` status, a WG voting member MUST perform the following actions:

    1. Determine the *target deliverable repo* that manages the deliverable
    2. Open an issue against the *target deliverable repo*.
    3. Fork the *target deliverable repo*
    4. Change the following header details in the 'README.md'

        ```

          - Status: [APPROVED](./process/lifecycle_management.md)
          - Since: YYYY-MM-DD (date of WG Approval)
          - Status Note: (explanation of state change, could be a link to WG Meeting Minutes)  

        ```

    5. Commit changes and submit a PR against the *target deliverable repo* referencing the issue created in Step 2. The PR comment should document why the status is being changed.
    6. Open an issue against the [Deliverables Repo](https://github.com/trustoverip/deliverables).
    7. Fork the **Deliverables Repo**
    9. Make the appropriate changes to the `/results/proposed.md` and `/results/approved.md` files.
    9. Commit changes and submit a PR against the **Deliverables Repo**. The PR comment should document the reason for the change.

### Foundation-wide Approved Deliverable

1. If the sponsoring WG seeks Foundation-wide approval, it must submit the deliverable in accepted state to the Executive Director for a vote by the Steering Committee.
2. Coordinate with the Executive Director on a Steering Committee Meeting date and agenda vote.
3. Prepare for planned meeting by selecting a WG voting member to perform the following actions:

    1. Determine the *target deliverable repo* that manages the deliverable
    2. Open an issue against the *target deliverable repo*.
    3. Fork the *target deliverable repo*
    4. Change the following header details in the 'README.md'

        ```

          - Status: [ACCEPTED](./process/lifecycle_management.md)
          - Since: YYYY-MM-DD (date of PLANNED Vote)
          - Status Note: (explanation of state change, could be a link to WG Meeting Minutes)  

        ```

    5. Commit changes and submit a PR against the *target deliverable repo* referencing the issue created in Step 2. The PR comment should document why the status is being changed.
    6. Open an issue against the [Deliverables Repo](https://github.com/trustoverip/deliverables).
    7. Fork the **Deliverables Repo**
    9. Make the appropriate changes to the `/results/approved.md` and `/results/accepted.md` files.
    9. Commit changes and submit a PR against the **Deliverables Repo**. The PR comment should document the reason for the change.
