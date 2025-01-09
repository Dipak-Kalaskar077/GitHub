# How to create a public repo using VS Code 

gh auth login

Authenticate with GitHub Browser and paste the OTP 

git init

gh repo create REPO_NAME --public --source=. --remote=origin

**** Now repository is Created successfully on GitHub account ****

**** Copy the Repository URL from GitHub Account and set origin ****

git remote add origin "Repo URL"

git add .

git commit -m "Initial Commit"

git push origin master

or

git push "Repo URL"

