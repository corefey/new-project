init
mkdir new-project
cd new-project/
git init
echo "init" > README.md
git add README.md
git commit -m "init"
git remote add origin https://github.com/corefey/new-project.git
git push --set-upstream origin master
git checkout -b development