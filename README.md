# Test01

aaaaa

```
echo "# Test01" >> README.md
git config --global init.defaultBranch main
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:s-sugamura/Test01.git
git push -u origin main
```


```
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
```

```
git add .
git commit -m "-"
git push
git push -u origin main

git push --set-upstream origin develop
```

----------
https://qiita.com/kagami_t/items/ade25ff6e8bf8faf2ab2


```
https://cdn.jsdelivr.net/gh/user/repo@version/file
https://cdn.jsdelivr.net/gh/s-sugamura/Test01@main/Doc01.md
https://cdn.jsdelivr.net/gh/s-sugamura/Test01@v0.2/Doc01.md
https://cdn.jsdelivr.net/gh/s-sugamura/Test01@develop/Doc01.md
```
git checkout main
git tag v0.1
git push --tags origin


# タグを設定
$ git tag [tag_name]

# タグをリモートへ反映
$ git push --tags origin
