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

>cd/mnt

>ls

>git clone`https://github.com/httpsmosquito/firstobsidian.git`

輸入github帳號密碼
若有使用雙重認證(2FA)，請至github生成[[Personal Access Token]]

4.開啟obsidian APP會看到firstobsidian，開啟他(若firstobsidian中已有資料會全部顯示出來)
5.確認"Git"中已經沒有"git is not ready"的訊息，才是git clone有成功，至Authentication/Commit Author中填寫帳號、密碼(Personal Access Token)、email


手機端補充：
1.若開啟APP時出現自動上傳失敗，輸入Github帳號及密碼/Personal Access Token可解決(20240526)=>重新git clone
2.重新在iSH進行git clone，若出現"某某"PATH已存在且不是空的，可用"rm -rf 某某/"，將資料夾全數刪除