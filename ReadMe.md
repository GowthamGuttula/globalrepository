git config --global user.email "your_email_on_github"
git config --global user.name "your_github_user_name"
Verify with: git config --global --list

git init
git add .
git commit -m "Initial commit"
git remote add origin your-git-internal-repo-address
git push -u origin master

git add .git commit -m "My first change"

git config --global credential.helper store
