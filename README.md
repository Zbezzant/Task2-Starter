The current project has three feature branches. Feature branch 1 added the ability to quit using negative numbers. Feature branch 2 added a limit the to maximum number of attempts. Feature branch 3 added hot and cold temperature indicators for how close the player is to the correct number.

Merge combines the branches, commits and all, into the target branch. Rebase rewrites history, putting the target branch into the current branches history. Squash combines any number of commits into one commit. Cherry-pick applies just one commit that is called out with its hash.

I deleted feature 1 as per the instructions, but I would imagine its history would look the same, but with an additional "merge" commit. feature 2 includes the entire history of dev because it was rebased. Feature 3 has only 1 commit representing its development because of the squash.

I would use merge as a standard way of putting together branches. I would use rebase only on feature branches to keep them up to date. I would use squash to clean up ugly commits. I would use cherry-picking if I ever needed to add just one helpful commit from a branch