# Contributing to Open Elements

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued.
See the Table of Contents for different ways to help and details about how this project handles them.
Please make sure to read the relevant section before making your contribution.
It will make it a lot easier for us maintainers and smooth out the experience for all involved.
The community looks forward to your contributions. 🎉

> And if you like the project, but just don't have time to contribute, that's fine.
> There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
>
> - Star the project
> - Tweet about it
> - Refer this project in your project's readme
> - Mention the project at local meetups and tell your friends/colleagues

## Code of Conduct

This project and everyone participating in it is governed by the
[Open Elements Code of Conduct](https://github.com/OpenElements/.github/blob/main/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.
Please report unacceptable behavior to <info@open-elements.com>.

## Developer Certificate of Origin (DCO)

To ensure all contributions are properly licensed and documented, we use the [Developer Certificate of Origin (DCO)](https://developercertificate.org/). The DCO is a lightweight mechanism for contributors to certify that they have the right to submit code or documentation to the project.

Currently, the DCO applies to two repositories:

- [hedera-enterprise](https://github.com/OpenElements/hedera-enterprise)
- [hedera-solo-action](https://github.com/OpenElements/hedera-solo-action)

The [DCO GitHub App](https://github.com/apps/dco) is installed on these repositories to automatically check that each commit is signed off. Each commit message must contain a "Signed-off-by" line with the contributor's name and email address, achieved by using the `-s` flag when committing.

### Sign-Off Example

Here’s an example of how to sign off your commits correctly:

```bash
git commit -s -m "Your commit message"
```

This will add a "Signed-off-by" line at the end of your commit message:

Signed-off-by: Your Name <your.email@example.com>

### Fixing Missing DCO Sign-Offs

If the DCO App flags your pull request for missing sign-offs, you can fix this by amending your commits:

```bash
git commit --amend -s
git push --force
```

## Pull Requests

Like most open-source projects, we use pull requests (PRs) to track code changes. Follow these steps to create a PR:

1.  Forking: Fork the repository on GitHub.

2.  Clone the Fork: Clone the forked repository to your local working directory.

        git clone https://github.com/${owner}/${repo}.git

3.  Add Upstream: Add an upstream remote to keep your fork in sync with the main repo.

        git remote add upstream https://github.com/OpenElements/${repo}.git

4.  Sync Your Local Branch: Sync your local `main` branch with the upstream repository.

        git pull upstream main

5.  Create a New Branch: Create a branch to add a new feature or fix an issue.

        git checkout -b new-feature

6.  Make Your Changes: Make changes in the new-feature branch, then build and test your code locally.

7.  Add Files to Commit: Add files that you want to commit.

        git add <file>

8.  Enable [GPG Signing:](https://docs.github.com/en/github/authenticating-to-github/managing-commit-signature-verification/signing-commits) Enable GPG signing of your commits. Signing all your commits with your public key allows the community to verify it’s really you.
    If you forgot to sign some commits, you can [rewrite your commit history](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History).

            git config commit.gpgsign true

9.  Sign Off on Commits: Use the `-s` flag to sign off on all commits. Also, GPG-sign your commits with your public key.

        git commit --signoff -S -m "Your commit message"

10. Submit a Pull Request (PR): Push your branch and open a PR on GitHub.

## I Have a Question

Before you ask a question, it is best to search for existing Issues that might help you.
In case you have found a suitable issue and still need clarification, you can write your question in this issue.
It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open an Issue.
- Provide as much context as you can about what you're running into.

We will then take care of the issue as soon as possible.

## Reporting Bugs Or Suggesting Enhancements

If you found a bug in our code or want to suggest a new feature or improvement please create a new Issue.

## Your First Code Contribution

We reserve issues for people who have never contributed to this project or any open source project in general.
We know that creating a pull request (PR) is a major barrier for new contributors.
The goal of issues labeled by [**'good first issue'**](https://github.com/issues?q=is%3Aopen+is%3Aissue+org%3AOpenElements+archived%3Afalse+label%3A%22good+first+issue%22) is to help you make your first contribution.

This does not mean that contribution is only welcome for those issues.
We are happy with any contribution.
The most important point is that an issue exists for the contribution.
If that is not the case please create an issue for a bug or enhancement.
Please comment on the given issue that you want to work on it.
Once a member of the team has assigned you to the issue you can start working on it.

## Attribution

This guide is based on the **contributing-gen**. [Make your own](https://github.com/bttger/contributing-gen)!
