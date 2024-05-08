---
created: 2024-05-08T10:32:00
Topics:
  - obsidian學習
  - obsidian同步
  - github同步
Source URL: https://blog.poychang.net/obsidian-sync-between-desktop-and-mobile-with-git/
---
## 1. 電腦端
1.在github.com建立一個空的Repository(設為私人)，點進去->code->HTTP->複製網址`https://github.com/httpsmosquito/firstobsidian.git`
httpsmosquito為帳號，firstobsidian是剛剛建立的Repository名稱
2.在本機任一資料夾(例如資料夾名稱為123)中輸入git clone`https://github.com/httpsmosquito/firstobsidian.git`，這個資料夾將是存放obsidian vault的地方
3.打開下載好的obsidian應用程式，open folder as vault，開啟剛剛建立的資料夾(123)
4.在obsidian應用程式中community plugins下載"Git"(或叫obsidian Git)並啟用
5.Git中最上方不會顯示"Git is nit ready"，且可以調整其他設定(Automatic等等)
## 2. 手機端
1.使用Iphone下載obsidian跟iSH
2.在檔案中確認有沒有obsidian資料夾存在
3.在iSH中執行
>apk update & upgrade
更新

>apk add git
下載git

>mount -t ios . /mnt
>會開啟檔案
>選擇要放obsidian vault的地方




