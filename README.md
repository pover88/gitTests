# Important Git Commands

# Clone a repository
* git clone https://github.com/pover88/gitTests.git
* Get remote URL: git config --get remote.origin.url


# Push back to repository
1. git add .
2. git commit -m "message"
3. git push
4. Push to specific remote branch: git push origin testbranch

# Create or select new branch
* Create and Select new branch: git checkout -b testbranch
* Select branch: git checkout testbranch
* See all branches: git branch

# See last commits
git branch -v

# Pull a branch, after having received a pull request
git merge testbranch