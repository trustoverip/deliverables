# Issue Management

![lifecycle](../_images/process/lifecycle.png)

ToIP Deliverables that are not on the brink of changing status are discussed through [Github Issues](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/managing-your-work-with-issues). We generally use Issues to discuss changes that are controversial, and pull requests (`PRs`) to propose changes that are vetted. This keeps the PR backlog small and avoids ineffective use of mailing-lists.

## Issue Creation Process

ToIP Deliverables may be managed in their own dedicated GitHub Repository or in the [trustoverip/deliverables](https://github.com/trustoverip/deliverables/) repo.

### Deliverables Repository
If the subject deliverable **is** one of the following types:

    * Recommendation - Design Principle
    * Recommendation - Best Practice

the follow these instructions:

1. Any community member can open an issue.

2. Visit the [trustoverip/deliverables - Issues](https://github.com/trustoverip/deliverables/issues) dashboard and select the appropriate button for the type of *Issue* you desire to open.

3. Depending on your selection, you will be presented with an **Issue Template** which will help you clearly communicate the relationship of your contribution to the subject deliverable. Each Issue Template will allow you to specify the **Deliverable Number** in the title. For example, to open an issue on **Deliverable 0025**, an appropriate
title for the issue might be:

    [BP0025]: Need better diagram in Reference section

4. When the community feels that it's reasonable to suggest a formal status change for a deliverable, best efforts are made to resolve all open issues against it. Then a PR is
raised against the deliverable's main `README.md`, where the status field in the header is updated. Discussion about the status change typically takes place in the comment
stream for the PR, with issues being reserved for non-status-change topics.

### Dedicated Deliverable Repository
If the subject deliverable **is not** one of the following types:

    * Recommendation - Design Principle
    * Recommendation - Best Practice

then you should refer to the Issues page for the dedicate repository

```
URL: https://github.com/trustoverip/<repo_name>/issues
```

where <repo_name> is the name of the dedicated deliverable repository.
