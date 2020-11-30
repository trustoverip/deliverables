## Purpose
These contribution instructions MUST be used when the following are all *true*:

1. The ToIP Deliverable is an instance of one of the following types:

    * Recommendation - Design Principle
    * Recommendation - Best Practice

2. The contributors have decided to collaborate on a single markdown file as their authoring approach.

## Target Repository
Our [trustoverip/deliverables](https://github.com/trustoverip/deliverables) GitHub repo is used to maintain certain types of recommendations. We use standard GitHub activities to track issues and feature requests, as well as accept all Pull Requests (`PR's`) related to the deliverables managed in this repo.

As a member contributor, use the ```trustoverip/deliverables``` repository to contribute to the ToIP Foundation in easy and transparent manner, whether it's:

* Reporting a bug
* Discussing the current state of the ToIP Deliverable
* Submitting a fix
* Proposing process recommendations
* other

## General GitHub Workflow

* [Issue Submission / Tracking](./github-issues.md)
* [Pull requests](./github-pullrequests.md)
* Organization Resources
    * [Code of Conduct](./code_of_conduct.md)
    * [ToIP GitHub Organization Management Policy](https://github.com/trustoverip/admin/blob/master/GITHUB_ORG_MANAGEMENT_POLICY.md)
* General GitHub Resources
    * [Issue Creation](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue)
    * [PR Creation](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
    * [Creating a PR from a Fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)

## Preparation

Before proposing a new deliverable, consider the following preparatory actions:

1. Exploring the idea in the appropriate WG Slack Channel.
2. Socialize the idea during a WG meeting.
3. Make use of the mailing lists to socialize the idea and to make an assessment that your proposal is novel and you will not be overlapping work already proposed.
4. Make use of the [Deliverables Portal](https://trustoverip.github.io/deliverables/) for a current listing of all work product efforts and their statuses so that you can appropriately position your proposal as unique.
5. Make a decision as to the [type of deliverable](./work_products.md) you will be proposing.
6. Discuss the roles each contributor will perform. Some members may be knowledgable content contributors, some may be skilled in GitHub, other may have both skills.  
7. Establish a preliminary outline for the content you will be delivering and who may be contributing specific sections of work.


## Submit a Proposal

1. [Fork and clone](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-forks) the [Deliverables Repo](https://github.com/trustoverip/deliverables).
2. In a terminal window, change directories to the `recommendations` folder.
3. Pick a descriptive folder name for your new deliverable following our [naming conventions](./work_product_mgmt.md). **Don't pick a number yet**.

      ```

      [~/deliverables/recommendations]
      ==> mkdir BP0000-utility-selection-criteria

      [~/deliverables/recommendations]
      ==> cd BP0000-utility-selection-criteria

      [~/deliverables/recommendations/BP0000-utility-selection-criteria]
      ==>

      ```

    * Decide on a clear and simple name that is descriptive, yet not verbose or vague.
    * Create a new folder.
    * Navigate into your new folder.

4. Copy the appropriate **template** from the ```templates``` folder to your new folder. See [Exploring Templates](./content_templates.md).

      ```

      [~/deliverables/recommendations/BP0000-utility-selection-criteria]
      ==>  cp ../../templates/Recommendations/Best_Practice_tmplt.md .

      [~/deliverables/recommendations/BP0000-utility-selection-criteria]
      ==>  mv Best_Practice_tmplt.md BP0000-utility-selection-criteria.md

      ```


5. The **template** file provides an outline to guide your work. Use the outline to bootstrap your work on the deliverable. [Use MUST and SHOULD per standard conventions](https://tools.ietf.org/html/rfc2119). Put care into the details! Deliverable submissions that do not present sufficient information as suggested by the **template** tend to be poorly received. You can add supporting artifacts and organize your folder as desired. You MAY want to:
    * Create an `images` folder to store `.jpg` and `.png` files that your content may reference.
    * Leverage [PlantUML](https://en.wikipedia.org/wiki/PlantUML) tools for the generation of UML diagrams. When doing so, you MUST include in your folder:
        * Source: `.puml` files in a `puml` folder
        * Output: `.jpg` or `.png` files
    * Leverage presentation tools (i.e.: PowerPoint, Keynote). When doing so, you MUST include in your folder:
        * Source: `.ppt` or `.key` files
        * Output: `.jpg` or `.png` files

          ```

          /images
            /src
              /puml
                interaction_diagram.puml
              /presentations
                diagrams.key
                slides.ppt
            interaction_diagram.svg
            interaction_diagram.png
            interaction_diagram.jpg
            diagram_1.png
            slide_1.jpg

          ```

6. Consider how your new proposal should be [tagged](./tags.md).
7. When you are ready to submit the draft proposal you will need to obtain a unique deliverable identifier. To assign a number to your deliverable submission. Get the number by loading [this web page](https://trustoverip.github.io/next-deliverable-num/).
    * Rename your folder name using the new number
    * Rename your file name to reflect the new number
    * At the top of your file modify the title so it is in the form:

        ```
        <TypeIndicator><4digitID>: Friendly Version of Your Title.
        ```

    * Commit your changes.
8. Commit an updated version of `../results/proposed.md` and push your changes.
11. Submit a pull request.
    * Make sure that all of your commits satisfy the [DCO requirements](https://github.com/probot/dco#how-it-works) of the repo and conform to the license restrictions noted [below](#intellectual-property).
    * The ToIP Deliverable Maintainers will check to see if the process has been followed, and request any process changes before merging the PR.
    * When the PR is merged, your deliverable is now formally in the **Proposed** state.
