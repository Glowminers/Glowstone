# Standard Procedures of X
This file contains the standard procedure of performing certain action X.

## Pull Request
We create pull requests when we want to submit our code changes to the upstream repository.
1. Find a bug on ```dev```
2. Find a solution
    * Make sure the solution passes Checkstyle
    * Make sure the solution passes tests
3. (Optional) Team review of the bug and fix
4. Branch off from ```dev```
5. Commit the change on the new branch to lock in changes
    * Commit message should include the name of the fix and bugs it fixed
6. Submit the pull request
7. Commit on the new branch to solve any change requests
8. Gets approved and merged into ```upstream/dev```
9. Merge ```dev``` into the new branch
10. Merge the new branch into ```FlTech_CSE2410_Spring2018```
11. Log K/D/A and achevements
