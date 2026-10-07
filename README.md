# Extra Commands
7. To check the status of git (vcs)
```
  git status
 ```
8.To update the remote repo url
  ```
  git remote set-url origin [your_repo_url]

To Verrify/Display added remote url:
git remote -v
```
9. To config the user.name and user.email:
   ```
   Project Based Config:
   git config user.name [your_github_username]
   git config user.email {your_github_email]

   Global Config:
   git config --global user.name [your_github_username]
   git config --global user.email {your_github_email]

   To Verify/Display Config (Note: enter to view more config and q to exit the opened editor):
   git config --list
   ```
   # After Changing on Project
   1. git add .
   2. git commit -m "[your_commit_message]"
   3. git push

   # Using personal Access Token (PAT) on https url:
   -
