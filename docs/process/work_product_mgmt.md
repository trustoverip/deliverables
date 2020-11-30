## Management of Deliverables

### Publication Categories
Each deliverable produced by the ToIP Foundation may be rendered for publication in a variety of formats. There are two categories:

| Publication Category | Description | Format Options |
| --- | --- | --- |
| Basic | A work-product rendered in only one format. | Markdown |
| Multi-Modal | A work-product rendered in multiple formats. | Markdown, PDF, HTML|

Table 2: Depicts the possible publication categories.

>Note: Regardless of publication category, the authoring process may leverage more than one Markdown file to produce the final work-product.

### Publication Access
This repo serves as the storage repository for work-products within the **Basic** publication category. These work-products can be found in the ```recommendations``` folder.

Each work-product within the **Multi-Modal** publication category will have a dedicated repository within the [ToIP Github Organization](https://github.com/trustoverip/) with unique publication process details.

## Naming Convention

### Type Indicators

| Deliverable Type | Type Indicator | Publication Category | Target Workspace |
| --- | --- | --- | --- |
| Specification| TSS | Multi-Modal | Dedicated Repo  |
| Glossary | GL |  Multi-Modal | TBD: Highly dependent in process proposed by CTWG. |
| Recommendation - TIP | TIP |  Multi-Modal | Dedicated Repo |
| Recommendation - Design Principle | DP |  Basic| Subfolder |
| Recommendation - Best Practice | BP |  Basic | Subfolder |
| Guide - Governance Guide | GG |  Multi-Modal | Dedicated Repo |
| Guide - Implementation Guide | IG |  Multi-Modal | Dedicated Repo |
| White Paper | WP |  Multi-Modal | Dedicated Repo |

### Common Publication Category Details

| Usage | Convention | Comments | Example |
| --- | --- | --- |  --- |
| Deliverable Title  | ```ToIP <TypeIndicator><4digitID>:  <DeliverableName>``` | ```<TypeIndicator>``` should be uppercase; ```<DeliverableName>``` | ToIP BP9999: Utility Selection Criteria |
| Filename | ```<TypeIndicator><4digitID>-<DeliverableName>``` | ```<TypeIndicator>``` should be uppercase; ```<DeliverableName>``` should be lowercase and each word separated by "-". | BP9999-utility-selection-criteria | BP9999-utility-selection-criteria.md |

### Basic Publication Category Workspaces

| Usage | Convention | Comments | Example |
| --- | --- | --- |  --- |
| Subfolder name within ```recommendations``` folder | ```<TypeIndicator><4digitID>-<DeliverableName>``` | ```<TypeIndicator>``` should be uppercase; ```<DeliverableName>``` should be lowercase and each word separated by "-". | BP9999-utility-selection-criteria |

### Multi-Modal Publication Category Workspaces

| Usage | Convention | Comments | Example |
| --- | --- | --- |  --- |
| Dedicated Repo | ```<TypeIndicator><4digitID>-<DeliverableName>``` | ```<TypeIndicator>``` should be uppercase; ```<DeliverableName>``` should be lowercase and each word separated by "-". | BP9999-utility-selection-criteria |

## Unique Deliverable Identifier
Our ```trustoverip/next-deliverable-num``` repo provides a simple webpage generator for the next available 4-digit deliverable identifier. This number is computed by determining the number of repos in the GitHub Org plus the number of existing folders in the ```recommendations``` folder. See [Issue 1](https://github.com/trustoverip/next-deliverable-num/issues/1).
