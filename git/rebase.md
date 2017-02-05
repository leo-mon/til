```
git rebase -i [hash]
```
でインタラクティブにコミットログの編集ができる。  
（ハッシュのチェックには`git log --oneline`)  

編集したポイントまで遡ったら、編集したいファイルを編集後
```
git add [該当ファイル]
```
```
git commit --amend
```
でコミット修正
```
git rebase --continue
```
でrebase完了
