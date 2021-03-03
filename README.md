### this is a git work flow document
1. create a repo named as REPO1 on github.com, and REPO address is like https://github.com/guardianf/REPO1.git
2. run code like these
```bash
#env=macos
workspace:~ user$ mkdir REPO1 && cd REPO1 #create workspace and move into it
workspace:REPO1 user$ git init #init git repository
workspace:REPO1 user$ echo '# REPO1' >> README.md # write "# REPO1" into README.md
workspace:REPO1 user$ git add README.md #add README file into the staging area
workspace:REPO1 user$ git commit -m "add README.md" # commit README.md file intolocal repository
workspace:REPO1 user$ git branch -M main #rename this branch as main
workspace:REPO1 user$ git remove add origin https://github.com/guardianf/REPO1.git #add remote address and named it as origin
workspace:REPO1 user$ git push origin main # push local repository to the remote repository
``` 
