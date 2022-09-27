# git-commands-developer-should-know

#### INSTALLATION & GUIS

##### GitHub for Windows
``` 
htps://windows.github.com
``` 
##### GitHub for Mac
``` 
htps://mac.github.com
``` 

##### SETUP
Configuring user information used across all local repositories

git config --global user.name “[firstname lastname]”  
set a name that is identifiable for credit when review version history 
```
```
git config --global user.email “[valid-email]”
set an email address that will be associated with each history marker
```
```
git config --global color.ui auto
set automatic command line coloring for Git for easy reviewing
```

##### SETUP & INIT
Configuring user information, initializing and cloning repositories

```
git init
initialize an existing directory as a Git repository
```
```
git clone [url]
retrieve an entire repository from a hosted location via URL
```

##### STAGE & SNAPSHOT
Working with snapshots and the Git staging area
```
git status
show modified files in working directory, staged for your next commit
```
```
git add [file]
add a file as it looks now to your next commit (stage)
```
```
git reset [file]
unstage a file while retaining the changes in working directory
```
```
git diff
diff of what is changed but not staged
```
```
git diff --staged
diff of what is staged but not yet commited
```
```
git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot
```

##### BRANCH & MERGE
Isolating work in branches, changing context, and integrating changes

```
git branch
list your branches. a * will appear next to the currently active branch
```
```
git branch [branch-name]
create a new branch at the current commit
```
```
git checkout
switch to another branch and check it out into your working directory
```
```
git merge [branch]
merge the specified branch’s history into the current one
```
```
git log
show all commits in the current branch’s history
```

#### Add existing project to a GitHub  repository.
 
 ```
- create a new repository from the GITHUB :leftwards_arrow_with_hook:
- git Init :leftwards_arrow_with_hook:
- git status :leftwards_arrow_with_hook:
- git add . :leftwards_arrow_with_hook:
- git commit -u -f origin master :leftwards_arrow_with_hook:
- git remote add origin https://github.com/ravikoppula/projectname.git
- git push :leftwards_arrow_with_hook:
- Log on to GITHUB account and refresh the repository to view all the commited files.
```

#### Working with GITHUB REPO
```
- Create a new repository from the GITHUB :leftwards_arrow_with_hook:
- git clone https://github.com/ravikoppula/projectname.git :leftwards_arrow_with_hook:
- git status :leftwards_arrow_with_hook:
- git add . :leftwards_arrow_with_hook:
- git commit -u -f origin master :leftwards_arrow_with_hook: 
- git push :leftwards_arrow_with_hook: 
```

