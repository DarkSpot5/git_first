echo "# git_second" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/DarkSpot5/git_second.git
git push -u origin main