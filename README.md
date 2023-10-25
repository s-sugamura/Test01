# Test01
Hello

echo "# Test01" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:s-sugamura/Test01.git
git push -u origin main



----------
https://qiita.com/kagami_t/items/ade25ff6e8bf8faf2ab2

git config --global init.defaultBranch main
git init
git add .
git commit -m "Initialize repository"
git remote add origin git@github.com:s-sugamura/Test01.git
git push origin main
-----
git branch -a
git checkout -b develop
git branch -a
