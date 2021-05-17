Make a new repository
Initiate Bash inside the directory to be pushed
touch .gitignore
git config --global user.name ""
git config --global user.name ""
git init
git add .
git commit -m "Initial Commit"
git status
# If the repository is private
ssh-keygen -t rsa -b 4096 -C "email@email.com"
tail <path to id-rsa.pub> # add this to git account
git remote add origin <git url>
git push origin master
