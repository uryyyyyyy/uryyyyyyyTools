## リモートリポジトリでは消えてるのにローカルはリモートリポジトリを参照し続けている場合の整理コマンド

`git remote prune origin`

## ローカルリポジトリでブランチを消したのをリモートにも反映させたい場合。

`git push origin　:<yourBranch>`

## 該当gitレポだけAuthorを変える。

```
git config --local user.name sea_mountain
git config --local user.email valid_email@example.com
```
