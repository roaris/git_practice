# git_practice

## 三種類のreset
・`git reset --soft` : HEADの位置のみ戻す  
・`git reset --mixed` : HEADの位置とステージを戻す  
・`git reset --hard` : HEADの位置とステージとワーキングツリーを戻す  

## HEAD位置の指定方法
・`HEAD@{1}` : 1つ前  
・`HEAD@{n}` : n個前  
・`HEAD^` : 1つ前  
・`HEAD^^` : 2つ前  


## CONFLICT
Current Changeがmasterでの変更で、Incoming Changeが作業ブランチでの変更  
