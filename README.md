# git commands
## 初回
```
git init
```
```
git status
```
```
git add .
```
```
git status
```
```
git commit -m "add:first commit"
```
```
git branch -M main
```
{url}には、自分のリポジトリのHTTPSを入力。（{}はいらないです。）
```
git remote add origin {url}
```
```
git push -u　origin main
```
## ２回目以降
```
git status
```
```
git add .
```
```
git status
```
```
git commit -m "modify:変更内容を記述"
```
```
git push
```
## 最終発表後
```
git remote -v
```
```
git branch -M <teamname>
```
```
git remote set-url origin https://github.com/caf112/Beginners-Hackathon.git
```
```
git remote -v
```
```
git push -u　origin <teamname>
```
