Extra file created to add to repository with some basic instructions:

Git Procedures and Workflow

Sequence of events:
- [ ] Go to GitHub and create / choose your repository (repo)
- [ ] Choose the button to CLONE your repo (with SSH)
- [ ] Copy the link to you clipboard

Next, go to TERMINAL and run:
- [ ] Enter {git clone “[pasted repo]”} - which creates a folder within WORKSPACE that has all of the files and branches within your GitHub repository
- [ ] Now create your BRANCH via {git checkout -b [“name of your branch”]} - this will create and switch you to that branch
- [ ] Run {git status} at any time to see where you are or {git branch} to see which branch you are in and {git checkout [“name of branch”]} to switch to a different branch


Next, go to Visual Studio Code:
- [ ] Open the folder where your repo is 
- [ ] Go to / make sure you are in the working branch
- [ ] Make any changes to the file(s) and then save them [command + s]
- [ ] Run {git add [“name of file”]}
- [ ] Run {git status} to see your file is in RED
- [ ] Run {git commit -m “message about the change”}
- [ ] Run {git status} to see your file is in GREEN
- [ ] Run {git push -u origin “name of branch”} to push the changes in the branch back up to the remote repo on GitHub

Now back to GitHub:
- [ ] Create and approve the pull request - branch > master
- [ ] Merge (and confirm) the pull request (changes from branch to master branch)
- [ ] Delete the branch (if you want to)

Back to TERMINAL:
- [ ] If you want to delete the branch (locally) then firstly change to the master branch via {git checkout master} and then
- [ ] run {git branch -D “name of the branch”} - remember this is optional
- [ ] And now run {git pull} to bring down the repo from GitHub

