# Git Integration: More!

We can also allow Waffle to track issues in different branches. One convention that Git users have adopted is using a new branch to work on a new issue. 

- Typically we create a new branch using the following command:
```
git checkout -b bug-fix
```
- However, Waffle allows teams to move issues into the "In-Progress" column in a similar fashion. We can checkout a new branch by including the issue number in the branch name:
![New Branch](/images/git_new_branch_2.png?raw=true "New Branch")
- This will automatically move the card with issue #2 into the "In-Progress" column. It will also assign the GitHub user that issued this command as an owner of this story.
![Moved to In-Progress](/images/w_new_branch_2.png?raw=true "Moved to In-Progress")
- This feature allows teams to easily assign stories and issues to developers and ensure that all work will be done in a branch other than "master".
