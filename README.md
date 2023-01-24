# Overview

`gh-update-branch` is a GitHub CLI extension that can ping the `update-branch`
API.

Usage is very simple: `gh update-branch [<number>]`

Accepts zero or one argument(s).

- If no argument, the current PR will be updated
- if argument is `--mine` than all yours PRs in the current repo will be updated
- Otherwise search a PR that respects argument criteria and update it

Additional features might be added in the future.
