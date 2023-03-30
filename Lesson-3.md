# Lesson 3

## A Pull Request to Main with Merge Conflict

In this lesson we will be merging branch `lesson-3` into `main`. Make sure you start this lesson on branch `lesson-3`

1. Let's create a file in the root folder of this project called `merge-conflict.md` and some content to the file.
2. Once saved, stage your recent changes through your favorite method or `git add .`
3. Lets commit our changes `gt cc -m "Added great content to merge-conflict.md`
4. Now we can submit our stack (stack of 1) as a PR by running `gt stack submit` or `gt ss` and follow the prompt messages.
5. If we head to the PR that was created we will see we are unable to merge due to merge conflicts.
6. To solve merge conflict first we must sync repo with the latest changes on remote with `gt repo sync` or `gt rs`
7. Lets update our stack with the latest stuff from `main` branch, with `gt stack restack` or  `gt sr`
8. In your IDE you should now see files with merge conflicts, and you can resolve with the best way you see fit, we can accept both changes here.
9. Now lets add our changes with `git add .`
10. Lets continue with the updating our stack process with `gt continue`
11. Finally we can once again submit our stack with `gt ss`
12. Congrats you have solved a merge conflict.