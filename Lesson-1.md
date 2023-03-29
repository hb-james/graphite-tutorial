# Lesson 1

## Standard Pull Request to Main

In this lesson we will be merging branch `lesson-1` into `main`. Make sure you are in the branch `lesson-1` before starting.

1. Add some content to the end of this file.
2. Once saved, stage your recent changes through your favorite method or `git add .`
3. Lets commit our changes `gt cc -m "Added great content to lesson 1"`
4. We can see our stacks by doing `gt l` or to look at the short list version you can do `gt ls`
4. Now we can submit our stack (stack of 1) as a PR by running `gt stack submit` or `gt ss` and follow the prompt messages.
5. You should now see a PR request created in github, and should be able to merge it from there
6. Once PR has been merged, lets go back to our `main` branch with `gt bco main`
7. Lets sync our local repo with the latest changes from remote by running `gt repo sync` or `gt rs`

Feel free to move onto Lesson 2, after this lesson.
