# bdl-15-solution

# Remotes

**Instructions**
* Create a repository on github.
* In the terminal, initialize a new repository. 
* Add your remote repository to the local repository that you just created. 
* Check the repository's remotes. 
* Create a branch on the repository.
* Add a readme file to the branch that you just created and add some text to the file. 
* Push the branch. 

# Solution

```bash

  cd Desktop/
  mkdir bdl-15-solution
  cd bdl-15-solution/
  echo "# bdl-15-solution" >> README.md
  git init
  git add .
  git commit -m "first commit"
  git branch -M main
  git remote add origin git@github.com:mrbubbles-src/bdl-15-solution.git
  git push -u origin main
  git branch -a
  git checkout -b new-branch 
  touch NEWREADME.md
  nano NEWREADME.md 
  git add .
  git commit -m "first commit"
  git push -u origin new-branch
```
