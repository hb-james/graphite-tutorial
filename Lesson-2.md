# Lesson 2

## A Stack Pull Request to Main

In this lesson we will be a stack and merging it into `main`. We will also start this lesson from the `main` branch

1. Add some content to the end of this file.
2. Once saved, stage your recent changes through your favorite method or `git add .`
3. Lets create a branch and commit our changes `gt bc -m "lesson-2.1"`
4. Once again add some changes to the end of this file.
5. Once again we can add and create a branch on top the current branch. `git add . && gt bc -m "lesson-2.2"`
6. Now we can submit our stack (stack of 1) as a PR by running `gt stack submit` or `gt ss` and follow the prompt messages.
7. You should now see 2 PR request created in github, and should be able to merge it from there, by merging first `lesson-2.2` onto `lesson-2.1` and then `lessons-2.1` onto `main`. Alternatively there's also graphite's web interface where it lets you merge a whole stack (much more convenient).
8. Once PR has been merged, lets go back to our `main` branch with `gt bco main`
9. Lets sync our local repo with the latest changes from remote by running `gt repo sync` or `gt rs`

Feel free to move onto `lesson-3` branch with `git checkout lesson-3 && gt btr lesson-3` 