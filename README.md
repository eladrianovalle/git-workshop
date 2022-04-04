# Git Workshop

Try workflows in git.

## Scenario

Squash-merge a feature branch that has downstream branches

## Why do we squash/rebase?

Pull requests are (typically) authored, reviewed, and verified holistically. While individual commits on a feature branch can give the reviewer clues about why something is the way it is, or what bits of that feature relate-to/rely-on each other, once the PR is merged it is extremely rare to refer to those individual commits again. Additionally, when merging those individual commits into the default branch, you can (and often do) introduce erroneous (or at the very least, unverified) rollback points.

Squashing ensures that code that was verified as a whole, is merged as a whole and _in theory_ ensures that every commit on the default branch is a safe branching/rollback point.

## Concepts

- [Ref](https://www.atlassian.com/git/tutorials/refs-and-the-reflog)
- Branch
- [Rebase](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)
- Squash
- [Stash](https://www.atlassian.com/git/tutorials/saving-changes/git-stash)
- [Cherry-pick](https://www.atlassian.com/git/tutorials/cherry-pick)
- [Reset](https://www.atlassian.com/git/tutorials/undoing-changes/git-reset)

## How to do an interactive rebase

- [Rider (how I do it in the presentation)](https://www.jetbrains.com/help/rider/Edit_project_history.html#interactive-rebase-onto-branch)
- [Sourcetree](https://www.atlassian.com/blog/sourcetree/interactive-rebase-sourcetree)
