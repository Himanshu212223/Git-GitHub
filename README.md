# Git & GitHub


## 📝 To see the current Git version on your system
```
git --version
```


## 📝 Configure Git with your username and email address
```
git config --global user.name "Himanshu Singh"
git config --global user.email "himanshu212223@gmail.com"
```


## 📝 To Check Configured User and Email on Git
```
git config --global user.name
git config --global user.email
```


## 📝 To set up a Git repository locally
```
git init
```

## 📝 To see which files are staged, unstaged, or untracked
```
git status
```

## 📝 Stage or Add a particular file to the Git staging area
```
git add file_Name
```


## 📝 Stage or Add a all files to the Git staging area
```
git add .
```


## 📝 To commit files on git
```
git commit -m "provide a message"
```


## 📝 To check all commit logs 
```
git log
```


## 📝 To move to any of the commits
```
git checkout use_the_hexcode_of_commit_from_log
```


## 📝 To create a new branch (name dev)
```
git branch dev
```


## 📝 To create a branch and move into it
```
git checkout -b branch_name
```


## 📝 To move among branches
```
git checkout dev         // to go to dev branch
git checkout master      // to go to master branch
```

## 📝 To check all Branch
```
git branch
```


## 📝 To check the presence of remote origin (i.e., cloud or GitHub)
```
git remote -v
```


## 📝 To set your GitHub repo as origin to push or fetch 
```
git remote add origin Git_Hub_Repo_link
git remote add origin https://github.com/myrepo       // this is an example
```


## 📝 To push code on GitHub
```
git push -u origin branch_name
```


## 📝 To push dev branch on GitHub
```
git checkout dev
git push -u origin dev
```


## 📝 Merge one branch to another (Suppost you want to merge Dev to Main Branch)

### 1️⃣ Switch to the main branch
```
git checkout main
```

### 2️⃣ Make sure main is up to date
```
git pull origin main
```

### 3️⃣ Merge dev into main
```
git merge dev
```

### 4️⃣ Resolve any merge conflicts (if prompted)
- Open the conflicted files.
- Edit them to resolve the conflicts.
```
git add <filename>
```

### 5️⃣ Push the merged code to remote main
```
git push origin main
```