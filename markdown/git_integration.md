# Git Integration

The "In-Progess" column should contain all stories and issues that are being worked on by developers in the current iteration. Again, drag the issue over into this column to mark it as "In-Progress". Once issues are moved into this column, you can begin to integrate Git with Waffle.

- First, open a new terminal:
- If you have not already done so, install git.
	- ex. `sudo apt-get install git`
- Change your working directory to where your GitHub repository is located:
![Change CWD](/images/git_cwd.png?raw=true "Change CWD")
- Create a new file and add some changes to it. For simplicity, use the following command:
```
echo "Stuff about adding stories" >> markdown/adding_stories.md
```
- Now use Waffle's git integration to mark this issue as "Done". To do so, use the following commands:
![Resolve Issue](/images/git_resolve_1.png?raw=true "Resolve Issue")
- If you are familiar with git, these commands should look very familiar.
	- You added the changed file ("markdown/adding_stories.md") to the staging repo by using the `git add` command
	- You committed the changes
		- The important thing to note here is that you used the keyword `resolves` along with the story or issue number. This lets Waffle know that it should move the specified story or issue into the "Done" column
	- You pushed the changes to the public repo with the `git push origin master` command
- If you look at the Waffle board, we will see the specified story or issue has moved itself into the "Done" column:
![Moved to Done](/images/w_moved_to_done.png?raw=true "Moved to Done")
- Waffle also keeps track of the throughput for the current week. For example, we just completed a story that was worth 3 points. At the top of the "Done" column, we can see that Waffle notes that we have completed 1 story and a total of 3 points. If we were to complete another story that was worth 5 points, the column would say we have completed 2 stories and a total of 8 points.


- If we look at our GitHub issues, we will also see that this issue has been closed:
![Issue Closed](/images/gh_issue_1_closed.png?raw=true "Issue Closed")

Up Next: [Git Integration: More!](https://github.com/rpcrimi/WaffleIO/blob/master/markdown/git_integration_more.md)