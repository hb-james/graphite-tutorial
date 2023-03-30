# graphite-tutorial
Welcome to the graphite tutorial.

## Installations
### Installing graphite
https://docs.graphite.dev/guides/graphite-cli/installing-the-cli

### Authenticating graphite
https://docs.graphite.dev/guides/graphite-cli/authenticating-the-cli

### Installing github CLI (Optional)
https://cli.github.com/manual/installation

## Lessons
1. Standard Pull Request to Main
2. A Stack Pull Request to Main
3. Pull Request with Merge Conflicts


## Getting Started
1. After going through installations, cd into your project folder, fork this repo `gh repo fork git@github.com:hb-james/graphite-tutorial.git` This will also ask if you want to clone the project, say yes. If doing it from the github UI make sure to copy branches.
2. Cd into the recently cloned graphite-tutorial project locally
3. Initialize graphite with `gt repo init` or `gt ri` choose `main` branch as your trunk.
4. It doesn't matter in this case what you select if you want to track current branches, normally I would select no, becuase I only want to track my changes/branches
5. Checkout the branch `lesson-1` with `git checkout lesson-1`
6. We can now add this branch to be tracked with `gt branch track lesson-1` or `gt btr lesson-1` 
7. Follow instructions on `Lesson-1.md`
