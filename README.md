## Rebasing

### Background
- Rebasing is the process of moving or combining a sequence of commits to a new base commit.
- From a content perspective, rebasing is changing the base of your branch from one commit to another making it appear as if you'd created your branch from a different commit.
- It's very important to understand that even though the branch looks the same, it's composed of entirely new commits.

This is from 1st commit on branch-2

### Steps.
- Pull the most recent versions of the target rebase branch.
- Perform the following command: 
```
git revbase -i <target branch>
```