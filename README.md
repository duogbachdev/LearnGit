# LearnGit by DuogBachDev

# Case 1 : You are the project owner

### Step 1 : Project Initialization

_- Initialize the project on the machine first and then add the remote from github_

```
echo "# LearnGit by DuogBachDev" >> README.md
git init
git add .
git commit -m "Project_Initialization"
git remote add origin https://github.com/...
git push origin master
```

### Step 2 : Checkout new branch

_- Stand from master branch and then switch to new working branch_

```
git checkout -b "New_Working_Branch"
```

### Step 3 : Change & commit code

_- Add features or modify the code in the project_

_- Add all new code_

```
git add .
```

_- Generate commit code_

```
git commit -m "First_Commit"
```

### Step 4 : Push the code to github

_- For the repository that you own, just push straight to the main branch or the branch you switched to the new branch_

```
git push origin "Branch_Name"
```

_- Create a pull request &_
