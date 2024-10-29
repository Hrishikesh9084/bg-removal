…or create a new repository on the command line
echo "# temp" >> README.md
git init
git commit -m "first commit"
git branch -M main
git remote add origin user-of-repo
git push -u origin main
