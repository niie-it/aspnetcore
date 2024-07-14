# aspnetcore
ASP.NET Core Course resources


# GIT & GITHUB
* GITHUB WEBSITE
https://github.com

* DOWNLOAD GIT
https://git-scm.com/downloads

* GIT CONFIGURATION COMMANDS
```
git config --global user.name "YOUR_USER_NAME"
git config --global user.email "YOUR_EMAIL"
```

* GIT COMMAND
  * Clone repo: ```git clone <repo_url>```
  * Git status: ```git status```
  * 3 steps to push code to remote repo:
    ```
    git add .
    git commit -m "message_desribe_your_commit"
    git pull --rebase
    git push origin HEAD:<name-of-remote-branch>
    ```
  * After push commit, should ```git pull``` before do code changes for next task
