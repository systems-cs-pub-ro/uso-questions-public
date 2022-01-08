# Reviewing Contributed Questions

As a reviewer, you will make sure that questions are of good quality:

* Difficulty is properly set.
* The topic of the question is appropriate.
* Question tags are appropriate and comprehensive.

You will also need to have a good overview of existing questions in the repository to prevent duplicates.

## Table of contents
- [Working on Pull Requests](#working-on-pull-requests)
- [Reviewing public pool repo contribution](#reviewing-public-pool-repo-contribution)
- [Reviewing private pool repo contribution](#reviewing-private-pool-repo-contribution)

## Working on Pull Requests

You will review contributions as pull requests.
Contributions will need to follow the [contributing guidelines](CONTRIBUTING.md).

Along with the question contents, please vet the commit messages against the [Git commit guidelines](CONTRIBUTING.md#git-commit-guidelines).

Question formatting will be validated automatically through the use of a GitHub actions script.

Add your review as comments and request for changes to the PR until everything is ready to be approved.
Then approve the PR.
Once approved, either you or someone with proper access rights can use `Rebase and merge` to merge the PR commits and integrate the contribution.

## Reviewing public pool repo contribution

<b>Starting</b>: There is a pending contribution to the public pool

<b>Workflow</b>:
* The reviewer goes through the pending contribution
* The reviewer checks the questions' relevance, format, metadata, whether they are different from the existing questions, while following the Reviewing guidelines
* If needed, the reviewer gives feedback and requests changes

<b>Result</b>:
* The contribution is accepted and integrated in the public pool repo
* The contribution needs updates according to the feedback
* The contribution is rejected, for one of these reasons:
    * The question is irrelevant, incorrect or unfixable
    * The question already exists in the public pool repo
    * The question already exists in the private pool repo


## Reviewing private pool repo contribution

<b>Starting</b>: There is a pending contribution to the private pool

<b>Workflow</b>:
* The reviewer goes through the pending contribution
* The reviewer checks the questions' relevance, format, metadata, whether they are different from the existing questions, while following the Reviewing guidelines
* If needed, the reviewer gives feedback and requests changes

<b>Result</b>:
* The contribution is accepted and integrated in the private pool repo
* The contribution needs updates according to the feedback
* The contribution is rejected, for one of these reasons:
    * The question is irrelevant, incorrect or unfixable
    * The question already exists in the public pool repo
    * The question already exists in the private pool repo
