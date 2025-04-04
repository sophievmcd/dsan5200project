# dsan5200project
DSAN 5200 Data Vizualization Project - Sophie McDowall, Danny Fischer, Ella Kulicki



**Collaborative Github info:**
To work with branches:

1. Create branch of your name in the branches settings (can do on github website by using the "New Branch" button or from local device using "git checkout -n BRANCH_NAME")
2. from your local device/terminal/VSCode:
3. use "git checkout <yourname>" to switch to your branch
4. use "git pull" to ensure your branch is up to date and use "git merge" or "git merge main" to ensure you have everyone else's up to date
5. use "git push" from your branch to save local changes (after doing "git add ." and "git commit -m "commit message"") *you may need to use the command "git push --set-upstream origin sophiem" the first time you push from your branch so that it pushes to main*
6. navigate to main using "git checkout main"
7. use "git merge <yourname>" to update the main branch with the changes from your branch, then use "git push" to ensure all is up to date

8. if you are behind main, switch to your branch ("git checkout <yourname>") and then merge with main using "git merge main" and then "git push main" to update on website

After these steps/using these commands, your branch should show 0 steps behind and 0 steps ahead of main. 


**Get latest updates from main (starting in Danny branch):**
git fetch origin  # Fetch latest changes from remote
git checkout main  # Switch to main branch
git pull origin main  # Pull latest changes

git checkout danny

git merge main

git push origin danny

**Merge local changes from Danny branch to main (starting in Danny branch):**
git add .  # Stages all changes (or specify a file, e.g., git add myfile.py)
git commit -m "Your commit message describing the changes"

git push origin danny

git checkout main  # Switch to the main branch
git pull origin main  # Make sure main is up-to-date

git merge danny

git push origin main