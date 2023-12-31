﻿# LearnGit by DuogBachDev

![Git Github Flow Mind Map](./img/git-github-flow-mind-map.jpeg)

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
**_Note :_**
If you have already committed with a commit name and want to modify that commit name, you can use the command

```
git commit --am -m "New_Commit_Name"
```

### Step 4 : Push the code to github

_- For the repository that you own, just push straight to the main branch or the branch you switched to the new branch_

```
git push origin "Branch_Name"
```

_- Create a pull request & compare_

### Step 5 : Review and update commit

_- In case after you have created a pull request and you want to edit it, you need the next code, then use the command_

```
git add .
git commit --amend
git push origin "Branch_Name" -f
```

### Step 6 : Merge pull resquest

_- Merge pull request from master branch_

```
git checkout "Master_Branch"
git pull origin "Master_Branch"
```

_- Delete branch on github and local_

```
1. Local :
git branch -D "Branch_Name"

2. Github :
Click the delete branch button on the github page
```

_- Then go back to step 2 and continue for the project_

**_Note :_**
Note for corporate projects, depending on the company, if you are decentralized, you can merge the code, otherwise the leader will do this.

## Case 2 : The project belongs to a certain company or organization

```
For example company name is : DuogBachDev
```

### Step 1 : Project Initialization

_- Folk project on personal github_

```
Click the folk button on the project's display page
```

_- Clone folk project to my computer_

```
git clone https://github.com/...
```

_- Add master remote from company repository_

```
git remote add "Company_Name" https://github.com/...
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

_- You need to push commit to your personal remote, not your company remote_

```
git push origin "Branch_Name"
```

_- Open the company's original repository and make a pull request_

### Step 5 : Review and update commit

_- In case after you have created a pull request and you want to edit it, you need the next code, then use the command_

```
git add .
git commit --amend
git push origin "Branch_Name" -f
```

### Step 6 : Merge pull resquest

_- Merge pull request from master branch_

```
git checkout "Master_Branch"
git pull origin "Master_Branch"
```

_- Delete branch on github and local_

```
1. Local :
git branch -D "Branch_Name"

2. Github :
Click the delete branch button on the github page
```

_- Then go back to step 2 and continue for the project_

**_Note :_**
Note for corporate projects, depending on the company, if you are decentralized, you can merge the code, otherwise the leader will do this.

### Additional

```
git reflog --no-abbrev, cherry pick..v.v
```

## Final

If you want to be quick, just finish the code and push straight to the master branch for quick (≧∇≦)ﾉ

## Copyright

_Author :_ **DuogBachDev** aka **DuogBachDev**

_Portfolio :_ https://portfolio-duogbachdev.vercel.app/

_DonateforMe :_ https://donate-duogbach.vercel.app/

_"A bit of fragrance clings to the hand that gives flowers!"_

_Thanks for watching !_
