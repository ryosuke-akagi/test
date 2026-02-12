# 使用したコマンド
### 1515
 - git clone <リモートリポジトリURL>
 - echo "# test" >> cmd.md
 - git init 
 - git add .
 - git commit -m "cmd.mdを作成"
 - git branch 
 - git push -u origin main 


### 1516
- git add main.c 
- git status 
- git commit -m "create main.c"
- git push 
- mkdir sub
- cd sub
- git add .
- git commit -m "create sub"
- git push


### 1517
- git rm main.c
- git log -- main.c
- git checkout <コミットID7桁> main.c
#### コミットして削除、復元
- git rm main.c 
- git commit -m "削除"
- git push
- git log -- main.c
- git checkout <コミットID7桁> main.c
- git commit -m "復元"
- git push


### 1518
- git branch hoge
- git checkout hoge
- git branch
- touch test.txt
- git add test.txt
- git commit -m "空ファイル作成"
- git push -u origin hoge
- git branch -m hoge feature
- git checkout main
- ls


### 1519
- git merge feature
- ls
- git branch -d feature
- git branch
