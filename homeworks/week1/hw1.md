## 交作業流程
#### 繳交作業
1. 連線至 GitHub 上自己的作業區： git clone https://github.com/Lidemy/mentor-program-5th-bo930236.git
2. 建立新 branch，設定 branch 名稱為 week1：git branch week1 <br> （這裡的新 branch 目前還只是存於自己電腦上，未同步於 GitHub） 
3. 切換至新 branch： git checkout week1
4. 寫 hw
5. 作業完成後將檔案 commit： git commit -am "finished hw1"
6. 將電腦上的新 branch week1 推到遠端 GitHub 上，讓 local 端 和 remote 端同步： git push origin week1 <br> （完成後 GitHub 上會出現 week1 這個 branch）
7. 在 GitHub 上點選 pull request 將 week1 merge 到 master 這個 branch，打完資訊後點選 Create pull request
8. 到學習系統點選繳交作業，看過自我檢討，貼上 pull request 後的網址繳交

#### 助教批改完作業

1. 切換回 master： git checkout master
2. 將 GitHub 上已經 merger 完的 master 拉到自己電腦上的 master：git pull origin master <br> （將 local 端 和 remote 端的 master 同步）
3. 刪除 local 端的 week1 branch：git branch -d week1
