First create a repo in your git account on web
Go to the working directory where you want to push the files to git
e.g.: pi@mgn-m-4:~/newFolder $
Execute
git init
git remote add origin https://github.com/ale1605/misc.git
git add filename.txt
git commit -m "initial commit"
git config --global user.name "ale1605"
git config --global user.email "sharanbandreddi415@gmail.com"
git branch -M main
git push -u origin main
prompt appears, type your username, "ale1605"
prompt appears, type your password, "paste the token"

To create token go to:
create a classic one with all privileges
https://github.com/settings/tokens
