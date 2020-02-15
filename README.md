# srtest

This repo does only exist to better understand and test [semantic-release](https://github.com/semantic-release/semantic-release). Don't expect it to do anything useful :)

# Change History

Steps I did manually, tracked here to be able to understand how things work. Its going to be `(branch) description`:

1. (master) initial commit
2. (master) couple bug fixes
3. (master) add feature commit
4. (beta) branched beta
5. (beta) add feature commit (confliced with master, rebased)
6. (beta) new beta feature (should be 7?)
7. (master) rebased and merged beta
8. (beta) new commit on beta
9. (master) new commit on master
10. (master) BREAKING
11. (master) master prereleases (BREAKING)
12. (master) hotfix
13. (beta) changes
14. (beta) another change on beta
15. (integration) fix something
