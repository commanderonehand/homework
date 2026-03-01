# Report Gitlocal
```bash
	7  mkdir 02.Git
    8  cd 02.Git/
    9  git init
   10  git branch
   11  git status
   12  touch README.md
   13  echo "hello, git" > README.md
   14  cat README.md
   15  git add .
   16  git status
   17  git commit -m "Init commit"
   18  git branch feature-branch
   19  git checkout feature-branch
   20  nano README.md
   21  git commit -m "Change README 2336"
   22  git add .
   23  git commit -m "Change README 2336"
   24  git checkout master
   25  git merge feature-branch
   26  nano README.md
   27  git log
   28  git log --oneline --graph --all
   29  git show 72fc6848b3e
   30  git tag v0.1 72fc684
   31  git show v0.1
   32  echo "some additional changes" >> README.md
   33  git add .
   34  git commit -m "Added changes to a file README"
   35  git tag v2.0 be9c3d4
   36  git log --oneline
   37  git checkout -b bug-fix
   38  echo "new change" >> README.md
   39  git add .
   40  git commit -m "More changes"
   41  git log --oneline
   42  git reset --soft HEAD~1
   43  git log --oneline
   44  git reset --hard HEAD~1
   45  git log --oneline
   46  git checkout -b experimental-feature
   47  echo "task 6" >> README.md
   48  git stash
   49  git switch feature-branch
   50  echo "task 6 changes in diff branch" >> README.md
   51  git add .
   52  git commit -m "kind of error"
   53  git stash pop
   54  git stash list
   55  nano README.md
   56  git add .
   57  git commit -m "kind of error 2"
   58  git stash drop
   59  git config --list
   60  git config --global alias.lg "log --oneline --graph --all"
   61  git lg
   62  git config user.name
   63  git config user.email
   64  git config --list
   65  history
```