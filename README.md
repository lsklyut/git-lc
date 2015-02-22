# git-lc

git-lc is a first attempt at a git efficiency utility (and also the first python project I've started in years). In other words, I was too lazy to type out 'feature/some-feature' in the use cases below.

# Roadmap
- test coverage
- leverage the GitPython library
- installation instructions for adding this as an extension to git

# Use Cases

Consider the following list of project branches:
- master
- feature/some-feature
- feature/some-other-feature
- hotfix/some-hotfix
- hotfix/some-other-hotfix

```
> git lc some-f
1) feature/some-feature
2) feature/some-other-feature
Given branch name matches several available branches. Please select one: 2
Switched to branch 'hotfix/some-hotfix'
```
```
> git lc mas
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.
```