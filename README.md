# Git Lesson

This lesson covers the basics of using Git for version control.

This lesson is for the first day of the MSSE bootcamp.

To make a commit (or 'version' or 'checkpoint') follow this procedure
1. Make changes to project that you would like to keep
2. When you have your changes, tell git you are ready to commit by adding files to the staging area using "git add filename"
3. Create a checkpoint ("commit") using 'git commit -m "commit description"

You can use git log --oneline to see IDs of previous commitments. You can use these IDs to revert to a previous checkpoint/commit

## Adding Features
Features should be developed on branches. To create and switch to a branch, use the command

'git switch -c new_branch_name'

To switch to an existing branch, use

'git switch branch_name'

To list all branches, use

'git branch'

To submit your feature to be incorporated to the main branch, you should submit a `Pull Request`. 
The repository maintainers will review your pull request before accepting your changes.