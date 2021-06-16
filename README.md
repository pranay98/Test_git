echo "# Test_git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/pranay98/Test_git.git
git push -u origin main
