# Git Integration: More!

We can also allow Waffle to track issues in different branches. One convention that Git users have adopted is using a new branch to work on a new issue. 

- First, lets add another issue. We'll call this issue bug-fix for simplicity:
![New Story](/images/w_new_story_2.png?raw=true "New Story")
- Typically we create a new branch using the following command:
```
git checkout -b bug-fix
```
- However, Waffle allows teams to move issues into the "In-Progress" column in a similar fashion. We can checkout a new branch by including the issue number in the branch name:
![New Branch](/images/git_new_branch_2.png?raw=true "New Branch")
- This will automatically move the card with issue #2 into the "In-Progress" column. It will also assign the GitHub user that issued this command as an owner of this story.
![Moved to In-Progress](/images/w_new_branch_2.png?raw=true "Moved to In-Progress")
- This feature allows teams to easily assign stories and issues to developers and ensure that all work will be done in a branch other than "master".
- We can issue pull requests through GitHub and include "closes #<issue_num>" in the title to allow Waffle to keep track of the change.
- Once the pull request has been reviewed, we can commit the changes by including "resolves #<issue_num>" in the commit message.
- We can then push the changes to master and view the results on Waffle:
![Moved to Done 2](/images/w_moved_to_done_2.png?raw=true "Moved to Done 2")