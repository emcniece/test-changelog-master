# test-changelog-master

## How To Use clog

1. Edit files, commit, submit PRs, merge, etc
1. When ready on master, execute `clog [--patch] [--minor] [--major]`
1. Increment app version to match clog's output
1. Tag to match versions, git push --tags
1. Commit changes, push


## Commitizen: Commit Helper

https://www.npmjs.com/package/commitizen

Commitizen is a global NPM package that assists with the creation of well-formed commit messages. The clog script will only include recognized commit types in the changelog, allowing devs to include or exclude specific pieces of information.

---

**Work Progress Indicator**

This list indicates commit progress:

* Commit #1 to master!
* Commit #2 to master
* Commit #3 to master